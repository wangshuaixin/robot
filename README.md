# robot
Golang爬虫框架。

##robot分四个接口：
* 下载模块(Downloader)
* 页面处理模块(PageProcesser)
* 任务调度模块(Scheduler)
* pipline

其中下载模块，调度模块已经实现，需要开发者自行实现页面处理规则与pipline