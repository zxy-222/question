#### 								swiper

###### 1、在同一个页面复用swiper轮播图失效

```
加上两行代码：
	1、observe：true，//修改swiper自己或子元素时，自动初始化swiper
	2、observeParents：true,//修改swiper的元素时，自动初始化swiper
```

###### 2、slide间距

```
1、可以是具体单位；eg：spaceBetween:30px;
2、可以是百分比;eg：spaceBetween:10%,是按container的百分比
```

###### 3、slidePerView

```
设置slide容器能同时显示slides的数量
可设置数字(可为小数，小数不可loop)，或者'auto'则自动根据slides的宽度来设定数量
```



