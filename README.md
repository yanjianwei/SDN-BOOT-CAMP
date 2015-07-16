SDN BOOT CAMP
===============

v0.1.0

[SDN](www.sdnlab.com) 是网路领域比较火热的技术，为满足广大SDN技术爱好者的学习需要，现写此书与大家交流技术心得，分享经验，由于笔者在学习SDN的过程中，受益于开源的项目，书籍，网站，今以gitBook的形式开放给大家，共同进步。
     
本书最大的亮点和特色是：
本书不同于学院派教科书般的说教，也不同于行业分析类的理论推演，而是注重实验，并尽力可视化实战过程和结果，让小学生都能看的明白，亦能让研究生茅塞顿开。！


在线阅读：[GitBook](https://www.gitbook.io/book/yanjianwei/sdn-boot-camp) 

## 主要版本历史

* 0.1: 2014-07-16
    * 添加基本内容;
    * 编写前言部分。



---


## 参加步骤
* 在 GitHub 上 `fork` 到自己的仓库，如 `yanjianwei/SDN-BOOT-CAMP.git`，然后 `clone` 到本地，并设置用户信息。
```
$ git clone git@github.com:yanjianwei/SDN-BOOT-CAMP.git
$ cd SDN-BOOT-CAMP
$ git config user.name "yourname"
$ git config user.email "your email"
```
* 修改代码后提交，并推送到自己的仓库。
```
$ #do some change on the content
$ git commit -am "Fix issue #1: change helo to hello"
$ git push
```
* 在 GitHub 网站上提交 pull request。
* 定期使用项目仓库内容更新自己仓库内容。
```
$ git remote add upstream https://github.com/yanjianwei/SDN-BOOT-CAMP.git
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```
