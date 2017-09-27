* 功能: 我的积分记录

* (GET) URL: /api/app/pointrecord

* request
```
http://apptest.bstcine.com/api/app/pointrecord?token=cb84Rvnc
```

* response
```
{
    "status": true,
    "data": {
        "currPage": 1,
        "pageSize": 2,
        "pageNum": 5,
        "totalRow": 8,
        "startPage": 1,
        "endPage": 4,
        "hasPrevious": false,
        "hasNext": false,
        "isFirst": true,
        "isLast": true,
        "totalPage": 4,
        "data": [
            {
                "id": "t011506334112200vZ4ZnyBJYH",
                "user_id": "466466466",
                "action": "11",
                "value": "1.00",
                "order_id": null,
                "source_user_id": null,
                "remark": null,
                "create_at": "2017-09-25 18:08:32",
                "create_by": "466466466",
                "update_at": null,
                "update_by": null,
                "delete_at": null,
                "delete_by": null,
                "current_total_value": 159,
                "sharelog_id": null,
                "action_text": "取消订单返还"
            },
            {
                "id": "t011506333919093MfJg0wkzSz",
                "user_id": "466466466",
                "action": "1",
                "value": "-1",
                "order_id": "2017092518052ZpNR",
                "source_user_id": null,
                "remark": null,
                "create_at": "2017-09-25 18:05:19",
                "create_by": "466466466",
                "update_at": null,
                "update_by": null,
                "delete_at": null,
                "delete_by": null,
                "current_total_value": 158,
                "sharelog_id": null,
                "action_text": "购买课程-消费"
            }
        ],
        "startRow": 0,
        "endRow": 2,
        "pages": [
            1,
            2,
            3,
            4
        ]
    }
}
```
