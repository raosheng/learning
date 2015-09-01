# SUPER TASKS LIST
## 待办清单

> 2015/8/27

学习Rails后的一个练习项目, 待办清单分配系统。

1. 练习登录模块。
2. 练习数据关联功能。
3. 练习软件测试。

## 页面
/signin
登录：用户名，密码
/signup
注册：用户名，密码，确认密码
/home
主页
用户名
任务清单，剩余时间
/tasks/:id
任务清单详情
/tasks
任务清单查找

## 数据库
表名：users 用户表
字段 | 类型 | 备注
-----|-------|-------
name | string | 用户名
password_digest | string | 密码
position | string | 权限

表名：tasks  任务表
字段 | 类型 | 备注
----|-------|--------
content | string | 任务内容
complete_date | date | 完成时限
user_id | intger | 负责人
