# 
最近看公司框架的时候对于error的报错级别一直有一些疑问。

PHP 主要有两种错误：触发错误和异常。
其中触发错误大概可以分为：编译错误、引擎错误和运行时错误，其中前两个是无法捕获的；异常都是可以捕获的，当没有尝试捕获时则会中断代码。
触发错误可以通过 error_get_last() 来进行获得，异常可以使用标准的 try...catch 语句来捕获。

文章部分摘自：http://feiyang.me/2014/05/handle-php-error-better-introduce-errors/
