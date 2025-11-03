# 医疗报销系统设计与实现

## 前言

欢迎来到本医疗报销系统的设计与实现项目。本项目是基于Java语言的Spring Boot框架进行开发，适用于计算机毕业设计或实战项目学习。以下将为您详细介绍本项目的相关内容。

## 内容介绍

医疗报销系统是一款针对我国医疗保险业务的在线处理系统，旨在为用户提供便捷、高效的服务。通过本系统，用户可以在线提交报销申请、查询报销进度、了解报销政策等。系统后端采用Java语言开发，前端则使用了JS、Vue和CSS3等技术。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是本项目中的一段核心代码，展示了如何使用Java和Spring Boot框架进行数据库操作：

```java
// 引入Spring Boot相关依赖
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.web.bind.annotation.*;

// 创建一个控制器类，用于处理医疗报销相关的请求
@RestController
@RequestMapping("/api/medical")
public class MedicalReimbursementController {

    // 注入医疗报销服务类
    @Autowired
    private MedicalReimbursementService medicalReimbursementService;

    // 查询报销列表
    @GetMapping("/list")
    public List<MedicalReimbursement> list(@RequestParam("userId") int userId) {
        return medicalReimbursementService.getListByUserId(userId);
    }

    // 添加报销记录
    @PostMapping("/add")
    public boolean add(@RequestBody MedicalReimbursement reimbursement) {
        return medicalReimbursementService.addReimbursement(reimbursement);
    }
}
```

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/325749/8/4566/141270/689ddb91Fe11e9a42/a497a36fa7373278.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/294192/14/13060/34493/689ddb6fF9583a79b/1436673c54da13ee.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/314077/40/26737/81548/689ddb70Ff069fb37/07989bc2c98bbd91.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/309417/6/26645/83892/689ddb72F974cc8dd/e78f82e9a6fd1d53.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/312735/27/26140/47692/689ddb73F36bd5d87/1a9e45e82005eb83.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326432/6/4568/82825/689ddb74F8c43cd66/45a31deaf122c254.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/289563/13/25204/88300/689ddb74Fbb925eab/ca59799fdd6e9154.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326602/39/4530/83686/689ddb75F334129a8/15b10c078b05b00c.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/303342/2/24588/45785/689ddb75F851a55f6/a7d61ef8c1aa2836.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/308194/4/25108/32005/689ddb76F791d468c/7af24ba44f5dc561.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
