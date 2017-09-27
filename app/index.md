* 功能: APP 首页，包括顶部轮播图、课程目录

* (GET) URL: /api/app/index

* request
```
http://apptest.bstcine.com/api/app/index?token=cb84Rvnc
```

* response
```
{
  "status": true,
  "data": {
    "lessoncategorys": [
      {
        "id": "d011501765721648rzJK3K4N32",
        "name": "词汇/写作/报刊精读",
        "status": "1",
        "remark": null,
        "seq": -10,
        "create_at": "2017-08-03 21:08:41",
        "create_by": "1",
        "update_at": "2017-09-01 15:18:55",
        "update_by": "1",
        "delete_at": null,
        "delete_by": null,
        "is_show_pc": "1",
        "is_show_ios": "1",
        "is_show_android": "1",
        "data": null,
        "type": "1",
        "icon": null,
        "tag": null,
        "children": [
          {
            "id": "d011502846526016MpDBrnsR8p",
            "name": "英美报刊精读-平权法案篇",
            "price": "168",
            "img": "2017/08/22/192030328SA4nFRZ.jpg",
            "total_join": 107,
            "lessoncategory_id": "d011501765721648rzJK3K4N32",
            "status": "1",
            "pay_status": 0
          }
        ]
      }
    ],
    "lunboImages": [
      {
        "lesson_id": "A011481685662619HkztzzwvxT",
        "name": "《小王子》上册精读课程",
        "img": "http://app.bstcine.com/web/img/picture1.png",
        "type": "1"
      },
      {
        "lesson_id": "d011453971898316wOnY4sRKIC",
        "name": "《查理和巧克力工厂》精读",
        "img": "http://app.bstcine.com/web/img/picture2.png",
        "type": "1"
      }
    ]
  }
}
```
