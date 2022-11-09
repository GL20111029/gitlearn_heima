[TOC]

# 1、开源
## 1.1 什么是开源开源

即开放源代码，任何人都可以去查看修改源代码

与之相对的就是闭源，即软件代码是封闭的，只有作者能查看和修改源代码

## 1.2 开源许可协议

开源并不意味着完全没有限制，为了限制使用者的使用范围和保护作者的权利，每个开源项目都应该遵守开源许可协议(Open Source License)

### 1.2.1 常见的五种开源协议

BSD（Berkeley Software Distribution）

Apache Licence 2.0

**GPL（GNU General Public License）**
```
GPL具有传染性的一种开源协议，不允许修改后和衍生的代码作为闭源的商业软件发布和销售
著名软件举例：Linux
```
LGPL（GNU Lesser General Public License） 

**MIT（Massachusetts Institute of Technology, MIT）**
```
是目前限制最少的协议，唯一的条件就是在修改后的代码或者发行包中，必须包含原作者的许可信息
jquery\Node.js
```

## 1.3 为什么要拥抱开源？

+ 开源给使用者更多的控制权
+ 开源让学习变得容易
+ 开源才有真正的安全

开源才是软件开发领域的大趋势，不必重复去造轮子，提高了开发效率

## 1.4 开源项目托管平台

+ Github (做好的开源托管平台)
+ Gitlab (对代码私有性支持较好，因此企业用户居多)
+ Gitee  (码云，是国产的开源项目托管平台。访问速度快，中文界面)

***因为只能托管Git的项目，所以它们的名字都以Git开头***

# 2、Github的使用

全球最大的开源项目托管平台，在这里你可以做

+ 关注自己喜欢的开源项目，为其点赞打call
+ 为自己喜欢的开源项目做贡献（Pull Request）
+ 和开源项目的作者讨论Bug和需求（Lssues）
+ 把喜欢的项目复制一份作为自己的项目进行修改（Fork）
+ 创建自己的开源项目
+ ……

## 2.1 新建空白远程仓库

+ 登录到Github，在左上角“+”里面选择 new repository
+ 填写完基本信息，如必填的Repository name，还有Description（选填）,仓库建议选择public（公开）
+ 然后点击 create repository

## 2.2 远程仓库的两种访问方式

Github上的远程仓库分为两种访问方式，分别是HTTPS和SSH

1. HTTPS零：配置；但是每次访问仓库需要重复输入Github的账号密码才能访问成功
2. SSH：需要额外的配置；但是配置成功后，每次访问就不要重复上输入Github的账号和密码了（推荐）

