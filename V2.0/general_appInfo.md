* 功能: 获取App审核信息

* URL: /api/review/version/info

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
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
        "id": "d011508402647449XkbVRx1SJm",
        "remark": null,
        "app_version": "1.1.3",
        "is_review_open": 1,    //关闭审核通道:0,打开审核通道:1
        "app_review_from": "2017-10-19",  //审核开始时间
        "app_review_to": "2017-10-25",    //审核开始时间
        "create_at": "2017-10-19 16:44:07",
        "update_at": "2017-10-19 16:44:07"
    }
}
```
