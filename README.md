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
&lt;/page&gt;
</pre>
you just have to write page>div.logo+ul#navigation>li*5>a{Item $}
<pre>
> used to write any tag inside of another tag
. used to specify class name
+ used to add another tag after one tag
# used to specify id
* used to count of tag you want to write
</pre>

## Difference between a Library and Framework?
A library is a collection of reusable code that developers can use to perform specific tasks or add functionality to their applications, it usually consist of a set of functions or classes. It does not dictate the overall structure or design of the application. Developers have more control over the application's overall design and architecture when using libraries.
Framework is a more comprehensive software architecture that provides a complete structure for developing applications. It often include libraries, but they also include additional components such as templates, APIs. Developers may have less control over the specific implementation details of the application.

## What is CDN? Why do we use it?

