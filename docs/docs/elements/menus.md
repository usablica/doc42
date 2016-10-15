---
layout: doc
title: Menus
categories: elements
permalink: /docs/elements/menus/
---

<p>Menu is one of useful Kissui features and it supports different types of menus. Those are useful to create awesome navigations, headers and footers.

The basic sample of menus is a like:

</p>

<nav class="menu">
    <a class="item" href="/">Home</a>
    <a class="item" href="/">Documents</a>
    <a class="item" href="/">Contact</a>
    <a class="item" href="/">About</a>
</nav>


<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;menu&quot;&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Home&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Documents&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Contact&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;About&lt;/a&gt;
&lt;/nav&gt;
</code>
</pre>

<p></p>

<h4>Basic</h4>

<nav class="basic menu">
    <a class="item" href="/">Home</a>
    <a class="item" href="/">Documents</a>
    <a class="item" href="/">Contact</a>
    <a class="item" href="/">About</a>
</nav>


<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;basic menu&quot;&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Home&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Documents&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Contact&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;About&lt;/a&gt;
&lt;/nav&gt;
</code>
</pre>

<p></p>

<h4>Header Item</h4>

<nav class="basic menu">
    <a class="header item" href="/">
    Your Product
    </a>
    <a class="item" href="/">Home</a>
    <a class="item" href="/">Documents</a>
    <a class="item" href="/">Contact</a>
    <a class="item" href="/">About</a>
</nav>


<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;basic menu&quot;&gt;
    &lt;a class=&quot;header item&quot; href=&quot;/&quot;&gt;
    Your Product
    &lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Home&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Documents&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Contact&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;About&lt;/a&gt;
&lt;/nav&gt;
</code>
</pre>

<p>Or you can add an icon next to an item:</p>

<nav class="basic menu">
    <a class="header icon item" href="/">
    <i class="fa fa-heart"></i>
    Your Product
    </a>
    <a class="item" href="/">Home</a>
    <a class="item" href="/">Documents</a>
    <a class="item" href="/">Contact</a>
    <a class="item" href="/">About</a>
</nav>


<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;basic menu&quot;&gt;
    &lt;a class=&quot;header icon item&quot; href=&quot;/&quot;&gt;
    &lt;i class=&quot;fa fa-heart&quot;&gt;&lt;/i&gt;
    Your Product
    &lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Home&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Documents&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Contact&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;About&lt;/a&gt;
&lt;/nav&gt;
</code>
</pre>

<p></p>

<h4>Border Menu</h4>

<p>You can borders to your menu.</p>

<nav class="border menu">
    <a class="header item" href="/">
    Your Product
    </a>
    <a class="item" href="/">Home</a>
    <a class="item" href="/">Documents</a>
    <a class="item" href="/">Contact</a>
    <a class="item" href="/">About</a>
</nav>

<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;border menu&quot;&gt;
    &lt;a class=&quot;header item&quot; href=&quot;/&quot;&gt;
    Your Product
    &lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Home&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Documents&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Contact&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;About&lt;/a&gt;
&lt;/nav&gt;
</code>
</pre>

<p></p>

<h4>Responsive Menu</h4>

<p>Menus can be responsive to render items better in portable devices. Add <code>responsive</code> class name to enable this feature.</p>

<nav class="responsive border menu">
    <a class="header item" href="/">
    Your Product
    </a>
    <a class="item" href="/">Home</a>
    <a class="item" href="/">Documents</a>
    <a class="item" href="/">Contact</a>
    <a class="item" href="/">About</a>
</nav>

<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;responsive border menu&quot;&gt;
    &lt;a class=&quot;header item&quot; href=&quot;/&quot;&gt;
    Your Product
    &lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Home&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Documents&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Contact&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;About&lt;/a&gt;
&lt;/nav&gt;
</code>
</pre>

<p></p>

<h4>Vertical Menu</h4>

