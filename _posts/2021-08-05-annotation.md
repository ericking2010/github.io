---
git@gitee.com:sjdt/geekhall.cn.gitlayout: post
title:  "Annotation 笔记"
date:   2021-08-05 13:44:25 +0800
categories: Annotation
---

## 1. 原生注解
|注解	| 作用 |
|:----	|:---- |
|@Target|	|



## Spring中的注解

|注解	| 作用 |
|:----	|:---- |
|@SpringBootApplication|表示这是一个SpringBoot的应用，可以自启动|
|@Configuration|表示这是一个配置类|
|@Component|注册Bean，把对象交给Spring管理|
|@Repository|表示存储层Bean，用在持久层的接口上，这个注解是将接口的一个实现类交给spring管理|
|@Service|表示业务层Bean，把对象交给Spring管理|
|@Controller|表示展示层Bean，把对象交给Spring管理|
‘’## JSR303校验

|Constraint	| 详细信息 |
|:----	|:---- |
|@Null|	被注释的元素必须为 null|
|@NotNull|	被注释的元素必须不为 null|
|@AssertTrue|	被注释的元素必须为 true|
|@AssertFalse|	被注释的元素必须为 false|
|@Min(value)|	被注释的元素必须是一个数字，其值必须大于等于指定的最小值|
|@Max(value)|	被注释的元素必须是一个数字，其值必须小于等于指定的最大值|
|@DecimalMin(value)|	被注释的元素必须是一个数字，其值必须大于等于指定的最小值|
|@DecimalMax(value)	|被注释的元素必须是一个数字，其值必须小于等于指定的最大值|
|@Size(max, min)	|被注释的元素的大小必须在指定的范围内|
|@Digits (integer, fraction)	|被注释的元素必须是一个数字，其值必须在可接|受的范围内
|@Past	|被注释的元素必须是一个过去的日期|
|@Future|	被注释的元素必须是一个将来的日期|
|@Pattern(value)	|被注释的元素必须符合指定的正则表达式|
‘


## Conditional 扩展注解
|注解	| 作用 |
|:----	|:---- |
|@ConditionalOnJava|系统的java版本是否符合要求|
|@ConditionalOnBean|容器中存在指定Bean|
|@ConditionalOnMissingBean|容器中不存在指定Bean|
|@ConditionalOnExpression|满足SpEL表达式指定|
|@ConditionalOnClass|系统中有指定的类|
|@ConditionalOnMissingClass|系统中没有指定的类|
|@ConditionalOnSingleCandidate|容器中只有一个指定的Bean，或者这个Bean是首选Bean|
|@ConditionalOnProperty|系统中指定的属性是否有指定的值|
|@ConditionalOnResource|类路径下是否存在指定资源文件|
|@ConditionalOnWebApplication|当前是Web环境|
|@ConditionalOnNotWebApplication|当前不是Web环境|
|@ConditionalOnJndi|JNDI存在指定项|

## MyBatis中的注解：
|注解	| 作用 |
|:----	|:---- |
|@Mapper|表示这是一个MyBatis的Mapper类，加了@Mapper注解之后接口在编译时会生成相应的实现类|
|@MapperScan("cn.geekhall.mapper")|扫描某个包下的所有类作为Mapper|


