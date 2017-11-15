* 功能: 更新分享状态

* URL: /api/share/updateStatus

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
        "type":"4"  //分享类型，默认为'4'即课程or订单分享
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
        "point": 0,
        "textArr": [],
        "textTpl": ""
    }
}
```
          
  - 参数异常时 response
  
 except_case_desc|错误描述
 -|-
 param_is_null|参数为空
 shareLog_not_found|分享不存在
 order_not_found|订单不存在
 lesson_not_found|课程不存在
 user_not_found|用户不存在
 not_allow_share_open|禁止分享开通

