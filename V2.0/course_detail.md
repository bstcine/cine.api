* 功能: 课程详情

* URL: /api/content/course/detail

* request
```
{
    "token":"", //nFmqtqzH
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.3",
    "data":{
      "cid":42  //course_id      
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
                            ...
                        ]
                    },
                    ...
                ]
            },
            "remark": "<html><head><style>*{margin:0;padding:0;-webkit-box-sizing:border-box;box-sizing:border-box}html{font-family:\"Microsoft YaHei\",\"Helvetica Neue\",Helvetica,Arial,sans-serif;font-size:16px;color:#212122}body{padding:16px 16px 45px}h2{font-size:16px;color:#023d7f;margin-top:12px;margin-bottom:4px}h2:first-child{margin-top:0}p{font-size:14px;line-height:22px;margin-bottom:2px}p img{margin:auto;display:block;padding:10px 15px;max-width:100%!important}</style></head><body><h2>\n\t内容简介\n</h2>\n<p>\n\t马诺尔农庄一只名叫老梅杰的猪在提出了“人类剥削动物，动物须革命”的理论之后死去，几个月后，农庄里掀起了一场由猪领导的革命，原来的剥削者——主人琼斯先生被赶走，动物们实现了“当家作主”的愿望，尝到了革命果实的甘美，马诺尔农庄被更名为“动物农庄”，还制定了七戒。然而不久，两只领头的猪为了权力而互相倾轧，胜利的一方宣布另一方是叛徒、内奸，猪们逐渐侵占了其他动物的劳动成果，成为新的特权阶级，“所有动物一律平等”的原则被修正为“但有些动物比其他动物更平等”，动物们又恢复到从前的悲惨状况。\n</p>\n<p>\n\t乔治•奥威尔（George Orwell，1903－1950），原名艾立克•阿瑟•布莱尔，出生于英国殖民地印度，童年耳闻目睹了殖民者与被殖民者之间尖锐的冲突。与绝大多数英国孩子不同，他的同情倾向悲惨的印度人民一边。少年时代，奥威尔受教育于著名的伊顿公学，后来被派到缅甸任警察，却站在苦役犯的一边。二十世纪三十年代，他参加西班牙内战，因属托洛茨基派系（第四国际）而遭排挤，回国后却又被划入左派，不得不流亡法国。二战中，他在英国广播公司（BBC）从事反法西斯宣传工作。一九五○年，死于困扰其数年的肺病，年仅四十七岁。乔治•奥威尔一生颠沛流离，疾病缠身，一直被视为危险的异端，却其以敏锐的洞察力和犀利的文笔审视和记录着他所生活的那个时代，作出了许多超越时代的预言，被称为 “一代人的冷峻良知”。代表作有《动物农庄》（1945）和《一九八四》（1949）。\n</p>\n<p>\n\t毫无疑问，动物农庄是一本史诗般的经典，她值得所有人去读，并且值得反复阅读。虽然以寓言的形式出现，但其思想之深、涉及历史事件之广，超乎绝大多数读者之想象。可以毫不夸张地说，把动物农庄读懂读透，收获的远不止英语的基本语法结构和两千多个词汇，还包括欧洲现代史和各种政治思潮、并促使我们去深入思考诸如平等、真实等概念。所以，动物农庄这本书最大的魔力在于，他能让我们陷入深思，他能在我们灵魂深处拷问一些最根本的问题，他能启发我们在众多扑朔迷离和似是而非的概念中寻找真相和答案。而这些，也正是中国学生最为缺乏但却最被美国教育所重视且强调的能力。\n</p>\n<p>\n\t在此，我们请读者思考：作为民主社会主义信徒的乔治奥威尔，他本来是对贫苦大众满怀同情，但在书中，他为何处处流露出对象征着劳苦大众的动物们智商低下之鄙视，其中包括那只任劳任怨的Boxer？实际上，这个问题在全书中出于核心地位。\n</p>\n<p>\n\t与其说批判专制主义，还不如说鞭挞愚昧。原因很简单：专制主义的危害显而易见，但对于愚昧之危害，人们却未必有足够的了解。许多人认为愚昧仅仅是弱势的表现，但动物农庄一书却告诉我们，愚昧是滋养专制主义的温床，是专制主义不折不扣的帮凶。这一点，和李嘉诚先生最近在一封公开信里所说“愚昧是人类最大的敌人”如出一辙。生活于愚昧和无知中的动物们，缺乏批判思考能力，不加分辨地接受并相信来自拿破仑的指令，包括“所有的动物们都一律平等，但是有些动物更加平等”这样的荒谬悖论，这恐怕才是动物农庄里动物们悲惨命运的根源所在。\n</p>\n<p>\n\t当然，以上只是我的个人解读。相信每个学生都会有自己独特的视角和独到的观点。我们需要明白，思考的结论并不重要，过程才重要。所以，我建议家长和孩子们一起读，一起讨论。\n</p>\n<p>\n\t相信这本书将成为孩子思想启蒙之原点。\n</p>\n<p>\n\t如欲购买本书，请至：http://item.jd.com/1056820778.html\n</p>\n<h2>\n\t课程特色\n</h2>\n<p>\n\t本视频课程采用：逐字逐句精讲＋扩展与启发相结合的方式，从英语学习和评判思维方面并行对学生进行辅导和启发。\n</p>\n<p>\n\t系统还提供免费的词汇学习功能，每个课程都可以在词汇学习功能中找到相应的学习入口。\n</p>\n<p>\n\t同时，我们还推出了微信群读书社，来自五湖四海的人和你一起读书、打卡、分享、讨论，一起组队抗击懒惰，一起享受阅读。\n</p>\n<h2>\n\t适合对象\n</h2>\n<p>\n\t适合托福70+或英文语言能力同等水平的学生。\n</p>\n<h2>\n\t学习目标\n</h2>\n<p>\n\t提高对英文字词句层面精准的理解, 从而提升词汇量和英文句法知识；学会把握小说中微妙的人物语气, 学会分析小说中的人物性格，提高文学鉴赏能力 (以上内容均为SAT考试小说阅读中的考察重点) ，提高整体的英文实际运用能力。\n</p>\n<h2>\n\t学习方法\n</h2>\n<p>\n\t建议在观看老师的精讲视频课件之前，先自行用纸质书或电子书进行阅读，建议直接用本系统提供的电子书格式进行阅读，并标记有问题或疑义的部分，在读完一定的章节后，再仔细观看视频课件，观看视频课件过程中，可以进行跟读和背诵，强烈推荐对课件进行不断的重复观看和学习，在阅读完每章后，建议做每章后面的相应习题，以巩固效果，同时利用习题自带的词汇学习功能，每天复习相应词汇。\n</p>\n<h2>\n\t录课老师简介\n</h2>\n<p class=\"a\">\n\t<img src=\"http://app.bstcine.com/f/2017/01/06/145509122SK3RJub.jpg\" alt=\"\" /> \n</p>\n<p>\n\t邱巍楠，上海外国语大学英语语言文学硕士, 英文专业八级(优秀), 2006年(大三)获上海市高级口译证书。托福119分(总分120)，SAT考试阅读数学双800(满分)。英文演讲比赛获奖无数。邱老师酷爱文学阅读，早在大学时期，她便阅读了近15本文学名著，包括《傲慢与偏见》《理智与情感》《罪与罚》《伟大的盖茨比》《忏悔录》《名利场》《茶花女》《远大前程》《红字》《唤醒》《常识》等高难度的经典文学作品。在5年的教书生涯中，她不仅教出 SAT TOEFL 高分学员无数，并且在通过教授学生英文原版阅读提高英文能力方面有着丰富的教学经验。已录有 “托福精读视频课” “《动物农庄》精读视频课” “《伟大的盖茨比》精读视频课” 以及 “《查理与巧克力工厂》精读视频课 ” 。\n</p></body></html>",
            "total_join": 5553,
            "total_like": 3,
            "total_view": 0,
            "seq": 2,
            "create_at": null,
            "create_by": null,
            "update_at": "2017-10-16 14:34:16",
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
* 说明：token为空和正确的token返回值中is_paid、can_learn的值不同 
* 错误token response
```
{
    "code": "1",
    "code_desc": "success",
    "except_case": "",
    "except_case_desc": "no_login"
}
```
