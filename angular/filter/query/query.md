# query

开始filter是分开的，一个业务写一个，由于后来越写越多，最后重构成目前这个。
queryFilter不仅可以获取自定义数据（ConfData），还可以获得缓存的接口数据（使用ajaxCacher返回的同步回调方法）

* 统一定义自定义数据
* 使用ajaxCache缓存的接口数据

![test](1.png)

![test](2.png)
