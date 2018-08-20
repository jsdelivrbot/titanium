### Nesting Containers

The best way to manipulate multiple containers in Titanium is by nesting them. For example, centering two containers on one line is impossible without nesting.

There are several different classes that can help you with this.


**Multiple containers on one line**

Use a parent div with the class `center-inside`.

```
<div class="center-inside">
  <div class="small">Hello, I'm div 1</div>
  <div class="small">Hello, I'm div 2</div>
 <div>
 ```

![Result](https://preview.ibb.co/npF148/Capture.png)

**Easy stacking**

To avoid having to add a stack class to many containers, use a parent element with the class `children-stack-left` or `children-stack-right`.

```
<div class="children-stack-left`>
  <div>I'm div 1</div>
  <div>I'm div 2</div>
</div>
```

![Result](https://preview.ibb.co/dDbYj8/Capture.png)
