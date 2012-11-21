NPWG_zh
=======

Network programming with Go 中文翻译版本

## 翻译组成员
人名不分先后，是按照QQ群里面的成员名字顺序排列的：

- 欧林猫
- Asta谢
- Lua
- 四月份平民
- 轩脉刃
- JessonChan
- KETQI
- RaiDen
- Wayne_Lau
- 打柴人
- 飛鱼
- 士豆口
- 吴文磊
- Border
- 微尘

## 翻译计划

<table border="1" width="100%">
    <tr>
        <td>章节</td>
        <td>第一翻译者</td>
        <td>First Review</td>
        <td>最终 Review</td>
        <td>负责人</td>
    </tr>
    <tr>
        <td>第一章：Architecture</td>
        <td>欧林猫</td>
        <td>Asta谢</td>
        <td>Lua</td>
        <td>四月份平民</td>
    </tr>
    <tr>
        <td>第二章：Overview of the Go language</td>
        <td>Asta谢<br>2012/12/27</td>
        <td>Lua</td>
        <td>四月份平民</td>
        <td>轩脉刃</td>
    </tr>
    <tr>
        <td>第三章：Socket-level Programming</td>
        <td>Lua</td>
        <td>四月份平民</td>
        <td>轩脉刃</td>
        <td>JessonChan</td>
    </tr>
    <tr>
        <td>第四章：Data serialisation</td>
        <td>四月份平民</td>
        <td>轩脉刃</td>
        <td>JessonChan</td>
        <td>KETQI</td>
    </tr>
    <tr>
        <td>第五章：Application-Level Protocols</td>
        <td>轩脉刃</td>
        <td>JessonChan</td>
        <td>KETQI</td>
        <td>RaiDen</td>
    </tr>
    <tr>
        <td>第六章：Managing character sets and encodings</td>
        <td>JessonChan</td>
        <td>KETQI</td>
        <td>RaiDen</td>
        <td>Wayne_Lau</td>
    </tr>
    <tr>
        <td>第七章：Security</td>
        <td>KETQI</td>
        <td>RaiDen</td>
        <td>Wayne_Lau</td>
        <td>打柴人</td>
    </tr>
    <tr>
        <td>第八章：HTTP</td>
        <td>RaiDen</td>
        <td>Wayne_Lau</td>
        <td>打柴人</td>
        <td>飛鱼</td>
    </tr>
     <tr>
        <td>第九章：Templates</td>
        <td>Wayne_Lau</td>
        <td>打柴人</td>
        <td>飛鱼</td>
        <td>士豆口</td>
    </tr>
    <tr>
        <td>第十章：A Complete Web Server</td>
        <td>打柴人</td>
        <td>飛鱼</td>
        <td>士豆口</td>
        <td>吴文磊</td>
    </tr>
    <tr>
        <td>第十一章：HTML</td>
        <td>飛鱼</td>
        <td>士豆口</td>
        <td>吴文磊</td>
        <td>Border</td>
    </tr>
    <tr>
        <td>第十二章：XML</td>
        <td>士豆口</td>
        <td>吴文磊</td>
        <td>Border</td>
        <td>微尘</td>
    </tr>
     <tr>
        <td>第十三章：Remote Procedure Call</td>
        <td>吴文磊</td>
        <td>Border</td>
        <td>微尘</td>
        <td>欧林猫</td>
    </tr>
    <tr>
        <td>第十四章：Network channels</td>
        <td>Border</td>
        <td>微尘</td>
        <td>欧林猫</td>
        <td>Asta谢</td>
    </tr>
    <tr>
        <td>第十五章：Web Sockets</td>
        <td>微尘</td>
        <td>欧林猫</td>
        <td>Asta谢</td>
        <td>四月份平民</td>
    </tr>
</table>

## 翻译格式

第一翻译、first review和最终Review的人需要保留英文

- 英文里面`<p></p>`为一个段落，那么把这一段修改成`<p class="en"></p>`，那么相应的中文也是一个段落`<p class="zh"></p>`

		<p>Please go to the <a href="..">main index</a> for the content pages for network computing.</p>
	
	那么加上中文之后应该如下：
	
		<p class="en">Please go to the <a href="..">main index</a> for the content pages for network computing.</p>
		<p class="zh">请访问<a href="..">主页</a>获取网络编程的其他页面</p>

- 英文里面`<h2></h2>`为一个层，首先需要给这个层加上`class="en"`,然后那么相应的中文为`<h2 class="zh"><h2>`

		<h2 id="heading_id_3">Introduction</h2>
		
	那么加上中文应该如下：
	
		<h2 id="heading_id_3" class="en">Introduction</h2>
		<h2 id="heading_id_3" class="zh">介绍</h2>	
- 英文里面`<ul></ul>`为一个列表，首先对原来的ul增加一个`class="en"`,然后相应的中文为`<ul class="zh"></ul>`

		<ul>
		<li><a href="http://golang.org/doc/install.html">Getting started</a></li>

		<li><a href="http://golang.org/doc/go_tutorial.html">A Tutorial for the Go Programming Language</a></li>

		<li><a href="http://golang.org/doc/effective_go.html">Effective Go</a></li>
		</ul>
		
	那么加上中文之后应该如下：
	
		<ul class="en">
		<li><a href="http://golang.org/doc/install.html">Getting started</a></li>

		<li><a href="http://golang.org/doc/go_tutorial.html">A Tutorial for the Go Programming Language</a></li>

		<li><a href="http://golang.org/doc/effective_go.html">Effective Go</a></li>
		</ul>
		<ul class="zh">
		<li><a href="http://golang.org/doc/install.html">安装入门</a></li>

		<li><a href="http://golang.org/doc/go_tutorial.html">Go程序设计入门</a></li>

		<li><a href="http://golang.org/doc/effective_go.html">Go高级编程</a></li>
		</ul>		

## 翻译约定

有些专用词无需翻译

- channel
- goroutine

	

