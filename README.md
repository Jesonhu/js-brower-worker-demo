## JS 浏览器环境Worker多线程测试

## 使用说明
+ 多线程测试
  + 1.打开index.html
  + 2.先点击'Start'按钮
  + 3.点击'Alert'按钮。建议多等几秒钟再点击alert的'确定'
  + 4.可以看到input的value值会突然变大了
![多线程效果展示](./img/worker_1.gif)

+ 单线程测试
  + 1.打开index_1.html
  + 2.先点击'Start'按钮
  + 3.点击'Alert'按钮。建议多等几秒钟再点击alert的'确定'
  + 4.可以看到input的value值会累加变大
![单线程效果展示](./img/worker_2.gif)

## 参考文档
+ [haodawang](https://www.cnblogs.com/haodawang/articles/5850822.html)
+ [Web Worker 使用教程](http://www.ruanyifeng.com/blog/2018/07/web-worker.html)
+ [Worker-MDN-en](https://developer.mozilla.org/en-US/docs/Web/API/Worker)
+ [ng2-webworker-dynamic](https://github.com/angular/angular/tree/master/packages/platform-webworker-dynamic)
+ [ng2-platform-webworker](https://github.com/angular/angular/tree/master/packages/platform-webworker)
