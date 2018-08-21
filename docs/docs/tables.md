### Tables

Tables in TitaniumCSS are very easy, as they are automatically styled for you. Just use the class `table`.

```
<table class="table">
  <tr>
    <th>First Name</th>
    <th>Last Name</th>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Doe</td>
  </tr>
  <tr>
    <td>Adam</td>
    <td>Johnson</td>
  </tr>
</table>
```

![Result](https://preview.ibb.co/hQHvE8/Capture.png)

The tables generated like this are very plain. You can add an outer border to the table using the class `border-` followed by a color.

```
<table class="table border-black">
...
</table>
```

![Result](https://preview.ibb.co/fSLbMo/Capture.png)

You can add inner borders as well using the class `children-border-` followed by a color.

```
<table class="table children-border-black">
...
</table>
```

![Result](https://preview.ibb.co/hEMNu8/Capture.png)

`table` itself can be styled with things such as `bg-blue`:

```
<table class="table children-border-black bg-blue">
...
</table>
```

![Result](https://preview.ibb.co/cshgMo/Capture.png)

And you can also style individual in-table components like `<tr>` and `<td>`.

A very useful feature is automatic striping with the `striped` class, which adds a grey background to every other row.

```
<table class="table childen-border-black striped">
...
</table>
```

![Result](https://preview.ibb.co/dmeiZ8/Capture.png)

You can also center all text in the table with the `all-center` class.

To make the table responsive, enclose it into a div with the class `table-container`.
