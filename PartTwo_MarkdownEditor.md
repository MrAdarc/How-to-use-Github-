# Part Two：Some Markdown Editor Way
&#8195;&#8195;为了更为形象的展示信息，在对文件内容进行编辑的时候可能会进行文档的版式编辑，甚至插入图片、公式、图表。这里对这部分操作内容进行记述，进行备忘。

整体内容包含以下几个部分：

</br><a href="#titleAnchor-wzbjyf">
1.基本的文字编辑语法</a>
</br><a href="#titleAnchor-btylb">
&#8195;&#8195;（1）标题与列表</a>
</br><a href="#titleAnchor-ztsz">
&#8195;&#8195;（2）字体设置</a>
</br><a href="#titleAnchor-gstbtpljcr">
2.数学公式、图表、图片、链接的插入</a>
</br><a href="#titleAnchor-gs">
&#8195;&#8195;（1）数学公式及其相关语法</a>
</br><a href="#titleAnchor-tb">
&#8195;&#8195;（2）图表及其相关语法</a>
</br><a href="#titleAnchor-tp">
&#8195;&#8195;（3）图片及其相关控制</a>
</br><a href="#titleAnchor-lj">
&#8195;&#8195;（4）链接插入</a>
</br><a href="#titleAnchor-qtxx">
3.其他选项插入</a>

<h2 id="titleAnchor-wzbjyf">
1.文字编辑语法</h2>

<h2 id="titleAnchor-gstbtpljcr">
2.数学公式、图表、图片、链接的插入</h2>

<h3 id="titleAnchor-gs">
（1）数学公式及其相关语法</h3>

&#8195;&#8195;在markdown文档中，由于支持HTML编程，因此对公式的插入也支持HTML形式，然而由于不支持Latex的公式输入，这里以产生图片链接的形式产生公式，如下：

**格式**</br>
```
<div align=center><img src="https://latex.codecogs.com/gif.latex?[公式]" /></a></div>
```

**说明**</br>
&#8195;&#8195;“[公式]”部分为填写公式的主要内容，支持Latex语法方式的输入；

**例子**</br>
```
<img src="https://latex.codecogs.com/gif.latex?f(\xi)=\frac{f(b)-f(a)}{b-a}" /></a>
```

**样式**</br>

<img src="https://latex.codecogs.com/gif.latex?f(\xi)=\frac{f(b)-f(a)}{b-a}" />

<h3 id="titleAnchor-gs">
（2）图标及其相关语法</h3>

<h3 id="titleAnchor-gs">
（3）图片及其相关控制</h3>

**格式**</br>

```
<img src="[图片地址]" >
```

**说明**</br>
&#8195;&#8195;1.在“[图片地址]”处添加图片地址；
&#8195;&#8195;2.控制大小则添加相关参数进行；
```
width="[横向比例]" height="[纵向比例]"
```

**实例**</br>
```
<img src="./PartTwo_Picture/20161028230559575.png" width="10%" height="8%">
```

**样式**</br>
<center>
<img src="./PartTwo_Picture/20161028230559575.png">
<img src="./PartTwo_Picture/20161028230559575.png" width="10%" height="8%">
</center>
