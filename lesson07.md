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

### 背景重复

默认情况下，除非另有说明，否则背景图像将无限制地垂直和水平重复。如果重复，则可以使用background-repeat属性来改变背景图像重复的方向。

```

例：div {background-image: url("alert.png");
     background-repeat: no-repeat;}

```

该background-repeat属性接受四个不同值：repeat，repeat-x，repeat-y，和no-repeat。重复值是默认值，将垂直和水平重复背景图像。

该repeat-x值将水平重复背景图像，而repeat-y值将垂直重复背景图像。最后，该no-repeat值将告诉浏览器一次显示背景图像 - 也就是说，根本不重复它。

### 背景位置

默认情况下，背景图像位于元素的左上角。但是，通过使用该background-position属性，我们可以精确控制背景图像相对于该角落的放置位置。

```
例：div {
  background-image: url("alert.png");
  background-position: 20px 10px;
  background-repeat: no-repeat;
}

```

该background-position属性需要两个值：水平偏移（第一个值）和垂直偏移（第二个值）。如果仅指定了一个值，则该值用于水平偏移，垂直偏移将默认为50%。

因为我们正在从元素的左上角移动背景图像，所以长度值将特别与该角相关。

要设置一个background-position值，我们可以使用top，right，bottom，left，和center关键字，像素，百分比，或任何长度测量值。关键字和百分比的工作方式非常相似关键字值left top与百分比值相同0 0，这将使图像位于元素的左上角。关键字值right bottom与百分比值相同，百分比值100% 100%将图像放置在元素的右下角。

### 简写背景图像值

background-color，background-image，background-position，和background-repeat属性可以被卷成对于单独的背景属性的速记值。这些性质作为简写的次序background属性值可能会发生变化，但它通常落在如background-color，background-image，background-position，然后background-repeat。

```
div {
  background: #b2b2b2 url("alert.png") 20px 10px no-repeat;
}
```

## 设计渐变背景 {#gradient-backgrounds}



































































































































