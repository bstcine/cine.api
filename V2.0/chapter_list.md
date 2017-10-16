* 功能: 课程的Chapter目录

* URL: /api/content/chapter/list

* request
```
{
    "token":"xTvcFJec",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
      "cid":"A0114655235938391eWYkAGPbk"  
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
    "contentsTree": [
      {
        "id": "1322",
        "lesson_id": "42",
        "parent_id": "1",
        "name": "General Introduction to Animal Farm",
        "short_name": "",
        "type": "1",
        "word_type": null,
        "duration": 0,
        "medias": "",
        "status": "1",
        "seq": 207,
        "is_free": "1",
        "create_at": null,
        "create_by": null,
        "update_at": "2017-03-04 13:54:56",
        "update_by": "123321",
        "delete_at": null,
        "delete_by": null,
        "learn_status": "2",
        "lessonlearndetail_id": "d011504753295341DUvgdaWdb7",
        "last_tag": "0",
        "last_position": "0",
        "children": [
          {
            "id": "1397",
            "lesson_id": "42",
            "parent_id": "1322",
            "name": "Introduction",
            "short_name": "Introduction",
            "type": "2",
            "word_type": null,
            "duration": 582,
            "medias": [
              {
                "type": "html",
                "url": "2016/08/31/175129614SbwIAGp.mp3",
                "duration": 66,
                "images": [
                  {
                    "time": "0",
                    "url": "2016/09/01/160210419SJInKBH.png"
                  }
                ],
                "is_free": "1"
              },
              ...
            ],
            "status": "1",
            "seq": 2,
            "is_free": "1",
            "create_at": null,
            "create_by": null,
            "update_at": "2017-03-15 10:16:40",
            "update_by": "A011454493804858vCnC6NpgJi",
            "delete_at": null,
            "delete_by": null,
            "learn_status": "2",
            "lessonlearndetail_id": "d011504753295240KwzCgRdN2P",
            "last_tag": "0",
            "last_position": "0"
          },
          ...
        ]
      }
    ],
    "last_content_id": "1315",
    "last_parent_content_id": "1313"
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
