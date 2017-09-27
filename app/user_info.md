* 功能: "我的"页面综合接口，包含用户基本信息、未支付数、未使用优惠券数、未分享数、未分享可领取积分

* (GET) URL: /api/app/userInfo

* request
```
http://apptest.bstcine.com/api/app/userInfo?token=cb84Rvnc
```

* response
```
{
    "status": true,
    "user": {
        "id": "466466466",
        "login": "studavid",
        "password": null,
        "nickname": "大卫",
        "email": "670121373@qq.com",
        "phone_code": "86",
        "phone": "17612169975",
        "role_id": "3",
        "status": "1",
        "head_image": "2017/06/02/d0114963866104022gHFgcZ2H4.jpg",
        "wechat": null,
        "wx_openid1": null,
        "wx_openid2": null,
        "wx_openid3": null,
        "wx_unionid": null,
        "create_at": null,
        "create_by": null,
        "update_at": "2017-09-25 18:08:32",
        "update_by": "466466466",
        "delete_at": null,
        "delete_by": null,
        "surname": "lv",
        "name": "david",
        "grade": "一年级",
        "gender": "2",
        "language": null,
        "country": null,
        "province": null,
        "city": "上海",
        "is_need_reset": "0",
        "is_app_logined": "1",
        "balance": 0,
        "point": 159,
        "agent_id": null,
        "unuseCouponsCount": 0,
        "unpayOrdersCount": 5,
        "unSharedOrders": 1,
        "unSharedPoint": 10
    }
}
```
