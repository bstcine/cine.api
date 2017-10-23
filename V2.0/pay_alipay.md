* 功能: 支付宝app支付

* URL: /api/pay/ali

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
        "pay_url": "app_id=2016080101690472&biz_content=%7B%22timeout_express%22%3A%2230m%22%2C%22seller_id%22%3A%22%22%2C%22product_code%22%3A%22QUICK_MSECURITY_PAY%22%2C%22total_amount%22%3A%222980.00%22%2C%22subject%22%3A%22%E3%80%8A%E4%BA%BA%E7%B1%BB%E7%9A%84%E6%95%85%E4%BA%8B%E3%80%8B%E7%B2%BE%E8%AF%BB%E8%AF%BE%E7%A8%8B%22%2C%22body%22%3A%22%E3%80%8A%E4%BA%BA%E7%B1%BB%E7%9A%84%E6%95%85%E4%BA%8B%E3%80%8B%E7%B2%BE%E8%AF%BB%E8%AF%BE%E7%A8%8B%22%2C%22out_trade_no%22%3A%22201710181153BQfcG%22%7D&charset=utf-8&method=alipay.trade.app.pay&notify_url=http%3A%2F%2Flocal.bstcine.com%3A9000%2Fapi%2Fapp%2Fpay%2Falipay%2Fpaynotify&sign_type=RSA&timestamp=2017-10-23%2018%3A23%3A43&version=1.0&sign=PyXFBCgtfs7qq28u1Yc1B2EPQMO4yginBeJ6VMCinCurrzn3STG3ciDpO1dFYd%2FQlpZ1A0I7n3Ruyi9O91CNzmLJ9T59ETWZuMkAXKbkd2Wi61W1IEnrE6r8fgcw6ecXopHbW4miFNsBQY7XcWLPMOspe2NKSUCnDVrLk67HrxE%3D"
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
