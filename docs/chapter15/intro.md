# 15.1 Github 客户端示例

本章新建一个 Flutter 工程，实现一个简单的 Github 客户端。这个实例的主要目标有两个：

1. 带领读者了解如何使用 Flutter 来开发一个完整 APP，了解 Flutter 应用开发流程及工程结构等。
2. 对前面章节所学内容的一个应用及总结。

需要注意的是，由于 Github 本身功能非常多，我们的焦点并不是去实现 Github 的所有业务功能。因此，我们只需要实现一个 APP 的骨架，能达到上面这两点即可。下面对我们要实现的功能如下：

1. 实现 Github 账号登录、退出登录功能
2. 登录后可以查看自己的项目主页
3. 支持换肤
4. 支持多语言
5. 登录状态可以持久化；

要实现上面这些功能会涉及到如下技术点：

1. 网络请求；需要请求 Github API。
2. Json 转 Dart Model 类；
3. 全局状态管理；语言、主题、登录态等都需要全局共享。
4. 持久化存储；保存登录信息，用户信息等。
5. 支持国际化、Intl 包的使用

现在，目标已经确定，在接下来章节中，我们将分模块一步一步实现上述功能。
