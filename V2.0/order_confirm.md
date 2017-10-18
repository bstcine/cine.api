* 功能: 确认订单

* URL: /api/order/confirm

* request
```
{
    "token":"r5QFdg7A",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{  
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
        "is_show_coupon": true,
        "is_show_point": true,
        "user": {
            "id": "d011495098151930dz0CsXrxSm",
            "login": "leo.zhang",
            "password": null,
            "nickname": "fdsafdsa",
            "email": null,
            "phone_code": "86",
            "phone": "18112382052",
            "role_id": "3",
            "status": "1",
            "head_image": null,
            "wechat": null,
            "wx_openid1": null,
            "wx_openid2": null,
            "wx_openid3": null,
            "wx_unionid": null,
            "create_at": "2017-05-18 17:02:31",
            "create_by": "d011495098151930dz0CsXrxSm",
            "update_at": "2017-10-10 09:34:23",
            "update_by": "d011495098151930dz0CsXrxSm",
            "delete_at": null,
            "delete_by": null,
            "surname": null,
            "name": null,
            "grade": null,
            "gender": "1",
            "language": null,
            "country": null,
            "province": null,
            "city": null,
            "is_need_reset": "0",
            "is_app_logined": "1",
            "balance": 0,
            "point": 12,
            "agent_id": "0"
        },
        "login": "leo.zhang",
        "lesson": {
            "id": "A011466215703591WQYDRNlWxH",
            "lessoncategory_id": "d011483588489325R1B2f1Z6dH",
            "name": "《人类的故事》精读课程",
            "author": "杨挚",
            "time_arrange": "90课时 (约30分钟/课时)",
            "feature": "<p class=\"p1\"> \t<span class=\"s1\"><span>1、精讲精读</span><br /> <span>2、配套练习</span><br /> <span>3、微信群读书社</span></span> </p> <p class=\"p1\"> \t<span class=\"s1\"></span>  </p>",
            "suit_to": "小学高年级-初中",
            "status": "1",
            "price": "2980",
            "img": "2017/03/11/102140770S6kpqqa.jpg",
            "img_ids": "d0114891989007703RDzNqnKDn,d011489198904039upnjVadwHt",
            "video": null,
            "is_free": "0",
            "contents": "{\"id\":\"A011466215703591WQYDRNlWxH\",\"name\":\"《人类的故事》精读课程\",",
            "total_join": 1096,
            "total_like": 3,
            "total_view": 0,
            "seq": 1,
            "create_at": null,
            "create_by": null,
            "update_at": "2017-10-18 14:54:40",
            "update_by": "1",
            "delete_at": null,
            "delete_by": null,
            "type": "1",
            "good": 0,
            "hot": 0,
            "product_type": "1",
            "packages": null,
            "try_contents": null,
            "original_price": null,
            "notice": null,
            "is_need_remark": "0",
            "is_show_pc": "1",
            "is_show_ios": "1",
            "is_show_android": "1",
            "is_full": "0",
            "share_marketing_id": null,
            "remark_ios": "<h2>\n\t内容介绍\n</h2>\n<p>\n\t美国作家房龙(1882-1944)的《人类的故事》是一本非常奇特的书。它的名字听起来很象是一本历史书。....",
            "remark_android":"...",
            "remark":"...",
            "object_type": "1",
            "related_lesson_id": null,
            "is_allow_coupon": "1",
            "base_join": 1000,
            "base_like": 0,
            "base_view": 0,
            "is_allow_point": "1",
            "featured_videos": null,
            "tag": null,
            "short_name": "《人类的故事》精读课程",
            "lesson_shareparam_id": "",
            "pay_shareparam_id": "",
            "learn_shareparam_id": "",
            "listen_shareparam_id": "",
            "share_h5_desc": null,
            "share_h5_img": null,
            "is_in_app": "0"
        },
        "calPrice": {
            "total_price": "2980",
            "discount_price": 0,
            "price": "2980",
            "pay_price": "2980"
        },
        "pointConvertConstant": "1"
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
 lesson_id_is_null|lesson_id为空 
 user_not_exist|用户不存在
 lesson_id_not_found|课程不存在
