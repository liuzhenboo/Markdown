
## **一.** 我学**markdown**的目的 
**markdown**是一种轻量级**标记语言**，语法非常简单，十分适合写笔记。以后准备以markdown为我的github仓库中的笔记格式。

## **二.** **markdown**语法
我会根据实际使用时候遇到的问题来更新markdown语法部分
### *2.1标题*
使用`#`，可表示1-6级标题。
```
# 一级标题   
## 二级标题   
### 三级标题   
#### 四级标题   
##### 五级标题   
###### 六级标题    
```
效果：
 # 一级标题   
 ## 二级标题   
 ### 三级标题   
 #### 四级标题   
 ##### 五级标题   
 ###### 六级标题

### *2.2 段落*

#### **2.2.1 换行**

不同段落之间空一行即可

### *2.3 代码区块*
代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）。如    
普通段落：

void main()    
{    
    printf("Hello, Markdown.");    
}    

代码区块：

    void main()
    {
        printf("Hello, Markdown.");
    }

其它方法：

\```

liu

\```

效果：

```
liu
```


**注意**:代码块需要和普通段落之间存在空行。

### *2.4 区块引用*
    > liu

示例：
> liu


### *2.5 字体*
在强调内容两侧分别加上`*`或者`_`，如：

 \*斜体\*，\_斜体\_    
 \*\*粗体\*\*，\_\_粗体\_\_

效果：

 *斜体*，_斜体_    
 **粗体**，__粗体__

### *2.6 列表*
#### *2.6.1 无序列表*

使用`-`、`+`、或`*`标记无序列表，如：

 \+  第一项

 \+   第二项

 \+   第三项

**注意**：标记后面最少有一个空格或制表符。若不在引用区块中，必须和前方段落之间存在空行。

效果：
 + 第一项
 + 第二项
 + 第三项
#### *2.6.2 有序列表*
有序列表的标记方式是将上述的符号换成数字,并辅以`.`，如：

 1 . 第一项   
 2 . 第二项    
 3 . 第三项    

效果：
 1. 第一项
 2. 第二项
 3. 第三项


### *2.7 分割线*

分割线最常使用就是三个或以上`*`，还可以使用`-`和`_`。

\***

输出：

***


### *2.8 链接*
链接可以由两种形式生成：**行内式**和**参考式**。  

**行内式**：

 \[lzb的Markdown库\]\(https:://github.com/liuzhenboo/Markdown\)

效果：
> [lzb的Markdown库](https:://github.com/liuzhenboo/Markdown)

**参考式**：

\[lzb的Markdown库1\]\[1\]    
\[lzb的Markdown库2\]\[2\]    
\[1\]:https:://github.com/liuzhenboo/Markdown

\[2\]:https:://github.com/liuzhenboo/Markdown

效果：

[lzb的Markdown库1][1]    
[lzb的Markdown库2][2]

[1]: https:://github.com/liuzhenboo/Markdown

[2]: https:://github.com/liuzhenboo/Markdown

**本地文件夹链接**

    点击[图片资源](resource)文件夹
效果：

点击[图片资源](resource)文件夹
### *2.9 图片*
添加图片的形式和链接相似：
#### 2.9.1 原图大小的图片

```
![图片名称](https://github.com/用户名/仓库名/raw/分支名/图片文件夹名称/***.png or ***.jpg)
```
比如：
```
![Aaron Swartz](https://github.com/liuzhenboo/Markdown/raw/master/resource/Aaron_Swartz.jpg)
```
效果：

![Aaron Swartz](https://github.com/liuzhenboo/Markdown/raw/master/resource/Aaron_Swartz.jpg)

### *2.9.2 调整图片的大小*

语法如下：

    <a href="https://github.com/liuzhenboo/Markdown/raw/master/resource" target="_blank"><img src="https://github.com/liuzhenboo/Markdown/raw/master/resource/Aaron_Swartz.jpg" 
    alt="example" width="240" height="180" border="10" /></a>

效果：

<a href="https://github.com/liuzhenboo/Markdown/raw/master/resource" target="_blank"><img src="https://github.com/liuzhenboo/Markdown/raw/master/resource/Aaron_Swartz.jpg" 
    alt="example" width="240" height="180" border="10" /></a>

 


### *2.10 反斜杠`\`*
相当于**反转义**作用。使符号成为普通符号。

    