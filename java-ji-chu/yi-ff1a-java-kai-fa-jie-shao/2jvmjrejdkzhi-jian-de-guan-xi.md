# 2.JVM、JRE、JDK之间的关系

## 总结
总体来说，三者的关系是包含关系，JDK是开发工具包，JRE是运行环境，JVM是JAVA的虚拟机(执行环境)，现在使用版本最普遍的是Java8这个版本，对于Java8的支持最终时间2025年3月。

## 参考资源
- [百度百科-JDK,JRE,JVM之间的关系](https://jingyan.baidu.com/article/425e69e6077283be15fc16ed.html)
- [简书](https://www.jianshu.com/p/1aaee6b3bc7a)
- [Java的历史版本-基维百科](https://zh.wikipedia.org/wiki/Java%E7%89%88%E6%9C%AC%E6%AD%B7%E5%8F%B2)
- [官方下载链接](https://www.oracle.com/technetwork/java/javase/downloads/index.html)

## JDK(Java Development Kit)
Java开发工具包，是针对Java开发员的产品，是整个Java的核心，包括了Java运行环境
JRE、Java工具和Java基础类库。
## JRE(Java Runtime Environment)
是运行JAVA程序所必须的环境的集合，包含JVM标准实现及Java核心类库。
## JVM(JVM是Java Virtual Machine)
Java虚拟机的缩写，是整个java实现跨平台的最核心的部分，能够
运行以Java语言写作的软件程序。
<p>

### JDK的历史版本

这张图是在基维百科上找到的，可以看出1995年开始JAVA的bate版发布到，支持力度最好的还是JAVA8版本，而且在Java 7发布之后，Oracle承诺回到以前每两年发布一次的发布周期。但在2013年时，Oracle却宣布他们将Java 8延迟一年发表，官方表示是为了修复与Java安全漏洞。

Java 8是唯一公开支持的版本，而在旧版本的公开支持期结束后，已经为Java 7和其它更早的版本发布了非公开的更新。

![image](https://github.com/whydejavu/engineer/raw/master/resource/image/java-ji-chu/jdk-history.jpeg)