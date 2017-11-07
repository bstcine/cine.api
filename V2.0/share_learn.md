* 功能: 打卡分享

* URL: /api/share/course/learn

* request
```
{
    "token":"C0Tt6sd7",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "cid":"1314",       //lesson_id
        "duration":123,      //学习时长
        "type":2,           //分享类型，默认为'2'即学习进度分享
        "rank":3,           //排名，可选参数
        "activeShare":'1'   //是否主动打卡，默认为'0'非主动打卡
    }
}
```

* response
```
{
    "code": "1",
    "code_desc": "success",
    "except_case": "",
    "except_case_desc": "",
    "result": {
        "shareParam": {
            "sharelog_id": "d011510033899401CB5t9qpPZ2",
            "share_title": "这是动物农庄标题哦",
            "share_desc": "fads",
            "share_link": "http://http://local.bstcine.com:9000/share?id=d011510033899401CB5t9qpPZ2",
            "share_imgUrl": "fad",
            "featured_video": "1"
        },
        "shareModal": {
            "id": "d011505119370350dWh8q2XD1e",
            "name": "默认打卡",
            "type": "1",
            "slogan": "你本次已经学习{#ext#}分钟,学到了{#ext#}！",
            "slogan_img": "http://www.bstcine.com/f/2017/09/26/172417195Sb74Jff.png",
            "point_tip": "打卡拼手气赢积分，1个积分=1元钱！！",
            "next_button": "http://www.bstcine.com/f/2017/09/26/172612597SYVTn1s.png",
            "background_img": "",
            "slogans": null,
            "create_at": "2017-09-11 16:42:50",
            "create_by": "1",
            "update_at": "2017-09-26 17:52:49",
            "update_by": "1",
            "delete_at": null,
            "delete_by": null,
            "share_button": "http://www.bstcine.com/f/2017/09/26/172646504SJC47Bw.png",
            "textArr": [
                3,
                "Chapter1/Paragraph1"
            ]
        }
    }
}
```
  - token错误时 response
  ```
  {
    "code": "1",
    "code_desc": "success",
    "except_case": "",
    "except_case_desc": "no_login"
  }
  ```
          
  - 参数异常时 response
  
 except_case_desc|错误描述
 -|-
 token_is_null|token为空
 param_is_null|参数为空
 contents_not_found|lesson不存在
 content_limit_share|该lesson限制打卡
 lesson_not_found|course不存在
 share_param_id_not_exist|分享配置参数id不存在
 share_param_not_found|分享配置参数不存在
 sharemodaltemplate_not_found|分享模板不存在
