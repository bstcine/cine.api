* 功能: 获取用户信息

* URL: /api/user/info

* request
```
{
    "token":"Hzn6R9Yb",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
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
        "id": "d011495098151930dz0CsXrxSm",
        "login": "leo.zhang",
        "password": null,
        "nickname": "fdsafdsa",
        "email": null,
        "phone_code": "86",
        "phone": "18112382052",
        "role_id": "3",
        "status": "1",
        "head_image": null,
        "wechat": null,
        "wx_openid1": null,
        "wx_openid2": null,
        "wx_openid3": null,
        "wx_unionid": null,
        "create_at": "2017-05-18 17:02:31",
        "create_by": "d011495098151930dz0CsXrxSm",
        "update_at": "2017-10-10 09:34:23",
        "update_by": "d011495098151930dz0CsXrxSm",
        "delete_at": null,
        "delete_by": null,
        "surname": null,
        "name": null,
        "grade": null,
        "gender": "1",
        "language": null,
        "country": null,
        "province": null,
        "city": null,
        "is_need_reset": "0",
        "is_app_logined": "1",
        "balance": 0,
        "point": 12,
        "agent_id": "0",
        "unpayOrdersCount": 6,
        "unuseCouponsCount": 0,
        "unSharedOrders": 0,
        "unSharedPoint": 0
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
 user_not_exist|用户不存在
 
