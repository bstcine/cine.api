* 功能: APP 首页，包括顶部轮播图、课程目录

* URL: /api/app/home

* request
```
{
    "token":"",
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
        "lessoncategorys": [
            {
                "id": "d011495787003995KQ847j7eGV",
                "name": "热推新品",
                "status": "1",
                "remark": null,
                "seq": -2,
                "create_at": "2017-05-26 16:23:23",
                "create_by": "A011454493804858vCnC6NpgJi",
                "update_at": "2017-09-06 09:51:37",
                "update_by": "1",
                "delete_at": null,
                "delete_by": null,
                "is_show_pc": "1",
                "is_show_ios": "1",
                "is_show_android": "1",
                "data": "'d0114895451784428WtHSkSvpN','A011473750883473MfD6eUge7h','41'",
                "icon": "hot",
                "tag": null,
                "type": "2",
                "children": [
                    {
                        "id": "d0114895451784428WtHSkSvpN",
                        "name": "《The Cat in The Hat》原版讲读",
                        "price": "28",
                        "img": "2017/03/17/15473133SHy4zRs.jpg",
                        "total_join": 1052,
                        "lessoncategory_id": "d011489544670568frqxJBxBjh",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "A011473750883473MfD6eUge7h",
                        "name": "SAT语法精讲",
                        "price": "1980",
                        "img": "2017/03/11/102850399SMXfqb0.jpg",
                        "total_join": 1108,
                        "lessoncategory_id": "d0114835885266600ydPBWPaJH",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "41",
                        "name": "托福阅读精讲",
                        "price": "2980",
                        "img": "2017/03/11/102254707Szqtn94.jpg",
                        "total_join": 2164,
                        "lessoncategory_id": "d0114835885266600ydPBWPaJH",
                        "status": "1",
                        "pay_status": 0
                    }
                ]
            },
            {
                "id": "d011493362894762kK7auPyeyy",
                "name": "精品套餐",
                "status": "1",
                "remark": null,
                "seq": -1,
                "create_at": "2017-04-28 15:01:34",
                "create_by": "A011454493804858vCnC6NpgJi",
                "update_at": "2017-08-30 16:51:41",
                "update_by": "A0114545674014796APR7h4ALO",
                "delete_at": null,
                "delete_by": null,
                "is_show_pc": "1",
                "is_show_ios": "1",
                "is_show_android": "1",
                "data": "'42','41'",
                "icon": "gift",
                "tag": null,
                "type": "2",
                "children": [
                    {
                        "id": "42",
                        "name": "《动物农庄》精读课程",
                        "price": "1",
                        "img": "2017/03/11/102106363SVEwqmp.jpg",
                        "total_join": 5553,
                        "lessoncategory_id": "d011483588489325R1B2f1Z6dH",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "41",
                        "name": "托福阅读精讲",
                        "price": "2980",
                        "img": "2017/03/11/102254707Szqtn94.jpg",
                        "total_join": 2164,
                        "lessoncategory_id": "d0114835885266600ydPBWPaJH",
                        "status": "1",
                        "pay_status": 0
                    }
                ]
            },
            {
                "id": "d011489544670568frqxJBxBjh",
                "name": "英文原版桥梁书 – Dr. Seuss 苏斯博士系列",
                "status": "1",
                "remark": null,
                "seq": 1,
                "create_at": "2017-03-15 10:24:30",
                "create_by": "A011454493804858vCnC6NpgJi",
                "update_at": "2017-03-28 16:32:08",
                "update_by": "A011454493804858vCnC6NpgJi",
                "delete_at": null,
                "delete_by": null,
                "is_show_pc": "1",
                "is_show_ios": "1",
                "is_show_android": "1",
                "data": null,
                "icon": null,
                "tag": null,
                "type": "1",
                "children": [
                    {
                        "id": "d0114895451784428WtHSkSvpN",
                        "name": "《The Cat in The Hat》原版讲读",
                        "price": "28",
                        "img": "2017/03/17/15473133SHy4zRs.jpg",
                        "total_join": 1052,
                        "lessoncategory_id": "d011489544670568frqxJBxBjh",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "d011489545230763dQnpS4PsE0",
                        "name": "《Fox in Socks》原版讲读",
                        "price": "0.01",
                        "img": "2017/03/15/165122402SkjgMqB.jpg",
                        "total_join": 1033,
                        "lessoncategory_id": "d011489544670568frqxJBxBjh",
                        "status": "1",
                        "pay_status": 0
                    }
                ]
            },
            {
                "id": "d011489544620521snx8MPm4r4",
                "name": "英文原版初级章节书 – 神奇树屋系列",
                "status": "1",
                "remark": null,
                "seq": 2,
                "create_at": "2017-03-15 10:23:40",
                "create_by": "A011454493804858vCnC6NpgJi",
                "update_at": "2017-03-28 16:26:49",
                "update_by": "A011454493804858vCnC6NpgJi",
                "delete_at": null,
                "delete_by": null,
                "is_show_pc": "1",
                "is_show_ios": "1",
                "is_show_android": "1",
                "data": null,
                "icon": null,
                "tag": null,
                "type": "1",
                "children": [
                    {
                        "id": "A011481356690908FzSf3w6uWp",
                        "name": "《神奇树屋1-恐龙谷历险记》精读课程",
                        "price": "0.01",
                        "img": "2017/03/11/101427698Syk7CAu.jpg",
                        "total_join": 1325,
                        "lessoncategory_id": "d011489544620521snx8MPm4r4",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "d011489544828252C98UhVm1x5",
                        "name": "《神奇树屋2 – 迷雾中的骑士》精读课程",
                        "price": "198",
                        "img": "2017/03/15/16504361SPp9QHg.jpg",
                        "total_join": 1046,
                        "lessoncategory_id": "d011489544620521snx8MPm4r4",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "A011481593478350BKERXB5gYq",
                        "name": "《神奇树屋5-忍者的秘密》精读课程",
                        "price": "28",
                        "img": "2017/03/11/101624931SsJcEYq.jpg",
                        "total_join": 1097,
                        "lessoncategory_id": "d011489544620521snx8MPm4r4",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "d011489544924565QYbxA1ACU6",
                        "name": "《神奇树屋6 – 亚马孙大冒险》精读课程",
                        "price": "198",
                        "img": "2017/03/15/165056371S13U3R3.jpg",
                        "total_join": 1039,
                        "lessoncategory_id": "d011489544620521snx8MPm4r4",
                        "status": "1",
                        "pay_status": 0
                    }
                ]
            },
            {
                "id": "d011483588421144CvNWznX0pm",
                "name": "英文原版必读经典 - 初阶",
                "status": "1",
                "remark": "适合需要强化英语基础",
                "seq": 3,
                "create_at": null,
                "create_by": null,
                "update_at": "2017-08-30 16:44:38",
                "update_by": "A0114545674014796APR7h4ALO",
                "delete_at": null,
                "delete_by": null,
                "is_show_pc": "1",
                "is_show_ios": "1",
                "is_show_android": "1",
                "data": null,
                "icon": null,
                "tag": null,
                "type": "1",
                "children": [
                    {
                        "id": "d0115033642484270Tw3Nw3ZMv",
                        "name": "《查理》音频",
                        "price": null,
                        "img": "2017/08/23/171411221SzDrGd8.jpg",
                        "total_join": 120,
                        "lessoncategory_id": "d011483588421144CvNWznX0pm",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "d011453971898316wOnY4sRKIC",
                        "name": "《查理和巧克力工厂》精读课程",
                        "price": "2980",
                        "img": "2017/06/23/174324564SEXC6cB.jpg",
                        "total_join": 1813,
                        "lessoncategory_id": "d011483588421144CvNWznX0pm",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "A0114655235938391eWYkAGPbk",
                        "name": "《夏洛特的网》精读课程",
                        "price": "2980",
                        "img": "2017/03/11/101816296SqQ72a5.png",
                        "total_join": 1122,
                        "lessoncategory_id": "d011483588421144CvNWznX0pm",
                        "status": "1",
                        "pay_status": 0
                    }
                ]
            },
            {
                "id": "d011483588489325R1B2f1Z6dH",
                "name": "英文原版必读经典 - 中阶",
                "status": "1",
                "remark": "适合英语基础较好",
                "seq": 4,
                "create_at": null,
                "create_by": null,
                "update_at": "2017-08-30 16:44:41",
                "update_by": "A0114545674014796APR7h4ALO",
                "delete_at": null,
                "delete_by": null,
                "is_show_pc": "1",
                "is_show_ios": "1",
                "is_show_android": "1",
                "data": null,
                "icon": null,
                "tag": null,
                "type": "1",
                "children": [
                    {
                        "id": "A011481685662619HkztzzwvxT",
                        "name": "《小王子》精读课程",
                        "price": "1680",
                        "img": "2017/03/03/111138125Scaavdm.jpg",
                        "total_join": 1050,
                        "lessoncategory_id": "d011483588489325R1B2f1Z6dH",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "d011489651853173VqHxB5aeds",
                        "name": "《纳尼亚传奇2：狮子、女巫和魔衣橱》精读课程",
                        "price": "待推出",
                        "img": "2017/03/16/161154932SgWZV8K.jpg",
                        "total_join": 1000,
                        "lessoncategory_id": "d011483588489325R1B2f1Z6dH",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "42",
                        "name": "《动物农庄》精读课程",
                        "price": "1",
                        "img": "2017/03/11/102106363SVEwqmp.jpg",
                        "total_join": 5553,
                        "lessoncategory_id": "d011483588489325R1B2f1Z6dH",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "A011466215703591WQYDRNlWxH",
                        "name": "《人类的故事》精读课程",
                        "price": "2980",
                        "img": "2017/03/11/102140770S6kpqqa.jpg",
                        "total_join": 1096,
                        "lessoncategory_id": "d011483588489325R1B2f1Z6dH",
                        "status": "1",
                        "pay_status": 0
                    }
                ]
            },
            {
                "id": "d011483588546284z1cgFS72YQ",
                "name": "英文原版必读经典 - 高阶",
                "status": "1",
                "remark": "适合托福90+或同等英语水平",
                "seq": 5,
                "create_at": null,
                "create_by": null,
                "update_at": "2017-08-30 16:44:45",
                "update_by": "A0114545674014796APR7h4ALO",
                "delete_at": null,
                "delete_by": null,
                "is_show_pc": "1",
                "is_show_ios": "1",
                "is_show_android": "1",
                "data": null,
                "icon": null,
                "tag": null,
                "type": "1",
                "children": [
                    {
                        "id": "d0114539825439251pL4DiFkem",
                        "name": "《福尔摩斯探案集-血字的研究》精读课程",
                        "price": "0.01",
                        "img": "2017/01/06/143815264Sb093F2.png",
                        "total_join": 1056,
                        "lessoncategory_id": "d011483588546284z1cgFS72YQ",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "A011459218776295IcEIrkdZwS",
                        "name": "《傲慢与偏见》精读课程",
                        "price": "2980",
                        "img": "2017/03/11/102717250SHP9jtk.png",
                        "total_join": 1086,
                        "lessoncategory_id": "d011483588546284z1cgFS72YQ",
                        "status": "1",
                        "pay_status": 0
                    }
                ]
            },
            {
                "id": "d0114835885266600ydPBWPaJH",
                "name": "托福/SAT课程",
                "status": "1",
                "remark": "适合托福备考的初高中学生",
                "seq": 6,
                "create_at": null,
                "create_by": null,
                "update_at": "2017-03-15 17:05:52",
                "update_by": "A011454493804858vCnC6NpgJi",
                "delete_at": null,
                "delete_by": null,
                "is_show_pc": "1",
                "is_show_ios": "1",
                "is_show_android": "1",
                "data": null,
                "icon": null,
                "tag": null,
                "type": "1",
                "children": [
                    {
                        "id": "d01149275890537720F9K972EK",
                        "name": "SAT套餐",
                        "price": "4980",
                        "img": "2017/04/28/145158479SAGA4DN.jpg",
                        "total_join": 1002,
                        "lessoncategory_id": "d0114835885266600ydPBWPaJH",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "41",
                        "name": "托福阅读精讲",
                        "price": "2980",
                        "img": "2017/03/11/102254707Szqtn94.jpg",
                        "total_join": 2164,
                        "lessoncategory_id": "d0114835885266600ydPBWPaJH",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "A0114848779057234dnkUVbCsu",
                        "name": "托福口语精讲",
                        "price": "1980",
                        "img": "2017/03/11/102409246SvRUfjV.jpg",
                        "total_join": 1031,
                        "lessoncategory_id": "d0114835885266600ydPBWPaJH",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "A011473750883473MfD6eUge7h",
                        "name": "SAT语法精讲",
                        "price": "1980",
                        "img": "2017/03/11/102850399SMXfqb0.jpg",
                        "total_join": 1108,
                        "lessoncategory_id": "d0114835885266600ydPBWPaJH",
                        "status": "1",
                        "pay_status": 0
                    },
                    {
                        "id": "A011481599400893DAhTPx3J6z",
                        "name": "SAT阅读精讲",
                        "price": "2980",
                        "img": "2017/03/11/104432245Sz4sn7h.jpg",
                        "total_join": 1048,
                        "lessoncategory_id": "d0114835885266600ydPBWPaJH",
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
            },
            {
                "name": "关注微信",
                "img": "http://app.bstcine.com/f/2017/03/03/175453670S5ywgUM.jpg",
                "type": "2"
            }
        ]
    }
}
```
