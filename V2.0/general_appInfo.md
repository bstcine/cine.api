* 功能: 获取App信息

* URL: /api/general/appInfo

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
        "id": "d011508397535171ezp8MFjven",
        "title": "iphone",
        "status": "0",    //未上架:0,已上架:1
        "type": "0",      //ios.iphone:0,ios.ipad:1,android.phone:2,android.pad:3
        "remark": null,
        "app_version": "1.1.3", //版本号
        "is_review_open": "0",  //关闭审核通道:0,打开审核通道:1
        "app_review_from": "2017-10-19",  //审核开始时间
        "app_review_to": "2017-10-25",    //审核结束时间
        "create_at": "2017-10-19 15:18:55",
        "create_by": "1",
        "update_at": "2017-10-19 15:18:55",
        "update_by": "1",
        "delete_at": null,
        "delete_by": null
    }
}
```
