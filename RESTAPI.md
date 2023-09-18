RESTAPI PROJECT 
# Introduction

## multi-layers Java Web Application
why USE multi-layer 

decoupling the code, make the application easy to maintain  
make the code reusable within component and across multiple system  
make it easy to extend the code to add new feature development  
team coding/unit testing  

## JavaEE-3-tier architecture
将整个业务应用划分为:  
**界面层UI(User Interface layer)** 用于显示数据和接收用户输入的数据,为用户提供一种交互式操作的界面  
**业务逻辑层BLL(Business Logic layer)**  
**数据访问层DAL(Data Access layer)**


![image](https://github.com/quinlan9/API/assets/129864794/fea46feb-920b-40eb-ba60-339073ae021a)

javaWeb三层构架: https://zhuanlan.zhihu.com/p/30832759    
use Spring MVC(Model-View-Controller) 做Application layer.  
use Spring IOC(Inversion of Controller)别名DI(Denpendency Injection) 做Service layer  

## HTTP Status
201 - record created  
200 - ok status  
204 - no content status  
400 - bad request  
403 - forbidden  
404 - not found  
500 - internal server error  
405 - method not allowed  
409 - used for rest api that you added a duplicated record  

## REST API APPLICATION
从最后层开始设计

1.创建entity bean: 一个对象负责和数据库做communication .  使用spring Data JPA



