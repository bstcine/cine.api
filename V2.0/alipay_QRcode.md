* 功能: 支付宝二维码支付

* URL: /api/pay/alipay/QRcode

* request
```
{
    "token":"yDS485Uv",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "cid":"201710181153BQfcG"   //订单id 
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
        "alipayRedirect": "https://mapi.alipay.com/gateway.do?_input_charset=UTF-8&body=%E3%80%8A%E4%BA%BA%E7%B1%BB%E7%9A%84%E6%95%85%E4%BA%8B%E3%80%8B%E7%B2%BE%E8%AF%BB%E8%AF%BE%E7%A8%8B&notify_url=http%3A%2F%2Flocal.bstcine.com%3A9000%2Fapi%2Fpay%2Falipay%2Fpaynotify&out_trade_no=201710181153BQfcG&partner=2088421371245377&payment_type=1&return_url=http%3A%2F%2Flocal.bstcine.com%3A9000%2Fapi%2Fpay%2Falipay%2Fpayreturn&seller_email=finance%40bstcine.com&service=create_direct_pay_by_user&subject=%E3%80%8A%E4%BA%BA%E7%B1%BB%E7%9A%84%E6%95%85%E4%BA%8B%E3%80%8B%E7%B2%BE%E8%AF%BB%E8%AF%BE%E7%A8%8B&total_fee=2980.00&sign=d7404451564dd33a0851077f3da90c75&sign_type=MD5"
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
 order_id_is_null|order_id为空 
 user_not_exist|用户不存在
 order_not_found|订单不存在
 already_paid|订单已支付
 already_closed|订单已关闭
 lesson_already_paid|课程已购买过
