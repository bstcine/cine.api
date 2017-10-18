* 功能: 我的订单列表

* URL: /api/order/mylist

* request
```
{
    "token":"r5QFdg7A",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
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
        "cur_page": "",
        "max_page": "",
        "total_rows": "",
        "rows": {
            "order": [
                {
                    "id": "201710181156b3eTm",
                    "user_id": "d011495098151930dz0CsXrxSm",
                    "lesson_id": "A011466215703591WQYDRNlWxH",
                    "coupon_no": null,
                    "total_price": "2980",
                    "discount_price": "0.00",
                    "pay_price": "2980.00",
                    "pay_type": null,
                    "pay_status": "4",
                    "pay_at": null,
                    "username": "fdsafdsa",
                    "phone": "18112382052",
                    "status": "4",
                    "other_sn": null,
                    "other_account": null,
                    "other_account_name": null,
                    "ip": null,
                    "user_agent": "PostmanRuntime/6.2.5",
                    "remark": "undefined",
                    "create_at": "2017-10-18 11:56:39",
                    "create_by": "d011495098151930dz0CsXrxSm",
                    "update_at": "2017-10-18 15:38:58",
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
                    "agent_id": null,
                    "img": "2017/03/11/102140770S6kpqqa.jpg",
                    "object_type": "1",
                    "is_free": "0",
                    "is_show_share": false
                },
                ...
            ]
        }
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
 token_is_null|token为空
 order_id_is_null|order_id为空 
 order_not_found|订单不存在
