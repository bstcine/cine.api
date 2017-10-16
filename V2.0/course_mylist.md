* 功能: 我的学习列表

* URL: /api/user/content/course/list

* request
```
{
    "token":"", //nFmqtqzH
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{}
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
                "id": "A011472527975665L94hXeJDmJ",
                "name": "《人类的故事》微信读书群实录",
                "img": "2017/03/07/174819130Spmg9wG.jpg",
                "price": "免费热播中",
                "total_join": 1001,
                "seq": 1,
                "is_in_app": "0"
            },
            ...
        ]
    }
}
```
* 说明：token为空和正确的token返回值中rows数据不同,正确token rows示例如下：
```
{
                "id": "42",
                "name": "《动物农庄》精读课程",
                "img": "2017/03/11/102106363SVEwqmp.jpg",
                "price": "1",
                "total_join": 5553,
                "seq": 2,
                "is_in_app": "0",
                "status": "1",
                "progress": "3.8",
                "last_content_id": "1315",
                "last_content": "Chapter1/Paragraph2",
                "create_at": "2017-09-07 11:01:35",
                "update_at": "2017-10-13 14:02:07",
                "learn_days": 39
  },
  ...
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
