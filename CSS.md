## CSS Grammar

### 渐变设置

#### linear-gradient（横向渐变）

```css
.c1{
	background-image: linear-gradient(blue, red);/*最简单用法，从上到下渐变*/
}
.c2{
	background-image: linear-gradient(to right, blue, red);/*声明从左到右的方向*/
}
.c3{
    background-image: linear-gradient(to bottom right, blue, red);/*从左上角到右下角*/
}
/*xdeg的用法：默认从六点钟方向为起点开始，起点顺时针旋转，x从0到360*/
.c4{
    background-image: linear-gradient(0deg, yellow, red);/*从下往上*/
}
.c5{
    background-image: linear-gradient(90deg, red, yellow); /*从左往右*/
}
.c6{
    background-image: linear-gradient(to right, transparent 50%, red);/*前50%为透明，剩余部分从透明渐变到红色*/
}

.c7{
    background-image: linear-gradient(to right, transparent 50%, red 0);/*前50%透明，剩余部分全是红色（记号0）*/
}
.8{
    background-image: linear-gradient(to right, transparent , red 0, blue);/*似乎等价于linear-gradient(to right, red, blue)，这里猜想加一个0会让该值前面所有渐变失效
}
```

#### circle-gradient（径向渐变）

# #######待施工##########

### transform: 2D变形



## CSS Instance

### 画圆形

```css
.container{
    width:100px;
    height:100px;/*Not limited size, width==height*/
    border-radius: 50%;
}
```

