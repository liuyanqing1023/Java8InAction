# Java8InAction

该存储库包含《 Java 8 in Action：Lambda，流和函数式编程》一书中的示例和测验的所有源代码。

您可以在这里购买该书：[http](http://manning.com/urma/) : [//manning.com/urma/](http://manning.com/urma/)或在亚马逊上

所有示例的源代码都可以在目录[src / main / java / lambdasinaction中找到](https://github.com/java8/Java8InAction/tree/master/src/main/java/lambdasinaction)

- 第1章：Java 8：为什么要关心？
- 第2章：通过行为参数化传递代码
- 第3章：Lambda表达式
- 第4章：使用流
- 第5章：使用流处理数据
- 第6章：使用流收集数据
- 第7章：并行数据处理和性能
- 第8章：重构，测试，调试
- 第9章：默认方法
- 第10章：使用Optional作为null的更好替代
- 第11章：CompletableFuture：可组合的异步编程
- 第12章：新的日期和时间API
- 第十三章：功能性思考
- 第14章：函数式编程技术
- 第15章：混合OOP和FP：比较Java 8和Scala
- 第16章：Java的结论和“下一步”
- 附录A：其他语言更新
- 附录B：其他库更新
- 附录C：在Stream上并行执行多项操作
- 附录D：Lambda和JVM字节码我们将在更新本书时更新存储库。敬请关注！

### 确保已安装JDK8

最新的二进制文件可以在这里找到：[http](http://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html) : [//www.oracle.com/technetwork/java/javase/overview/java8-2100321.html](http://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html)

$ java-版本

Java版本“ 1.8.0_05” Java™SE运行时环境（内部版本1.8.0_05-b13）Java HotSpot（TM）64位服务器VM（内部版本25.5-b02，混合模式）

您可以在此处下载预览版：[https](https://jdk8.java.net/) : [//jdk8.java.net/](https://jdk8.java.net/)

### 编译/运行示例

使用Maven：

$ mvn编译

$ cd目标/类别

$ java lambdasinaction / chap1 / FilteringApples

或者，您可以在src / main / java目录中手动编译文件

您也可以在自己喜欢的IDE中导入项目：*在IntelliJ中，使用“文件->打开”菜单并导航到项目所在的文件夹*在Eclipse中，使用“文件->导入->现有Maven项目”（也可以修改“冗余超级接口”报告为警告而不是错误*在Netbeans中，使用“文件->打开项目”菜单