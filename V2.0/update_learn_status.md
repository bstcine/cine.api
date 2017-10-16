* 功能: 更新学习进度，把当前节点标记为 学习中 或 已学完，计算整个课程的学习进度百分比，以及本次最新学到的节点 id

* URL: /api/user/content/course/updateLearnStatus

* request
```
{
    "token":"xTvcFJec",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
      "cid":"42",
      "content_id":"1315",
      "status":1,
      "last_tag":3,
      "last_position":1512,
      "duration":123      
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
    - cid、content_id为空时，response except_case_desc值为param_is_null
