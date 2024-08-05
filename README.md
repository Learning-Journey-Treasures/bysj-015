![gh_17810254f3db_258](https://github.com/user-attachments/assets/a26b5cf2-44cc-4fa6-95c3-576fd8e5198c)

**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务。项目仅供学习和毕业设计参考~**

#### 1.项目介绍

技术栈+工具： SpringBoot +JSP + MySQL5 + Maven +IDEA2022

系统角色：管理员、普通用户

系统功能：管理员（商品分类管理、商品管理、商品咨询管理、订单管理、留言管理、销售统计、会员管理、轮播图管理）、普通用户/门户（注册登录、商城咨询、商品搜索、商品详情、在线购买、我的订单、我的收藏、猜你喜欢）

#### 2.项目部署

- 创建数据库，导入项目中的sql

- 打开IDEA，导入项目trade

- 根据本地数据库环境，修改数据库的连接信息 src/main/resources/application.properties 13-16行

- 启动项目，运行 http://localhost:8080/limall 普通用户账号/密码：15797881255/123456 

- 管理web http://localhost:8080/limall/admin/login.jsp  管理员账号/密码： admin/admin
