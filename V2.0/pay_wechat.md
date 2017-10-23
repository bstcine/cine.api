* 功能: 获取订单状态

* URL: /api/pay/wechat

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
        "payObj": {
            "appid": "wx249c741c50a289a0",
            "partnerId": "1437616302",
            "prepayId": "",
            "nonceStr": "RbEvFURS9h",
            "timeStamp": "1508747533",
            "package": "Sign=WXPay",
            "sign": "573FFF34B953120A572BD79FB5A48E0A",
            "order_id": "201710181153BQfcG"
        },
        "order": {
            "id": "201710181153BQfcG",
            "user_id": "d011495098151930dz0CsXrxSm",
            "lesson_id": "A011466215703591WQYDRNlWxH",
            "coupon_no": null,
            "total_price": "2980",
            "discount_price": "0.00",
            "pay_price": "2980.00",
            "pay_type": "3",
            "pay_status": "3",
            "pay_at": null,
            "username": "fdsafdsa",
            "phone": "18112382052",
            "status": "3",
            "other_sn": null,
            "other_account": null,
            "other_account_name": null,
            "ip": "::ffff:127.0.0.1",
            "user_agent": "PostmanRuntime/6.2.5",
            "remark": "undefined",
            "create_at": "2017-10-18 11:53:26",
            "create_by": "d011495098151930dz0CsXrxSm",
            "update_at": "2017-10-23 16:32:12",
            "update_by": "d011495098151930dz0CsXrxSm",
            "delete_at": null,
            "delete_by": null,
            "expire_at": null,
            "source_id": null,
            "subject": "《人类的故事》精读课程",
            "body": "《人类的故事》精读课程",
            "coupon_discount": "0.00",
            "balance_discount": "0.00",
            "point_discount": "0.00",
            "source_user_id": null,
            "price": "2980",
            "is_shared": "0",
            "agent_id": null
        }
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
