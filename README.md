##  CoffeeHeader，一个搅拌咖啡效果的下拉刷新Header。
### 博客详情： <https://blog.csdn.net/u011387817/article/details/100530256>

### 使用方式:
#### 添加依赖：(需配合[SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)使用)
```
implementation 'com.wuyr:coffeeheader:1.0.1'
```

### APIs:
|Method|Description|
|---------|-------------|
|updateSize(int cupRadius)|更新杯子半径|
|updateSize(int width, int height, int cupRadius)|更新Drawable尺寸和杯子半径|
|setCupBodyColor(int color)|设置杯身颜色|
|setCupBottomColor(int color)|设置杯底颜色|
|setCoffeeColor(int color)|设置咖啡颜色|
|setHandColor(int color)|设置手颜色|
|setStickColor(int color)|设置搅拌棒颜色|
|setStirringDuration(long duration)|设置搅拌一圈的时长 (默认: 500)|
|setHideDuration(long duration)|设置隐藏手臂动画时长 (默认: 300)|
|setEdgeFadeDuration(long duration)|设置咖啡边缘渐变动画时长 (默认: 500)|

### Attributes:
|Name|Format|Description|
|----|-----|-----------|
|coffeeColor|color (默认: 咖啡色)|咖啡颜色|
|cupBodyColor|color (默认: 白色)|杯身颜色|
|cupBottomColor|color (默认: 青色)|杯底颜色|
|handColor|color (默认: 棕黄)|手颜色|
|stickColor|color (默认: 白色)|搅拌棒颜色|
|cupRadius|dimension (默认: 总宽度的1/15)|杯子半径|


### Demo下载: [app-debug.apk](https://github.com/wuyr/CoffeeDrawable/raw/master/app-debug.apk)
### Demo源码地址: <https://github.com/wuyr/CoffeeDrawable>
### CoffeeDrawable源码地址: <https://github.com/Ifxcyr/CoffeeDrawable>

### 效果图：
![preview](https://github.com/wuyr/CoffeeDrawable/raw/master/previews/preview1.gif) ![preview](https://github.com/wuyr/CoffeeDrawable/raw/master/previews/preview2.gif)
