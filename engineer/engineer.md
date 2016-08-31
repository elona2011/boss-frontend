# 原因

1.实现业务优先、模块化的架构。由于现在没有按模块分，合代码时很痛苦，经常会有代码忘记合。平时开发时，找文件也比较费事，要在app.js里搜索

2.app.js已经非常大了，directives.js也越来越大，views和controllers文件夹里有几百个文件

2.非覆盖式发布

3.自动打包文件，减少网络请求

4.提高开发效率，HMR，支持ES2015，自动编译、自动刷新

5.Cross-Domain LocalStorage

# 已实现但未上线

已实现的这部分在``/src``的目录下，做了两个业务模块softOrder和afterSellRecord，如果通过``npm start``起的项目，这两个业务模块会运行，替代掉原来的软装和售后的相关页面。所以，通过``npm start``起的项目，需要注释掉app.js里的orders和reject-orders

![test](1.png)
