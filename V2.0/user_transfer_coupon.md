* 功能: 优惠券转让

* URL: /api/user/coupon/transfer

* request
```
{
    "token":"Hzn6R9Yb",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "transfer":"", //转让用户ID
        "coupon_no":"",  //转让优惠券券码
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
    "result": 0
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
 
