* 功能: 创建订单

* URL: /api/order/create

* request
```
{
    "token":"r5QFdg7A",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{  point,coupon_no,source_id,remark为可选参数
      "cid":"A011466215703591WQYDRNlWxH"
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
        "order_id": "201710181156b3eTm",
        "pay_status": "0"
    }
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
 user_not_exist|用户不存在
 token_is_null|token为空
 param_not_null|lesson为空 
 lesson_not_exist|lesson错误
 invalid_point|积分参数类型错误
 not_allow_point|不允许使用积分
 point_not_enough|积分不足
 not_allow_coupon|不允许使用优惠券
 coupon_not_exist|优惠券不存在
 coupon_not_belong|优惠券不属于该用户
 coupon_expired|优惠券已过期
 coupon_not_effective|优惠券失效
 coupon_limit_new_order|优惠券限首单用户使用
 coupon_limit_new_dev_user|优惠券限新学员使用
 coupon_limit_lesson|优惠券限指定课程使用
 coupon_used|优惠券已使用
 coupon_in_use|优惠券使用中
 order_already_paid|订单已支付
 related_lesson_required|写作课程请先购买对应的视频课程
 point_too_large|当前积分已超出应付金额
