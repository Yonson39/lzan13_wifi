这个小例子可以判断设备是否已经连接网络，并且在连接网络的状态下可以判断是wifi无线连接还是GPRS手机网络连接，这样就可以在不同的网络连接下去调用不同的方法，处理不同的事情，比如一个有下载功能的app可以判断只有当wifi连接的是后去下载文件，GPRS流量连接则不下载！

在没有连接的网络的情况下会弹出一个对话框，让用户选择是否去设置网络连接！

![image](http://img.blog.melove.net/blog/uploads/images/2013/05/wifi-state.png)

我这里为了能明确的说明wifi和GPRS连接的不同情况，设置了wifi连接下加载一个admob的广告条，GPRS下不去加载广告，这也算是在实际的开发中提升用户体验的一个途径吧！ 

更多请关注我的个人博客：[http://www.melove.net](http://www.melove.net)
