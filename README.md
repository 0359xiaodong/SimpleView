##View画圆

觉得重绘图层觉得很难，对它一直会排斥，今天看到鸿大神的这个样例，突然觉得不错，清晰易懂，特此将这个Demo保留下来
![p0](http://img.blog.csdn.net/20140426141003906)

博客：http://blog.csdn.net/lmj623565791/article/details/24529807

对要画笔工具，可以参照这里：http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2012/1212/703.html

```
    //绘制弧线区域   
                                                                                                                                  
    RectF rect = new RectF(0, 0, 100, 100);   
                                                                                                                                  
    canvas.drawArc(rect, //弧线所使用的矩形区域大小   
            0,  //开始角度   
            90, //扫过的角度   
            true, //是否使用中心   
            paint);
```

![p1](http://www.jcodecraeer.com/uploads/allimg/130305/19311M430-0.jpg)

> Canvas可以绘制的对象有：弧线(arcs)、填充颜色(argb和color)、 Bitmap、圆(circle和oval)、点(point)、线(line)、矩形(Rect)、图片(Picture)、圆角矩形 (RoundRect)、文本(text)、顶点(Vertices)、路径(path)。
> Android还提供了一些对Canvas位置转换的方法：rorate、scale、translate、skew(扭曲)等

