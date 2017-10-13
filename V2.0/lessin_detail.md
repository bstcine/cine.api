* 功能: 课内容

* URL: /api/content/lesson/detail

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
      "content_id":1315
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
        "detail": {
            "id": "1315",
            "lesson_id": "42",
            "parent_id": "1313",
            "name": "Paragraph 2",
            "short_name": "Chapter1/Paragraph2",
            "type": "2",
            "quiz_id": null,
            "word_type": null,
            "medias": [
                {
                    "type": "html",
                    "url": "http://cdn.bstcine.com/mp3/42/f/2016/08/31/2243313Sk6IRqF.mp3",
                    "duration": 46,
                    "images": [
                        {
                            "time": "0",
                            "url": "http://cdn.bstcine.com/img/42/f/2016/08/31/23091565SDlxkjq.jpg.jpg"
                        }
                    ],
                    "is_free": "1"
                },
                {
                    "type": "html",
                    "url": "http://cdn.bstcine.com/mp3/42/f/2016/08/31/230620348Sgkd2lB.mp3",
                    "duration": 73,
                    "images": [
                        {
                            "time": "0",
                            "url": "http://cdn.bstcine.com/img/42/f/2016/08/31/230630252S8czlji.jpg.jpg"
                        }
                    ],
                    "is_free": "1"
                },
                {
                    "type": "html",
                    "url": "http://cdn.bstcine.com/mp3/42/f/2016/08/31/230650519SH1RkjN.mp3",
                    "duration": 45,
                    "images": [
                        {
                            "time": "0",
                            "url": "http://cdn.bstcine.com/img/42/f/2016/08/31/23070375SHzW8GE.jpg.jpg"
                        }
                    ],
                    "is_free": "1"
                },
                {
                    "type": "html",
                    "url": "http://cdn.bstcine.com/mp3/42/f/2016/08/31/230754663SbWMAyY.mp3",
                    "duration": 107,
                    "images": [
                        {
                            "time": "0",
                            "url": "http://cdn.bstcine.com/img/42/f/2016/08/31/230803900S8lxUbX.jpg.jpg"
                        }
                    ],
                    "is_free": "1"
                }
            ],
            "duration": 271,
            "remark": "<p style=\"text-align:justify;text-indent:2em;\">\n\t<span style=\"font-family:'font-size:18px;\"><span style=\"font-family:'Times New Roman';font-size:18px;\">As soon as the light in the bedroom went out there was a stirring and a fluttering all through the farm buildings.</span> <span style=\"font-size:18px;font-family:'Times New Roman';\"> Word had gone round during the day that old Major, the prize Middle White boar, had had a strange dream on the previous night and wished to communicate it to the other animals.&nbsp;</span></span><span style=\"font-size:18px;font-family:'Times New Roman';\"> &nbsp;</span><span style=\"font-family:'Times New Roman';font-size:18px;\">It had been agreed that they should all meet in the big barn as soon as Mr. Jones was safely out of the way.&nbsp;</span><span style=\"font-size:18px;font-family:'Times New Roman';\"> &nbsp;</span><span style=\"font-family:'Times New Roman';font-size:18px;\">Old Major (so he was always called, though the name under which he had been exhibited was Willingdon Beauty ) was so highly regarded on the farm that everyone was quite ready to lose an hour's sleep in order to hear what he had to say.</span><span style=\"font-size:18px;font-family:'Times New Roman';\"> </span> \n</p>\n<p style=\"text-align:justify;text-indent:2em;\">\n\t<span style=\"font-family:TimesNewRoman;font-size:12pt;\"></span> \n</p>\n<p>\n\t<br />\n</p>\n<p style=\"text-align:justify;text-indent:2em;\">\n\t<span style=\"font-family:'font-size:18px;\"></span> \n</p>",
            "status": "1",
            "seq": 2,
            "is_free": "1",
            "create_at": null,
            "create_by": null,
            "update_at": "2017-03-15 10:20:03",
            "update_by": "A011454493804858vCnC6NpgJi",
            "delete_at": null,
            "delete_by": null,
            "is_show_modal": "1"
        }
    }
}
```
