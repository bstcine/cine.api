* 功能:
APP 发送手机验证码（注册&重置密码）

* (GET) URL: /api/app/register/checkPhone

* request
```
http://apptest.bstcine.com/api/app/register/checkPhone?phone=17612169975&resetPassword&phone_code=86&device
```

备注：
* resetPassword 为 true 时，为重置密码

* response
```
{
    "status": true
}
```
