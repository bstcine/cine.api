* 功能: 删除消息

* URL: /api/message/delate

* request
```
{
"locale":"ch",
"appver":"2.2.0",
"data":{
     "msg_log_id":"d011521085575261sp86p5CmJT"
},
"sitecode":"cine.ios.iphone",
"channel":"",
"token":"PrXcYbXM"

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

* token为空或错误token response
```
{
    "code": "1",
    "code_desc": "success",
    "except_case": "",
    "except_case_desc": "no_login"
}
```
