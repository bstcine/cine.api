* 功能: 订单预计算

* (GET) URL: /api/app/precalprice

* request
```
http://apptest.bstcine.com/api/app/precalprice?token=cb84Rvnc&lesson_id=d011500278732891DXFVjw2D47&point=1&coupon_no=&operator=point
```

* response
```
{
    "status": true,
    "data": {
        "total_price": "198.00",
        "coupon_discount": "0.00",
        "balance_discount": "0.00",
        "point_discount": "1.00",
        "total_discount": "1.00",
        "pay_price": "197.00",
        "discount_price": "1.00"
    }
}
```
