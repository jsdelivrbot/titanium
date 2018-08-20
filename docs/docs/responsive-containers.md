### Responsive Containers

As most of the units used in Titanium are relative (%, vh, ect.) designing a website normally makes it reasonably responsive. But what happens when the screen gets too small to accommodate multiple containers? For example, if you have four containers and the screen is the size of a phone:

![Result](https://image.ibb.co/mWZ0xT/Capture.png)

The best solution to this is for the inner containers to expand when the screen gets too small. For this to happen, use the responsive versions of `center-inside`. 

There are three of these:

* `center-inside-sensitive`
* `center-inside-normal`
* `center-inside-insensitive`

These three settings simply dictate when to expand the divs - the `center-inside-sensitive` class will expand them before `center-inside-normal`. Use a more sensitive option when you have more inner containers.

```
<div class="center-inside-normal">
  <div class="xs">1</div>
  <div class="xs">2</div>
  <div class="xs">3</div>
  <div class="xs">4</div>
</div>
```

![Result](https://preview.ibb.co/ex1xu8/Capture.png)


This solution will only work on divs. If you wish for other elements to expand, place them inside a div.
