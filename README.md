# 毕业设计
## 题目：《基于Java Web的新冠疫苗综合服务平台》
  新冠疫苗综合服务平台是一款旨在简化公众接种流程、提高接种效率的网站。使用的框架技术包括：Springboot、Vue、Mybatis，是一款前后端分离的管理平台。
# 主要功能
## 主要功能包括：
     用户端：
           1.接种在线预约：用户输入个人信息、接种情况并选择接种点与疫苗完成接种申请，并等待审批结果。
           2.在线医生问题咨询：实现一个聊天窗口，供用户与医生进行一对一问题咨询。
           3.地图信息查询：引入高德地图插件，对附近的接种点进行标记，提供位置坐标与基本信息。
           4.信息展示模块：对疫苗信息、新闻公告进行公示，提高交互性
           5.调查问卷：用户根据自身情况填写问卷，并得到结果评估。
           6.防疫动态管理：请求腾讯健康与网易接口并使用echarts工具对新冠与疫苗接种数据进行可视化的处理。
     医护端：
           1.预约审批：对用户的接种申请按照时间顺序进行审批。
           2.在线医生问题咨询：与上述相同。
           3.接种处理：包括填写接种信息、留观处理（倒计时30分钟）与接种计划安排并且接种者端进行同步更新。
     管理员端：
           1.人员信息管理：包括医护人员与接种者信息。
           2.数据可视化展示：使用折线图、饼状图与柱状图对疫苗接种情况进行可视化展示。
           3.资源文件管理：对需要在用户端进行公示的信息，如：通知公告、接种新闻等等，进行发布与删除管理
           4.接种计划审批：对接种点上报的接种计划按照实际情况进行审批。
           5.库存物资管理：对现存的物资进行可视化展示，并根据接种点的请求完成物资分配。
# 如何部署
    1.IntelliJ IDEA;
    2.尽量使用Chrome浏览器;
    3.安装Maven进行依赖管理;
    4.安装Vue运行环境;
    5.安装springboot环境;
    6.添加Mybatis依赖。
