/*
	author ： 梅刚
	time : 2014-10-14 10:10
	for : 定义前台目录，及项目规范
*/
1.项目基于jdk8 + tomcat7 + eclipse_luna开发。
2.项目编码统一使用utf-8。
3.项目前台目录结构:
	WebContent:
		|css -- 存放css的资源文件
		|image -- 存放图片的资源文件
		|js -- 存放js的资源文件
	eg.	|bootstrap -- 插件的目录(目前没有)
		|fclient -- 前台页面文件
		|bclient -- 后台页面文件
		|public -- 用来存放通用的jsp文件
		......
4.大家在建立文件的时候，记得加上/*author,time,for*/的注释，必须遵守。
	在Java class中就使用java doc的注释(eg.@author)。
5.代码必须有良好的规范，可读性。严格遵循缩进。
6.前台使用html5 + css3 + div + js。
......