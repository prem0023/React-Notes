# React-Notes
this repo contains the core as well as theoretical concept React

## What is Emmet?
Most editor allow us to store and re-use commonly used code, calles snippet. It boost our productivity. But is has some drawback, first we have to define it and then we can use it, also we can't extend it in run time.
And here emmet cam in picture, we can write css expresseion that can be dynamically parsed and produce output.

For example,

If you want to write below code ->
<
<page>
      <div class="logo"></div>
      <ul id="navigation">
        <li><a href="">Item 1</a></li>
        <li><a href="">Item 2</a></li>
        <li><a href="">Item 3</a></li>
        <li><a href="">Item 4</a></li>
        <li><a href="">Item 5</a></li>
      </ul>
</page>

you just have to write page>div.logo+ul#navigation>li*5>a{Item $}
> used to write any tag inside of another tag
. used to specify class name
+ used to add another tag after one tag
# used to specify id
* used to count of tag you want to write
>
