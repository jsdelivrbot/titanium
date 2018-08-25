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
