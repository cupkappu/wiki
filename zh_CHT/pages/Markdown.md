# Markdown

Markdown是一種標記語言，創始人為John Gruber。其本意是創造一種易於閲讀的，可以被轉換爲HTML的標記語言。本文亦使用Markdown語言編寫。

## 歷史

Markdown在創建初期純粹是爲了實現一種易於直接使用文本格式閲讀，且可以轉換爲HTML的標記語言。2004年，John Gruber發佈了Markdown。

現在，Markdown出現了許多的分支，意為Markdown添加更多的額外功能（例如表格、數學公式、脚注、定義列表）。不過，這導致了Markdown生態圈的混亂。

一般情況，GFM（Github于2017年發佈的Markdown規範）為現今Markdown的通用規範。

## 語法

### 段落
段落以空白行分隔。

### 標題

使用`#`標記標題，# xxx為一級，## xxx為二級，最高可到六級
```Markdown
# 一級標題
## 二級標題
### 三級標題
#### 四級標題
##### 五級標題
###### 六級標題
```
**顯示效果**

># 一級標題
>## 二級標題
>### 三級標題
>#### 四級標題
>##### 五級標題
>###### 六級標題

### 文本標記

使用`*`號標記文本為斜體，粗體或斜粗體。

```Markdown
*斜體*，**粗體**，***斜粗體***
```

**顯示效果**

>*斜體*，**粗體**，***斜粗體***

### 水平綫
水平綫使用`-`號標記

```Markdown
------
```

**顯示效果**

> ------

### 列表
使用`+`或`*`號作爲開頭作爲列表，可多級。
```Markdown
+ 一級列表1
  + 二級列表1
    * 三級列表1
  + 二級列表2
* 一級列表2
```

**顯示效果**

> + 一級列表1
>   + 二級列表1
>     * 三級列表1
>   + 二級列表2
> * 一級列表2

### 編號列表
使用`1. ；2. ；3. `等進行編號。
```Markdown
1. 一
2. 二
3. 三
```
**顯示效果**
>1. 一
>2. 二
>3. 三

### 鏈接
使用`[Linkname](url://)`創建鏈接
```Markdown
點擊[這裏](../Markdown.md)

點擊[這裏][here]去google

[here]:google
```
**顯示效果**
>點擊[這裏](../Markdown.md)
>
>點擊[這裏][here]去google
>
>[here]:google

### 圖片
使用`![Image name](url://.png)`創建圖片
```Markdown
![Link](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)

![Base64](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEYAAAAUCAAAAAAVAxSkAAABrUlEQVQ4y+3TPUvDQBgH8OdDOGa+oUMgk2MpdHIIgpSUiqC0OKirgxYX8QVFRQRpBRF8KShqLbgIYkUEteCgFVuqUEVxEIkvJFhae3m8S2KbSkcFBw9yHP88+eXucgH8kQZ/jSm4VDaIy9RKCpKac9NKgU4uEJNwhHhK3qvPBVO8rxRWmFXPF+NSM1KVMbwriAMwhDgVcrxeMZm85GR0PhvGJAAmyozJsbsxgNEir4iEjIK0SYqGd8sOR3rJAGN2BCEkOxhxMhpd8Mk0CXtZacxi1hr20mI/rzgnxayoidevcGuHXTC/q6QuYSMt1jC+gBIiMg12v2vb5NlklChiWnhmFZpwvxDGzuUzV8kOg+N8UUvNBp64vy9q3UN7gDXhwWLY2nMC3zRDibfsY7wjEkY79CdMZhrxSqqzxf4ZRPXwzWJirMicDa5KwiPeARygHXKNMQHEy3rMopDR20XNZGbJzUtrwDC/KshlLDWyqdmhxZzCsdYmf2fWZPoxCEDyfIvdtNQH0PRkH6Q51g8rFO3Qzxh2LbItcDCOpmuOsV7ntNaERe3v/lP/zO8yn4N+yNPrekmPAAAAAElFTkSuQmCC)

![Link][linking]

[linking]:https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png
```
**顯示效果**
>![Link](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)
>
>![Base64](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEYAAAAUCAAAAAAVAxSkAAABrUlEQVQ4y+3TPUvDQBgH8OdDOGa+oUMgk2MpdHIIgpSUiqC0OKirgxYX8QVFRQRpBRF8KShqLbgIYkUEteCgFVuqUEVxEIkvJFhae3m8S2KbSkcFBw9yHP88+eXucgH8kQZ/jSm4VDaIy9RKCpKac9NKgU4uEJNwhHhK3qvPBVO8rxRWmFXPF+NSM1KVMbwriAMwhDgVcrxeMZm85GR0PhvGJAAmyozJsbsxgNEir4iEjIK0SYqGd8sOR3rJAGN2BCEkOxhxMhpd8Mk0CXtZacxi1hr20mI/rzgnxayoidevcGuHXTC/q6QuYSMt1jC+gBIiMg12v2vb5NlklChiWnhmFZpwvxDGzuUzV8kOg+N8UUvNBp64vy9q3UN7gDXhwWLY2nMC3zRDibfsY7wjEkY79CdMZhrxSqqzxf4ZRPXwzWJirMicDa5KwiPeARygHXKNMQHEy3rMopDR20XNZGbJzUtrwDC/KshlLDWyqdmhxZzCsdYmf2fWZPoxCEDyfIvdtNQH0PRkH6Q51g8rFO3Qzxh2LbItcDCOpmuOsV7ntNaERe3v/lP/zO8yn4N+yNPrekmPAAAAAElFTkSuQmCC)
>
>![Link][linking]
>
>[linking]:https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png

### 引用
使用`>`符號置前進行引用
```Markdown
> 被引用
```
**顯示效果**
> > 被引用

*由於顯示效果以引用顯示，這裏的效果可能不清晰*

### 插入HTML
可以直接在Markdown裏面插入HTML
```Markdown
**Youtube影片**
<iframe width="300" height="300" src="https://www.youtube.com/embed/5v9UyBc03og" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```
**顯示效果**
>**Youtube影片**
><iframe width="300" height="300" src="https://www.youtube.com/embed/5v9UyBc03og" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### 表格
在GFM裏，支援了表格的使用。
```Markdown
| 列1       | 列2       |
| :-------- | :-------- |
| 左對齊項1 | 左對齊項2 |
| 左對齊項3 | 左對齊項4 |

| 列1     | 列2     |
| :-----: | :-----: |
| 居中項1 | 居中項2 |
| 居中項3 | 居中項4 |

| 列1       | 列2       |
| --------: | --------: |
| 右對齊項1 | 右對齊項2 |
| 右對齊項3 | 右對齊項4 |
```
**顯示效果**
>| 列1       | 列2       |
>| :-------- | :-------- |
>| 左對齊項1 | 左對齊項2 |
>| 左對齊項3 | 左對齊項4 |
>
>| 列1     | 列2     |
>| :-----: | :-----: |
>| 居中項1 | 居中項2 |
>| 居中項3 | 居中項4 |
>
>| 列1       | 列2       |
>| --------: | --------: |
>| 右對齊項1 | 右對齊項2 |
>| 右對齊項3 | 右對齊項4 |
