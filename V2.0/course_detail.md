* 功能: 课程详情

* URL: /api/content/course/detail

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
      "lesson_id":42
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
            "id": "42",
            "lessoncategory_id": "d011483588489325R1B2f1Z6dH",
            "name": "《动物农庄》精读课程",
            "author": "邱巍楠",
            "time_arrange": "40课时 (约30分钟/课时)",
            "feature": "1、精讲精读<br /> 2、配套练习<br /> 3、微信群读书社<br />",
            "suit_to": "适合托福70+或英文语言能力同等水平的学生。",
            "status": "1",
            "price": "1",
            "img": "2017/03/11/102106363SVEwqmp.jpg",
            "img_ids": "d011489198866363FjKCZ9mAQY,d011489198869612cnAKcDaSQa",
            "video": null,
            "is_free": "0",
            "contents": {
                "id": "42",
                "name": "《动物农庄》精讲",
                "children": [
                    {
                        "id": "1322",
                        "name": "General Introduction to Animal Farm",
                        "short_name": "",
                        "type": "1",
                        "is_free": true,
                        "children": [
                            {
                                "id": "1397",
                                "name": "Introduction",
                                "short_name": "Introduction",
                                "type": "2",
                                "is_free": true,
                                "duration": 582
                            }
                        ]
                    },
                    {
                        "id": "1313",
                        "name": "Chapter 1",
                        "short_name": "",
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A0114544817389786B1llm7v6n",
                                "name": "本章单词",
                                "short_name": "Chapter1/Word",
                                "type": "5",
                                "is_free": true
                            },
                            {
                                "id": "1314",
                                "name": "Paragraph 1",
                                "short_name": "Chapter1/Paragraph1",
                                "type": "2",
                                "is_free": true,
                                "duration": 223
                            },
                            {
                                "id": "1315",
                                "name": "Paragraph 2",
                                "short_name": "Chapter1/Paragraph2",
                                "type": "2",
                                "is_free": true,
                                "duration": 271
                            },
                            {
                                "id": "1316",
                                "name": "Paragraph 3",
                                "short_name": "Chapter1/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 1000
                            },
                            {
                                "id": "1317",
                                "name": "Paragraph 4",
                                "short_name": "Chapter1/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 393
                            },
                            {
                                "id": "1318",
                                "name": "Paragraph 5",
                                "short_name": "Chapter1/Paragraph5",
                                "type": "2",
                                "is_free": false,
                                "duration": 77
                            },
                            {
                                "id": "1319",
                                "name": "Paragraph 6",
                                "short_name": "Chapter1/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 230
                            },
                            {
                                "id": "1320",
                                "name": "Paragraph 7",
                                "short_name": "Chapter1/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 188
                            },
                            {
                                "id": "1321",
                                "name": "Paragraph 8",
                                "short_name": "Chapter1/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 325
                            },
                            {
                                "id": "A011472670490265n3bz6KJ9lP",
                                "name": "Paragraph 9",
                                "short_name": "Chapter/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 599
                            },
                            {
                                "id": "1399",
                                "name": "Paragraph 10",
                                "short_name": "Chapter1/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 311
                            },
                            {
                                "id": "1400",
                                "name": "Paragraph 11",
                                "short_name": "Chapter1/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 300
                            },
                            {
                                "id": "1401",
                                "name": "Paragraph 12",
                                "short_name": "Chapter1/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 268
                            },
                            {
                                "id": "1402",
                                "name": "Paragraph 13",
                                "short_name": "Chapter1/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 104
                            },
                            {
                                "id": "1403",
                                "name": "Paragraph 14",
                                "short_name": "Chapter1/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 44
                            },
                            {
                                "id": "1404",
                                "name": "Paragraph 15",
                                "short_name": "Chapter1/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 110
                            },
                            {
                                "id": "1405",
                                "name": "Paragraph 16",
                                "short_name": "Chapter1/Paragraph16",
                                "type": "2",
                                "is_free": false,
                                "duration": 224
                            },
                            {
                                "id": "1406",
                                "name": "Paragraph 17",
                                "short_name": "Chapter1/Paragraph17",
                                "type": "2",
                                "is_free": false,
                                "duration": 508
                            },
                            {
                                "id": "1407",
                                "name": "Paragraph 18",
                                "short_name": "Chapter1/Paragraph18",
                                "type": "2",
                                "is_free": false,
                                "duration": 43
                            },
                            {
                                "id": "1408",
                                "name": "Paragraph 19",
                                "short_name": "Chapter1/Paragraph19",
                                "type": "2",
                                "is_free": false,
                                "duration": 290
                            },
                            {
                                "id": "1409",
                                "name": "Paragraph 20",
                                "short_name": "Chapter1/Paragraph20",
                                "type": "2",
                                "is_free": false,
                                "duration": 338
                            },
                            {
                                "id": "d011454055395095VGZr3rUO9j",
                                "name": "Animal Farm Chapter 1 - 习题",
                                "short_name": "Chapter1/Exercise1",
                                "type": "4",
                                "is_free": true
                            },
                            {
                                "id": "d0114888521323045TKfT4xcJn",
                                "name": "Animal Farm Chapter 1 - 答案",
                                "short_name": "Chapter1/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    },
                    {
                        "id": "1410",
                        "name": "Chapter 2",
                        "short_name": null,
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A0114544938229828lNxe5JjHO",
                                "name": "本章单词",
                                "short_name": "Chapter2/Word",
                                "type": "5",
                                "is_free": false
                            },
                            {
                                "id": "1411",
                                "name": "Paragraph 1",
                                "short_name": "Chapter2/Paragraph1",
                                "type": "2",
                                "is_free": false,
                                "duration": 148
                            },
                            {
                                "id": "1412",
                                "name": "Paragraph 2",
                                "short_name": "Chapter2/Paragraph2",
                                "type": "2",
                                "is_free": false,
                                "duration": 1133
                            },
                            {
                                "id": "1413",
                                "name": "Paragraph 3",
                                "short_name": "Chapter2/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 437
                            },
                            {
                                "id": "1414",
                                "name": "Paragraph 4",
                                "short_name": "Chapter2/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 50
                            },
                            {
                                "id": "1415",
                                "name": "Paragraph 5",
                                "short_name": "Chapter2/Paragraph5",
                                "type": "3",
                                "is_free": false
                            },
                            {
                                "id": "1416",
                                "name": "Paragraph 6",
                                "short_name": "Chapter2/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 128
                            },
                            {
                                "id": "1417",
                                "name": "Paragraph 7",
                                "short_name": "Chapter2/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 30
                            },
                            {
                                "id": "1418",
                                "name": "Paragraph 8",
                                "short_name": "Chapter2/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 428
                            },
                            {
                                "id": "1419",
                                "name": "Paragraph 9",
                                "short_name": "Chapter2/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 158
                            },
                            {
                                "id": "1420",
                                "name": "Paragraph 10",
                                "short_name": "Chapter2/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 271
                            },
                            {
                                "id": "1421",
                                "name": "Paragraph 11",
                                "short_name": "Chapter2/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 612
                            },
                            {
                                "id": "1422",
                                "name": "Paragraph 12",
                                "short_name": "Chapter2/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 181
                            },
                            {
                                "id": "1423",
                                "name": "Paragraph 13",
                                "short_name": "Chapter2/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 404
                            },
                            {
                                "id": "1424",
                                "name": "Paragraph 14",
                                "short_name": "Chapter2/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 32
                            },
                            {
                                "id": "1425",
                                "name": "Paragraph 15",
                                "short_name": "Chapter2/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 61
                            },
                            {
                                "id": "1426",
                                "name": "Paragraph 16",
                                "short_name": "Chapter2/Paragraph16",
                                "type": "2",
                                "is_free": false,
                                "duration": 169
                            },
                            {
                                "id": "1427",
                                "name": "Paragraph 17",
                                "short_name": "Chapter2/Paragraph17",
                                "type": "2",
                                "is_free": false,
                                "duration": 345
                            },
                            {
                                "id": "1428",
                                "name": "Paragraph 18",
                                "short_name": "Chapter2/Paragraph18",
                                "type": "2",
                                "is_free": false,
                                "duration": 435
                            },
                            {
                                "id": "1429",
                                "name": "Paragraph 19",
                                "short_name": "Chapter2/Paragraph19",
                                "type": "2",
                                "is_free": false,
                                "duration": 0
                            },
                            {
                                "id": "1430",
                                "name": "Paragraph 20",
                                "short_name": "Chapter2/Paragraph20",
                                "type": "2",
                                "is_free": false,
                                "duration": 53
                            },
                            {
                                "id": "1431",
                                "name": "Paragraph 21",
                                "short_name": "Chapter2/Paragraph21",
                                "type": "2",
                                "is_free": false,
                                "duration": 728
                            },
                            {
                                "id": "1432",
                                "name": "Paragraph 22",
                                "short_name": "Chapter2/Paragraph22",
                                "type": "2",
                                "is_free": false,
                                "duration": 85
                            },
                            {
                                "id": "1433",
                                "name": "Paragraph 23",
                                "short_name": "Chapter2/Paragraph23",
                                "type": "2",
                                "is_free": false,
                                "duration": 55
                            },
                            {
                                "id": "1434",
                                "name": "Paragraph 24",
                                "short_name": "Chapter2/Paragraph24",
                                "type": "2",
                                "is_free": false,
                                "duration": 189
                            },
                            {
                                "id": "1435",
                                "name": "Paragraph 25",
                                "short_name": "Chapter2/Paragraph25",
                                "type": "2",
                                "is_free": false,
                                "duration": 0
                            },
                            {
                                "id": "1436",
                                "name": "Paragraph 26",
                                "short_name": "Chapter2/Paragraph26",
                                "type": "2",
                                "is_free": false,
                                "duration": 54
                            },
                            {
                                "id": "1437",
                                "name": "Paragraph 27",
                                "short_name": "Chapter2/Paragraph27",
                                "type": "2",
                                "is_free": false,
                                "duration": 58
                            },
                            {
                                "id": "1438",
                                "name": "Paragraph 28",
                                "short_name": "Chapter2/Paragraph28",
                                "type": "2",
                                "is_free": false,
                                "duration": 97
                            },
                            {
                                "id": "d011454055420008A8AIZnBVte",
                                "name": "Animal Farm Chapter 2 - 习题",
                                "short_name": "Chapter2/Exercise1",
                                "type": "4",
                                "is_free": false
                            },
                            {
                                "id": "d011488853342227Z8jdf2kwkM",
                                "name": "Animal Farm Chapter 2 - 答案",
                                "short_name": "Chapter2/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    },
                    {
                        "id": "1439",
                        "name": "Chapter 3",
                        "short_name": null,
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A011454493852815MGRS9eFmNO",
                                "name": "本章单词",
                                "short_name": "Chapter3/Word",
                                "type": "5",
                                "is_free": false
                            },
                            {
                                "id": "1440",
                                "name": "Paragraph 1",
                                "short_name": "Chapter3/Paragraph1",
                                "type": "2",
                                "is_free": false,
                                "duration": 45
                            },
                            {
                                "id": "1441",
                                "name": "Paragraph 2",
                                "short_name": "Chapter3/Paragraph2",
                                "type": "2",
                                "is_free": false,
                                "duration": 520
                            },
                            {
                                "id": "1442",
                                "name": "Paragraph 3",
                                "short_name": "Chapter3/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 560
                            },
                            {
                                "id": "1443",
                                "name": "Paragraph 4",
                                "short_name": "Chapter3/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 673
                            },
                            {
                                "id": "1444",
                                "name": "Paragraph 5",
                                "short_name": "Chapter3/Paragraph5",
                                "type": "2",
                                "is_free": false,
                                "duration": 645
                            },
                            {
                                "id": "1445",
                                "name": "Paragraph 6",
                                "short_name": "Chapter3/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 497
                            },
                            {
                                "id": "1446",
                                "name": "Paragraph 7",
                                "short_name": "Chapter3/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 42
                            },
                            {
                                "id": "1447",
                                "name": "Paragraph 8",
                                "short_name": "Chapter3/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 524
                            },
                            {
                                "id": "1448",
                                "name": "Paragraph 9",
                                "short_name": "Chapter3/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 202
                            },
                            {
                                "id": "1449",
                                "name": "Paragraph 10",
                                "short_name": "Chapter3/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 85
                            },
                            {
                                "id": "1450",
                                "name": "Paragraph 11",
                                "short_name": "Chapter3/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 136
                            },
                            {
                                "id": "1451",
                                "name": "Paragraph 12",
                                "short_name": "Chapter3/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 227
                            },
                            {
                                "id": "1452",
                                "name": "Paragraph 13",
                                "short_name": "Chapter3/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 221
                            },
                            {
                                "id": "1453",
                                "name": "Paragraph 14",
                                "short_name": "Chapter3/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 345
                            },
                            {
                                "id": "18614442938461921951334435",
                                "name": "Paragraph 15",
                                "short_name": "Chapter3/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 594
                            },
                            {
                                "id": "d011454055439381YYNmaCatw6",
                                "name": "Animal Farm Chapter 3 - 习题",
                                "short_name": "Chapter3/Exercise1",
                                "type": "4",
                                "is_free": false
                            },
                            {
                                "id": "d011488853405166FzbevUpdDD",
                                "name": "Animal Farm Chapter 3 - 答案",
                                "short_name": "Chapter3/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    },
                    {
                        "id": "1454",
                        "name": "Chapter 4",
                        "short_name": null,
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A011454493873230D7gDzDvCcE",
                                "name": "本章单词",
                                "short_name": "Chapter4/Exercise",
                                "type": "5",
                                "is_free": false
                            },
                            {
                                "id": "1455",
                                "name": "Paragraph 1",
                                "short_name": "Chapter4/Paragraph1",
                                "type": "2",
                                "is_free": false,
                                "duration": 258
                            },
                            {
                                "id": "1456",
                                "name": "Paragraph 2",
                                "short_name": "Chapter4/Paragraph2",
                                "type": "2",
                                "is_free": false,
                                "duration": 678
                            },
                            {
                                "id": "1457",
                                "name": "Paragraph 3",
                                "short_name": "Chapter4/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 421
                            },
                            {
                                "id": "1458",
                                "name": "Paragraph 4",
                                "short_name": "Chapter4/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 582
                            },
                            {
                                "id": "1459",
                                "name": "Paragraph 5",
                                "short_name": "Chapter4/Paragraph5",
                                "type": "2",
                                "is_free": false,
                                "duration": 167
                            },
                            {
                                "id": "1460",
                                "name": "Paragraph 6",
                                "short_name": "Chapter4/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 90
                            },
                            {
                                "id": "1461",
                                "name": "Paragraph 7",
                                "short_name": "Chapter4/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 355
                            },
                            {
                                "id": "1462",
                                "name": "Paragraph 8",
                                "short_name": "Chapter4/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 833
                            },
                            {
                                "id": "1463",
                                "name": "Paragraph 9",
                                "short_name": "Chapter4/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 68
                            },
                            {
                                "id": "1464",
                                "name": "Paragraph 10",
                                "short_name": "Chapter4/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 39
                            },
                            {
                                "id": "1465",
                                "name": "Paragraph 11",
                                "short_name": "Chapter4/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 57
                            },
                            {
                                "id": "1466",
                                "name": "Paragraph 12",
                                "short_name": "Chapter4/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 22
                            },
                            {
                                "id": "1467",
                                "name": "Paragraph 13",
                                "short_name": "Chapter4/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 0
                            },
                            {
                                "id": "1468",
                                "name": "Paragraph 14",
                                "short_name": "Chapter4/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 264
                            },
                            {
                                "id": "1469",
                                "name": "Paragraph 15",
                                "short_name": "Chapter4/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 252
                            },
                            {
                                "id": "1470",
                                "name": "Paragraph 16",
                                "short_name": "Chapter4/Paragraph16",
                                "type": "2",
                                "is_free": false,
                                "duration": 178
                            },
                            {
                                "id": "1471",
                                "name": "Paragraph 17",
                                "short_name": "Chapter4/Paragraph17",
                                "type": "2",
                                "is_free": false,
                                "duration": 249
                            },
                            {
                                "id": "18614443723685171707357813",
                                "name": "Questions For Review and Discussion",
                                "short_name": "Questions and Discussion",
                                "type": "2",
                                "is_free": false,
                                "duration": 130
                            },
                            {
                                "id": "d011454055500582VMca7NCY9G",
                                "name": "Animal Farm Chapter 4 - 习题",
                                "short_name": "Chapter4/Exercise1",
                                "type": "4",
                                "is_free": false
                            },
                            {
                                "id": "d011488853561471AxhqRaRy79",
                                "name": "Animal Farm Chapter 4 - 答案",
                                "short_name": "Chapter4/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    },
                    {
                        "id": "1472",
                        "name": "Chapter 5",
                        "short_name": null,
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A011454493894806qsfOGdaavZ",
                                "name": "本章单词",
                                "short_name": "Chapter5/Word",
                                "type": "5",
                                "is_free": false
                            },
                            {
                                "id": "1473",
                                "name": "Paragraph 1",
                                "short_name": "Chapter5/Paragraph1",
                                "type": "2",
                                "is_free": false,
                                "duration": 250
                            },
                            {
                                "id": "1474",
                                "name": "Paragraph 2",
                                "short_name": "Chapter5/Paragraph2",
                                "type": "2",
                                "is_free": false,
                                "duration": 69
                            },
                            {
                                "id": "1475",
                                "name": "Paragraph 3",
                                "short_name": "Chapter5/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 25
                            },
                            {
                                "id": "1476",
                                "name": "Paragraph 4",
                                "short_name": "Chapter5/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 36
                            },
                            {
                                "id": "1477",
                                "name": "Paragraph 5",
                                "short_name": "Chapter5/Paragraph5",
                                "type": "2",
                                "is_free": false,
                                "duration": 22
                            },
                            {
                                "id": "1478",
                                "name": "Paragraph 6",
                                "short_name": "Chapter5/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 99
                            },
                            {
                                "id": "1479",
                                "name": "Paragraph 7",
                                "short_name": "Chapter5/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 224
                            },
                            {
                                "id": "1480",
                                "name": "Paragraph 8",
                                "short_name": "Chapter5/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 761
                            },
                            {
                                "id": "1481",
                                "name": "Paragraph 9",
                                "short_name": "Chapter5/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 243
                            },
                            {
                                "id": "1482",
                                "name": "Paragraph 10",
                                "short_name": "Chapter5/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 672
                            },
                            {
                                "id": "1483",
                                "name": "Paragraph 11",
                                "short_name": "Chapter5/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 443
                            },
                            {
                                "id": "1484",
                                "name": "Paragraph 12",
                                "short_name": "Chapter5/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 372
                            },
                            {
                                "id": "1485",
                                "name": "Paragraph 13",
                                "short_name": "Chapter5/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 562
                            },
                            {
                                "id": "1486",
                                "name": "Paragraph 14",
                                "short_name": "Chapter5/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 331
                            },
                            {
                                "id": "1487",
                                "name": "Paragraph 15",
                                "short_name": "Chapter5/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 248
                            },
                            {
                                "id": "1488",
                                "name": "Paragraph 16",
                                "short_name": "Chapter5/Paragraph16",
                                "type": "2",
                                "is_free": false,
                                "duration": 241
                            },
                            {
                                "id": "1489",
                                "name": "Paragraph 17",
                                "short_name": "Chapter5/Paragraph17",
                                "type": "2",
                                "is_free": false,
                                "duration": 325
                            },
                            {
                                "id": "1490",
                                "name": "Paragraph 18",
                                "short_name": "Chapter5/Paragraph18",
                                "type": "2",
                                "is_free": false,
                                "duration": 0
                            },
                            {
                                "id": "1491",
                                "name": "Paragraph 19",
                                "short_name": "Chapter5/Paragraph19",
                                "type": "2",
                                "is_free": false,
                                "duration": 226
                            },
                            {
                                "id": "1492",
                                "name": "Paragraph 20",
                                "short_name": "Chapter5/Paragraph20",
                                "type": "2",
                                "is_free": false,
                                "duration": 0
                            },
                            {
                                "id": "1493",
                                "name": "Paragraph 21",
                                "short_name": "Chapter5/Paragraph21",
                                "type": "2",
                                "is_free": false,
                                "duration": 99
                            },
                            {
                                "id": "1494",
                                "name": "Paragraph 22",
                                "short_name": "Chapter5/Paragraph22",
                                "type": "2",
                                "is_free": false,
                                "duration": 162
                            },
                            {
                                "id": "1495",
                                "name": "Paragraph 23",
                                "short_name": "Chapter5/Paragraph23",
                                "type": "2",
                                "is_free": false,
                                "duration": 331
                            },
                            {
                                "id": "1496",
                                "name": "Paragraph 24",
                                "short_name": "Chapter5/Paragraph24",
                                "type": "2",
                                "is_free": false,
                                "duration": 145
                            },
                            {
                                "id": "1497",
                                "name": "Paragraph 25",
                                "short_name": "Chapter5/Paragraph25",
                                "type": "2",
                                "is_free": false,
                                "duration": 325
                            },
                            {
                                "id": "d011454055547517BBHg8OhEH5",
                                "name": "Animal Farm Chapter 5 - 习题",
                                "short_name": "Chapter5/Exercise1",
                                "type": "4",
                                "is_free": false
                            },
                            {
                                "id": "d011488853607473bCqRURd9XQ",
                                "name": "Animal Farm Chapter 5 - 答案",
                                "short_name": "Chapter5/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    },
                    {
                        "id": "1498",
                        "name": "Chapter 6",
                        "short_name": null,
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A011454493917039xgFSp9dI5w",
                                "name": "本章单词",
                                "short_name": "Chapter6/Word",
                                "type": "5",
                                "is_free": false
                            },
                            {
                                "id": "1499",
                                "name": "Paragraph 1",
                                "short_name": "Chapter6/Paragraph1",
                                "type": "2",
                                "is_free": false,
                                "duration": 131
                            },
                            {
                                "id": "1500",
                                "name": "Paragraph 2",
                                "short_name": "Chapter6/Paragraph2",
                                "type": "2",
                                "is_free": false,
                                "duration": 242
                            },
                            {
                                "id": "1501",
                                "name": "Paragraph 3",
                                "short_name": "Chapter6/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 446
                            },
                            {
                                "id": "1502",
                                "name": "Paragraph 4",
                                "short_name": "Chapter6/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 526
                            },
                            {
                                "id": "1503",
                                "name": "Paragraph 5",
                                "short_name": "Chapter6/Paragraph5",
                                "type": "2",
                                "is_free": false,
                                "duration": 350
                            },
                            {
                                "id": "1504",
                                "name": "Paragraph 6",
                                "short_name": "Chapter6/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 233
                            },
                            {
                                "id": "1505",
                                "name": "Paragraph 7",
                                "short_name": "Chapter6/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 459
                            },
                            {
                                "id": "1506",
                                "name": "Paragraph 8",
                                "short_name": "Chapter6/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 211
                            },
                            {
                                "id": "1507",
                                "name": "Paragraph 9",
                                "short_name": "Chapter6/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 677
                            },
                            {
                                "id": "1508",
                                "name": "Paragraph 10",
                                "short_name": "Chapter6/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 350
                            },
                            {
                                "id": "1509",
                                "name": "Paragraph 11",
                                "short_name": "Chapter6/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 56
                            },
                            {
                                "id": "1510",
                                "name": "Paragraph 12",
                                "short_name": "Chapter6/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 0
                            },
                            {
                                "id": "1511",
                                "name": "Paragraph 13",
                                "short_name": "Chapter6/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 0
                            },
                            {
                                "id": "1512",
                                "name": "Paragraph 14",
                                "short_name": "Chapter6/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 175
                            },
                            {
                                "id": "1513",
                                "name": "Paragraph 15",
                                "short_name": "Chapter6/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 183
                            },
                            {
                                "id": "1514",
                                "name": "Paragraph 16",
                                "short_name": "Chapter6/Paragraph16",
                                "type": "2",
                                "is_free": false,
                                "duration": 105
                            },
                            {
                                "id": "1515",
                                "name": "Paragraph 17",
                                "short_name": "Chapter6/Paragraph17",
                                "type": "2",
                                "is_free": false,
                                "duration": 326
                            },
                            {
                                "id": "1516",
                                "name": "Paragraph 18",
                                "short_name": "Chapter6/Paragraph18",
                                "type": "2",
                                "is_free": false,
                                "duration": 212
                            },
                            {
                                "id": "1517",
                                "name": "Paragraph 19",
                                "short_name": "Chapter6/Paragraph19",
                                "type": "2",
                                "is_free": false,
                                "duration": 242
                            },
                            {
                                "id": "1518",
                                "name": "Paragraph 20",
                                "short_name": "Chapter6/Paragraph20",
                                "type": "2",
                                "is_free": false,
                                "duration": 234
                            },
                            {
                                "id": "1519",
                                "name": "Paragraph 21",
                                "short_name": "Chapter6/Paragraph21",
                                "type": "2",
                                "is_free": false,
                                "duration": 177
                            },
                            {
                                "id": "1520",
                                "name": "Paragraph 22",
                                "short_name": "Chapter6/Paragraph22",
                                "type": "2",
                                "is_free": false,
                                "duration": 171
                            },
                            {
                                "id": "d011454055589083K4cimNajjk",
                                "name": "Animal Farm Chapter 6 - 习题",
                                "short_name": "Chapter6/Exercise1",
                                "type": "4",
                                "is_free": false
                            },
                            {
                                "id": "d011488853777727KYxqWJ90QE",
                                "name": "Animal Farm Chapter 6 - 答案",
                                "short_name": "Chapter6/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    },
                    {
                        "id": "1521",
                        "name": "Chapter 7",
                        "short_name": null,
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A011454493936463L5FIDIB5n8",
                                "name": "本章单词",
                                "short_name": "Chapter7/Word",
                                "type": "5",
                                "is_free": false
                            },
                            {
                                "id": "1522",
                                "name": "Paragraph 1",
                                "short_name": "Chapter7/Paragraph1",
                                "type": "2",
                                "is_free": false,
                                "duration": 205
                            },
                            {
                                "id": "1523",
                                "name": "Paragraph 2",
                                "short_name": "Chapter7/Paragraph2",
                                "type": "2",
                                "is_free": false,
                                "duration": 358
                            },
                            {
                                "id": "1524",
                                "name": "Paragraph 3",
                                "short_name": "Chapter7/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 221
                            },
                            {
                                "id": "1525",
                                "name": "Paragraph 4",
                                "short_name": "Chapter7/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 513
                            },
                            {
                                "id": "1526",
                                "name": "Paragraph 5",
                                "short_name": "Chapter7/Paragraph5",
                                "type": "2",
                                "is_free": false,
                                "duration": 186
                            },
                            {
                                "id": "1527",
                                "name": "Paragraph 6",
                                "short_name": "Chapter7/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 109
                            },
                            {
                                "id": "1528",
                                "name": "Paragraph 7",
                                "short_name": "Chapter7/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 424
                            },
                            {
                                "id": "1529",
                                "name": "Paragraph 8",
                                "short_name": "Chapter7/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 247
                            },
                            {
                                "id": "1530",
                                "name": "Paragraph 9",
                                "short_name": "Chapter7/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 275
                            },
                            {
                                "id": "1531",
                                "name": "Paragraph 10",
                                "short_name": "Chapter7/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 290
                            },
                            {
                                "id": "1532",
                                "name": "Paragraph 11",
                                "short_name": "Chapter7/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 106
                            },
                            {
                                "id": "1533",
                                "name": "Paragraph 12",
                                "short_name": "Chapter7/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 295
                            },
                            {
                                "id": "1534",
                                "name": "Paragraph 13",
                                "short_name": "Chapter7/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 236
                            },
                            {
                                "id": "1535",
                                "name": "Paragraph 14",
                                "short_name": "Chapter7/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 35
                            },
                            {
                                "id": "1536",
                                "name": "Paragraph 15",
                                "short_name": "Chapter7/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 56
                            },
                            {
                                "id": "1537",
                                "name": "Paragraph 16",
                                "short_name": "Chapter7/Paragraph16",
                                "type": "2",
                                "is_free": false,
                                "duration": 71
                            },
                            {
                                "id": "1538",
                                "name": "Paragraph 17",
                                "short_name": "Chapter7/Paragraph17",
                                "type": "2",
                                "is_free": false,
                                "duration": 218
                            },
                            {
                                "id": "1539",
                                "name": "Paragraph 18",
                                "short_name": "Chapter7/Paragraph18",
                                "type": "2",
                                "is_free": false,
                                "duration": 87
                            },
                            {
                                "id": "1540",
                                "name": "Paragraph 19",
                                "short_name": "Chapter7/Paragraph19",
                                "type": "2",
                                "is_free": false,
                                "duration": 40
                            },
                            {
                                "id": "1541",
                                "name": "Paragraph 20",
                                "short_name": "Chapter7/Paragraph20",
                                "type": "2",
                                "is_free": false,
                                "duration": 54
                            },
                            {
                                "id": "1542",
                                "name": "Paragraph 21",
                                "short_name": "Chapter7/Paragraph21",
                                "type": "2",
                                "is_free": false,
                                "duration": 49
                            },
                            {
                                "id": "1543",
                                "name": "Paragraph 22",
                                "short_name": "Chapter7/Paragraph22",
                                "type": "2",
                                "is_free": false,
                                "duration": 46
                            },
                            {
                                "id": "1544",
                                "name": "Paragraph 23",
                                "short_name": "Chapter7/Paragraph23",
                                "type": "2",
                                "is_free": false,
                                "duration": 154
                            },
                            {
                                "id": "1545",
                                "name": "Paragraph 24",
                                "short_name": "Chapter7/Paragraph24",
                                "type": "2",
                                "is_free": false,
                                "duration": 258
                            },
                            {
                                "id": "1546",
                                "name": "Paragraph 25",
                                "short_name": "Chapter7/Paragraph25",
                                "type": "2",
                                "is_free": false,
                                "duration": 325
                            },
                            {
                                "id": "1547",
                                "name": "Paragraph 26",
                                "short_name": "Chapter7/Paragraph26",
                                "type": "2",
                                "is_free": false,
                                "duration": 257
                            },
                            {
                                "id": "1548",
                                "name": "Paragraph 27",
                                "short_name": "Chapter7/Paragraph27",
                                "type": "2",
                                "is_free": false,
                                "duration": 422
                            },
                            {
                                "id": "1549",
                                "name": "Paragraph 28",
                                "short_name": "Chapter7/Paragraph28",
                                "type": "2",
                                "is_free": false,
                                "duration": 47
                            },
                            {
                                "id": "1550",
                                "name": "Paragraph 29",
                                "short_name": "Chapter7/Paragraph29",
                                "type": "2",
                                "is_free": false,
                                "duration": 51
                            },
                            {
                                "id": "1551",
                                "name": "Paragraph 30",
                                "short_name": "Chapter7/Paragraph30",
                                "type": "2",
                                "is_free": false,
                                "duration": 679
                            },
                            {
                                "id": "1552",
                                "name": "Paragraph 31",
                                "short_name": "Chapter7/Paragraph31",
                                "type": "2",
                                "is_free": false,
                                "duration": 87
                            },
                            {
                                "id": "1553",
                                "name": "Paragraph 32",
                                "short_name": "Chapter7/Paragraph32",
                                "type": "2",
                                "is_free": false,
                                "duration": 130
                            },
                            {
                                "id": "1556",
                                "name": "Paragraph 33",
                                "short_name": "Chapter7/Paragraph33",
                                "type": "2",
                                "is_free": false,
                                "duration": 108
                            },
                            {
                                "id": "1557",
                                "name": "Paragraph 34",
                                "short_name": "Chapter7/Paragraph34",
                                "type": "2",
                                "is_free": false,
                                "duration": 61
                            },
                            {
                                "id": "1558",
                                "name": "Paragraph 35",
                                "short_name": "Chapter7/Paragraph35",
                                "type": "2",
                                "is_free": false,
                                "duration": 119
                            },
                            {
                                "id": "d0114540556172547j1Elv28Dh",
                                "name": "Animal Farm Chapter 7 - 习题",
                                "short_name": "Chapter7/Exercise1",
                                "type": "4",
                                "is_free": false
                            },
                            {
                                "id": "d011488853882564w6HgCRDkHJ",
                                "name": "Animal Farm Chapter 7 - 答案",
                                "short_name": "Chapter7/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    },
                    {
                        "id": "1559",
                        "name": "Chapter 8",
                        "short_name": null,
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A011454493961878PwWi75Fvr7",
                                "name": "本章单词",
                                "short_name": "Chapter8/Word",
                                "type": "5",
                                "is_free": false
                            },
                            {
                                "id": "1560",
                                "name": "Paragraph 1",
                                "short_name": "Chapter8/Paragraph1",
                                "type": "2",
                                "is_free": false,
                                "duration": 312
                            },
                            {
                                "id": "1561",
                                "name": "Paragraph 2",
                                "short_name": "Chapter8/Paragraph2",
                                "type": "2",
                                "is_free": false,
                                "duration": 308
                            },
                            {
                                "id": "1562",
                                "name": "Paragraph 3",
                                "short_name": "Chapter8/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 234
                            },
                            {
                                "id": "1563",
                                "name": "Paragraph 4",
                                "short_name": "Chapter8/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 888
                            },
                            {
                                "id": "1564",
                                "name": "Paragraph 5",
                                "short_name": "Chapter8/Paragraph5",
                                "type": "2",
                                "is_free": false,
                                "duration": 86
                            },
                            {
                                "id": "1565",
                                "name": "Paragraph 6",
                                "short_name": "Chapter8/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 291
                            },
                            {
                                "id": "1566",
                                "name": "Paragraph 7",
                                "short_name": "Chapter8/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 463
                            },
                            {
                                "id": "1567",
                                "name": "Paragraph 8",
                                "short_name": "Chapter8/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 465
                            },
                            {
                                "id": "1568",
                                "name": "Paragraph 9",
                                "short_name": "Chapter8/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 556
                            },
                            {
                                "id": "1569",
                                "name": "Paragraph 10",
                                "short_name": "Chapter8/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 214
                            },
                            {
                                "id": "1570",
                                "name": "Paragraph 11",
                                "short_name": "Chapter8/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 185
                            },
                            {
                                "id": "1571",
                                "name": "Paragraph 12",
                                "short_name": "Chapter8/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 231
                            },
                            {
                                "id": "1572",
                                "name": "Paragraph 13",
                                "short_name": "Chapter8/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 136
                            },
                            {
                                "id": "1573",
                                "name": "Paragraph 14",
                                "short_name": "Chapter8/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 164
                            },
                            {
                                "id": "1574",
                                "name": "Paragraph 15",
                                "short_name": "Chapter8/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 171
                            },
                            {
                                "id": "1575",
                                "name": "Paragraph 16",
                                "short_name": "Chapter8/Paragraph16",
                                "type": "2",
                                "is_free": false,
                                "duration": 398
                            },
                            {
                                "id": "1576",
                                "name": "Paragraph 17",
                                "short_name": "Chapter8/Paragraph17",
                                "type": "2",
                                "is_free": false,
                                "duration": 53
                            },
                            {
                                "id": "1578",
                                "name": "Paragraph 18",
                                "short_name": "Chapter8/Paragraph18",
                                "type": "2",
                                "is_free": false,
                                "duration": 48
                            },
                            {
                                "id": "1579",
                                "name": "Paragraph 19",
                                "short_name": "Chapter8/Paragraph19",
                                "type": "2",
                                "is_free": false,
                                "duration": 52
                            },
                            {
                                "id": "1580",
                                "name": "Paragraph 20",
                                "short_name": "Chapter8/Paragraph20",
                                "type": "2",
                                "is_free": false,
                                "duration": 110
                            },
                            {
                                "id": "1581",
                                "name": "Paragraph 21",
                                "short_name": "Chapter8/Paragraph21",
                                "type": "2",
                                "is_free": false,
                                "duration": 511
                            },
                            {
                                "id": "1582",
                                "name": "Paragraph 22",
                                "short_name": "Chapter8/Paragraph22",
                                "type": "2",
                                "is_free": false,
                                "duration": 210
                            },
                            {
                                "id": "1583",
                                "name": "Paragraph 23",
                                "short_name": "Chapter8/Paragraph23",
                                "type": "2",
                                "is_free": false,
                                "duration": 64
                            },
                            {
                                "id": "1586",
                                "name": "Paragraph 24",
                                "short_name": "Chapter8/Paragraph24",
                                "type": "2",
                                "is_free": false,
                                "duration": 63
                            },
                            {
                                "id": "1588",
                                "name": "Paragraph 25",
                                "short_name": "Chapter8/Paragraph25",
                                "type": "2",
                                "is_free": false,
                                "duration": 27
                            },
                            {
                                "id": "1589",
                                "name": "Paragraph 26",
                                "short_name": "Chapter8/Paragraph26",
                                "type": "2",
                                "is_free": false,
                                "duration": 75
                            },
                            {
                                "id": "1592",
                                "name": "Paragraph 27",
                                "short_name": "Chapter8/Paragraph27",
                                "type": "2",
                                "is_free": false,
                                "duration": 129
                            },
                            {
                                "id": "1593",
                                "name": "Paragraph 28",
                                "short_name": "Chapter8/Paragraph28",
                                "type": "2",
                                "is_free": false,
                                "duration": 281
                            },
                            {
                                "id": "1594",
                                "name": "Paragraph 29",
                                "short_name": "Chapter8/Paragraph29",
                                "type": "2",
                                "is_free": false,
                                "duration": 271
                            },
                            {
                                "id": "1595",
                                "name": "Paragraph 30",
                                "short_name": "Chapter8/Paragraph30",
                                "type": "2",
                                "is_free": false,
                                "duration": 166
                            },
                            {
                                "id": "1596",
                                "name": "Paragraph 31",
                                "short_name": "Chapter8/Paragraph31",
                                "type": "2",
                                "is_free": false,
                                "duration": 229
                            },
                            {
                                "id": "1597",
                                "name": "Paragraph 32",
                                "short_name": "Chapter8/Paragraph32",
                                "type": "2",
                                "is_free": false,
                                "duration": 285
                            },
                            {
                                "id": "1598",
                                "name": "Paragraph 33",
                                "short_name": "Chapter8/Paragraph33",
                                "type": "2",
                                "is_free": false,
                                "duration": 87
                            },
                            {
                                "id": "d0114540558767344hMonKWIFD",
                                "name": "Animal Farm Chapter 8 - 习题",
                                "short_name": "Chapter8/Exercise1",
                                "type": "4",
                                "is_free": false
                            },
                            {
                                "id": "d011488853992695rUGSTdMu9d",
                                "name": "Animal Farm Chapter 8 - 答案",
                                "short_name": "Chapter8/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    },
                    {
                        "id": "1599",
                        "name": "Chapter 9",
                        "short_name": null,
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A011454493981994Y4Te2tZyqr",
                                "name": "本章单词",
                                "short_name": "Chapter9/Word",
                                "type": "5",
                                "is_free": false
                            },
                            {
                                "id": "1600",
                                "name": "Paragraph 1",
                                "short_name": "Chapter9/Paragraph1",
                                "type": "2",
                                "is_free": false,
                                "duration": 208
                            },
                            {
                                "id": "1601",
                                "name": "Paragraph 2",
                                "short_name": "Chapter9/Paragraph2",
                                "type": "2",
                                "is_free": false,
                                "duration": 197
                            },
                            {
                                "id": "1602",
                                "name": "Paragraph 3",
                                "short_name": "Chapter9/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 472
                            },
                            {
                                "id": "1603",
                                "name": "Paragraph 4",
                                "short_name": "Chapter9/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 233
                            },
                            {
                                "id": "1604",
                                "name": "Paragraph 5",
                                "short_name": "Chapter9/Paragraph5",
                                "type": "2",
                                "is_free": false,
                                "duration": 468
                            },
                            {
                                "id": "1605",
                                "name": "Paragraph 6",
                                "short_name": "Chapter9/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 717
                            },
                            {
                                "id": "1606",
                                "name": "Paragraph 7",
                                "short_name": "Chapter9/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 347
                            },
                            {
                                "id": "1607",
                                "name": "Paragraph 8",
                                "short_name": "Chapter9/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 389
                            },
                            {
                                "id": "1608",
                                "name": "Paragraph 9",
                                "short_name": "Chapter9/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 328
                            },
                            {
                                "id": "1609",
                                "name": "Paragraph 10",
                                "short_name": "Chapter9/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 63
                            },
                            {
                                "id": "1610",
                                "name": "Paragraph 11",
                                "short_name": "Chapter9/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 77
                            },
                            {
                                "id": "1612",
                                "name": "Paragraph 12",
                                "short_name": "Chapter9/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 69
                            },
                            {
                                "id": "1614",
                                "name": "Paragraph 13",
                                "short_name": "Chapter9/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 275
                            },
                            {
                                "id": "1615",
                                "name": "Paragraph 14",
                                "short_name": "Chapter9/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 207
                            },
                            {
                                "id": "1616",
                                "name": "Paragraph 15",
                                "short_name": "Chapter9/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 197
                            },
                            {
                                "id": "1618",
                                "name": "Paragraph 16",
                                "short_name": "Chapter9/Paragraph16",
                                "type": "2",
                                "is_free": false,
                                "duration": 57
                            },
                            {
                                "id": "1619",
                                "name": "Paragraph 17",
                                "short_name": "Chapter9/Paragraph17",
                                "type": "2",
                                "is_free": false,
                                "duration": 39
                            },
                            {
                                "id": "1620",
                                "name": "Paragraph 18",
                                "short_name": "Chapter9/Paragraph18",
                                "type": "2",
                                "is_free": false,
                                "duration": 43
                            },
                            {
                                "id": "1621",
                                "name": "Paragraph 19",
                                "short_name": "Chapter9/Paragraph19",
                                "type": "2",
                                "is_free": false,
                                "duration": 92
                            },
                            {
                                "id": "1622",
                                "name": "Paragraph 20",
                                "short_name": "Chapter9/Paragraph20",
                                "type": "2",
                                "is_free": false,
                                "duration": 38
                            },
                            {
                                "id": "1623",
                                "name": "Paragraph 21",
                                "short_name": "Chapter9/Paragraph21",
                                "type": "2",
                                "is_free": false,
                                "duration": 264
                            },
                            {
                                "id": "1624",
                                "name": "Paragraph 22",
                                "short_name": "Chapter9/Paragraph22",
                                "type": "2",
                                "is_free": false,
                                "duration": 363
                            },
                            {
                                "id": "1626",
                                "name": "Paragraph 23",
                                "short_name": "Chapter9/Paragraph23",
                                "type": "2",
                                "is_free": false,
                                "duration": 43
                            },
                            {
                                "id": "1627",
                                "name": "Paragraph 24",
                                "short_name": "Chapter9/Paragraph24",
                                "type": "2",
                                "is_free": false,
                                "duration": 204
                            },
                            {
                                "id": "1628",
                                "name": "Paragraph 25",
                                "short_name": "Chapter9/Paragraph25",
                                "type": "2",
                                "is_free": false,
                                "duration": 160
                            },
                            {
                                "id": "1629",
                                "name": "Paragraph 26",
                                "short_name": "Chapter9/Paragraph26",
                                "type": "2",
                                "is_free": false,
                                "duration": 192
                            },
                            {
                                "id": "1630",
                                "name": "Paragraph 27",
                                "short_name": "Chapter9/Paragraph27",
                                "type": "2",
                                "is_free": false,
                                "duration": 238
                            },
                            {
                                "id": "d011454055906017KbhN18NhE2",
                                "name": "Animal Farm Chapter 9 - 习题",
                                "short_name": "Chapter9/Exercise1",
                                "type": "4",
                                "is_free": false
                            },
                            {
                                "id": "d011488854038830dpNedAhbGQ",
                                "name": "Animal Farm Chapter 9 - 答案",
                                "short_name": "Chapter9/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    },
                    {
                        "id": "1631",
                        "name": "Chapter 10",
                        "short_name": null,
                        "type": "1",
                        "is_free": false,
                        "children": [
                            {
                                "id": "A011454493998462ZWGF45ar8X",
                                "name": "本章单词",
                                "short_name": "Chapter10/Word",
                                "type": "5",
                                "is_free": false
                            },
                            {
                                "id": "1632",
                                "name": "Paragraph 1",
                                "short_name": "Chapter10/Paragraph1",
                                "type": "2",
                                "is_free": false,
                                "duration": 116
                            },
                            {
                                "id": "1633",
                                "name": "Paragraph 2",
                                "short_name": "Chapter10/Paragraph2",
                                "type": "2",
                                "is_free": false,
                                "duration": 209
                            },
                            {
                                "id": "1634",
                                "name": "Paragraph 3",
                                "short_name": "Chapter10/Paragraph3",
                                "type": "2",
                                "is_free": false,
                                "duration": 229
                            },
                            {
                                "id": "1635",
                                "name": "Paragraph 4",
                                "short_name": "Chapter10/Paragraph4",
                                "type": "2",
                                "is_free": false,
                                "duration": 352
                            },
                            {
                                "id": "1636",
                                "name": "Paragraph 5",
                                "short_name": "Chapter10/Paragraph5",
                                "type": "2",
                                "is_free": false,
                                "duration": 285
                            },
                            {
                                "id": "18614430579060910838281722",
                                "name": "Paragraph 6",
                                "short_name": "Chapter10/Paragraph6",
                                "type": "2",
                                "is_free": false,
                                "duration": 318
                            },
                            {
                                "id": "18614430579827352742971950",
                                "name": "Paragraph 7",
                                "short_name": "Chapter10/Paragraph7",
                                "type": "2",
                                "is_free": false,
                                "duration": 523
                            },
                            {
                                "id": "18614430581721025101815668",
                                "name": "Paragraph 8",
                                "short_name": "Chapter10/Paragraph8",
                                "type": "2",
                                "is_free": false,
                                "duration": 167
                            },
                            {
                                "id": "18614430582752369003253158",
                                "name": "Paragraph 9",
                                "short_name": "Chapter10/Paragraph9",
                                "type": "2",
                                "is_free": false,
                                "duration": 57
                            },
                            {
                                "id": "18614430583718983812205075",
                                "name": "Paragraph 10",
                                "short_name": "Chapter10/Paragraph10",
                                "type": "2",
                                "is_free": false,
                                "duration": 61
                            },
                            {
                                "id": "18614430584354884857581144",
                                "name": "Paragraph 11",
                                "short_name": "Chapter10/Paragraph11",
                                "type": "2",
                                "is_free": false,
                                "duration": 199
                            },
                            {
                                "id": "18614430585709070929526890",
                                "name": "Paragraph 12",
                                "short_name": "Chapter10/Paragraph12",
                                "type": "2",
                                "is_free": false,
                                "duration": 254
                            },
                            {
                                "id": "18614430587194746525252902",
                                "name": "Paragraph 13",
                                "short_name": "Chapter10/Paragraph13",
                                "type": "2",
                                "is_free": false,
                                "duration": 40
                            },
                            {
                                "id": "18614430587792488365852841",
                                "name": "Paragraph 14",
                                "short_name": "Chapter10/Paragraph14",
                                "type": "2",
                                "is_free": false,
                                "duration": 68
                            },
                            {
                                "id": "18614430588512122003580487",
                                "name": "Paragraph 15",
                                "short_name": "Chapter10/Paragraph15",
                                "type": "2",
                                "is_free": false,
                                "duration": 44
                            },
                            {
                                "id": "18614430589349450400289248",
                                "name": "Paragraph 16",
                                "short_name": "Chapter10/Paragraph16",
                                "type": "2",
                                "is_free": false,
                                "duration": 131
                            },
                            {
                                "id": "18614430589896272158904526",
                                "name": "Paragraph 17",
                                "short_name": "Chapter10/Paragraph17",
                                "type": "2",
                                "is_free": false,
                                "duration": 173
                            },
                            {
                                "id": "18614430595061562431858708",
                                "name": "Paragraph 18",
                                "short_name": "Chapter10/Paragraph18",
                                "type": "2",
                                "is_free": false,
                                "duration": 101
                            },
                            {
                                "id": "18614430595791108754071676",
                                "name": "Paragraph 19",
                                "short_name": "Chapter10/Paragraph19",
                                "type": "2",
                                "is_free": false,
                                "duration": 79
                            },
                            {
                                "id": "18614430596397087225409367",
                                "name": "Paragraph 20",
                                "short_name": "Chapter10/Paragraph20",
                                "type": "2",
                                "is_free": false,
                                "duration": 135
                            },
                            {
                                "id": "18614430598303458775709253",
                                "name": "Paragraph 21",
                                "short_name": "Chapter10/Paragraph21",
                                "type": "2",
                                "is_free": false,
                                "duration": 81
                            },
                            {
                                "id": "18614430599310570826149552",
                                "name": "Paragraph 22",
                                "short_name": "Chapter10/Paragraph22",
                                "type": "2",
                                "is_free": false,
                                "duration": 516
                            },
                            {
                                "id": "18614430600086129503884320",
                                "name": "Paragraph 23",
                                "short_name": "Chapter10/Paragraph23",
                                "type": "2",
                                "is_free": false,
                                "duration": 349
                            },
                            {
                                "id": "18614430600812171249191522",
                                "name": "Paragraph 24",
                                "short_name": "Chapter10/Paragraph24",
                                "type": "2",
                                "is_free": false,
                                "duration": 70
                            },
                            {
                                "id": "18614430601437881504402521",
                                "name": "Paragraph 25",
                                "short_name": "Chapter10/Paragraph25",
                                "type": "2",
                                "is_free": false,
                                "duration": 98
                            },
                            {
                                "id": "18614430602305214215755212",
                                "name": "Paragraph 26",
                                "short_name": "Chapter10/Paragraph26",
                                "type": "2",
                                "is_free": false,
                                "duration": 236
                            },
                            {
                                "id": "18614430602919637399989000",
                                "name": "Paragraph 27",
                                "short_name": "Chapter10/Paragraph27",
                                "type": "2",
                                "is_free": false,
                                "duration": 273
                            },
                            {
                                "id": "18614430603599596589451195",
                                "name": "Paragraph 28",
                                "short_name": "Chapter10/Paragraph28",
                                "type": "2",
                                "is_free": false,
                                "duration": 158
                            },
                            {
                                "id": "18614430604943828521333121",
                                "name": "Paragraph 29",
                                "short_name": "Chapter10/Paragraph29",
                                "type": "2",
                                "is_free": false,
                                "duration": 145
                            },
                            {
                                "id": "18614430605664628211271892",
                                "name": "Paragraph 30",
                                "short_name": "Chapter10/Paragraph30",
                                "type": "2",
                                "is_free": false,
                                "duration": 207
                            },
                            {
                                "id": "18614430607076213532828342",
                                "name": "Paragraph 31",
                                "short_name": "Chapter10/Paragraph31",
                                "type": "2",
                                "is_free": false,
                                "duration": 236
                            },
                            {
                                "id": "d011454055938782Xv3HocqJq2",
                                "name": "Animal Farm Chapter 10 - 习题",
                                "short_name": "Chapter10/Exercise1",
                                "type": "4",
                                "is_free": false
                            },
                            {
                                "id": "d011488854180219YjbW98FHz0",
                                "name": "Animal Farm Chapter 10 - 答案",
                                "short_name": "Chapter10/Key1",
                                "type": "4",
                                "is_free": false
                            }
                        ]
                    }
                ]
            },
            "remark": "<html><head><style>*{margin:0;padding:0;-webkit-box-sizing:border-box;box-sizing:border-box}html{font-family:\"Microsoft YaHei\",\"Helvetica Neue\",Helvetica,Arial,sans-serif;font-size:16px;color:#212122}body{padding:16px 16px 45px}h2{font-size:16px;color:#023d7f;margin-top:12px;margin-bottom:4px}h2:first-child{margin-top:0}p{font-size:14px;line-height:22px;margin-bottom:2px}p img{margin:auto;display:block;padding:10px 15px;max-width:100%!important}</style></head><body><h2>\n\t内容简介\n</h2>\n<p>\n\t马诺尔农庄一只名叫老梅杰的猪在提出了“人类剥削动物，动物须革命”的理论之后死去，几个月后，农庄里掀起了一场由猪领导的革命，原来的剥削者——主人琼斯先生被赶走，动物们实现了“当家作主”的愿望，尝到了革命果实的甘美，马诺尔农庄被更名为“动物农庄”，还制定了七戒。然而不久，两只领头的猪为了权力而互相倾轧，胜利的一方宣布另一方是叛徒、内奸，猪们逐渐侵占了其他动物的劳动成果，成为新的特权阶级，“所有动物一律平等”的原则被修正为“但有些动物比其他动物更平等”，动物们又恢复到从前的悲惨状况。\n</p>\n<p>\n\t乔治•奥威尔（George Orwell，1903－1950），原名艾立克•阿瑟•布莱尔，出生于英国殖民地印度，童年耳闻目睹了殖民者与被殖民者之间尖锐的冲突。与绝大多数英国孩子不同，他的同情倾向悲惨的印度人民一边。少年时代，奥威尔受教育于著名的伊顿公学，后来被派到缅甸任警察，却站在苦役犯的一边。二十世纪三十年代，他参加西班牙内战，因属托洛茨基派系（第四国际）而遭排挤，回国后却又被划入左派，不得不流亡法国。二战中，他在英国广播公司（BBC）从事反法西斯宣传工作。一九五○年，死于困扰其数年的肺病，年仅四十七岁。乔治•奥威尔一生颠沛流离，疾病缠身，一直被视为危险的异端，却其以敏锐的洞察力和犀利的文笔审视和记录着他所生活的那个时代，作出了许多超越时代的预言，被称为 “一代人的冷峻良知”。代表作有《动物农庄》（1945）和《一九八四》（1949）。\n</p>\n<p>\n\t毫无疑问，动物农庄是一本史诗般的经典，她值得所有人去读，并且值得反复阅读。虽然以寓言的形式出现，但其思想之深、涉及历史事件之广，超乎绝大多数读者之想象。可以毫不夸张地说，把动物农庄读懂读透，收获的远不止英语的基本语法结构和两千多个词汇，还包括欧洲现代史和各种政治思潮、并促使我们去深入思考诸如平等、真实等概念。所以，动物农庄这本书最大的魔力在于，他能让我们陷入深思，他能在我们灵魂深处拷问一些最根本的问题，他能启发我们在众多扑朔迷离和似是而非的概念中寻找真相和答案。而这些，也正是中国学生最为缺乏但却最被美国教育所重视且强调的能力。\n</p>\n<p>\n\t在此，我们请读者思考：作为民主社会主义信徒的乔治奥威尔，他本来是对贫苦大众满怀同情，但在书中，他为何处处流露出对象征着劳苦大众的动物们智商低下之鄙视，其中包括那只任劳任怨的Boxer？实际上，这个问题在全书中出于核心地位。\n</p>\n<p>\n\t与其说批判专制主义，还不如说鞭挞愚昧。原因很简单：专制主义的危害显而易见，但对于愚昧之危害，人们却未必有足够的了解。许多人认为愚昧仅仅是弱势的表现，但动物农庄一书却告诉我们，愚昧是滋养专制主义的温床，是专制主义不折不扣的帮凶。这一点，和李嘉诚先生最近在一封公开信里所说“愚昧是人类最大的敌人”如出一辙。生活于愚昧和无知中的动物们，缺乏批判思考能力，不加分辨地接受并相信来自拿破仑的指令，包括“所有的动物们都一律平等，但是有些动物更加平等”这样的荒谬悖论，这恐怕才是动物农庄里动物们悲惨命运的根源所在。\n</p>\n<p>\n\t当然，以上只是我的个人解读。相信每个学生都会有自己独特的视角和独到的观点。我们需要明白，思考的结论并不重要，过程才重要。所以，我建议家长和孩子们一起读，一起讨论。\n</p>\n<p>\n\t相信这本书将成为孩子思想启蒙之原点。\n</p>\n<p>\n\t如欲购买本书，请至：http://item.jd.com/1056820778.html\n</p>\n<h2>\n\t课程特色\n</h2>\n<p>\n\t本视频课程采用：逐字逐句精讲＋扩展与启发相结合的方式，从英语学习和评判思维方面并行对学生进行辅导和启发。\n</p>\n<p>\n\t系统还提供免费的词汇学习功能，每个课程都可以在词汇学习功能中找到相应的学习入口。\n</p>\n<p>\n\t同时，我们还推出了微信群读书社，来自五湖四海的人和你一起读书、打卡、分享、讨论，一起组队抗击懒惰，一起享受阅读。\n</p>\n<h2>\n\t适合对象\n</h2>\n<p>\n\t适合托福70+或英文语言能力同等水平的学生。\n</p>\n<h2>\n\t学习目标\n</h2>\n<p>\n\t提高对英文字词句层面精准的理解, 从而提升词汇量和英文句法知识；学会把握小说中微妙的人物语气, 学会分析小说中的人物性格，提高文学鉴赏能力 (以上内容均为SAT考试小说阅读中的考察重点) ，提高整体的英文实际运用能力。\n</p>\n<h2>\n\t学习方法\n</h2>\n<p>\n\t建议在观看老师的精讲视频课件之前，先自行用纸质书或电子书进行阅读，建议直接用本系统提供的电子书格式进行阅读，并标记有问题或疑义的部分，在读完一定的章节后，再仔细观看视频课件，观看视频课件过程中，可以进行跟读和背诵，强烈推荐对课件进行不断的重复观看和学习，在阅读完每章后，建议做每章后面的相应习题，以巩固效果，同时利用习题自带的词汇学习功能，每天复习相应词汇。\n</p>\n<h2>\n\t录课老师简介\n</h2>\n<p class=\"a\">\n\t<img src=\"http://app.bstcine.com/f/2017/01/06/145509122SK3RJub.jpg\" alt=\"\" /> \n</p>\n<p>\n\t邱巍楠，上海外国语大学英语语言文学硕士, 英文专业八级(优秀), 2006年(大三)获上海市高级口译证书。托福119分(总分120)，SAT考试阅读数学双800(满分)。英文演讲比赛获奖无数。邱老师酷爱文学阅读，早在大学时期，她便阅读了近15本文学名著，包括《傲慢与偏见》《理智与情感》《罪与罚》《伟大的盖茨比》《忏悔录》《名利场》《茶花女》《远大前程》《红字》《唤醒》《常识》等高难度的经典文学作品。在5年的教书生涯中，她不仅教出 SAT TOEFL 高分学员无数，并且在通过教授学生英文原版阅读提高英文能力方面有着丰富的教学经验。已录有 “托福精读视频课” “《动物农庄》精读视频课” “《伟大的盖茨比》精读视频课” 以及 “《查理与巧克力工厂》精读视频课 ” 。\n</p></body></html>",
            "total_join": 5553,
            "total_like": 3,
            "total_view": 0,
            "seq": 2,
            "create_at": null,
            "create_by": null,
            "update_at": "2017-10-13 15:38:54",
            "update_by": "1",
            "delete_at": null,
            "delete_by": null,
            "type": "1",
            "good": 0,
            "hot": 0,
            "product_type": "1",
            "packages": null,
            "try_contents": null,
            "original_price": null,
            "notice": null,
            "is_need_remark": "0",
            "is_show_pc": "1",
            "is_show_ios": "1",
            "is_show_android": "1",
            "is_full": "0",
            "share_marketing_id": "d011491882471012uYzmgx0350",
            "remark_ios": null,
            "remark_android": null,
            "object_type": "1",
            "related_lesson_id": null,
            "is_allow_coupon": "1",
            "base_join": 5000,
            "base_like": 0,
            "base_view": 0,
            "is_allow_point": "1",
            "featured_videos": "1",
            "tag": "2",
            "short_name": "《动物农庄》",
            "lesson_shareparam_id": "",
            "pay_shareparam_id": "",
            "learn_shareparam_id": "d011505181797874amPSRrq2ct",
            "listen_shareparam_id": "",
            "share_h5_desc": "我正在参加善恩英语的{#content_name#}，\\n已经坚持了{#seriesDuration#}天！",
            "share_h5_img": "fdafda",
            "is_in_app": "0",
            "is_show_share": true,
            "is_paid": false,
            "can_learn": false,
            "bigImg": "2017/03/11/102109612SnKmu7s.jpg"
        }
    }
}
```
