# 静态网站部署至github

### 1. 创建**.github.io仓库

登录GitHub创建一个新的远程仓库

![创建](./READMEfile/p1.png)

用户什么名字，仓库就建立“你的名字.github.io”

![命名](./READMEfile/p2.png)

然后可在仓库的setting

![网址](./READMEfile/p3.png)

滚动拉到GitHub Pages，能够看到部署的网址为：“用户名.github.io”

![查看网址](./READMEfile/p4.png)

基本立马可登陆查看

### 2. 部署代码

最简单的是直接在Code中，选择Upload files

![点击upload](./READMEfile/p5.png)

然后会出现页面，让你直接拖拽文件

![拖拽文件](./READMEfile/p6.png)

例如我将文件全拖拽提交后

![显示文件](./READMEfile/p7.png)

提交成功了，输入网址查看，成了

![显示文件](./READMEfile/p8.png)

### 3. 修改后更新

也是直接拖拽就欧克，反正会自动覆盖

# 关于访客统计插件添加

[插件网址:https://clustrmaps.com/](https://clustrmaps.com/)

### 1. 插件官网获得相关代码

先创建用户（免费用户），在主页点击Get Your Map

![显示文件](./READMEfile/p9.png)

填入github.io网址

![填写1](./READMEfile/p10.png)

选了free计划

![填写1](./READMEfile/p11.png)

选择Map widget的方式

![选择map widget](./READMEfile/p12.png)

复制下图所示内容

![选择复制](./READMEfile/p13.png)

### 2. 修改自己的index.html

找到id="footer"处，将复制内容粘贴即可

``` html
<div id="footer">
  <div style="height:30px;float:right">
      
	<!-- 复制内容粘贴至此处 -->
      
  </div>
```

图示位置：

![代码粘贴处](./READMEfile/p14.png)

<div id="footer">

然后将index拖拽至库进行更新就好了。

