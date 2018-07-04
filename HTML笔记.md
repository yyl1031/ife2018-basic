1.  HTML是什么？HTML5是什么？
    HTML，全文“HyperText Markup Language”,中译“超文本标记语言”，标准通用标记语言下的一个应用。
      
    HTML5，html的第五次重大修改。

    HTML元素标签、属性都是什么概念？
    HTML标签标记了HTML文档和HTML元素。
    HTML标签由开始标签和结束标签组成：<h1> study notes</h1>  
                                开始标签         结束标签
                                元素名           /元素名
2.  HTML的元素是指从开始标签到结束标签的所有代码。
    例如:<p>段落</p>
    表示一个html元素。
    一个html元素主要包括html标签和纯文本，标签定义了网页显示的格式，文本表示网页的内容。
    网页 =  html文档
    html文档则是由html元素定义的。

    HTML属性为HTML元素提供附件信息。
    例如：<h1 class="stn" id="stn" style="color:red">study notes</h1>
    属性总是以名称/值的形式出现,例如:name = “value”
    属性总是在开始标签中定义。

3.  文档类型是什么概念，起什么作用？
    doctype(文档类型)是document type（文档定义）的简写，用来说明web设计中所用的html或xhtml的类型，指出浏览器或者其他阅读程序按照什么样的规则集去解释文档中的标记。
    doctype的作用：
    1. 浏览器要使老旧的网页正常工作，但这部分网页没有doctype声明，所以浏览器对老旧的没有doctype声明的网页采用queirks mode解析。
    2. 对于浏览器不能识别doctye声明，采用strict mode解析。
    3. 在doctype声明中，没有使用DTD声明或者使用HTML4以下的DTD声明时，基本所有的浏览器都是使用quirks mode呈现，其他的则使用strict mode解析。
    4. 在现有有doctype声明的网页，绝大多数是采用strict mode进行解析渲染的。
    5. doctype声明，让浏览器使用标准模式。

4.  meta标签都用来做什么的？
    w3cschool:metadate(元数据)是关于数据的信息。
             标签提供关于HTML文档的元数据。元数据不会显示在页面上，但是对于机器是可读的。
             典型的事件是，meta元素被用于规定页面的描述、关键词、文档的作者、最后修改时间以及其他元数据。
             meta标签之中位于head元素中。
             元数据可以用与浏览器（如何显示内容或重新加载页面）、搜素引擎（关键词）、或其他web服务。
    meta的作用
    meta里的数据时供机器解读的，告诉机器该如何解析这个页面，还有一个用途是可以添加服务器发送到浏览器的http头部内容。
    例如：
    <meta http-equiv="charset" content="iso-8859-1">
    那么浏览器头部就会包括这些：
    charset:iso-8859-1 (显示字符集的设定)

5.  web语义化是什么，是为了解决什么问题？
    学术界将web语义化成为web3.0的核心，目标是将当前的网页提升为计算机能够“理解”和处理的网页。核心思想史标注网页对象使其对应本体中的实体，并通过逻辑等手段进行自动推理。作用在于更好的整合网络上的资源，使计算机能够处理分布于不同位置的信息，自动产生问题的解决方案。
    web语义化的目的是提高计算机和人对web代码的可读性。
    例如：
    <footer></footer>代替了<div id="footer" class="footer"></div>

6.  链接是什么概念，对应什么标签？
    链接(link)也称超级链接，超链接是指从一个网页指向一个目标的连接关系,而在一个网页中用来超链接的对象,可以是一段文本或者是一个图片.当浏览者单击已经链接的文字或图片后,链接目标将显示在浏览器上,并且根据目标的类型来打开或运行。
    例如：
        超链接  锚标签 <a href="www.baidu.com" target=_blank>百度</a> 
                    href=链接 url=www.baidu.com target=_blank=转到空白页
                    <a href="mailto:name@email.com">email<a>
        绝对路径 c:\baidu\index.html
        相对路径 c:\baidu\index.html(源端点)
                c:\baidu\tieba.baidu.com(目标端点)

