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

##  What is crossorigin in script tag?
Cross-Origin Resource Sharing (CORS) is a mechanism that allows web applications to make requests to a domain that is different from the domain of the origin of the application. The Same-Origin Policy (SOP) restricts web pages from making requests to a different domain than the one that served the page. SOP is a security measure to prevent malicious code from accessing sensitive data.
CORS enables a web page to include content from another domain in a safe manner by using HTTP headers to allow or deny access to resources. The web server hosting the resource needs to explicitly allow cross-origin requests by adding an Access-Control-Allow-Origin header in the response. This header specifies the origin that is allowed to access the resource. If the requested origin is not in the Access-Control-Allow-Origin header, the browser blocks the request.
CORS is a critical security feature for modern web applications that rely on third-party APIs and resources. Without CORS, it would be impossible to build rich, dynamic web applications that integrate with various services and data sources.

