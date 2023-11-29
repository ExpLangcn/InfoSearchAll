**停止更新（归档处理），请关注后续项目**

**[点击关注 Twitter](https://twitter.com/ExpLang_Cn) 以便快速了解我的动态.**

----

# 网络测绘平台综合搜索引擎 - InfoSearchAll

#### 😄 I’m ExpLang [**Twitter**](https://twitter.com/ExpLang_Cn) 欢迎关注fo～


## 程序介绍

为了方便安全从业人员在使用网络测绘平台进行信息搜集时的效率，本程序集合了多个网络测绘平台，可以快速在多个网络测绘平台搜索信息并且合并展示及导出。

## 法律免责声明

本工具仅面向合法授权的企业安全建设行为，如您需要测试本工具的可用性，请自行搭建靶机环境。 在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。请勿对非授权目标进行扫描。 如果发现上述禁止行为，我们将保留追究您法律责任的权利。

如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任. 您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。

## 开发环境

Java14
JavaFx

已支持JDK8、JDK11

## 功能展示

- [x] 集合FOFA网络测绘搜索引擎
- [x] 集合360Quake网络测绘搜索引擎
- [x] 集合Shodan网络测绘搜素引擎
- [x] 支持搜索：标题、内容、应用、域名、主机、端口、系统
- [x] 批量导出到CSV表格文件
- [ ] 待集合奇安信网络测绘搜索引擎
- [ ] 待增加WEB应用存活探测功能
- [ ] 待增加WEB端口存活探测功能
- [ ] 待增加一些漏洞POC利用功能

## 更新记录

**2022.6.16 V1.2**

- 多线程查询 - 修复卡顿问题 #1 
- 统一语法支持 #2 
- 多语法组合查询支持 #2 
- JDK8适配 #6 

**注：由于三个平台的部分语法不同，所以无法统一查询，例如你可以使用FOFA的语法进行查询，但是你使用了Quake没有的语法那么就不会显示Quake的结果，其他平台同理，程序默认使用FOFA语法，你在搜索框输入FOFA语法，程序会转换成其他平台的语法进行联合查询，当然你也可以使用其他平台语法。**

**2022.6.9 V1.0**

- 发布程序

## 程序展示

#### 多平台搜索标题信息

![image-20220609180756672](https://tva1.sinaimg.cn/large/e6c9d24egy1h325izhp6mj20rk0kw434.jpg)

![image-20220609180829053](https://tva1.sinaimg.cn/large/e6c9d24egy1h325jhnr5hj20rk0kwwk3.jpg)

#### 配置中心

![image-20220609180900281](https://tva1.sinaimg.cn/large/e6c9d24egy1h325k1kghgj20rk0kwwja.jpg)
