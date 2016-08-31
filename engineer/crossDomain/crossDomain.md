# 跨域Session

实际开发过程中，本地环境和线上环境(11)经常会同时使用。因为联的是同一后台，两套环境先后登陆会产生不同的sessionId，所以不能同时登陆。但实际上，只要是sessionId相同，就可以同时登陆。

解决方法：使用iframe的postMessage方法可以实现跨tab页的通信。本地环境每次载入时，都会向线上11页写入一次sessionId

![test](1.png)
