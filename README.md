# Readme

# MWeb mweb-stuart-theme Theme

mweb-stuart-theme 图示：

![1533480917765](http://res.stuarthua.com/1533480917765.png)

![1533480917766](http://res.stuarthua.com/1533480917766.jpg)

## 安装 (Install)

```
cd ~/Library/Containers/com.coderforart.MWeb/Data/Documents/themes/SiteThemes
git clone https://github.com/stuarthua/mweb-stuart-theme.git
```

## 使用方法（Usage）

### 网站拓展设置

![1533480917767](http://res.stuarthua.com/1533480917767.png)

* site_auther: 网站作者
* site_time: 网站©时间
* site_contact_email: 联系邮箱
* site_contack_github: 联系 github
* site_contact_stack_overflow: 联系 stack_overflow
* site_contact_instagram： 联系 instagram
* site_contact_twitter：联系 twitter
* site_contact_home：网站主页

### 网站菜单设置

![1533480917768](http://res.stuarthua.com/1533480917768.png)


#### Archives

直接填写 `archives.html`，重新生成网站，即可访问

#### Category

在 MWeb 静态网站文件夹中，新建文件

* 文件中写入：`# Category`
* 设置 HTML 文件名：fenlei （注意：不可更改）
* 勾选 `是否页面(Is Page)`

![1533480917769](http://res.stuarthua.com/1533480917769.png)

在网站菜单中填写 `fenlei.html`，重新生成网站，即可访问

#### About

>设置同 Category

在 MWeb 静态网站文件夹中，新建文件

* 文件中写入：
  ```
  # About
  
  <div class="page-title">About</div>
  
  Hello, I am Stuart Hua.
  
  <div class="page-title">License</div>
  
  * All the blogs are licensed under a [CC BY-NC-ND 4.0]  (http://creativecommons.org/licenses/by-nc-nd/4.0/) license.
  ```
* 设置 HTML 文件名：about （注意：不可更改）
* 勾选 `是否页面(Is Page)`

在网站菜单中填写 `about.html`，重新生成网站，即可访问

#### Index

>设置同 Category

在 MWeb 静态网站文件夹中，新建文件

* 文件中写入：`# Index`
* 设置 HTML 文件名：index （注意：不可更改）
* 勾选 `是否页面(Is Page)`

在网站菜单中填写 `index.html`，重新生成网站，即可访问

### 参考：

* http://coderforart.com/mweb-medium-like-theme.html
* https://zh.mweb.im/custom-site-theme-detail-zh.html

