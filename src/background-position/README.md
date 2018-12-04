# background-position

## 定义和用法
background-position 属性设置背景图像的起始位置  
这个属性设置背景原图像(由background-image定义)的位置，背景图像如果要重复，将从这一点开始。

>提示：您需要把background-attachement属性设置为"fixed"，才能保证该属性在Firefox和Opera中正常工作。

 

默认值：	0% 0%   
继承性：	no    
版本：	CSS1    
JavaScript 语法：	object.style.backgroundPosition="center"

## 可能的值

| 值        | 描述    |
| :--------:   | :-----:   |
|top left||
|top center||
|top right||
|center left||
|center center|如果您仅规定了一个关键词，那么第二个值将是"center"。默认值：0% 0%。|
|center right||
|bottom left||
|bottom center||
|bottom right||
|x% y%| 第一个值是水平位置，第二个值是垂直位置。 左上角是0% 0%。右下角是100% 100%。如果您仅规定了一个值，另一个值将是50% |
|xpos ypos | 第一个值是水平位置，第二个值是垂直位置。左上角是0 0。单位是像素(0px 0px)或任何其他的CSS单位。 如果您仅规定了一个值，另一个值将是50%。您可以混合使用%和position值。 |
