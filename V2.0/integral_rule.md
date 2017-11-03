* 功能: 积分规则

* URL: /api/global/integral/rule

* request
```
{
    "token":"",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "type":"1"          //默认为'1',即积分规则
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
        "remark": "<html><head><style>*{margin:0;padding:0;-webkit-box-sizing:border-box;box-sizing:border-box}html{font-family:\"Microsoft YaHei\",\"Helvetica Neue\",Helvetica,Arial,sans-serif;font-size:16px;color:#212122}body{padding:16px 16px 45px}h2{font-size:16px;color:#023d7f;margin-top:12px;margin-bottom:4px}h2:first-child{margin-top:0}p{font-size:14px;line-height:22px;margin-bottom:2px}p img{margin:auto;display:block;padding:10px 15px;max-width:100%!important}</style></head><body><p style=\"font-weight: bold;\">\n\t 积分规则 \n</p>\n<p>\n\t1. 注册新用户获得50积分\n</p>\n<p>\n\t2. APP首次登录即可获得50积分\n</p>\n<p>\n\t3. 购买支付后分享至朋友圈获得实付金额的5%积分(取整)，小于10则计10积分\n</p>\n<p>\n\t4. 每次学习完成分享至朋友圈获得2积分。分享24小时内，阅读数1-5个获得1分；6-10个获得2分；10个以上获得3分\n</p>\n<p>\n\t5. 点对点推荐购买，推荐者送实付金额的5%积分\n</p>\n<p>\n\t6. 其它线下活动，请联系“善恩小助手，微信号:BSTCINE01”，例如：1)学习群/社区表现优秀者获得10积分,2)善恩在线英语学堂使用体验征文录用\n</p>\n<p style=\"font-weight: bold;\">\n\t<strong>积分说明</strong> \n</p>\n<p>\n\t1. 1个积分相当于1元。\n</p>\n<p>\n\t2. 积分不可提现，不可转让。\n</p>\n<p style=\"font-weight: bold;\">\n\t<strong>积分用途</strong> \n</p>\n<p>\n\t1. 积分可以直接用于课程购买\n</p></body></html>"
    }
}
```
          
  - 参数异常时 response
  
 except_case_desc|错误描述
 -|-
 type_not_exist|type参数错误
