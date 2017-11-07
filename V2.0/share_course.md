* 功能: 课程详情分享(购买后订单分享)

* URL: /api/share/coursePackage

* request
```
{
    "token":"C0Tt6sd7",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "cid":"42" ,     //course_id课程ID
        "order_id":201711061655cVQh8,   //order_id,购买后分享时传递，不传则为课程分享
        "type":'4'  //分享类型，默认为'4'即课程or订单分享
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
        "sharelog_id": "d011510038258768jNbm7gxfGS",
        "share_title": "这是动物农庄标题哦",
        "share_desc": "fads",
        "share_link": "http://http://local.bstcine.com:9000/lesson/42?source_user_id=d011495098151930dz0CsXrxSm&sharelog_id=d011510038258768jNbm7gxfGS",
        "share_imgUrl": "fad"
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
 lesson_not_found|课程不存在
 unsupport_type|类型不支持
 share_param_id_not_exist|分享配置参数不存在
 share_param_not_found|分享参数不存在
 
