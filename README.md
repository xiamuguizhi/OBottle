﻿# OBottle 🍪 
## 更轻量的免数据库博客——OBottle  
* Markdown解析器源于Parsedown:  
😂 <http://parsedown.org>  

![](https://ww2.sinaimg.cn/large/ed039e1fgy1ft3gual1czj20qc0englt)   

--------------------------------
<h3 style='color:0099FF;'>麻雀虽小，五脏俱全</h3> 

--------------------------------
## 质感设计版:MDBottle  
感谢@Subilan为OBottle创造MDUI版.  
<https://github.com/Subilan/MDBottle>  

--------------------------------
## 特点♂
* 轻便  
* 超容易备份  
* 支持自定义模板  
* 自带标签页，搜索功能 
* 支持文章置顶  
* 简洁,高速  
* 原生AJAX  
* RSS支持  
 
--------------------------------
## 备份方法
打包根目录下的**p**目录，走人~

--------------------------------
## RSS
访问/r目录即可.  

--------------------------------
## 关于安装  
1. 根目录下解压后界面就可以访问 
2. 访问/a/，会显示让你用指定方式生成通行证，之后登陆即可发布文章/页面.
3. 修改/a/conf.php文件以达到配置的目的。
然后 ...好好享受♂吧！ 

--------------------------------
## 隐藏的东西
* 标签页http://localhost/#tag
* 搜索文章http://localhost/#?搜索内容  

<ul>可搜索内容：

<li>日期</li>
<li>文章标题</li>
<li>文章内容</li>
</ul>  

--------------------------------
## 模板说明  
* 目录：./t  
* 替换值：  

  | 内容 | 值 | 注意 |  
  |:-------:|:-------:|:-------:|  
  | [rand:\<value\>] | 范围1-范围2 | 必须要填写两个范围，例如[rand:1-50]取1-50中的随机数 |  
  | [file:\<value\>] | 文件在./t/内的路径 | 不用写t/，例如放在./t/style.css，写作[file:style.css] |  
  | [name] | 无 | 返回站点名字，仅用于header/footer |  
  | [intro] | 无 | 返回站点描述，仅用于header/footer |  
  | [year] | 无 | 返回当前年份，仅用于header/footer |  
  | [avatar] | 无 | 返回站点头像地址，仅用于header/footer |  
  | [host] | 无 | 返回站点url地址，仅用于header/footer |  
  | [posts] | 无 | 返回文章**列表**，仅用于m.php |  
  | [title] | 无 | 返回当前文章的标题，仅用于p.php |  
  | [editbar] | 无 | 返回当前文章的编辑栏，仅用于p.php |  
  | [date] | 无 | 返回当前文章的日期，仅用于p.php |  
  | [!page] | 无 | 如果不是页面而是文章，加载[!page]后方的内容(常用于评论区的加载)，仅用于p.php |  
  | [tag] | 无 | 返回当前文章的标签条，仅用于p.php |  
  | [searchs] | 无 | 返回当前搜索的**列表**，仅用于search.php |  
  | [tags] | 无 | 返回有所有标签的**列表**，仅用于tag.php |  
  
* 额外的html:  
  1. post.html 文章**列表**每一项的样式  
  2. tags.html 标签**列表**每一项的样式  
