---
title: markdown 基本语法
date: 2021-01-27 21:20:58
tags: 随笔

---

# 测试markdown语法

## 一.标题

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

## 二.字体

**加粗**
*倾斜*
***斜体加粗***
~~加删除线~~

## 三.引用

>一级引用
>>二级引用
>>>>四级引用
>>>>>>>七级引用

## 四.分割线

---
分割线一


----- 

分割线二

## 五.图片

![keqing](/images/keqing/16007778945f69eea63857b1.36560461.jpeg '刻晴')

## 六.超链接
[简书](http://jianshu.com)
[百度](http://baidu.com)
[reference](https://www.jianshu.com/p/191d1e21f7ed)

## 七.列表

### 1. 无序列表
- 列表内容1
+ 列表内容2
* 列表内容3
```
	-，+，*都可以作为无序列表开头的标识
	
```
### 2. 有序列表
```
	数字加点如1. 2. 3. 等作为开头标识

```	
*注：列表可以嵌套*

## 八.表格
语法：
```
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
```
技术|所用语言|方向
---|:--:|--:
Spring Boot|java|后端/javaEE
Django|python|后端
Bootstrap|javascript|前端
虚幻四|c++|游戏开发
爬虫|python|黑客



## 九.代码

```
	单行代码：`内容`

```
如：`print('hello world')`

```
	多行代码：
	(```)
		......
		......
		......
	(```)	


```

## 十.流程图
```
flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&
```

flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op

