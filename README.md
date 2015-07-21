SDN BOOT CAMP
===============

v0.1.0

[Openstack](http://www.openstack.org/)[Docker](https://www.docker.com/)[SDN/NFV](www.sdnlab.com) 是最近比较火热的技术领域，现写此书与大家交流技术心得，分享经验，您也可以提出宝贵意见，希望与大家共同进步。
     
本书最大的亮点和特色是：
1.本书不同于学院派教科书般的说教，也不同于行业分析类的理论推演，而是注重实战，并尽力可视化实战过程和结果，让小学生都能看的明白，亦能让研究生茅塞顿开
2.本书将也将重点关注编程的基本功积累，通过对openstack的代码解读，学习其设计和编程技巧

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
