* 功能: 获取订单状态

* URL: /api/order/pay/status

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "cid":"201709081615bMgFQ"   //订单id
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
        "pay_status": "1"
    }
}
```
          
  - 参数异常时 response
  
 except_case_desc|错误描述
 -|-
 order_id_is_null|order_id为空 
 order_not_found|订单不存在
