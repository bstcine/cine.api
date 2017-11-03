* 功能: 添加优惠券

* URL: /api/user/coupon/add

* request
```
{
    "token":"y5atdEZ3",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "no":94758894   //优惠券号码
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
        "id": "d011509696066307FB21ZhkH7c",
        "no": "94758894",
        "name": "test",
        "value": "15.00",
        "status": "0",
        "effective_at": "2017-11-03 00:00:00",
        "expire_at": "2017-12-03 23:59:59",
        "match_lesson_ids": "'42'",
        "use_at": null,
        "user_id": "d011495098151930dz0CsXrxSm",
        "order_id": null,
        "remark": null,
        "create_at": "2017-11-03 16:01:06",
        "create_by": "1",
        "update_at": "2017-11-03 16:01:17",
        "update_by": "d011495098151930dz0CsXrxSm",
        "delete_at": null,
        "delete_by": null,
        "type": "1",
        "condition": "1",
        "desc": "适用课程:《动物农庄》精读课程"
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
 no_login|未登录
 no_is_null|优惠券号码为空
 coupon_not_exist|优惠券不存在
 coupon_not_belong|优惠券不属于该用户
 coupon_expired|优惠券已过期
 coupon_in_use|优惠券使用中
