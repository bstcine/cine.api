## 注册/登录

*  登录 

(GET) [/api/app/login](./login.md)
  
<br>
* 发送手机验证码（注册&重置密码），检查手机号是否注册

(GET)  [/api/app/register/checkPhone](./register_check_phone.md)  
 
<br>
*  验证手机验证码

 (GET)   [/api/app/register/checkPhoneCode](./register_check_phone_code.md)

<br>
* 发送手机验证码，直接发，不检查手机号在系统中注册情况

 (GET)  [/api/app/register/sendPhoneCode](./register_send_phone_code.md)

<br>
* 手机号注册

 (GET)  [/api/app/register/phone](./register_phone.md)

<br>
* 手机号重置密码

 (GET) [/api/app/resetPassword/phone](./reset_password_phone.md)

<br>
* 发送邮箱验证码（注册&重置密码）

 (GET) [/api/app/register/checkEmail](./register_check_email.md)

<br>
*  验证邮箱验证码

 (GET) [/api/app/register/checkEmailCode](./register_check_email_code.md)

<br>
* 发送邮箱验证码，直接发，不检查邮箱在系统中注册情况

(GET) [/api/app/register/sendEmailCode](./register_send_email_code.md)

<br>
*  邮箱注册

 (GET) [/api/app/register/email](./register_email.md)

<br>
*  邮箱重置密码

 (GET) [/api/app/resetPassword/email](./reset_password_email.md)

<br>

## 课程 

*  APP 首页，包括顶部轮播图、课程目录

 (GET)  [/api/app/index](./index.md)

<br>
* 课程详情

 (GET)  [/api/app/lesson](./lesson.md)

<br>
* 课程目录

 (GET) [/api/app/contentTree](./content_tree.md)

<br>
*  课内容

 (GET) [/api/app/content](./content.md)

<br>
* 更新学习进度，把当前节点标记为 学习中 或 已学完，计算整个课程的学习进度百分比，以及本次最新学到的节点 id

 (GET) [/api/app/updateLearnStatus/:lesson_id](./update_learn_status.md)


<br>

## 订单


* 确认订单

[/api/app/confirmorder](./confirm_order.md)

<br>
* 订单预计算

(GET)  [/api/app/precalprice](./precal_price.md)

<br>
* 创建订单

[/api/app/createorder](./create_order.md)

<br>
* 取消订单

 [/api/app/cancelorder](./cancel_order.md)

<br>
* 订单列表

 (GET) [/api/app/myorders](./my_orders.md)

<br>
* 订单详情

 (GET)  [/api/app/myorder](./my_order.md)



<br>

## 个人中心


* 功能: "我的"页面综合接口，包含用户基本信息、未支付数、未使用优惠券数、未分享数、未分享可领取积分
* (GET) URL: [/api/app/userInfo](./user_info.md)

<br>
* 功能: 我的积分记录
* (GET) URL: [/api/app/pointrecord](./point_record.md)

<br>
* 功能: 修改用户信息
* URL: [/api/app/saveUserInfo](./save_user_info.md)

<br>
* 功能: 上传头像
* URL: [/api/app/saveUserPhoto](./save_user_photo.md)

<br>
* 功能: 积分规则
* (GET) URL: [/api/app/rule](./rule.md)


<br>

## 分享


* 功能: 课程分享
* (GET) URL: [/api/app/addsharelog](./add_share_log.md)

<br>
* 功能: 更新分享状态
* (GET) URL: [/api/app/updatesharelog](./update_share_log.md)

<br>
* 功能: 打卡分享
* (GET) URL: [/api/app/learnshare](./learn_share.md)

<br>
* 功能: 一键分享 APP
* (GET) URL: [/api/app/appshare](./app_share.md)



