* 功能: 我的可用优惠券列表

* URL: /api/user/coupon/activeList

* request
```
{
    "token":"y5atdEZ3",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "cid":42        //课程ID
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
        "cur_page": "",
        "max_page": "",
        "total_rows": "",
        "rows": [
            {
                "id": "d011509695541580yVQFXnkh56",
                "no": "79032044",
                "name": "test",
                "value": "15.00",
                "status": "0",
                "effective_at": "2017-11-03 00:00:00",
                "expire_at": "2017-12-03 23:59:59",
                "match_lesson_ids": "'42'",
                "use_at": null,
                "user_id": "d011495098151930dz0CsXrxSm",
                "order_id": null,
                "remark": null,
                "create_at": "2017-11-03 15:52:21",
                "create_by": "1",
                "update_at": "2017-11-03 15:53:00",
                "update_by": "d011495098151930dz0CsXrxSm",
                "delete_at": null,
                "delete_by": null,
                "type": "1",
                "condition": "1",
                "desc": "适用课程:《动物农庄》精读课程",
                "price": "15.00"
            },
            ...
        ]
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
 no_login|未登录
 course_id_is_null|课程ID为空
