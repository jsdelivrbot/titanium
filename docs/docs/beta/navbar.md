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

You can make a horizontal navbar completely responsive with the `responsive-h` class. More responsive options will arrive with the next version.

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

Be advised that sticky navbars may not work properly on mobile devices or with the `responsive-h` class.
