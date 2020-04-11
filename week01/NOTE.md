# 前端工程师的自我修炼之道      
时间：2020.4.7     

## 课程主题
1. 如何规划自己的前端职业生涯，站在更高起点？
2. 掌握正确的学习方法，破局成为前端专家
3. 企业眼中优秀的前端人是什么样的？
4. 在训练营中，我会如何带你进阶资深前端工程师？

## 思考问题
1. 关于前端，你都会什么？      
2. 关于前端，你都不会什么？

## 前端技能模型搭建   
![前端技能模型](./images/model.png)       

* 编程能力：通俗的描述就是提出一个问题能否解决出来。编程能力解决的是：难，写不出来的问题。
即可以认为数据结构、算法题等，将一个复杂的逻辑问题拆分出来加以实现的能力，即可为编程能力。（岗位的基础）       
* 架构能力：架构能力是解决：大，写不出来的问题。架构能力包括了对复杂系统的分析，对复杂
系统所需要的程序进行软件设计，对代码的规范，多个程序员协同开发的管理等的架构。     
* 工程能力：工程能力解决的就是人多怎么协同的问题。     
* 前端知识： HTML/CSS/JavaScript/Node.js/浏览器相关API等。需要通过建立知识体系
来管理前端知识。              
* 领域知识：跟从事的领域有关系，需要所处行业和职业规划在实践中学习，例如新零售需要
做埋点分析等。     

其中，编程能力可以通过刻意练习的方式提升，例如刷题；而架构能力可通过读源代码，参与
开源项目的方式，例如可以通过带着目的，解决开源项目issue的问题的方式，不太建议通读
源代码。        

## 学习方法     

### 整理法
通过关系进行将知识串联。可以通过相关的知识点迅速定位对应的知识点。     
* 顺序关系      
* 组合关系      
* 维度关系      
* 分类关系              
整理知识体系还需要完备性，确保每个环节的完整。     
![整理法](./images/sort.png)  

### 追朔法
![追朔法](./images/history.png)

## 权威参考     

* [https://www.w3.org/](https://www.w3.org/)        
* [http://w3school.com/](http://w3school.com/)      
* [https://whatwg.org/](https://whatwg.org/)      
* [https://scholar.google.com/](https://scholar.google.com/)      
* [https://developer.mozilla.org/](https://developer.mozilla.org/)      
* [https://docs.microsoft.com/](https://docs.microsoft.com/)      
* [https://developer.apple.com/](https://developer.apple.com/)      

# 前端技术体系
时间：2020.4.9     

前端技术体系划分：       
* HTML      
* JavaScript        
* CSS       
* API       
单独划分一个API是基于前端生态进行的划分，例如主流的是面向**浏览器**的API；还有基于**Node**的后台服务或者中间层实现；
另外有基于桌面应用开发的**Electron**和微信/支付宝/快应用等一些列的**小程序端**开发等。     

## HTML
基于**维度关系**对HTML进行分析，把HTML作为一种开发语言，继承了通用的计算机语言、SGML和XML。    
1. 通用的计算机语言
    * 语法        
    * 词法        
2. SGML     
标准通用标记语言(Standard Generalized Markup Language),它是国际上定义电子文件结构和内容描述的标准，
（SGML是一种在Web发明之前就早已存在的用标记来描述文档资料的通用语言）。         
它的组成包括语法定义，DTD，实例三部分。
    * DTD（Document Type Definition,即文档类型定义）            
    其中，HTML5的DTD即为：<! doctype html>     
    * Entity（实体）        
    例如，< 实体为&lt;解释为标签的开头；> 实体为&gt；解释为标签的结尾等 ，参考：[https://github.com/PCAaron/Frontend-01-Template/issues/2](https://github.com/PCAaron/Frontend-01-Template/issues/2)                 
3. XML      
Extentsible Markup Language(可扩展标记语言)，)用于标记电子文件使其具有结构性的标记语言，
可以用来标记数据、定义数据类型，是一种允许用户对自己的标记语言进行定义的源语言。             
    * Namespace   
    xmlns 属性可以在文档中定义一个或多个可供选择的命名空间。该属性可以放置在文档内任何元素的开始标签中。该属性的值类似于 URL，它定义了一个命名空间，
    浏览器会将此命名空间用于该属性所在元素内的所有内容。          
    可以认为和DTD一样，只是从不同的角度定义标签属性。      
    例如：<html  xmlns="http://www.w3.org/1999/xhtml" >        
    * Tag    
    
## JavaScript
通用基于**维度关系**对JavaScript分析，可以从文法/语法、语义和运行时来划分。     
1. 文法/语法   
    * 词法        
    空格符、换行符、注释、标识       
    * 语法(语法结构)             
    Atom(对应于词法的标识Token)、表达式、语句、函数、类等        
2. 语义       
3. 运行时      


## CSS  


## API

![前端体系](./images/series.png)

## 补充知识点及参考        

* SGML引申说明：             
GML 是第一代置标语言，使文档能明确将标示和内容分开，所以文件使用同样的标示方法。SGML 在 GML 的基础上进行整理，
形成了一套非常严谨的文件描述方法。    

* HTML元素(Tag)：[https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element)        

        


       


