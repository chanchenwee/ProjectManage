## Project management plans of practical training made by cw chai as the porject leader.
# X组项目进度安排

 
  本组项目中商家端开发进行整体任务分配机制，各成员同步开发自己负责部分组件，也在一定程度上降低了组件之间的耦合度。用户端开发由于功能之间的关联程度较强，于是分阶段性开发，由于是阶段性梯度开发，所以在开发过程中需要其他成员进行相关功能的修订。同时本次进度安排不安排假期周末，假期周末为计划同步时间，落后人员需要在假期、周末完成进度匹配，同时周五进行问题总结，查漏补缺，问题将于周末解决。
  本进度主要阐述始点、终点和关键点，部分过程将简述。

 

整体任务分配
|              |                                                              |                                  |
| ------------ | ------------------------------------------------------------ | -------------------------------- |
| 客户端       | 导航栏                                                       | 为不同功能实现不同的路由跳转     |
| 功能栏       | 陈列用户部分信息、展示logo、为个人中心创造入口               |                                  |
| 标签栏       | 页面标签功能                                                 |                                  |
| 用户密码登录 | 登录                                                         |                                  |
| 用户注册     | 手机号注册                                                   |                                  |
| 忘记密码     | 验证身份，重写密码                                           |                                  |
| 常见问题     | 常见问题集锦                                                 |                                  |
| 个人中心     | 个人信息维护和会员中心以及                                   |                                  |
| 美食检索     | 美食分类展示和点餐                                           |                                  |
| 评论         | 评价和评论                                                   |                                  |
| 购物车       | 商品增加、删除、提交                                         |                                  |
| 订单-红包    | 提交订单、取消订单、历史订单                                 |                                  |
| 支付         | 订单提交后支付                                               |                                  |
| 活动         | 活动展示区域                                                 |                                  |
| 通知         | 用户通知                                                     |                                  |
|              |                                                              |                                  |
| 商家端       | 财务统计                                                     | 通过统计有效订单，统计出收入信息 |
| 流量统计     | 通过分析用户登录信息和订单信息，从流量信息中获取不同分类     |                                  |
| 食品管理     | 维护食品属性信息，保证库存和价格正常                         |                                  |
| 食品分类管理 | 维护不同食品分类所包含的不同食品信息                         |                                  |
| 优惠管理     | 为不同身份的用户发放红包和维护满减信息                       |                                  |
| 活动面板维护 | 展示当前活动，提示用户相应的食品有活动优惠，方便用户直达活动商品 |                                  |
| ip限制管理   | 由于用户无需登录可直达主界面，所以限制恶意ip访问             |                                  |
| 用户管理     | 对恶意用户实施封禁                                           |                                  |
| 订单管理     | 维护订单（接单、取消订单）                                   |                                  |
| 评论管理     | 回复、删除                                                   |                                  |
| 权限管理     | 维护用户所属权限                                             |                                  |
| 角色管理     | 添加用户、维护用户信息                                       |                                  |

 

 

# 具体计划以及安排事宜
  **第一周** 6月22日-6月26日
**本周完全完成商家端的前后端开发工作，以及完成用户pc端前端页面总体架构(用户端任务备选，若无法完成，则可假期、周末进行)
**周计划准备：之前完成了商家端的大部分任务，同时由于本周工作日为四天，所以在本周进行商家端的整理工作。

6月22日
在之前开发结果的基础之上，完善页面布局和展示方式，以美化前端为当天的主要任务，同时进行功能完善，包括个人中心以及通知等次要功能；
搭建用户pc端git仓库；
xx完成用户pc端界面整体布局搭建；

6月23日
完成前端js部分编写，包括所需数据和控制方法等，同时完成跳转和一些弹出框的动态效果；
xx完成用户登录、注册、忘记密码和常见问题功能；
xx和xxx完成食品检索功能；

6月24日
创建数据库，并添加数据，同时完成ajax编写
xx在昨天食品检索功能的基础上，完成购物车功能；
xx在用户登录的基础上进行个人中心开发；
xx开始订单页面开发；
xx进行支付、活动、通知功能开发

6月26日

在本周的最后一天，进行进度统一，若进度同意产生问题，周末加班务必保质保量完成；同时进行商家端系统共同评估，保证功能的合理性，总结问题，进行系统修订；在本周末完成商家端系统所有工作；
对于用户pc端主要界面设计，与本周基本完成；
xx进行评论功能开发

**第二周** 本周应当可以进行同步开发工作
6月29日-7月3日
**实际上当用户端前端基本完成之后，所有人员即可以进行同步开发了。**
本周在上周基础上完成用户pc端界面设计，未完成人员**自行完成**，不进行单独时间分配，布局美化完成；同时在完成界面基础上，进行合理性讨论，修订前端问题；进行前端功能设计，完成数据和方法设计，保证页面连贯操作；最后有余力人员进行数据库创建和后端开发。

6月29日
各自进行界面设计和数据、方法编写

6月30日
各自进行界面设计和数据、方法编写

7月1日
各自进行界面设计和数据、方法编写

***\*****里程碑**7月2日
由于本系统的连贯性，从今天开始进行系统整合验证，进行错误总结和不合理部分处理（本任务由组长执行，发现问题记录并让相应负责人员修改）；
进行界面修订和js编写

7月3日
进行系统整合验证，验证过程中将出现一系列功能不合理、布局不合适等问题，可能需要局部大范围修订，即便需要修订也应当于本周末完成前端设计。

**第三周**

7月6日-7月10日
顺延前端功能设计，未完成人员可同时与数据获取进行同步开发；本周进行用户端数据库表创建和后端开发工作

7月6日
创建数据库表并开始后端开发同时结合前端测试

7月7日
后端开发和测试

7月8日
后端开发和测试

7月9日
***\*****里程碑（今天结束之后，移动端布局框架搭建好，而且伴随着正在开发的后端，之后的任务应当完成速度较于之前，有质的提升）** 后端开发和测试，以及将于今天进行移动端主要布局框架搭建

7月10日
后端开发和测试，xx开始实现用户登录、注册、找回密码、常见问题功能；
xx、xx进行美食检索功能编写
**备注：本周主要任务应当于今日完全完成，周末进行修订工作**

**第四周**（本周工作很有可能提前进行，因为用户端界面有较强的关联性，难以同步性开发，所以和其他工作进行同步开发效果更好）

7月13日-7月17日
移动端开发

7月13日
xx开始进行购物车功能编写；
xx在用户登录基础上进行用户中心开发；
xx进行支付、活动、通知功能开发

7月14日
xx开始订单页面开发；
xx在完成个人中心之后，在食品检索的食品条目信息中完成评论功能

7月15日
xx在以开发基础上，在订单中加入评论功能

7月16日
布局修订、美化界面，进行数据、方法编写

7月17日
完善动态效果，同时于今天进行最后的前端评估，小组成员发现问题，总结问题，于今天和周末进行问题修订，同时于本周末进行微服务搭建

**第五周**

7月20日-7月24日
本周修订完善之前功能，进行微信小程序开发和微服务搭建和相关配置实现

7月20日
xx、xx着手搭建环境，并开发；其他成员整理文档，并进行最终的测试和评估修订以及微服务搭建和相关功能实现

7月21日
xx、xx继续进行开发，并将于今天完成并进行测试。其他成员整理文档，并并进行最终的测试和评估修订以及微服务搭建和相关功能实现

7月22日
最终的测试和评估修订，以及整理文档

7月23日
文档整理

7月24日
答辩事宜
