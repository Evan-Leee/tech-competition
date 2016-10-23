Jekyll theme
=========================

Jekyll theme based on [Freelancer bootstrap theme ](http://startbootstrap.com/template-overviews/freelancer/)

## 使用方法
 - 把想要使用的图片放到 `/img/portfolio/`路径下
 - 如果需要使用contact功能，把自己邮箱`you@email.com` 替换到 `_includes/contact_static.html` 文件中对应的位置. 
 - 可以创建自己的post. post都为markdown格式，具体模板如下:
```
layout: default
modal-id: 1
date: 2014-07-18
img: cabin.png
alt: image-alt
project-date: July 2014
client: The Client
category: Web Development
description: The description of the project
```
 - 每一个模板对应页面上一个project，也就是portfolio板块下的东西，
 模板可以修改，可以添加自己想要的field
 
## Demo
[模板连接](https://evan-leee.github.io/tech-competition)

## 本地的启服务的方式
 - 安装好jekyll后 在文件目录下执行 `jekyll serve --baseurl '' `可以在本地`4000`端口查看模板内容
  