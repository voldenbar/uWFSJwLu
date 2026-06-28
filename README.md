# 前言

随着新冠疫情的不断发展，小区疫情防控变得越来越重要。为了更好地管理小区疫情，我们开发了一款基于微信小程序的小区疫情防控SSM系统。本文将详细介绍该项目的内容、技术以及如何获取免费源码。

# 内容介绍

本微信小程序小区疫情防控SSM系统主要包括以下功能：个人信息管理、健康状况上报、疫情动态查询、防控知识学习等。通过这些功能，业主可以便捷地上报健康状况，实时了解疫情动态，学习疫情防控知识，提高防疫意识。同时，物业管理人员可以高效地收集、整理、分析小区疫情数据，为小区疫情防控提供有力支持。

# 技术介绍

## 语言：Java

## 使用框架：Spring Springmvc，MyBatis，微信小程序

## 前端技术：JS、Vue、CSS3，Uniapp

## 开发工具：IDEA/Eclipse，Uniapp

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven：apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中的部分核心代码：

```java
// 查询疫情动态
@RequestMapping(value = "/queryDynamics", method = RequestMethod.GET)
public ResponseBean queryDynamics(@RequestParam("userId") String userId) {
    List<EpidemicDynamic> dynamics = epidemicDynamicService.queryByUserId(userId);
    return new ResponseBean(HttpStatus.OK.value(), "查询成功", dynamics);
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/333293/27/12461/79473/68c57c9eF6ed9626b/450bcd8f8c2cd741.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/334253/20/12776/11424/68c57c76F5154f0ba/2acf21d824e8367d.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/342731/2/1906/23945/68c57c76Fc1980c57/9c18cd0864a5f607.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/339808/39/10395/13648/68c57c77Fd9429276/ce65c53b14232026.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327088/1/19884/19144/68c57c77F2774db82/874bace8cd7b761a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340221/38/10446/14682/68c57c78F1f2941a5/5024df27b7178b38.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/350447/35/3059/13965/68c57c78F99aedc9d/322124e4b65496d0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/337748/14/8831/68337/68c57c79Fa30aed09/c4ea9bdf9315313e.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/345675/22/3058/14649/68c57c78F531a541e/7e5318a571da45ec.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327494/34/19771/36502/68c57c79Facef762c/c8fc413d77f63bf7.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
