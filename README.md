# 参赛手册

# 首届vLoong能源AI挑战赛

欢迎各位同学参加vLoong能源AI挑战赛，我们通过比赛机制，**鼓励选手创新方法（不必严格遵守原论文方法）复现顶刊论文指标，达到更高精度**，助力更多科研成果落地，为智慧能源开源生态建设贡献力量。

本次挑战赛以线上比赛的形式进行，参赛选手需在规定时间复现并改进模型，率先达到 **指定精度** 的选手通过验收即可获得复现奖，并依据最终精度排名瓜分万元现金大奖！



# 一、赛程赛制

## **1  整体说明**

![img](https://github.com/thinkenergy/vloong-nature-energy/blob/master/static/流程图.jpg)

（1） **报名**：报名比赛的同学，你需要进入vLoong能源AI挑战赛社群进行报名，所有大赛相关信息都会在群中及时同步；

（2） **讲座**：为了大家能够更好的理解和实践比赛，我们特意为大家准备了比赛宣讲与论文复现案例实操经验分享；

（3） **重要**：收到论文后，自行新建一个GitHub Repo；

（4） **提升**：为提升对论文的理解，选手需要跑通组委会提供的原论文参考代码。

（5） **福利**： 跑通参考代码后，你可以发邮件至[ vLoong@thinkenergy.tech ](http://vLoong@thinkenergy.tech)联系工作人员，简要描述模型重要信息并给出原论文参考代码的预测结果，邮件模板见[邮件提交规范](https://github.com/thinkenergy/vloong-nature-energy/blob/master/邮件提交规范.md) ，经邮件确认后可以分配 **专属导师** ，一对一贴身提供论文复现答疑；

（6） **完成**：按照官方 [REPO提交规范](https://github.com/thinkenergy/vloong-nature-energy/blob/master/REPO%20%E6%8F%90%E4%BA%A4%E8%A7%84%E8%8C%83.md)中的文档和规范，提供数据、模型、基本使用（模型训练、评估、项目主文件）等信息，在文档中体现训练过程的部分日志信息以及预测结果；

（7） **重要**： 比赛完成后提交结果，按邮件模板，发送邮件至[ vLoong@thinkenergy.tech ](http://vLoong@thinkenergy.tech)；如需提供训练日志(train.log)文件，训练日志中需要包含loss、验证集精度（如果训练时开启评估），当前的epoch和iter数量；model文件夹内模型必须可以通过参赛队伍提供代码重新生成；**以此完成结果的正式提交**，提交时间以组委会收到邮件时间为准（复现奖以第一次提交符合精度时间为准）

（8） **验收**：提交后3个工作日内，组委会进行验收，如果需要修改，会及时通知选手，选手修改后再次完成提交；

（9） **奖励发放**：**最终提交论文的精度、代码规范、Repo文档符合要求后，宣布论文复现成功并更新比赛信息**，前5名达到精度要求的选手即可获得复现奖，并依据最终精度排名瓜分万元现金大奖！



> vLoong平台是昇科能源自主研发的国内首个电池 AI 开放平台，于 2021 年 12 月 8 日正式上线，配备了可智能化调度的算力。提供在线编程环境、GPU算力、海量开源算法和开放数据，帮助开发者快速创建和部署模型。



# 二、挑战要求

| **论文名称**                                                 | **复现参考实现代码**                                         |                        **复现数据集**                        |                       **复现精度要求**                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | :----------------------------------------------------------: | :----------------------------------------------------------: |
| [2019 Data-driven prediction of battery cycle life before capacity degradation.pdf](https://github.com/thinkenergy/vloong-nature-energy/blob/master/2019%20Data-driven%20prediction%20of%20battery%20cycle%20life%20before%20capacity%20degradation.pdf) | [template](https://github.com/thinkenergy/vloong-nature-energy/blob/master/repo_template) | 以下三种数据集使用方式参赛选手可任意选择： <br/>1.原作者链接 https://data.matr.io/1 <br/>2.腾讯微云链接 https://share.weiyun.com/cjmHpfld <br/>3.vLoong算力平台链接 http://vloong.thinkenergy.tech/data/datasets/custom/154 | MAPE≤10% （注：第4步“跑通参考代码”无精度要求；评选“复现奖”、“季军奖”、“亚军奖”、“冠军奖”复现精度最低应达到此要求） |

1. 参赛选手需反复阅读论文，并理解论文中提到的实验思路，明确实验背景以及方法、实验过程、实验目的。

1. 本次比赛不必严格遵守原论文实验方法，鼓励参赛选手使用创新方法，包括但不限于使用不同的feature、创新模型结构等。

1. 本次比赛的复现指标需要与论文在相同的实验背景下得到，例如：9.1%的test error是在前100个cycle中得到的，为保证实验背景一致，复现指标也需要在前100的cycle中得到。

![img](https://github.com/thinkenergy/vloong-nature-energy/blob/master/static/image.png)

# **三、时间安排**

| **时间**        | **日程**              |
| --------------- | --------------------- |
| 2022/6/30       | 发布比赛&报名入口开启 |
| 2022/7/31 24:00 | 报名入口关闭          |
| 2022/7/31 24:00 | 比赛结果截止提交      |

# **四、奖项设置**

| **奖项**                           | **个数（团队）** | **奖励** |
| ---------------------------------- | ---------------- | -------- |
| 冠军奖                             | 1                | ¥5000    |
| 亚军奖                             | 2                | ¥2000    |
| 季军奖                             | 3                | ¥500     |
| 复现奖                             | 5                | 精美车模 |
| 参与奖（提交能成功运行的复现代码） | 不限             | 免费算力 |

**其他奖励**

比赛中表现优异的同学有机会加入vLoong Studio人才计划。

> vLoong Studio是由昇科能源与欧阳明高院士工作站联合设立，旨在研发前沿AI for Smart Energy技术，探索AI技术在新能源领域的应用，促进学科交叉，实现AI技术产业化落地，培养高级电池AI人才。



**特别注意**

（1）**以上所有提及金额均为税前金额。**

（2）获奖评定需选手提供系统报告（包括方法说明、系统代码和数据、参考文献和引用开源工具等）及团队成员名单。



# **五、参赛方式**

## 1  参赛对象

本次竞赛面向全社会开放，不限年龄、身份、国籍，相关领域的个人、高等院校、科研机构、企业单位、初创团队等人员均可报名参赛。

## 2  参赛要求

（1）支持以个人或团队（线下自由组队）的形式参赛，**每支参赛队伍的人数不超过3人**，允许跨单位/院校自由组队，每人只能参加一支队伍。

（2）参赛选手报名须保证所提供的个人信息真实、准确、有效。如发放奖金或礼品时发现选手填写的报名信息与个人身份不相符，组委会将保留停止发放奖金或礼品的权利。

## 3  比赛报名

（1）组队报名

- **组队报名方法**：队长提前确认参赛队员并填写报名表报名，自比赛报名截止前起，队长不得转让队长身份、解散团队、移除队员，队员不得离开团队。

（2）官方交流报名群

![img](https://github.com/thinkenergy/vloong-nature-energy/blob/master/static/加入群聊二维码.png)



## 4  结果提交

（1）结果提交请按邮件模板，发送邮件至[ vLoong@thinkenergy.tech ](http://vLoong@thinkenergy.tech)。

（2）大赛组委会会定期更新赛事信息到官方社群中。

（3）如果发现有恶意提交、抄袭等违规作弊的现象，可能会取消比赛资格。

## 5  vLoong系列挑战赛不收取任何报名费用。



# 六、反作弊声明

- 参与者禁止加入多个战队报名，一经发现将取消成绩；

- 参与者禁止在指定考核技术能力的范围外利用规则漏洞或技术漏洞等不良途径提高成绩排名，一经发现取消成绩；

- 参与者如有恶意提交、抄袭等违规作弊的现象，可能会取消比赛资格。

# 七、其他

主办方在法律法规许可范围内对本比赛规程享有解释权。