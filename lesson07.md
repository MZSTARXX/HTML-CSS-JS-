# 设置背景和渐变

在CSS中，元素背景可以是纯色，图像，渐变或这些的组合。

## 添加背景颜色 {#background-color}

向元素添加背景的最快方法是使用background or background-color属性添加单色背景。该background属性接受简写形式的色彩和图像，而background-color属性是严格用于设置固体的背景色。

```
例：div {background-color: #b2b2b2;}
```

## 添加背景图像 {#background-image}

除了为元素添加背景颜色外，我们还可以添加背景图像。背景图像与背景颜色类似;然而，它们提供了一些额外的属性来精细化图像。和以前一样，我们可以使用background具有简写值的属性，或者我们可以background-image直接使用该属性。无论我们使用哪个属性，都必须使用url\(\)函数识别图像源。

该url\(\)函数值将背景图片的路径，以及用于创建超链接路径的熟悉规则适用于此。留意不同的目录，并确保准确显示图像所在的位置。路径将放在括号内并引用。

```
div {background-image: url("alert.png");}
```



