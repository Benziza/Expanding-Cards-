# Expanding-Cards

## 1-Vh in CSS

In CSS, "vh" stands for viewport height. It is a unit of measurement that represents a percentage of the height of the viewport (the visible portion of the web page).

The viewport height ("vh") unit allows you to specify sizes and positions relative to the height of the viewport. It is particularly useful for creating responsive designs that adapt to different screen sizes.

Here's a simple example to illustrate the usage of "vh" in CSS:

```
<!DOCTYPE html>
<html>
  <head>
    <style>
      /* Set the height of the element to 50% of the viewport height */
      .box {
        height: 50vh;
        background-color: coral;
      }
    </style>
  </head>
  <body>
    <div class="box"></div>
  </body>
</html>
```

In this example, we have a CSS rule for a class called "box". The height of the "box" element is set to 50vh, which means it will occupy 50% of the viewport height. The background color is set to coral, just to make the element visible.

By using "vh", the height of the element will automatically adjust based on the height of the viewport. So, if the viewport is 800 pixels high, the "box" element will be 400 pixels high (50% of 800).

## 2-Vw in CSS

In CSS, "vw" stands for viewport width. It is a unit of measurement that represents a percentage of the width of the viewport, which is the visible area of a web page.

To understand how "vw" works, let's consider a simple example. Suppose you have a container div element with a width of 50vw. This means that the width of the container will be 50% of the viewport width.

Here's an example of how you can use "vw" in CSS:

```
.container {
  width: 50vw;
  height: 200px;
  background-color: lightblue;
}
```

In this example, the container div will always be half the width of the viewport. So if the viewport width is 1000px, the container will have a width of 500px.
