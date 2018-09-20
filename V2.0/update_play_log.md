* 功能: 更新当前 Lesson 的播放纪录

* URL: /api/user/content/course/updatePlayLog

* request
``` javascript
{
    "token":"xTvcFJec",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
      "cid":"1314", //lesson id
      "cur_at":"2018-09-20 18:00:00",
      "logs":[{media_id:'d011516603127442cKr4PtTZ80',start_at:'2018-09-19 10:00:00',end_at:'2018-09-19 10:01:10',duration:10},{start_at:'2018-09-19 11:00:00',end_at:'2018-09-19 11:10:10',duration:10}],  
    }
}
```

* 正确token response
   ``` 
    {
        "code": "1",
        "code_desc": "success",
        "except_case": "",
        "except_case_desc": "",
        "result": ""
    }
    ```
* 错误token response
``` 
    {
        "code": "1",
        "code_desc": "success",
        "except_case": "",
        "except_case_desc": "no_login"
    }
```
* 参数异常 response
    - token为空 response except_case_desc值为token_is_null
    - cid、lesson_id、cur_at 为空时，response except_case_desc值为param_is_null
