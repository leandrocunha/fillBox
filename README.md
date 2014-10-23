## FillBox ##
>v.1.0.0

A jQuery plugin to expand and centralize a image related to parent element independent of size him


### 1.Getting Started
Load jQuery and include FillBox plugin file

```html
<!-- Include jquery -->
<script src="jquery.js"></script>

<!-- Include fillbox plugin -->
<script src="fill.box.js"></script>
```
### 2.Set up your HTML
You don't need any special markup. All you need is add the class ".fill-box" to any image warraped with a block (preferencially) element.

```html
<div>
  <img src="myimage.jpg" class="fill-box" />
</div>
```
### 3.Call the plugin
Now just call the FillBox initializer function and tadaaaaa.

```html
$(".fill-box").fillBox();
```



License
------------
The MIT License (MIT)
