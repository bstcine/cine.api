* 功能: APP 登录

* (GET) URL: /api/app/login

* request
```
http://apptest.bstcine.com/api/app/login?phone=studavid&password=123&phone_code=86&device_uid=BC452AB3-AEF3-4082-9ABF-179E47AB2070&device
```

* response
```
{
    "status": true,
    "go": "",
    "token": "cb84Rvnc",
    "user": {
        "id": "466466466",
        "login": "studavid",
        "password": null,
        "nickname": "大卫",
        "email": "670121373@qq.com",
        "phone_code": "86",
        "phone": "1761216997522",
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
        "update_at": "2017-09-24 23:48:36",
        "update_by": "1",
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
        "agent_id": null
    },
    "msg": "success"
}
```

