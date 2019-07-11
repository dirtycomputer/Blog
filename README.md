<h1 id="toc_0">Markdown是什么</h1>
<p>（PS：学会了Typora请自动略过本教程）555～我也是全学会了语法以后才知道有这种作弊app</p>

<p>markdown是一种<strong>标记性语言</strong>，以纯文本编写而最终以<strong>HTML</strong>格式发布。即以MRKDOWN语法编写的语言向HTML的转化。（但是由此我就不禁想到了，应该也会有word转markdown的工具吧，手动滑稽~_~）</p>

<hr>

<h1 id="toc_1">创造者</h1>

<p>1.Aaron Swartz
2.John Gruber</p>

<hr>

<h1 id="toc_2">为什么使用</h1>

<p>跨平台<br>
易读易写</p>

<hr>

<h1 id="toc_3">主要语法</h1>

<ul>
<li>标题</li>
<li>段落 </li>
<li>区块 </li>
<li>代码区 </li>
<li>强调 </li>
<li>列表 </li>
<li>分割线 </li>
<li>链接 </li>
<li>图片 </li>
<li>反斜杠 </li>
<li>符号</li>
</ul>

<hr>

<h3 id="toc_4">标题</h3>

<div><pre><code class="language-none">#一级标题
##二级标题
###三级标题
####四级标题
#####五级标题
######六级标题</code></pre></div>

<h5 id="toc_5">效果</h5>

<h1 id="toc_6">一级标题</h1>

<h2 id="toc_7">二级标题</h2>

<h3 id="toc_8">三级标题</h3>

<h4 id="toc_9">四级标题</h4>

<h5 id="toc_10">五级标题</h5>

<h6 id="toc_11">六级标题</h6>

<h3 id="toc_12">段落</h3>

<p>前后要有空行，强制换行使用两个以上空格加回车。</p>

<hr>

<h3 id="toc_13">区块</h3>

<p>在段落的每行或者第一行使用符号&gt;，还可以嵌套使用。   </p>

<h5 id="toc_14">文本范例</h5>

<div><pre><code class="language-none">&gt;区块引用
&gt;&gt;嵌套引用</code></pre></div>

<h5 id="toc_15">效果</h5>

<blockquote>
<p>区块引用</p>

<blockquote>
<p>嵌套引用</p>
</blockquote>
</blockquote>

<hr>

<h3 id="toc_16">代码区</h3>

<p>代码区要与普通段落之间有空行，代码区的建立是在每行加上4个空格或者一个制表符。</p>

<h5 id="toc_17">普通段落</h5>

<p>void main()
{
    printf(&quot;Hello,Markdown.&quot;);
}</p>

<h5 id="toc_18">代码效果</h5>

<div><pre><code class="language-none">    void main()
{
    printf(&quot;Hello,Markdown.&quot;);
}</code></pre></div>

<hr>

<h3 id="toc_19">强调</h3>

<p>在强调内容两侧分别加上<code>*</code>或<code>_</code></p>

<h5 id="toc_20">文本范例</h5>

<div><pre><code class="language-none">*斜体*    or  _斜体_
**粗体**  or  __粗体__</code></pre></div>

<h5 id="toc_21">效果</h5>

<p><em>斜体</em> <em>斜体</em><br>
<strong>粗体</strong> <strong>粗体</strong></p>

<hr>

<h3 id="toc_22">列表</h3>

<p>使用<code>·</code>、<code>+</code>（常用）、或<code>-</code>标记<strong>无序列表</strong>。与其他段落有空行，与<code>+</code>之间有空格。</p>

<div><pre><code class="language-none">+ 第一项
+ 第二项
+ 第三项</code></pre></div>

<h5 id="toc_23"><code>+</code>效果:</h5>

<ul>
<li>第一项</li>
<li>第二项</li>
<li>第三项</li>
</ul>

<p>也可以制<strong>有序表</strong>（第一个打出<code>1.something</code>然后后面的数字会自动填充的）：</p>

<div><pre><code class="language-none">1. 第一项
2. 第二项
3. 第三项</code></pre></div>

<h5 id="toc_24">效果：</h5>

<ol>
<li>第一项</li>
<li>第二项</li>
<li>第三项</li>
</ol>

<hr>

<h3 id="toc_25">分割线</h3>

<p>最常使用就是三个或以上<code>*</code>，还可以使用-和_。</p>

<div><pre><code class="language-none">***
---
___</code></pre></div>

<h5 id="toc_26">效果：</h5>

<hr>

<hr>

<h3 id="toc_27">链接</h3>

<p>链接可以由两种形式生成：行内式和参考式。</p>

<h5 id="toc_28">行内式：</h5>

<div><pre><code class="language-none">[本人的github主页](https://github.com/dirtycomputer)</code></pre></div>

<h5 id="toc_29">行内式的效果：</h5>

<p><a href="https://github.com/dirtycomputer">本人的github主页</a></p>

<h5 id="toc_30">参考式：</h5>

<div><pre><code class="language-none">[本人的github主页][1]  
[本人github的一个项目][2]
[1]:https://github.com/dirtycomputer
[2]:https://github.com/dirtycomputer/Learning-materials</code></pre></div>

<h5 id="toc_31">参考式的效果：</h5>

<p><a href="https://github.com/dirtycomputer">本人的github主页</a><br>
<a href="https://github.com/dirtycomputer/Learning-materials">本人github的一个项目</a></p>

<hr>

<h3 id="toc_32">图片</h3>

<p>跟插入链接没什么区别，只是多加了一个<code>!</code></p>

<div><pre><code class="language-none">![当图片找不到时的替代文字](图片链接 &quot;鼠标悬置于图片上会出现的标题文字，可以不写&quot;)</code></pre></div>

<p>温馨提示：<strong>图床</strong>是个好东西！</p>

<h5 id="toc_33">效果：</h5>

<p><img src="https://avatars1.githubusercontent.com/u/48406770?s=400&amp;u=4e2b3298d6f65f8bd228845d812b092890b62cc3&amp;v=4" alt="404图片找不到了"></p>

<hr>

<h3 id="toc_34">反斜杠</h3>

<p>类似于C语言中实现反转义，使符号成为普通符号。</p>

<div><pre><code class="language-none">\#哈哈</code></pre></div>

<h5 id="toc_35">效果：</h5>

<p>#哈哈</p>

<hr>

<h3 id="toc_36">符号&#39;`&#39;</h3>

<p>起标记作用</p>

<div><pre><code class="language-none">`Command+V`</code></pre></div>

<h5 id="toc_37">效果：</h5>

<p><code>Command+V</code></p>

<hr>

<h1 id="toc_38">都有谁在使用Markdown</h1>

<ul>
<li>Github</li>
<li>简书</li>
<li>Stack Overflow</li>
<li>Apollo</li>
<li>Moodle</li>
<li>Reddit</li>
<li>Wordpress</li>
</ul>

<hr>

<h1 id="toc_39">关于Markdown的快捷键</h1>

<p>博主也是写完这篇问了下度娘，结果还有快捷键！？！？  </p>

<p><img src="https://t1.picb.cc/uploads/2019/05/28/giIvk8.png" alt="404 not found"></p>

<hr>