7.  常用标签都有哪些，对应着什么功能，都有哪些属性？
    <!--...-->	定义注释	
    <!DOCTYPE> 	定义文档类型
    <a>	        定义超链接
    <abbr>	    定义缩写
    <acronym>	不支持。定义首字母缩写
    <address>	定义地址元素
    <applet>	不支持。定义 applet
    <area>	    定义图像映射中的区域
    <article>	定义 article
    <aside>	    定义页面内容之外的内容
    <audio>	    定义声音内容
    <b>	        定义粗体文本
    <base>	    定义页面中所有链接的基准 URL
    <basefont>	不支持。请使用 CSS 代替
    <bdo>	    定义文本显示的方向
    <big>	    不支持。定义大号文本
    <blockquote>	定义长的引用
    <body>  	定义 body 元素
    <br>	    插入换行符
    <button>	定义按钮
    <canvas>	定义图形
    <caption>	定义表格标题
    <center>	不支持。定义居中的文本
    <cite>	    定义引用
    <code>	    定义计算机代码文本
    <col>	    定义表格列的属性
    <colgroup>	定义表格列的分组
    <command>	定义命令按钮
    <datagrid>	定义树列表 (tree-list) 中的数据
    <datalist>	定义下拉列表
    <datatemplate>	定义数据模板
    <dd>	    定义定义的描述
    <del>	    定义删除文本
    <details>	定义元素的细节
    <dialog>	定义对话（会话）
    <dir>	    不支持。定义目录列表
    <div>   	定义文档中的一个部分
    <dfn>	    定义定义项目
    <dl>	    定义定义列表
    <dt>	    定义定义的项目
    <em>	    定义强调文本
    <embed>	    定义外部交互内容或插件
    <event-source>	为服务器发送的事件定义目标
    <fieldset>	定义 fieldset
    <figure>	定义媒介内容的分组，以及它们的标题
    <font>	    不赞成。定义文本的字体、尺寸和颜色
    <footer>	定义 section 或 page 的页脚
    <form>	    定义表单
    <frame>	    不支持。定义子窗口（框架）
    <frameset>	不支持。定义框架的集
    <h1> to <h6>定义标题 1 到标题 6
    <head>  	定义关于文档的信息
    <header>	定义 section 或 page 的页眉
    <hr>	    定义水平
    <html>	    定义 html 文档
    <i>	        定义斜体文本
    <iframe>	定义行内的子窗口（框架）
    <img>	    定义图像
    <input>	    定义输入域
    <ins>	    定义插入文本
    <isindex>	不支持。定义单行的输入域
    <kbd>	    定义键盘文本
    <label>	    定义表单控件的标注
    <legend>	定义 fieldset 中的标题
    <li>	    定义列表的项目
    <link>	    定义资源引用
    <m>	        定义有记号的文本
    <map>	    定义图像映射
    <menu>	    定义菜单列表
    <meta>  	定义元信息
    <meter> 	定义预定义范围内的度量
    <nav>	    定义导航链接
    <nest>	    定义数据模板中的嵌套点
    <noframes>	不支持。定义 noframe 部分
    <noscript>	不支持。定义 noscript 部分
    <object>	定义嵌入对象
    <ol>	    定义有序列表
    <optgroup>	定义选项组
    <option>	定义下拉列表中的选项
    <output>	定义输出的一些类型
    <p> 	    定义段落
    <param>	    为对象定义参数
    <pre>	    定义预格式化文本
    <progress>	定义任何类型的任务的进度
    <q>	        定义短的引用
    <rule>	    为升级模板定义规则
    <s>	        不支持。定义加删除线的文本
    <samp>	    定义样本计算机代码
    <script>    定义脚本
    <section>	定义 section
    <select>	定义可选列表
    <small>	    不支持。定义小号文本
    <source>	定义媒介源
    <span>	    定义文档中的 section
    <strike>	不支持。定义加删除线的文本
    <strong>	定义强调文本
    <style>	    定义样式定义
    <sub>	    定义上标文本
    <sup>	    定义下标文本
    <table>	    定义表格
    <tbody>	    定义表格的主体
    <td>	    定义表格单元
    <textarea>	定义 textarea
    <tfoot> 	定义表格的脚注
    <th>	    定义表头
    <thead>	    定义表头
    <time>	    定义日期/时间
    <title>	    定义文档的标题
    <tr>	    定义表格行
    <tt>	    不支持。定义打字机文本
    <u>	        不支持。定义下划线文本
    <ul>	    定义无序列表
    <var>	    定义变量
    <video>	    定义视频
    <xmp>	    不支持。定义预格式文本

8.  表单的标签都有哪些，对应着什么功能，都有哪些属性？
    <form> 标签用于为用户输入创建 HTML 表单。
    表单能够包含 input 元素，比如文本字段、复选框、单选框、提交按钮等等。
    表单还可以包含 menus、textarea、fieldset、legend 和 label 元素。

9.  ol,ul,li,dl,dd,dt等这些标签都适合在什么地方，举个例子？
    无序列表
    <ul>
        <li></li>
        <li></li>
    </ul>
    此列项目使用粗体圆点进行标记。
    
    有序列表
    <ol>
        <li></li>
        <li></li>
    </ol>    
    此列项目使用数字进行标记

    定义列表
    <dl>
        <dt></dt>
        <dd></dd>
        <dt></dt>
        <dd></dd>
    </dl>
    此列列表是项目及其注释的组合dt为自定义列表项，dd为自定义列表项的定义