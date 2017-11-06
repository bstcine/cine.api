* 功能: 首页搜索

* URL: /api/content/home/search

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "search":"精读"   //课程名称
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
        "cur_page": "",
        "max_page": "",
        "total_rows": "",
        "rows": [
            {
                "id": "d011489544924565QYbxA1ACU6",
                "name": "《神奇树屋6 – 亚马孙大冒险》精读课程",
                "price": "198",
                "img": "2017/03/15/165056371S13U3R3.jpg",
                "total_join": 1039,
                "lessoncategory_id": "d011489544620521snx8MPm4r4"
            },
            ....
        ]
    }
}
```
          
  - 参数异常时 response
  
 except_case_desc|错误描述
 -|-
 search_is_null|搜索参数为空
 sitecode_err|参数格式错误
