
## 标题
> 在Markdown中，你只需要在文本前加上#即可，同理 你还可以增加二级标题、三级标题等等，可以到六级。只要增加#即可
> ，标题字号相应降低即可。例如:
```
  > # 一级标题
  > ## 二季标题
  > ### 三级标题
  > #### 四级标题
  ```
效果如下：
> # 一级标题
> ## 二级标题
> ### 三级标题
> #### 四级标题

## 引用
Markdown标记的区块是使用类似email中>的引用方式，只需要在整个段落的第一行加〉:
>Markdown标记的区块是使用类似email中>的引用方，只需要在整个段落的第一行加>:

* 区块嵌套可以嵌套，只要根据层次加上不同数量的>:
```
  > 这是第一级引用
  >> 这是第二级引用
  >
  > 回到第一级
  >
  
  ```
  效果如下：
  > 这是第一级引用
  >> 这是第二级引用
  >
  > 回到第一级
  >
  
  * 引用区块可以使用其他Markdown语法，包括 标题 列表 代码区块等。
  ``` 
     > # This is a header
     > 1. This is the first list.
     > 2. This is the second list.
     
     ```
     
效果如下：
 > # This is a header
 > 1. This is the first list.
 > 2. This is the second list.
 > 
 
 ## 代码
 只要你把你的代码包裹在```你就不需要通过无休止的所进来标记代码了。a，你可以指定一格可选得预言表示符，然
 后我们就可以为他启用语着色了。举个例子，这样可以为一段Ruby代码着色：
 
  ```ruby
  require 'redcarpet'
	markdown = Redcarpet.new("Hello World")
	puts markdown.to_html
	```
  ## 强调
  在Markdown中，可以使用*和_来表示斜体和加粗：
  ``` *Markdown*```  *Markdown*
  ``` **Markdown**``` *Markdown*
  ## 链接
  * 方括号显示说明，圆括号内显示网址，Markdown自动转化成链接，例如：
  ```[云开发平台](http://coding.net)```
  效果如下
  [云开发平台](http://coding.net)
  * 或者可以用<>，将网址放在中间，也能将地址转换成链接，例如：
  ``` <http://coding.net>```
  效果如下：
  <http://coding.net>
  ## 列表
  1. **无序列表**： * + - 都可以实现
  ``` * red
      - green
      + bule
      ```
  效果如下：
  * red
  - green
  + bule
 2.  **有序列表**: 直接用数字加.
 ``` 1. red
     2. green
     3. bule
     ```
 效果如下：
 1. red
 2. green
 3. bule

 3. 表格中使用引用要缩进>：
 ```
 * conding.net 的功能
  > 代码托管平台
  > 在线运营环境 
  > 代码质量监控
  > 项目平台管理
 ```
 效果图如下：
 * Coding.net有以下功能：
	>代码托管平台  
  >在线运行环境  
 	>代码质量调控   
  >项目管理平台 
  
## 图片
  
  
 
