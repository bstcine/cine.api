* 功能: 我的优惠券列表

* URL: /api/user/coupon/listbystatus

* request
```
{
    "token":"y5atdEZ3",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
        "status":0,             // 优惠券状态 默认是0未使用
        "page":2,               //当前页,默认第一页
        "pageSize":2,           //页面大小，默认大小为10
        "orderBy":"create_at",  //排序字段
        "orderValue":"desc"     //排序方式
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
        "cur_page": 1,
        "max_page": 1,
        "total_rows": 4,
        "rows": [
            {
                "id": "d011504248360903pF6zTzebS3",
                "no": "MWS5HK7S",
                "name": "新学员专享优惠券",
                "value": "0.05",
                "status": "1",
                "effective_at": "2017-09-01 00:00:00",
                "expire_at": "2017-10-01 23:59:59",
                "match_lesson_ids": null,
                "use_at": null,
                "user_id": "d011495098151930dz0CsXrxSm",
                "order_id": "201709011446P4hZb",
                "remark": null,
                "create_at": "2017-09-01 14:46:00",
                "create_by": "A011461998979982CQJwFJXATR",
                "update_at": "2017-09-01 14:49:01",
                "update_by": "1",
                "delete_at": null,
                "delete_by": null,
                "type": "2",
                "condition": "3",
                "desc": "新学员专享"
            },
            ....
        ]
    }
}
```
  - token错误时 response
  ```
  {
    "code": "1",
    "code_desc": "success",
    "except_case": "",
    "except_case_desc": "no_login"
  }
  ```
          
  - 参数异常时 response
  
 except_case_desc|错误描述
 -|-
 token_is_null|token为空
 no_login|未登录
