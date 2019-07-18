
markdown的使用
==============
分级别
-----------
（以上是标题符的使用）
# 标题级别
# 一级标题
## 二级
### 三级
#### 四级  
##### 五级
###### 六级
####### 无级别
or
# 标题级别 ###############
（行首的井字符数量决定标题的阶数）


## 无序列表
* 1
* 3
* 4
+ 5
- 7

（‘*’ = ‘+’ =‘-’）

## 有序列表
1. 1
2. 2
3. 3
5. 3

（与前面的数字无关 
建议第一个项目最好还是从 1. 开始，因为 Markdown 支持有序列表的 start 属性）


## 引用
>引用
>>>引用

（块引号可以包含其他Markdown元素，包括头、列表和代码块：）
(符号数量代表级别）



*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.



## 图片

![Mou icon](http://mouapp.com/Mou_128.PNG) 
//![名字]（远程地址）

## 链接
[link](https://note.youdao.com/)

//同上



## 粗体
**粗体**
 
 
## 斜体 
 *斜体*


## 表格
| tables | Are | cool|
| ------ |:------:|:-------:|
| 1 | 2 | 3 |
| 4 | 5 | 6 |


# 代码框（问题）
```
    printf（"Hello world"）`

` DASDASDAS
```


## 分割线
***
## 文本转换成html格式
*   Bird
*   Magic


or

*   Bird

*   Magic
*   （这两种最后转换成的html格式结果不一样）
*  
*  
*  
*  
*  ##  自动链接
*  <http://example.com/>
*  

\*literal asterisks\*

常规段落

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

另一个常规段落

&copy;//版权

    AT&T
 
    4 < 5  翻译成    4 &lt; 5
    
    
    
    
    1986\. What a great season.
    （避免有序列表）
    
~~删除线~~
    
***斜体加粗***


---

### Java
- 跨平台 
- 易用 
- 面向对象
1. Java是高斯林写的
2. Java非常好学
```
public static void main（String[] args）
{
    
}
```
-----



-----
### SVN ： 集中式文件管理工具
----
### 分布式管理工具  git    分布式版本控制系统
分成两部分：暂存区  
本地仓库（自己设置）  
先到暂存区  
再到本地库  
再到远程仓库  
再到GitHub  
（中国的git——码云）  
git内有大量源码  
公司：微软  


-----
### Linux内核   林纳斯
### JAVA    高斯林

----
pwd  查看目录  ls  列出所有文件

cd / 返回根目录



--------
### 配置git本地仓库
在对应文件夹右键   bash  
git init  //初始化  
git add README.md //添加文件  
git commit -m "first commit"//提到本地文件
git remote add origin https://github.com/971632046/JY8.git
git push -u origin master