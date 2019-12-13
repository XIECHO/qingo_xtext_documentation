# 如何使用qingo（xtext版本）
这篇文档主要介绍如何使用qingo（xtext版本）
- JRE安装
- JAR包和配置文件下载
- 例子
- 其他

# JRE安装
如果你已经安装JDK，可以跳过这步。

从[官网](https://www.java.com/zh_CN/download/)下载最新版本JRE。执行下载文件并在安装界面点击下一步直到安装完成。

# JAR包和配置文件下载

从[网站](https://github.com/XIECHO/qingo_xtext_documentation.git)下载qingo.jar、standard_operations.qingo、config-qingo.qingo。

# 例子
## T1
从[网站](https://github.com/XIECHO/qingo_xtext_documentation.git)下载t1.qingo。
将下好的qingo.jar、standard_operations.qingo、config-qingo.qingo、t1.qingo放在一个目录下，在terminal执行命令
```
java -jar qingo.jar t1.qingo standard_operations.qingo config-qingo.qingo
```
> t1.qingo: 书写的qingo程序

> standard_operations.qingo: t1依赖的库文件

> config-qingo.qingo: t1依赖的库文件

执行完后，当前目录下会生成一个子目录”src-gen“，子目录下生成文件t1.eqasm。
当前目录为
* qingo.jar
- t1.qingo 
- standard_operations.qingo
- config-qingo.qingo
- src-gen
- - t1.eqasm
## 自己写例子
所有用qingo编译器编译的源文件以".qingo"结尾命名。
把t1.qingo替换为你书写的例子，并执行命令(将t1.qingo替换为你写的例子)
```
java -jar qingo.jar XXXXXXX.qingo standard_operations.qingo config-qingo.qingo
```
# 其他
## qingo语法
语法可从[网站](https://code.ihub.org.cn/projects/429/repository/revisions/xtext/entry/docs/qingo_spec/syntax_core.md)查阅。
## 提交问题
你可以向[网站](https://github.com/XIECHO/qingo_xtext_documentation)issue反馈问题，或者直接在群里反馈。
