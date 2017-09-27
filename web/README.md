#### `GET` /login 用户登录页

* go 可选，encodeURIComponent 后的 URL 地址，用于登录后跳转
* login 可选，登录框自动填写账号

#### `GET` /resetPassword 用户找回密码页 

* type 可选，默认为1，1:手机号找回 2:邮箱找回

#### `GET` /api/web/resetPasswordByPhone PC 端通过手机重置密码

* phone 手机号
* phone_code 可选，默认为86
* password 密码
* auth_code 验证码

#### `GET` /api/web/resetPasswordByEmail PC 端通过邮箱重置密码
* email 邮箱
* password 密码
* auth_code 验证码

#### `POST` /api/web/login 用户登录
* go encodeURIComponent 后的 URL 地址，用于登录后跳转
* username 登录账号，可用 `login`、`email`、`phone` 登录
* password 密码



