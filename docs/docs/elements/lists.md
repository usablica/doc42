---
layout: doc
title: Lists
categories: elements
permalink: /docs/elements/lists/
---

<div class="row docs-example">
<div class="six columns">
  <ul>
    <li>Unordered lists have basic styles</li>
    <li>
      They use the circle list style
      <ul>
        <li>Nested lists styled to feel right</li>
        <li>Can nest either type of list into the other</li>
      </ul>
    </li>
    <li>Just more list items mama san</li>
  </ul>
</div>
<div class="six columns">
  <ol>
    <li>Ordered lists also have basic styles</li>
    <li>
      They use the decimal list style
      <ul>
        <li>Ordered and unordered can be nested</li>
        <li>Can nest either type of list into the other</li>
      </ul>
    </li>
    <li>Last list item just for the fun</li>
  </ol>
</div>
</div>


<pre class="code-example">
<code class="language-html">&lt;ul&gt;
  &lt;li&gt;Item 1&lt;/li&gt;
  &lt;li&gt;
    Item 2
    &lt;ul&gt;
      &lt;li&gt;Item 2.1&lt;/li&gt;
      &lt;li&gt;Item 2.2&lt;/li&gt;
    &lt;/ul&gt;
  &lt;/li&gt;
  &lt;li&gt;Item 3&lt;/li&gt;
&lt;/ul&gt;

&lt;!-- Easily substitute any &lt;ul&gt; or an &lt;ol&gt; to get number lists or sublists. Kissui doesn't support lists nested deeper than 2 levels --&gt;
</code>
</pre>
