Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。  
用于编写说明文档，并且以“README.MD”的文件名保存在软件的目录下面。  
该文件用来测试和展示书写README的各种markdown语法。GitHub的markdown语法在标准的markdown语法基础上做了扩充，称之为GitHub Flavored Markdown。简称GFM，GFM在GitHub上有广泛应用，除了README文件外，issues和wiki均支持markdown语法。



README标题
=========================
<br/><br/><br/>

## 中级标题(二级标题)
中级标题(二级标题)
---
<br/><br/><br/>

## 目录
[横线](#横线)  
[标题](#标题)  
[文本](#文本)  
[图片](#图片)  
[链接](#链接)  
[锚点](#锚点)  
[列表](#列表)  
[块引用](#块引用)  
[代码高亮](#代码高亮)  
[表格](#表格)  
[表情](#表情)  
[diff](#diff)

横线
---
#### 语法：横线可以用*** ___ --- 表示
***
___
---

标题
---
# 一级标题  
## 二级标题
### 三级标题  
#### 四级标题  
##### 五级标题  
###### 六级标题 
***

文本
---
### 1.普通文本
一段普通文本dfawef

### 2.单行文本
#### 语法：行首加1个Tab或者4个空格
    单行文本发的违法二分法单行文本发的违法二分法

### 3.文本块
#### 语法1（在连续的文本开头加入tab或者四个空格键）
    发货回复埃尔文部分
    护肤维保费
    风还未发布
#### 语法2（s会用一对各三个的反引号```）
```
sssfaef回复按辈分
```

### 文字高亮（使用一对反引号``）
`高亮了`

### 换行`(回车不能直接换行)`
#### 语法1：在要换行的文本后加入两个空格
第一行  
第二行
#### 语法2：在两行文字的中间加入空行`（这种方式间隙比较大）`
第一行

第二行

## 斜体，粗体，删除线

|语法|效果|
|-----|------|
|`*斜体效果1*`|*斜体效果1*|
|`_斜体效果2_`|_斜体效果2_|
|`**粗体效果1**`|**粗体效果1**|
|`__粗体效果2__`|__粗体效果2__|
|`~~删除线~~`|~~删除线~~|
|`***斜粗体1***`|***斜粗体1***|
|`___斜粗体2___`|___斜粗体2___|
|`***~~斜粗体删除线1~~***`|***~~斜粗体删除线1~~***|
|`~~***斜粗体删除线1***~~`|~~***斜粗体删除线1***~~|
|`___~~斜粗体删除线2~~___`|___~~斜粗体删除线2~~___|
|`~~___斜粗体删除线2___~~`|~~___斜粗体删除线2___~~|

***

图片
---
#### 语法：`![alt](URL title)`  
![baidu](https://www.baidu.com/img/bdlogo.gif "百度logo")  
![baidu](https://www.baidu.com/img/bdlog.gif "百度logo") 

alt和title即对应HTML中的alt和title属性（都可省略）：
- alt表示图片显示失败时的替换文本
- title表示鼠标悬停在图片时的显示文本（注意这里要加引号）
***

链接
---
#### 语法：
|#|语法|效果|
|---|----|-----|
|1|`[积分商城](https://pointh5.vivo.com.cn "悬停显示")`|[积分商城](https://pointh5.vivo.com.cn "悬停显示")|
|2|`[积分商城][pointh5]`|[积分商城][pointh5] |

>使用URL标识符能达到复用的目的，一般把全文所有的URL标识符统一放在文章末尾，这样看起来比较干净。

### 图片的链接
`[![baidu]](https://www.baidu.com)`  
[![baidu]](https://www.baidu.com)
***

锚点
---
#### 语法：`[回到顶部](#readme标题)` 每一个标题都是一个锚点，和HTML的锚点（#）类似
[回到顶部](#readme标题)
***

列表
---
### 无序列表
#### 语法：- 或者 * 开头加空格
- 1111
- 2222
- 3333
* 1111
* 2222
* 3333

### 多级无序列表
#### 语法：每层开头加一个tab
* 1111
    * 2222
        * 3333
            * 4444

### 有序列表
#### 语法：在数字后面加一个点，再加一个空格
1. 123123  
3. 222222
4. wwfwfef

### 多级有序列表
1. 1111
    1. 1111
    3. 5555
2. 2222
    1. 8888
    2. 9999

### 复选框列表
#### 语法：- [x] 内容
- [x] 需求分析
- [x] 系统设计
- [x] 详细设计
- [ ] 编码
- [ ] 测试
- [ ] 交付
***

块引用
---
块引用多层j解构
> 数据结构
>> 树
>>> 二叉树
>>>> 平衡二叉树
>>>>> 满二叉树
***

代码高亮
---
#### 语法：在三个反引号后面加上编程语言的名字，另起一行开始写代码，最后一行再加上三个反引号
```javascript
var a = 5
console.log(a)
```
***

表格
---
#### 语法:
| 表头1  | 表头2| 表头3|
| --------- | -----------| -------|
| 表格单元   | 表格单元   | 表格单元 |
| 表格单元   | 表格单元   | 表格单元 |
#### 表格对齐语法：
| 左对齐         | 居中             | 右对齐 |
| :------------ |:---------------:| -----:|
| 1             |               1 | 1     |
| 22222         | center          |    fw |
| kobe          | haha            | right |
***

表情
---
Github的markdown语法支持emoji表情
#### 语法：两个冒号包围的字符表情集
:waxing_gibbous_moon:  
表情符号集：https://www.webpagefx.com/tools/emoji-cheat-sheet/
***

diff
---
#### 语法：展示一个文件内容的增加与删除;绿色表示新增，红色表示删除;以 `+ `开头表示新增，`- `开头表示删除
```diff
+ var a = 5
- var a = 3
```



------------------
[pointh5]:https://pointh5.vivo.com.cn "积分商城"
[baidu]:https://www.baidu.com/img/bdlogo.gif
