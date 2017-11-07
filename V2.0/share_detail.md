* 功能: 查看分享详情

* URL: /api/share/detail

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "cid":"d011510038258768jNbm7gxfGS"   //分享ID
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
        "detail": {
            "id": "d011510038258768jNbm7gxfGS",
            "user_id": "d011495098151930dz0CsXrxSm",
            "lesson_id": "42",
            "type": "4",
            "coupon_template_id": null,
            "order_id": null,
            "is_reward": "0",
            "reward_status": "0",
            "device_uid": null,
            "ip": "::ffff:127.0.0.1",
            "user_agent": "PostmanRuntime/6.2.5",
            "remark": "{\"lesson_name\":\"《动物农庄》精读课程\",\"featured_video\":\"1\",\"textArr\":[],\"textTpl\":\"\"}",
            "create_at": "2017-11-07 15:04:18",
            "create_by": "d011495098151930dz0CsXrxSm",
            "update_at": "2017-11-07 15:17:53",
            "update_by": "d011495098151930dz0CsXrxSm",
            "delete_at": null,
            "delete_by": null,
            "share_title": "这是动物农庄标题哦",
            "share_desc": "fads",
            "share_link": "http://http://local.bstcine.com:9000/lesson/42?source_user_id=d011495098151930dz0CsXrxSm&sharelog_id=d011510038258768jNbm7gxfGS",
            "share_imgUrl": "fad",
            "status": "1",
            "content_id": null
        }
    }
}
```
          
  - 参数异常时 response
  
 except_case_desc|错误描述
 -|-
 param_is_null|参数为空
 sharelog_not_exist|分享不存在

