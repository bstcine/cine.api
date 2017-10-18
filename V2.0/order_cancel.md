* 功能: 取消订单

* URL: /api/order/cancel

* request
```
{
    "token":"r5QFdg7A",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{  
      "cid":"201710181156b3eTm"
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
    "result": ""
}
```
          
  - 错误token response
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
 order_id_is_null|order_id为空 
 order_not_found|订单不存在
 order_not_belong|订单不属于该用户
 already_paid|订单已支付
 already_closed|订单已关闭
