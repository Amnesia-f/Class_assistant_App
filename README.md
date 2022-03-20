# Class_assistant_App  班级管理助手

## 创作思想

当老师们平时在上课时，总会有统计学生缺勤次数、随机点名提问以及对学生回答情况进行评价等需求，但传统的方式有些许的缺点，如：

1. 老师同时教几个班级，记不清名字；

2. 老师手头上没有姓名册，无法进行点名；

3. 传统姓名册可能会因为插班生而未能及时更新。

4. 考勤数据纸质化难以保存；

5. 统计回答情况工作量繁琐；

综上所述，我开发了这一款App——班级管理助手。

## 同类优势

据我所知，市面上也是有类似于班级管理功能的App或PC端软件，

经过我对其他同类产品的实际体验，在其原有功能的基础上加以改进及创新，对比总结得出班级管理助手的优势：

1.支持直接调用学生数据，不必老师手动导入数据。

2.移动端App方式，方便随时随地直接打开使用。

3.支持在App内直接对学生数据进行操作和查找功能。

4.快速切换班级，方便老师在不同班级授课。

5.方便统一对数据进行管理。

6.支持抽取学号功能。

7.支持记录未考勤学生，避免抽取缺勤或特殊情况同学。

8.支持手动导入Excel表格添加学生数据。

9.支持对学生回答进行评价并统计导出为Excel表。


## 创作思路

### 随机点名

通过在教务系统或本地数据表格，将班级内所有学生及学号导入TinyWebDB数据库，

在手机端读取所在班级的学生信息，再通过随机抽取列表内姓名的方式达到点名的功能。

### 统计回答评价情况

在随机点名后，可以对学生进行A、B、C等级的评价，App将会保存评价数据至本地数据库中，

教师可以随时对评价情况进行查看并导出为excel表格进行其他操作。


## 实现功能

1. 支持对不同的班级学生进行点名操作；

2. 支持直接在手机端对数据库进行操作；

3. 支持模糊搜索学生名字(单字符或双字符)；

4. 支持抽取学号；

5. 支持对上课人数进行统计；

6. 支持导入excel表格功能，手动导入学生数据；

7. 支持对学生进行考勤操作，避免点名到缺勤学生；

8. 支持在线检测下载更新功能；

9. 支持保存使用数据至本地。

## 展望未来

1. 实现在手机端导入学生信息的Excel表格；

2. 统计学生回答问题次数及正确率；

3. 统计某学生缺勤次数并上报；

4. 添加统计学生回答问题正误次数的功能；

## 使用扩展

- [io.mohamed.CustomSpotlight.aix](https://community.kodular.io/t/f-os-custom-spotlight-extension/111632)（聚光灯）

- [com.sumit1334.fetchdownloader.aix](https://community.kodular.io/t/free-fetch-a-powerful-and-simple-download-tool/171951)（下载更新）

- [com.sunny.Net.aix](https://community.appinventor.mit.edu/t/net-get-some-information-about-network/10670?u=taifun)（检测网络状态）

## 服务支持

编写支持：[MIT AppInventor Wxbit](app.wxbit.com)

扩展来源：[Kodular Community](https://community.kodular.io/)

云端数据库：[TinyWebDB 网络微数据库](tinywebdb.appinventor.space)

图标来源：[iconfont - 阿里巴巴矢量图标库](https://www.iconfont.cn/)

## 相关信息

Copyright © 湛江市第十七中学

系湛江市第十七中学星火创客团队比赛项目