<p>Simply change your menu to vertical by adding <b>vertical</b> class to your menu.</p>

<nav class="vertical menu">
    <a class="header item" href="/">
    Your Product
    </a>
    <a class="item" href="/">Home</a>
    <a class="item" href="/">Documents</a>
    <a class="item" href="/">Contact</a>
    <a class="item" href="/">About</a>
</nav>


<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;vertical menu&quot;&gt;
    &lt;a class=&quot;header item&quot; href=&quot;/&quot;&gt;
    Your Product
    &lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Home&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Documents&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Contact&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;About&lt;/a&gt;
&lt;/nav&gt;
</code>
</pre>

<p></p>

<h4>Vertical Fluid Menu</h4>

<p>Vertical menus can have a fluid container. Add <b>fluid</b> class to your vertical menu.</p>

<nav class="vertical fluid border menu">
    <a class="header item" href="/">
    Your Product
    </a>
    <a class="item" href="/">Home</a>
    <a class="item" href="/">Documents</a>
    <a class="item" href="/">Contact</a>
    <a class="item" href="/">About</a>
</nav>


<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;vertical fluid menu&quot;&gt;
    &lt;a class=&quot;header item&quot; href=&quot;/&quot;&gt;
    Your Product
    &lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Home&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Documents&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Contact&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;About&lt;/a&gt;
&lt;/nav&gt;
</code>
</pre>

<p></p>

<h4>Vertical Border Menu</h4>

<p>Vertical menu can have <code>border</code> class name.</p>

<nav class="vertical border menu">
    <a class="header item" href="/">
    Your Product
    </a>
    <a class="item" href="/">Home</a>
    <a class="item" href="/">Documents</a>
    <a class="item" href="/">Contact</a>
    <a class="item" href="/">About</a>
</nav>


<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;vertical border menu&quot;&gt;
    &lt;a class=&quot;header item&quot; href=&quot;/&quot;&gt;
    Your Product
    &lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Home&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Documents&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;Contact&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;/&quot;&gt;About&lt;/a&gt;
&lt;/nav&gt;
</code>
</pre>

<p></p>

<h4>Menu Grouping</h4>

<p>Items can be nested and make a group of items.</p>

<nav class="vertical menu">
<div class="items">
    <div class="icon item header">
        <i class="fa fa-gear"></i>
        First
    </div>

    <a class="item" href="">Child</a>
    <a class="item" href="">Child</a>
    <a class="item" href="">Child</a>
</div>

<div class="items">
    <div class="icon item header">
        <i class="fa fa-heart"></i>
        Second
    </div>

    <a class="item" href="">Child 2</a>
    <a class="item" href="">Child 2</a>
    <a class="item" href="">Child 2</a>
</div>
</nav>

<pre class="code-example">
<code class="language-html">
&lt;nav class=&quot;vertical menu&quot;&gt;
&lt;div class=&quot;items&quot;&gt;
    &lt;div class=&quot;icon item header&quot;&gt;
        &lt;i class=&quot;fa fa-gear&quot;&gt;&lt;/i&gt;
        First
    &lt;/div&gt;

    &lt;a class=&quot;item&quot; href=&quot;&quot;&gt;Child&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;&quot;&gt;Child&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;&quot;&gt;Child&lt;/a&gt;
&lt;/div&gt;

&lt;div class=&quot;items&quot;&gt;
    &lt;div class=&quot;icon item header&quot;&gt;
        &lt;i class=&quot;fa fa-heart&quot;&gt;&lt;/i&gt;
        Second
    &lt;/div&gt;

    &lt;a class=&quot;item&quot; href=&quot;&quot;&gt;Child 2&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;&quot;&gt;Child 2&lt;/a&gt;
    &lt;a class=&quot;item&quot; href=&quot;&quot;&gt;Child 2&lt;/a&gt;
&lt;/div&gt;
&lt;/nav&gt;
</code>
</pre>
