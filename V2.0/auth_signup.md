* 功能: 用户注册（短信、邮箱）

* URL:/api/auth/signup

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "type":"1",         //类型，type:['1':手机，'2':邮箱]
        "phone":"183****8311",      //phone,当type 为'1'时，phone为必选参数
        "email":"leo****@bstcne.com", //email,当type 为'2'时，email为必选参数
        "password":123321, //密码
        "auth_code":7670,   //验证码
        "login":leo111,     //账号，为空时默认为用户的id
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
    "result": {}
}
```
          
  - 参数异常时 response
  
 except_case_desc|错误描述
 -|-
 type_is_null|类型参数为空
 phone_is_null|phone为空
 email_is_null|email为空
 phone_wrong_format|手机号码格式错误
 email_wrong_format|邮箱格式错误
 auth_code_wrong|验证码错误
 phone_already_registered|phone已注册过
 email_already_registered|email已经注册过


