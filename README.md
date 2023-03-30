# React-Notes
this repo contains the core as well as theoretical concept React

## What is Emmet?
Most editor allow us to store and re-use commonly used code, calles snippet. It boost our productivity. But is has some drawback, first we have to define it and then we can use it, also we can't extend it in run time.
And here emmet cam in picture, we can write css expresseion that can be dynamically parsed and produce output.

For example,

If you want to write below code ->
<pre>
&lt;page&gt;
      &lt;div class="logo"&gt;&lt;/div&gt;
      &lt;ul id="navigation"&gt;
        &lt;li&gt;&lt;a href=""&gt;Item 1&lt;/a&gt;&lt;/li&gt;
        &lt;li&gt;&lt;a href=""&gt;Item 2&lt;/a&gt;&lt;/li&gt;
        &lt;li&gt;&lt;a href=""&gt;Item 3&lt;/a&gt;&lt;/li&gt;
        &lt;li&gt;&lt;a href=""&gt;Item 4&lt;/a&gt;&lt;/li&gt;
        &lt;li&gt;&lt;a href=""&gt;Item 5&lt;/a&gt;&lt;/li&gt;
      &lt;/ul&gt;
&lt;/page&gt
<pre>
you just have to write page>div.logo+ul#navigation>li*5>a{Item $}
<pre>
> used to write any tag inside of another tag
. used to specify class name
+ used to add another tag after one tag
# used to specify id
* used to count of tag you want to write
<pre>
