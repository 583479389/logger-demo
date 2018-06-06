# logger-demo


Apache Commons Logging(Jakarta Commons Logging)
* commons-logging:commons-logging的原生全部内容
* log4j-jcl:commons-logging到log4j的桥梁 commons-logging适配log4j
* log4j-jul:commons-logging到jdk logging的桥梁 commons-logging适配jdk logging

Slf4j(Simple Logging Facade for Java)
* slf4j-api
slf4j转向某个实际的日志框架
场景介绍:如使用slf4j的API进行编程,底层想使用log4j1来进行实际的日志输出,这就是slf4j-log4j12干的事.
* slf4j-jdk14:slf4j到jdk-logging的桥梁
* slf4j-log4j12:slf4j到log4j1的桥梁
* log4j-slf4j-impl:slf4j到log4j2的桥梁
* logback-classic:slf4j到logback的桥梁
* slf4j-jcl:slf4j到commons-logging的桥梁
某个实际的日志框架转向slf4j
场景介绍:如使用log4j1的API进行编程,但是想最终通过logback来进行输出,所以就需要先将log4j1的日志输出转交给slf4j来输出,slf4j再交给logback来输出.将log4j1的输出转给slf4j,这就是log4j-over-slf4j做的事.
* jul-to-slf4j:jdk-logging到slf4j的桥梁
* log4j-over-slf4j:log4j1到slf4j的桥梁
* jcl-over-slf4j:commons-logging到slf4j的桥梁

Apache Log4j
* log4j:log4j1的全部内容

Apache Log4j2
* log4j-api:log4j2定义的API
* log4j-core:log4j2上述API的实现

Logback
* logback-core:logback的核心包
* logback-classic:logback实现了slf4j的API

Jul(Java Util Logging) JDK-Logging

Jboss-Logging
* jboss-logging
* jboss-logging-annotations











