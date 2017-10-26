* 功能: 支付宝二维码支付

* URL: /api/pay/ali/QRcode

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
        "prepay_id": "wx20171023170201b3cca4d4210998598776",
        "code_url": "weixin://wxpay/bizpayurl?pr=S0X9Gxm"
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
 third_party_error|支付失败
