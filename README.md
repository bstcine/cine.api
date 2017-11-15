## API格式标准：request & response

####  Request
```
{
    "token":"1384595117-ddc161cb-3b93-4809-a54e-07ac49189737-178953",
    "sitecode": "cine.ios.ipad",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
        "wort":"bestimmt",
        .....       
    }
}


注：
sitecode:{
"苹果手机":"cine.ios.iphone",
"ipad":"cine.ios.ipad",
"安卓手机":"cine.android.iphone",
"安卓平板":"cine.android.pad",
"pc":'cine.web'
}
```

<br>

#### Response

- case: list

```json
{
    "code": 1,
    "code_desc": "success",
    "except_case": "101-01",
    "except_case_desc": "no record",
    "result": { 
        "cur_page": 3,
        "max_page": 281,
        "total_rows": 561,
        "rows": [
            {
                "id": "CA1709XFNzsBDJR27L8lh7LkeGEZCx",
                "cover_thumbnail_src": "http://i2.cdn.cnn0000000-super-tease.jpg",
                "cover_src": null,
                "title": "Trump retweets GIF of him hitting Clinton with golf ball",
                "subtitle": null,
                "original_url": "olitics/trump-tweet-clinton/index.html",
                "desc": "President Donald Trump retweeted an edited video Sunday m.",
                "format_type": 0,
                "body_match_level": 0,
                "channel_id": "",
                "tag_id": "t10003",
                "publish_at": "2017-09-17T17:52:32Z",
                "last_update_date": "2017-09-17 17:52:32",
                "is_recommend": false,
                "publish_status": 0
            },
            {
                "id": "CA1709RI28bF4NSISBKrZ+KpOhFBb1",
                "cover_thumbnail_src": "s/846963430.jpg?t=20170517",
                "cover_src": null,
                "title": "U.S. considering closing its embassy in Cuba",
                "subtitle": null,
                "original_url": "e1-f167-4010-8147-39dbe33edf35_story.html",
                "desc": "Tillerson said the move is “",
                "format_type": 0,
                "body_match_level": 0,
                "channel_id": "",
                "tag_id": "t10010",
                "publish_at": "2017-09-17T17:41:00Z",
                "last_update_date": "2017-09-17 17:41:00",
                "is_recommend": false,
                "publish_status": 0
            }
        ]
        
        
    }
       
}
```

- case: detail

```json
{
    "code": 1,
    "code_desc": "success",
    "except_case": "101-01",
    "except_case_desc": "no record",
    "result": {
        "detail": {
            "id": "CA1709XFNzsBDJR27L8lh7LkeGEZCx",
             "cover_thumbnail_src": "http://i2.cdn.cnn0000000-super-tease.jpg",
             "cover_src": null,
             "title": "Trump retweets GIF of him hitting Clinton with golf ball"
        }
    }
       
}
```
<br>

- case: other

```json
{
    "code": 1,
    "code_desc": "success",
    "except_case": "101-01",
    "except_case_desc": "no record",
    "result": {
       ...     
    }
       
}
```

<br>

#### app 相关api
[./app/README.md](./app/README.md)


#### pc/web 相关api
[./pc/web/README.md](./pc/web/README.md)


#### pc/admin 相关api
[./pc/admin/README.md](./pc/admin/README.md)
