#### 注册/登录

* 功能: 登录
* (GET) URL: [/api/app/login](./login.md)


* 功能: 发送手机验证码（注册&重置密码），检查手机号是否注册
* (GET) URL: [/api/app/register/checkPhone](./register_check_phone.md)    


* 功能: 验证手机验证码
* (GET) URL: [/api/app/register/checkPhoneCode](./register_check_phone_code.md)


* 功能: 发送手机验证码，直接发，不检查手机号在系统中注册情况
* (GET) URL: [/api/app/register/sendPhoneCode](./register_send_phone_code.md)


* 功能: 手机号注册
* (GET) URL: [/api/app/register/phone](./register_phone.md)


* 功能: 手机号重置密码
* (GET) URL: [/api/app/resetPassword/phone](./reset_password_phone.md)


* 功能: 发送邮箱验证码（注册&重置密码）
* (GET) URL: [/api/app/register/checkEmail](./register_check_email.md)


* 功能: 验证邮箱验证码
* (GET) URL: [/api/app/register/checkEmailCode](./register_check_email_code.md)


* 功能: 发送邮箱验证码，直接发，不检查邮箱在系统中注册情况
* (GET) URL: [/api/app/register/sendEmailCode](./register_send_email_code.md)


* 功能: 邮箱注册
* (GET) URL: [/api/app/register/email](./register_email.md)


* 功能: 邮箱重置密码
* (GET) URL: [/api/app/resetPassword/email](./reset_password_email.md)



#### 课程 

* 功能: APP 首页，包括顶部轮播图、课程目录
* (GET) URL: [/api/app/index](./index.md)


* 功能: 课程详情
* (GET) URL: [/api/app/lesson](./lesson.md)


* 功能: 课程目录
* (GET) URL: [/api/app/contentTree](./content_tree.md)


* 功能: 课内容
* (GET) URL: [/api/app/content](./content.md)


* 功能: 更新学习进度，把当前节点标记为 学习中 或 已学完，计算整个课程的学习进度百分比，以及本次最新学到的节点 id
* (GET) URL: [/api/app/updateLearnStatus/:lesson_id](./update_learn_status.md)



#### 订单


* 功能: 确认订单
* URL: [/api/app/confirmorder](./confirm_order.md)


* 功能: 订单预计算
* (GET) URL: [/api/app/precalprice](./precal_price.md)


* 功能: 创建订单
* URL: [/api/app/createorder](./create_order.md)


* 功能: 取消订单
* URL: [/api/app/cancelorder](./cancel_order.md)


* 功能: 订单列表
* (GET) URL: [/api/app/myorders](./my_orders.md)


* 功能: 订单详情
* (GET) URL: [/api/app/myorder](./my_order.md)



#### 个人中心


* 功能: "我的"页面综合接口，包含用户基本信息、未支付数、未使用优惠券数、未分享数、未分享可领取积分
* (GET) URL: [/api/app/userInfo](./user_info.md)


* 功能: 我的积分记录
* (GET) URL: [/api/app/pointrecord](./point_record.md)


* 功能: 修改用户信息
* URL: [/api/app/saveUserInfo](./save_user_info.md)


* 功能: 上传头像
* URL: [/api/app/saveUserPhoto](./save_user_photo.md)


* 功能: 积分规则
* (GET) URL: [/api/app/rule](./rule.md)


#### 分享


* 功能: 课程分享
* (GET) URL: [/api/app/addsharelog](./add_share_log.md)


* 功能: 更新分享状态
* (GET) URL: [/api/app/updatesharelog](./update_share_log.md)


* 功能: 打卡分享
* (GET) URL: [/api/app/learnshare](./learn_share.md)


* 功能: 一键分享 APP
* (GET) URL: [/api/app/appshare](./app_share.md)



