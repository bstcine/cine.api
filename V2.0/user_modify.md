* 功能: 修改用户信息

* URL: /api/user/profile/modify

* request
```
{
    "token":"dwuv1Yn3",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{            //可选参数
        "nickname":12356,       //昵称
        "phone":138xxxx5678,    //手机号
        "email":''              //邮箱
        "city":''               //城市
        "grade":''              //年级    
        "gender":''             //性别
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
        "data": []
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
 email_already_exist|email已经存在
 phone_already_exist|phone已经存在
 
