# orx-image-fit

Fits images in frames with two options, contain and cover. Similar to CSS object-fit (https://www.w3schools.com/css/css3_object-fit.asp)

## usage

`imageFit(img: ColorBuffer, x: Double, y: Double, w: Double, h: Double, fitMethod, horizontalPosition:Double, verticalPosition:Double)`


fitMethod
 - `contain`
 - `cover`
 
horizontal values
 - left ... right
 - `-1.0` ... `1.0`
 
 vertical values
 - top ... bottom
 - `-1.0` ... `1.0`