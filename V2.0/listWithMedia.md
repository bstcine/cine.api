* 功能: 课程的Chapter目录,包含medias

* URL: /api/content/chapter/listWithMedia

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
      "cid":"42",//course_id 
      "filter":["A011467016381932vY8AtkQpvq","xxxxxxaaaaxxx",....]  //lesson_id,可选参数，为空时返回所有lesson的medias,传入lesson_id时仅显示对应lesson的medias
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
        "rows": [
            {
                "id": "A011467016275998xPRiNro85z",
                "lesson_id": "A0114655235938391eWYkAGPbk",
                "parent_id": "1",
                "name": "Introduction",
                "short_name": null,
                "type": "1",
                "word_type": null,
                "duration": 0,
                "status": "1",
                "seq": -1,
                "is_free": "1",
                "update_at": null,
                "update_by": null,
                "medias": "",
                "children": [
                    {
                        "id": "A011467016381932vY8AtkQpvq",
                        "lesson_id": "A0114655235938391eWYkAGPbk",
                        "parent_id": "A011467016275998xPRiNro85z",
                        "name": "Introduction",
                        "short_name": "Introduction",
                        "type": "2",
                        "word_type": null,
                        "duration": 2518,
                        "status": "1",
                        "seq": 1,
                        "is_free": "1",
                        "update_at": "2017-03-15 10:15:34",
                        "update_by": "A011454493804858vCnC6NpgJi",
                        "medias": [
                            {
                                "type": "html",
                                "url": "2016/06/27/164013928SvU5PkY.mp3",
                                "duration": 225,
                                "images": [
                                    {
                                        "time": "0",
                                        "url": "2016/06/27/164128207STOtTUB.png"
                                    }
                                ],
                                "is_free": "1"
                            },
                            ...
                        ]
                    }
                ]
            },
            ...
        ]
    }
}
```
          
* 错误token response
```
{
    "code": "1",
    "code_desc": "success",
    "except_case": "",
    "except_case_desc": "no_login"
}
```
* token为空 response 中没有learn_status、lessonlearndetail_id、last_tag、last_position

备注： 关于 type 字段的疑惑，为何会有 1、2、html、video 等不同，请给出该字段的释义，如果是枚举值请列出详细参考值。
