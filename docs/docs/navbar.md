### Navbar beta

There are 2 main types of navbar in Titanium - horizontal and vertical. They have no additional styling, but can be styled using the basic styling classes. *Note: If you wish to style text colors, use the `children-text-color` classes instead of the `text-color` classes. Add it to the `ul`.*

**Horizontal**

Use the class `horizontal-navbar` on an unordered list to produce a horizontal navbar across the top of the page. Place the HTML just below the `body` tag.

```
<ul class="horizontal-navbar">
  <li><a href="#">Link</a></li>
  <li><a href="#">Link</a></li>
</ul>
```

By default, the navbar's items will stack to the left. To make them stack to the right, add the class `navbar-stack-right` to the `ul`.

**Vertical**

A vertical navbar is similar to a horizontal one. Add the class `vertical-navbar` on an unordered list to produce a vertical navbar on the side of the page. Place the HTML just below the `body` tag. **Enclose all content after the vertical navbar in a plain `div`.**

```
<ul class="vertical-navbar">
  <li><a href="#">Link</a></li>
  <li><a href="#">Link</a></li>
</ul>

<div>
...
</div>
```

**Sticky Navbars**

A sticky navbar has a fixed position on the page. You can use the class `horizontal-navbar-sticky` or `vertical-navbar-sticky` in place of the ordinary navbar classes. 

```
<ul class="vertical-navbar-sticky">
  <li><a href="#">Link</a></li>
  <li><a href="#">Link</a></li>
</ul>

<div>
...
</div>
```

**Responsive Navbars**

There are two types of responsive navbar in Titanium. For the first one, simply add the class `responsive-h` to the `ul`. This is pretty basic.

![Result](https://preview.ibb.co/kwnvCz/Capture.png)

The second type of responsive navbar is `responsive-h2`. This requires some extra imports and HTML. Add these links to the `head` section of your webpage:

`<script src="https://cdn.rawgit.com/rappatic/titanium/master/beta/beta/titanium.js"></script>`

`<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">`

You also need to add some HTML to the bottom of the `ul`:

```
<li>
    <a href="#" onclick="compressNavbar()"><i class="fa fa-bars"></i></a>
</li>
```

This will create a result like this:

![Result](https://image.ibb.co/hqC1kK/Capture.png)

The first link in the list (usually Home) will be kept, and a hamburger button (**you must include the above HTML**) will be displayed to the right. Clicking the hamburger button will fold out a menu with all your links.
