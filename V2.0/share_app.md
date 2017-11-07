* 功能: app分享

* URL: /api/share/app

* request
```
{
    "token":"C0Tt6sd7",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "type":"6"      //分享类型，默认为'6'即app分享
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
        "sharelog_id": "d011510033326589nF2yKsaGAJ",
        "share_title": "App分享",
        "share_desc": "善恩英语App上线了",
        "share_link": "http://www.bstcine.com/mAppDownload?id=d011510033326589nF2yKsaGAJ",
        "share_imgUrl": "fdasfdasfdas"
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
 param_error|参数错误
 shareparam_not_found|分享配置参数未找到
