* 功能: 发送验证码（短信、邮箱）
```
注册发送验证码：对手机号和email是否在系统中存在做效验，如果存在则提示已经存在，如果不存在则发送验证码
重置密码发送验证码：对手机号和email是否在系统中存在做效验，如果存在则发送验证码，如果不存在则则提示用户不存在
```

* URL:/api/auth/send/verificationCode

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
        "phone_code":'86'           //国家代码，默认为'86'即中国
        "phone":"183****8311",      //phone,当type 为'1'时，phone为必选参数
        "email":"leo****@bstcne.com", //email,当type 为'2'时，email为必选参数
        "password":123321, //密码
        "resetPassword":false,  //重置密码时为必选参数['true':重置密码，'false':非重置密码]
        "device":""     //设备信息，可选参数
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
 user_not_exist|用户不存在
 phone_exist|phone已经存在
 email_exist|email已经存在
 send_sms_max_limit|发送短信验证码到达系统上限
 send_email_max_limit|发送email验证码到达系统上限


