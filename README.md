# Faygo User Manual

User manual of faygo frame.

[Faygo](https://github.com/henrylee2cn/faygo) is a fast and concise Go Web framework that can be used to develop high-performance web app(especially API) with fewer codes. Just define a struct Handler, Faygo will automatically bind/verify the request parameters and generate the online API doc.

Manual status: gradually completing...

[简体中文](README_ZH.md)

## 目录

* 1.[欢迎使用 faygo](zh/01.00.md)
 - 1.1. [安装 faygo](zh/01.01.md)
 - 1.2. [项目架构](zh/01.02.md)

* 2.[创建服务](zh/02.00.md)
 - 2.1. [单服务&单监听](zh/02.01.md)
 - 2.2. [单服务&多监听](zh/02.02.md)
 - 2.3. [多服务&单监听](zh/02.03.md)
 - 2.4. [多服务&多监听](zh/02.04.md)

* 3.[项目部署运行](zh/03.00.md)
 - 3.1. [启动所有服务实例](zh/03.01.md)
 - 3.2. [平滑关闭与重启](zh/03.02.md)
 - 3.3. [部署及元编程工具 fay](zh/03.03.md)
 
* 4.[操作与中间件](zh/04.00.md)
 - 4.1. [函数类型Handler](zh/04.01.md)
 - 4.2. [结构体类型Handler](zh/04.02.md)
 - 4.3. [Swagger2.0在线API文档](zh/04.03.md)

* 5.[路由器](zh/05.00.md)
 - 5.1. [两种注册形式](zh/05.01.md)
 - 5.2. [静态路由](zh/05.02.md)
 - 5.3. [中间件](zh/05.03.md)
 - 5.4. [过滤器](zh/05.04.md)
 - 5.5. [配置信息](zh/05.05.md)

* 6.[模版渲染](zh/06.00.md)
 - 6.1. [渲染模板](zh/06.01.md)
 - 6.2. [模板标签和过滤器基础](zh/06.02.md)
 - 6.3. [模版包含](zh/06.03.md)
 - 6.4. [模版继承](zh/06.04.md)
