* 功能: 课程评论

* URL: /api/content/course/comment

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
        "cid":"42"
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
                "id": 1,
                "user_id": "466466466",
                "course_id": "42",
                "lesson_id": null,
                "comment_desc": "课程内容很丰富，讲解清晰透彻",
                "comment_like_times": 100,
                "create_at": "2017-12-27 09:56:07",
                "create_by": "1",
                "update_at": "2017-12-27 09:56:07",
                "update_by": "1",
                "delete_at": null,
                "delete_by": null
            }
        ]
    }
}
```
          
  - 参数异常时 response
  
 except_case_desc|错误描述
 -|-
 course_id_is_null|课程id为空
 course comment not found|课程评论不存在
