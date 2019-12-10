# Markdown

Markdown是一种标记语言，创始人为John Gruber。其本意是创造一种易于阅读的，可以被转换为HTML的标记语言。本文亦使用Markdown语言编写。

## 历史

Markdown在创建初期纯粹是为了实现一种易于直接使用文本格式阅读，且可以转换为HTML的标记语言。 2004年，John Gruber发布了Markdown。

现在，Markdown出现了许多的分支，意为Markdown添加更多的额外功能（例如表格、数学公式、脚注、定义列表）。不过，这导致了Markdown生态圈的混乱。

一般情况，GFM（Github于2017年发布的Markdown规范）为现今Markdown的通用规范。

## 语法

### 段落
段落以空白行分隔。

### 标题

使用`#`标记标题，# xxx为一级，## xxx为二级，最高可到六级
```Markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
**显示效果**

># 一级标题
>## 二级标题
>### 三级标题
>#### 四级标题
>##### 五级标题
>###### 六级标题

### 文本标记

使用`*`号标记文本为斜体，粗体或斜粗体。

```Markdown
*斜体*，**粗体**，***斜粗体***
```

**显示效果**

>*斜体*，**粗体**，***斜粗体***

### 水平线
水平线使用`-`号标记

```Markdown
------
```

**显示效果**

> ------

### 列表
使用`+`或`*`号作为开头作为列表，可多级。
```Markdown
+ 一级列表1
  + 二级列表1
    * 三级列表1
  + 二级列表2
* 一级列表2
```

**显示效果**

> + 一级列表1
> + 二级列表1
> * 三级列表1
> + 二级列表2
> * 一级列表2

### 编号列表
使用`1. ；2. ；3. `等进行编号。
```Markdown
1. 一
2. 二
3. 三
```
**显示效果**
>1. 一
>2. 二
>3. 三

### 链接
使用`[Linkname](url://)`创建链接
```Markdown
点击[这里](../Markdown.md)
```
**显示效果**
>点击[这里](../Markdown.md)

### 图片
使用`![Image name](url://.png)`创建图片
```Markdown
![Google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)
```
**显示效果**
>![Google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)

### 引用
使用`>`符号置前进行引用
```Markdown
> 被引用
```
**显示效果**
> > 被引用

*由于显示效果以引用显示，这里的效果可能不清晰*

### 插入HTML
可以直接在Markdown里面插入HTML
```Markdown
**Youtube影片**
<iframe width="300" height="300" src="https://www.youtube.com/embed/5v9UyBc03og" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in -picture" allowfullscreen></iframe>
```
**显示效果**
>**Youtube影片**
><iframe width="300" height="300" src="https://www.youtube.com/embed/5v9UyBc03og" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture- in-picture" allowfullscreen></iframe>

### 表格
在GFM里，支援了表格的使用。
```Markdown
| 列1 | 列2 |
| :-------- | :-------- |
| 左对齐项1 | 左对齐项2 |
| 左对齐项3 | 左对齐项4 |

| 列1 | 列2 |
| :-----: | :-----: |
| 居中项1 | 居中项2 |
| 居中项3 | 居中项4 |

| 列1 | 列2 |
| --------: | --------: |
| 右对齐项1 | 右对齐项2 |
| 右对齐项3 | 右对齐项4 |
```
**显示效果**
>| 列1 | 列2 |
>| :-------- | :-------- |
>| 左对齐项1 | 左对齐项2 |
>| 左对齐项3 | 左对齐项4 |
>
>| 列1 | 列2 |
>| :-----: | :-----: |
>| 居中项1 | 居中项2 |
>| 居中项3 | 居中项4 |
>
>| 列1 | 列2 |
>| --------: | --------: |
>| 右对齐项1 | 右对齐项2 |
>| 右对齐项3 | 右对齐项4 |
