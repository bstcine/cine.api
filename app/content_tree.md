* 功能: 课程目录

* (GET) URL: /api/app/contentTree

* request
```
http://apptest.bstcine.com/api/app/contentTree?token=cb84Rvnc&lesson_id=42
```

* response
```
{
  "status": true,
  "data": {
    "contentsTree": [
      {
        "id": "1313",
        "lesson_id": "42",
        "parent_id": "1",
        "name": "Chapter 1",
        "short_name": "",
        "type": "1",
        "word_type": null,
        "duration": 0,
        "status": "1",
        "seq": 208,
        "is_free": "0",
        "create_at": null,
        "create_by": null,
        "update_at": "2017-03-04 11:25:41",
        "update_by": "123321",
        "delete_at": null,
        "delete_by": null,
        "children": [
          {
            "id": "1314",
            "lesson_id": "42",
            "parent_id": "1313",
            "name": "Lesson 1",
            "short_name": "Lesson 1",
            "type": "2",
            "word_type": null,
            "duration": 1887,
            "status": "1",
            "seq": 1,
            "is_free": "1",
            "create_at": null,
            "create_by": null,
            "update_at": "2017-06-22 11:17:59",
            "update_by": "1",
            "delete_at": null,
            "delete_by": null
          }
        ]
      }
    ],
    "last_content_id": null,
    "last_parent_content_id": null
  }
}
```
