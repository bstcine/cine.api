* 功能: 我的积分列表

* URL: /api/user/integral/list

* request
```
{
    "token":"y5atdEZ3",
    "sitecode": "cine.ios.iphone",
    "channel": "i5", 
    "locale": "zh_CN",
    "appver": "1.1.6",
    "data":{
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
        "cur_page": 2,
        "max_page": 7,
        "total_rows": 14,
        "rows": [
            {
                "id": "d011507599231158AC4QDXQpe3",
                "user_id": "d011495098151930dz0CsXrxSm",
                "action": "12",
                "value": "1",
                "order_id": null,
                "source_user_id": null,
                "remark": null,
                "create_at": "2017-10-10 09:33:51",
                "create_by": "d011495098151930dz0CsXrxSm",
                "update_at": null,
                "update_by": null,
                "delete_at": null,
                "delete_by": null,
                "current_total_value": 10,
                "sharelog_id": "d011507599163068fMA9fG4Y95",
                "action_text": "app分享-奖励"
            },
            {
                "id": "d011506044508103Ugk6vhVBV9",
                "user_id": "d011495098151930dz0CsXrxSm",
                "action": "12",
                "value": "1",
                "order_id": null,
                "source_user_id": null,
                "remark": null,
                "create_at": "2017-09-22 09:41:48",
                "create_by": "d011495098151930dz0CsXrxSm",
                "update_at": null,
                "update_by": null,
                "delete_at": null,
                "delete_by": null,
                "current_total_value": 9,
                "sharelog_id": "d0115060444694676nVqmSxukx",
                "action_text": "app分享-奖励"
            }
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
