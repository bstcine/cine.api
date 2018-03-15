* 功能: 我的消息列表

* URL: /api/message/list

* request
```
{
"locale":"ch",
"appver":"2.2.0",
"data":{
	"type":"1" 
},
"sitecode":"cine.ios.iphone",
"channel":"",
"token":"PrXcYbXM"
}

- 说明：type为可选参数，为空时默认全部消息，[消息：'1',通知:'2']
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
                "id": "d011521085498599S7krv4fHz9",
                "user_id": "d0115178123382694T6E4UMBa0",
                "message_id": "d011520995132386axuzmEyMB0",
                "platform": "",
                "read": "0",
                "read_time": null,
                "create_at": "2018-03-15 11:44:58",
                "create_by": "1",
                "update_at": null,
                "update_by": null,
                "delete_at": null,
                "delete_by": null,
                "type": "1",
                "title": "notifiyation",
                "content": "test1235",
                "link": null,
                "alert_img": null,
                "content_type": "3",
                "course_id": ""
            },
            ...
        ]
    }
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
