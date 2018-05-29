* 功能: 查询用户信息，根据login,phone,email

* URL: /api/user/query

* request
```
{
    "token":"Hzn6R9Yb",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "query":"kim"
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
    "result": [
        {
            "id": "d011506750041915sTsJ5w4Wmm",
            "login": "kim",
            "phone": "15961412132",
            "email": null,
            "name": null,
            "nickname": "kim聊聊",
            "head_image": null
        }
    ]
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
 
