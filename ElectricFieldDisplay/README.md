# ElectricFieldDisplay

大学物理的一个作业……  
An assignment of Physics course.

这个程序可以绘制由 n 个静止点电荷形成的电场，用 RGB 颜色深浅表示电场强度的大小。  
This program can draw the electric field generated by n static point charges. The strength of the electric field is showed by the depth of the RGB color.

第一行输入一个正整数 n，表示需绘制的点电荷个数，接下来 n 行输入三个实数 x, y, q，表示这个点电荷的坐标为 (x, y)，带电量为 q。最后一行输入五个实数，分别是绘制范围（一个矩形）的左下角的横坐标与纵坐标，右上角的横坐标与纵坐标，最后一个是绘制的精度。  
You should input an integer n at the first line, indicating the number of the point charges. Input three real numbers x, y, q at the following n lines, indicating the position of the charge is (x, y) and the charged quantity is q. At the last line, input five real number, indicating the lower-left coner and the top right conrt of the range (a rectangle), the last one is the precision when drawing.

最后会生成一个 png 图像。  
At last, the program will generate a png image.

本程序使用 [EGE 库](https://xege.org/)进行图形绘制。  
This program use [EGE library](https://xege.org/) when drawing the graphics.

但是感觉绘制效果不算太好……  
But I feel the result is not so good...

用得愉快！  
Enjoy using!

HeRaNO  
2019.4.5
