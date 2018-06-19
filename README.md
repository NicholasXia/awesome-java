Java相关的库/框架/软件
- [Awesome Java](#awesome-java)
    - [Bean Mapping-Bean映射](#bean-mapping)
    - [Build-构建](#build)
    - [Bytecode Manipulation-字节码操作](#bytecode-manipulation)
    - [Caching-缓存](#caching)
    - [Code Analysis-代码分析](#code-analysis)
    - [Code Coverage-代码覆盖率](#code-coverage)
    - [Code Generators-代码生成](#code-generators)
    - [Command-line Argument Parsers-命令行解析](#command-line-argument-parsers)
    - [Compiler-compiler-编译器](#compiler-compiler)
    - [Configuration-配置](#configuration)
    - [CSV-CSV](#csv)
    - [Data structures-数据结构](#data-structures)
    - [Database-数据库](#database)
    - [Date and Time-日期和时间](#date-and-time)
    - [Dependency Injection-依赖注入](#dependency-injection)
    - [Development-开发](#development)
    - [Distributed Applications-分布式应用](#distributed-applications)
    - [Distributed Transactions-分布式事务](#distributed-transactions)
    - [Distribution-发布](#distribution)
    - [Document Processing-文档解析](#document-processing)
    - [Functional Programming-函数式编程](#functional-programming)
    - [Geospatial-地理位置](#geospatial)
    - [High Performance-高性能](#high-performance)
    - [HTTP Clients-HTTP客户端](#http-clients)
    - [IDE-IDE](#ide)
    - [Imagery-图片](#imagery)
    - [JSON Processing-JSON处理](#json-processing)
    - [JSON-JSON](#json)
    - [JVM and JDK-JVM和JDK](#jvm-and-jdk)
    - [Logging-日志](#logging)
    - [Machine Learning-机器学习](#machine-learning)
    - [Messaging-消息](#messaging)
    - [Miscellaneous-杂项](#miscellaneous)
    - [Monitoring-监控](#monitoring)
    - [Microservice-微服务](#microservice)
    - [Networking-网络](#networking)
    - [ORM-对象关系映射](#orm)
    - [PDF-PDF](#pdf)
    - [Performance analysis-性能分析](#performance-analysis)
    - [Platform-平台](#platform)
    - [Reactive libraries-响应式](#reactive-libraries)
    - [REST Frameworks-REST框架](#rest-frameworks)
    - [Search-搜索](#search)
    - [Security-安全](#security)
    - [Serialization-序列化](#serialization)
    - [Server-服务器](#server)
    - [Template Engine-模板引擎](#template-engine)
    - [Testing-测试](#testing)
    - [Utility-工具](#utility)
    - [Web Crawling-web爬虫](#web-crawling)
    - [Web Frameworks-web开发框架](#web-frameworks)
    - [Version Managers-版本管理](#version-managers)
- [Resources-资源](#resources)
    - [Awesome Lists-杂项列表](#awesome-lists)
    - [Communities-社区](#communities)
    - [Influential Books-书籍](#influential-books)
    - [Websites-网站](#websites)

- - -

## Bean Mapping-Bean映射

*bean映射相关的框架.*

* [Dozer](https://github.com/DozerMapper/dozer/) - Mapper that copies data from one object to another using annotations and API or XML configuration.
* [MapStruct](https://github.com/mapstruct/mapstruct) - Code generator that simplifies mappings between different bean types, based on a convention-over-configuration approach.

## Build-构建

*build构建工具*


* [Apache Maven](http://maven.apache.org/) - java标准构建工具
* [Gradle](http://gradle.org/) -基于Groovy取代xml的构建工具

## Bytecode Manipulation-字节码操作

*编程操作字节码.*

* [ASM](http://asm.ow2.org/) - All-purpose, low-level bytecode manipulation and analysis.
* [Byte Buddy](http://bytebuddy.net/) - Further simplifies bytecode generation with a fluent API.
* [cglib](https://github.com/cglib/cglib) - Bytecode generation library.
* [Javassist](https://jboss-javassist.github.io/javassist/) - Tries to simplify bytecode editing.

## Caching-缓存

*提供缓存的库*

* [Caffeine](https://github.com/ben-manes/caffeine) - High-performance, near-optimal caching library.
* [Ehcache](http://www.ehcache.org/) - Distributed general-purpose cache.
* [Infinispan](http://infinispan.org/) - Highly concurrent key/value datastore used for caching.



## Code Analysis-代码分析

*都是为了保证代码质量*

* [Checkstyle](https://github.com/checkstyle/checkstyle) - Static analysis of coding conventions and standards.
* [Error Prone](https://github.com/google/error-prone) - Catches common programming mistakes as compile-time errors.
* [Infer](https://github.com/facebook/infer) - Modern static analysis tool for verifying the correctness of code.
* [jQAssistant](https://jqassistant.org/) - Static code analysis with Neo4J-based query language.
* [NullAway](https://github.com/uber/NullAway) - Eliminates NullPointerExceptions with low build-time overhead.
* [SonarJava](https://github.com/SonarSource/sonar-java) - Static analyzer for SonarQube & SonarLint.
* [Sourcetrail ![c]](https://www.sourcetrail.com) - Visual source code navigator.

## Code Coverage-代码覆盖率

*测试代码覆盖率*

* [Clover ![c]](https://www.atlassian.com/software/clover/overview) - Relies on source-code instrumentation instead of bytecode instrumentation.
* [JaCoCo](http://eclemma.org/jacoco/) - Framework that enables collection of code coverage metrics, using both offline and runtime bytecode instrumentation.

## Code Generators-代码生成

*代码生成降低重复编码.*

* [Auto](https://github.com/google/auto) - Generates factory, service, and value classes.
* [FreeBuilder](https://github.com/google/FreeBuilder) - Automatically generates the Builder pattern.
* [Immutables](https://immutables.github.io/) - Annotation processors to generate simple, safe and consistent value objects.
* [JavaPoet](https://github.com/square/javapoet) - API to generate source files.
* [JHipster](https://github.com/jhipster/generator-jhipster) - Yeoman source code generator for Spring Boot and AngularJS.
* [Joda-Beans](http://www.joda.org/joda-beans/) - Small framework that adds queryable properties to Java, enhancing JavaBeans.
* [Lombok](https://projectlombok.org/) - Code generator that aims to reduce verbosity.

## Command-line Argument Parsers-命令行解析

*更容易创建命令行工具.*

* [Airline](https://github.com/airlift/airline) - Annotation-based framework for parsing Git-like command-line arguments.
* [JCommander](http://jcommander.org/) - Command-line argument-parsing framework with custom types and validation via implementing interfaces.
* [picocli](http://picocli.info/) - ANSI colors and styles in usage help. Can be included as source to avoid dependency. Annotation-based, POSIX/GNU/any syntax, subcommands, strong typing for both options and positional args.

## Compiler-compiler-编译器

*创建解释器/编译器*

* [ANTLR](http://www.antlr.org/) - Complex full-featured framework for top-down parsing.
* [JFlex](http://jflex.de/) - A lexical analyzer generator.

## Configuration-配置

*用来抽象外部配置管理.*


* [cfg4j](https://github.com/cfg4j/cfg4j) - Modern configuration library for distributed apps written in Java.
* [config](https://github.com/typesafehub/config) - Configuration library for JVM languages.
* [owner](https://github.com/lviggiano/owner) - Reduces boilerplate of properties.


## CSV-CSV

*简化写入读取CSV.*

* [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) - Jackson extension for reading and writing CSV.
* [Super CSV](https://super-csv.github.io/super-csv/) - Powerful CSV parser with support for Dozer, Joda-Time and Java 8.
* [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers) - One of the fastest and most feature-complete parsers. Also comes with parsers for TSV and fixed-width records.

## Database-数据库

*简化数据库操作.*

* [Apache Phoenix](https://phoenix.apache.org/) - High-performance relational database layer over HBase for low-latency applications.
* [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) - Efficient, in-memory (opt. persisted to disk), off-heap key-value store.
* [FlexyPool](https://github.com/vladmihalcea/flexy-pool) - Brings metrics and failover strategies to the most common connection pooling solutions.
* [Flyway](https://flywaydb.org/) - Simple database migration tool.
* [H2](https://h2database.com/) - Small SQL database notable for its in-memory functionality.
* [HikariCP](https://github.com/brettwooldridge/HikariCP) - High-performance JDBC connection pool.
* [JDBI](http://jdbi.org/) - Convenient abstraction of JDBC.
* [Jedis](https://github.com/xetorthio/jedis) - Small client for interaction with Redis, with methods for commands.
* [Jest](https://github.com/searchbox-io/Jest) - Client for the Elasticsearch REST API.
* [jetcd](https://github.com/justinsb/jetcd) - Client library for etcd.
* [jOOQ](https://www.jooq.org/) - Generates typesafe code based on SQL schema.
* [Liquibase](http://www.liquibase.org/) - Database-independent library for tracking, managing and applying database schema changes.
* [MapDB](http://www.mapdb.org/) - Embedded database engine that provides concurrent collections backed on disk or in off-heap memory.
* [OrientDB](https://orientdb.com/orientdb/) - Embeddable distributed database written on top of Hazelcast.
* [Presto](https://github.com/prestodb/presto) - Distributed SQL query engine for big data.
* [Realm](https://github.com/realm/realm-java) - Mobile database to run directly inside phones, tablets or wearables.
* [Redisson](https://github.com/mrniko/redisson) - Allows for distributed and scalable data structures on top of a Redis server.
* [Xodus](https://jetbrains.github.io/xodus/) - Highly concurrent transactional schema-less and ACID-compliant embedded database.

## Data Structures-数据结构

*高效率数据结构*

* [Apache Avro](https://avro.apache.org/) - Data interchange format with dynamic typing, untagged data, and absence of manually assigned IDs.
* [Apache Orc](https://orc.apache.org/) - Fast and efficient columnar storage format for Hadoop-based workloads.
* [Apache Parquet](https://parquet.apache.org/) - Columnar storage format based on assembly algorithms from Google's paper on Dremel.
* [Apache Thrift](https://thrift.apache.org/) - Data interchange format that originated at Facebook.
* [Protobuf](https://github.com/google/protobuf) - Google's data interchange format.
* [Tape](https://github.com/square/tape) - A lightning-fast, transactional, file-based FIFO.
* [Wire](https://github.com/square/wire) - Clean, lightweight protocol buffers.

## Date and Time-日期和时间

*操作日期和时间*

* [iCal4j](https://github.com/ical4j/ical4j) - Parse and build iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) data models.
* [Time4J](https://github.com/MenoData/Time4J) - Advanced date and time library.

## Dependency Injection-依赖注入

*便于实现控制反转IOC*

* [Dagger2](https://google.github.io/dagger/) - Compile-time injection framework without reflection.
* [Governator](https://github.com/Netflix/governator) - Extensions and utilities that enhance Google Guice.
* [Guice](https://github.com/google/guice) - Lightweight and opinionated framework that completes Dagger.

## Development-开发

*开发相关的东东*

* [AspectJ](https://eclipse.org/aspectj/) - Seamless aspect-oriented programming extension.
* [DCEVM](https://dcevm.github.io/) - JVM modification that allows unlimited redefinition of loaded classes at runtime.
* [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) - Unlimited runtime class and resource redefinition.
* [JavaParser](https://github.com/javaparser/javaparser) - Parse, modify and generate Java code.
* [JRebel ![c]](https://zeroturnaround.com/software/jrebel/) - Instantly reloads code and configuration changes without redeploys.

## Distributed Applications-分布式应用

*一些分布式应用框架.*

* [Apache Geode](https://geode.apache.org/) - In-memory data management system that provides reliable asynchronous event notifications and guaranteed message delivery.
* [Apache Storm](https://storm.apache.org/) - Realtime computation system.
* [Apache ZooKeeper](https://zookeeper.apache.org/) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.
* [Atomix](http://atomix.io/atomix/) - Fault-tolerant distributed coordination framework.
* [Axon Framework](http://www.axonframework.org/) - Framework for creating CQRS applications.
* [Failsafe](https://github.com/jhalterman/failsafe) - Simple failure handling with retries and circuit breakers.
* [Hazelcast ![c]](https://hazelcast.org/) - Highly scalable in-memory datagrid with a free open-source version.
* [Hystrix](https://github.com/Netflix/Hystrix) - Provides latency and fault tolerance.
* [JGroups](http://www.jgroups.org/) - Toolkit for reliable messaging and cluster creation.
* [Orbit](http://www.orbit.cloud/) - Virtual actors; adds another level of abstraction to traditional actors.
* [Quasar](https://www.paralleluniverse.co/quasar/) - Lightweight threads and actors for the JVM.
* [resilience4j](https://github.com/resilience4j/resilience4j) - Functional fault tolerance library.
* [Zuul](https://github.com/Netflix/zuul) - A gateway service that provides dynamic routing, monitoring, resiliency, security, and more.

## Distributed Transactions-分布式事务

*分布式事务*

* [Atomikos](https://www.atomikos.com) - Provides transactions for REST, SOA and microservices with support for JTA and XA.
* [Bitronix](https://github.com/bitronix/btm) - A simple but complete implementation of the JTA 1.1 API.
* [Narayana](http://narayana.io) - Provides support for traditional ACID and compensation transactions, also complies with JTA, JTS and other standards.

## Distribution-发布

*发布打包*

* [Capsule](http://www.capsule.io/) - Simple and powerful packaging and deployment. A fat JAR on steroids, or a "Docker for Java" that supports JVM-optimized containers.
* [Central Repository](https://search.maven.org/) - Largest binary component repository available as a free service to the open-source community. Default used by Apache Maven, and available in all other build tools.
* [IzPack](http://izpack.org/) - Setup authoring tool for cross-platform deployments.
* [Nexus ![c]](https://www.sonatype.com/nexus/solution-overview) - Binary management with proxy and caching capabilities.
* [packr](https://github.com/libgdx/packr/) - Packs JARs, assets and the JVM for native distribution on Windows, Linux and Mac OS X.

## Document Processing-文档处理

*处理office文档*

* [Apache POI](https://poi.apache.org/) - Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).
* [documents4j](http://documents4j.com) - API for document format conversion using third-party converters such as MS Word.
* [docx4j](https://www.docx4java.org/trac/docx4j) - Create and manipulate Microsoft Open XML files.


## Functional Programming-函数式编程

*函数式编程*

* [cyclops-react](https://github.com/aol/cyclops-react) - Monad and stream utilities, comprehensions, pattern matching, functional extensions for all JDK collections, future streams, trampolines and much more.
* [Fugue](https://bitbucket.org/atlassian/fugue) - Functional extensions to Guava.
* [Functional Java](http://www.functionaljava.org) - Implements numerous basic and advanced programming abstractions that assist composition-oriented development.
* [jOOλ](https://github.com/jOOQ/jOOL) - Extension to Java 8 that aims to fix gaps in lambda by providing numerous missing types and a rich set of sequential Stream API additions.
* [StreamEx](https://github.com/amaembo/streamex) - Enhances Java 8 Streams.
* [Vavr](http://www.vavr.io/) - Functional component library that provides persistent data types and functional control structures.


## Geospatial-地理坐标

*操作地理位置坐标*

* [Apache SIS](https://sis.apache.org/) - Library for developing geospatial applications.
* [Geotoolkit.org](http://www.geotoolkit.org/) - Library for developing geospatial applications. Built on top of the Apache SIS project.
* [GeoTools](http://geotools.org/) - Library that provides tools for geospatial data.
* [GraphHopper](https://github.com/graphhopper/graphhopper) - Road-routing engine. Used as a Java library or standalone web service.
* [H2GIS](http://www.h2gis.org/) - A spatial extension of the H2 database.



## High Performance-高性能

*高性能相关的操作和类库.*

* [Agrona](https://github.com/real-logic/Agrona) - Data structures and utility methods that are common in high-performance applications.
* [Disruptor](https://lmax-exchange.github.io/disruptor/) - Inter-thread messaging library.
* [Eclipse Collections](https://github.com/eclipse/eclipse-collections) - Collections framework inspired by Smalltalk.
* [fastutil](http://fastutil.di.unimi.it/) - Fast and compact type-specific collections.
* [HPPC](https://labs.carrotsearch.com/hppc.html) - Primitive collections.
* [JCTools](https://github.com/JCTools/JCTools) - Concurrency tools currently missing from the JDK.
* [Koloboke](https://github.com/OpenHFT/Koloboke) - Hash sets and hash maps.

## HTTP Clients-HTTP客户端

*HTTP相关操作*

* [Async Http Client](https://github.com/AsyncHttpClient/async-http-client) - Asynchronous HTTP and WebSocket client library.
* [Feign](https://github.com/Netflix/feign) - HTTP client binder inspired by Retrofit, JAXRS-2.0, and WebSocket.
* [OkHttp](https://square.github.io/okhttp/) - HTTP+SPDY client.
* [Ribbon](https://github.com/Netflix/ribbon) - Client-side IPC library that is battle-tested in cloud.


## IDE-IDE相关

*集成开发工具.*

* [Eclipse](http://www.eclipse.org/) - 开源集成开发环境.
* [IntelliJ IDEA](http://www.jetbrains.com/idea/) -支持很多JVM语言的IDE，有社区版本和商业版本.
* [NetBeans](https://netbeans.org/) - JAVA SE和JAVA EE的开发环境.

## Imagery-图片

*操作图片*

* [Imgscalr](https://github.com/thebuzzmedia/imgscalr) - Simple, efficient and hardware-accelerated image-scaling library implemented in pure Java 2D.
* [Thumbnailator](https://github.com/coobird/thumbnailator) - High-quality thumbnail generation library.
* [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) - Collection of plugins that extend the number of supported image file formats.
* [ZXing](https://github.com/zxing/zxing) - Multi-format 1D/2D barcode image processing library.

## JSON-JSON

*序列化/反序列化JSON/JAVA OBJ.*

* [Genson](https://owlike.github.io/genson/) - Powerful and easy-to-use Java-to-JSON conversion library.
* [Gson](https://github.com/google/gson) - Serializes objects to JSON and vice versa. Good performance with on-the-fly usage.
* [HikariJSON](https://github.com/brettwooldridge/HikariJSON) - High-performance JSON parser, 2x faster than Jackson.
* [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8) - Set of Jackson modules for Java 8 datatypes and features.
* [Jackson](https://github.com/FasterXML/jackson) - Similar to GSON, but offers performance gains if you need to instantiate the library more often.
* [jsoniter](http://jsoniter.com) - Fast and flexible library with iterator and lazy parsing API.
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare) - JSON parsing and serializing library based on Jackson's streaming API. Outperforms GSON & Jackson's library.
* [Moshi](https://github.com/square/moshi) - Modern JSON library, less opinionated and uses built-in types like List and Map.

## JSON Processing-处理JSON

*解析JSON格式*

* [fastjson](https://github.com/alibaba/fastjson) - Very fast processor with no additional dependencies and full data binding.
* [JsonPath](https://github.com/jayway/JsonPath) - Extract data from JSON using XPATH-like syntax.

## JVM and JDK-JAVA和JDK

*JVM和JDK的实现*

* [Avian](https://github.com/ReadyTalk/avian) - JVM with both JIT and AOT modes. Includes an iOS port.
* [OpenJ9](https://github.com/eclipse/openj9) - High performance, enterprise calibre, flexibly licensed, openly governed cross platform Java Virtual Machine extending and augmenting the runtime technology components from the Eclipse OMR and OpenJDK project.
* [OpenJDK](http://openjdk.java.net/) - Open-source implementation for Linux.
* [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) - VM with non-blocking, concurrent GC for iOS.

## Logging-日志

*日志相关*

* [Apache Log4j 2](https://logging.apache.org/log4j/) - Complete rewrite with a powerful plugin and configuration architecture.
* [Kibana](https://www.elastic.co/products/kibana) - Analyzes and visualizes log files. Some features require payment.
* [Logback](https://logback.qos.ch/) - Robust logging library with interesting configuration options via Groovy.
* [Logstash](https://www.elastic.co/products/logstash) - Tool for managing log files.
* [SLF4J](https://www.slf4j.org/) - Abstraction layer/simple logging facade.

## Machine Learning-机器学习

*机器学习*

* [Apache Flink](https://flink.apache.org/) - Fast, reliable, large-scale data processing engine.
* [Apache Mahout](https://mahout.apache.org/) - Scalable algorithms focused on collaborative filtering, clustering and classification.
* [Apache Spark](https://spark.apache.org/) - Data analytics cluster-computing framework.
* [DatumBox](http://www.datumbox.com) - Provides several algorithms and pre-trained models for natural language processing.
* [Deeplearning4j](https://deeplearning4j.org/) - Distributed and multi-threaded deep learning library.
* [H2O](https://www.h2o.ai/) - Analytics engine for statistics over big data.
* [Oryx 2](https://github.com/OryxProject/oryx) - Framework for building real-time, large-scale machine learning applications. Includes end-to-end applications for collaborative filtering, classification, regression, and clustering.
* [Weka](https://www.cs.waikato.ac.nz/ml/weka/) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization.

## Messaging-消息

*事件消息.*

* [Aeron](https://github.com/real-logic/Aeron) - Efficient, reliable, unicast and multicast message transport.
* [Apache ActiveMQ](https://activemq.apache.org/) - Message broker that implements JMS and converts synchronous to asynchronous communication.
* [Apache Camel](https://camel.apache.org/) - Glues together different transport APIs via Enterprise Integration Patterns.
* [Apache Kafka](https://kafka.apache.org/) - High-throughput distributed messaging system.
* [Hermes](http://hermes.allegro.tech) - Fast and reliable message broker built on top of Kafka.
* [Nakadi](https://github.com/zalando/nakadi) - Provides a RESTful API on top of Kafka.
* [RabbitMQ](https://www.rabbitmq.com/) - RabbitMQ is the most widely deployed open source message broker.

## Miscellaneous-杂项

*查漏补缺*

* [CQEngine](https://github.com/npgall/cqengine) - Ultra-fast, SQL-like queries on Java collections.
* [Design Patterns](https://github.com/iluwatar/java-design-patterns) - Implementation and explanation of the most common design patterns.
* [Failsafe](https://github.com/jhalterman/failsafe) - Simple failure handling with retries and circuit breakers.
* [JBake](http://jbake.org) - Static website generator.
* [JBot](https://github.com/ramswaroop/jbot) - Framework for building chatbots.
* [Jimfs](https://github.com/google/jimfs) - In-memory file system.
* [Joda-Money](http://www.joda.org/joda-money/) - Basic currency and money classes and algorithms not provided by the JDK.
* [LightAdmin](http://lightadmin.org/) - Pluggable CRUD UI library for rapid application development.
* [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial) - Popular Java 8 guide.
* [Modernizer](https://github.com/andrewgaul/modernizer-maven-plugin) - Detect uses of legacy Java APIs.
* [OpenRefine](http://openrefine.org/) - Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
* [Polyglot for Maven](https://github.com/takari/polyglot-maven/) - Extensions for Maven 3.3.1+ that allows writing the POM model in dialects other than XML.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Browser extension which allows to navigate through code on GitHub more efficiently.

## Microservice-微服务

*管理微服务*

* [Apollo](https://spotify.github.io/apollo/) - Libraries for writing composable microservices.
* [consul-api](https://github.com/Ecwid/consul-api) - Client for the [Consul](https://www.consul.io/) API: a distributed, highly available and datacenter-aware registry/discovery service.
* [Eureka](https://github.com/Netflix/eureka) - REST-based service registry for resilient load balancing and failover.

## Monitoring-监控

*在生产环境下监控java*


* [Glowroot](https://glowroot.org/) - Open-source Java APM.
* [inspectIT](http://www.inspectit.rocks) - Captures detailed run-time information via hooks that can be changed on the fly. It supports tracing over multiple systems via the OpenTracing API and can correlate the data with end user monitoring.
* [JavaMelody](https://github.com/javamelody/javamelody) - Performance monitoring and profiling.
* [jmxtrans](https://github.com/jmxtrans/jmxtrans/) - Connect to multiple JVMs and query them for their attributes via JMX. Its query language is based on JSON, which allows non-Java programmers to access the JVM attributes. Supports different output writes, including Graphite, Ganglia, and StatsD.
* [Kamon](http://www.kamon.io/) - Tool for monitoring applications running on the JVM.
* [Metrics](http://metrics.dropwizard.io/) - Expose metrics via JMX or HTTP and send them to a database.
* [Pinpoint](https://github.com/naver/pinpoint) - Open-source APM tool.
* [Prometheus](https://prometheus.io/) - Provides a multi-dimensional data model, DSL, autonomous server nodes and much more.
* [Stagemonitor](https://github.com/stagemonitor/stagemonitor) - Open-source performance monitoring and transaction tracing for JVM apps.




## Networking-网络

*创建网络服务器*

* [Finagle](https://github.com/twitter/finagle) - Extensible RPC system for constructing high-concurrency servers. It implements uniform client and server APIs for several protocols, and is protocol-agnostic to simplify implementation of new protocols.
* [Grizzly](https://javaee.github.io/grizzly) - NIO framework. Used as a network layer in Glassfish.
* [gRPC](https://github.com/grpc/grpc-java) - RPC framework based on protobuf and HTTP/2.
* [MINA](https://mina.apache.org/) - Abstract, event-driven async I/O API for network operations over TCP/IP and UDP/IP via Java NIO.
* [Netty](https://netty.io/) - Framework for building high-performance network applications.
* [Nifty](https://github.com/facebook/nifty) - Implementation of Thrift clients and servers on Netty.
* [Undertow](http://undertow.io/) - Web server providing both blocking and non-blocking APIs based on NIO. Used as a network layer in WildFly.

## ORM-对象关系映射

*ORM持久化*

* [Apache Cayenne](https://cayenne.apache.org/) - Provides a clean, static API for data access. Also includes a GUI Modeler for working with database mappings, and DB reverse engineering and generation.
* [Ebean](https://ebean-orm.github.io/) - Provides simple and fast data access.
* [EclipseLink](https://www.eclipse.org/eclipselink/) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
* [Hibernate](http://hibernate.org/orm/) - Robust and widely used, with an active community.
* [MyBatis](http://www.mybatis.org/mybatis-3/) - Couples objects with stored procedures or SQL statements.


## PDF-PDF

*操作创建PDF*

* [Apache PDFBox](https://pdfbox.apache.org/) - Toolbox for creating and manipulating PDFs.
* [Dynamic Jasper](http://dynamicjasper.com/) - Abstraction layer to JasperReports.
* [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer) - XML/XHTML and CSS 2.1 renderer.
* [iText ![c]](https://itextpdf.com/) - Creates PDF files programmatically.
* [JasperReports](https://community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine.

## Performance analysis-性能分析

*性能分析及调优*

* [honest-profiler](https://github.com/RichardWarburton/honest-profiler) - A low-overhead, bias-free sampling profiler.
* [jHiccup](https://github.com/giltene/jHiccup) - Logs and records platform JVM stalls.
* [JMH](http://openjdk.java.net/projects/code-tools/jmh/) - a Java harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targeting the JVM.
* [JProfiler ![c]](https://www.ej-technologies.com/products/jprofiler/overview.html) - Database profiling for JDBC, JPA and NoSQL, with JEE support.
* [XRebel ![c]](https://zeroturnaround.com/software/xrebel/) - Real-time profiling for web applications, with an in-browser widget.

## Platform-平台

*一站式平台.*

* [Light-Java](https://github.com/networknt/light-java) - A fast, lightweight and productive microservices framework with built-in [security](https://github.com/networknt/light-oauth2).
* [Spring](https://spring.io/projects) - Provides many packages for dependency injection, aspect-oriented programming, security, etc.

## Reactive libraries-响应式

*开发响应式应用*

* [Akka](https://akka.io) - Toolkit and runtime for building concurrent, distributed, fault-tolerant and event-driven applications.
* [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm/) - Provides a standard for asynchronous stream processing with non-blocking backpressure.
* [Reactor](https://projectreactor.io/) - Library for building reactive fast-data applications.
* [vert.x](http://vertx.io/) - Polyglot event-driven application framework.

## REST Frameworks-REST框架

*创建REST服务*

* [Dropwizard](https://dropwizard.github.io/dropwizard/) - Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.
* [Jersey](https://jersey.github.io/) - JAX-RS reference implementation.
* [Microserver](https://github.com/aol/micro-server) — A convenient, extensible microservices plugin system for Spring & Spring Boot. With more than 30 plugins and growing, it supports both micro-monolith and pure microservices styles.
* [rest.li](https://github.com/linkedin/rest.li) - Framework for building robust, scalable RESTful architectures using typesafe bindings and asynchronous, non-blocking IO with an end-to-end developer workflow that promotes clean practices, uniform interface design and consistent data modeling.
* [RESTEasy](https://resteasy.jboss.org/) - Fully certified and portable implementation of the JAX-RS specification.
* [RestExpress](https://github.com/RestExpress/RestExpress) - Thin wrapper on the JBoss Netty HTTP stack that provides scaling and performance.
* [Spark](http://sparkjava.com/) - Sinatra inspired framework.



## Search-搜索

*搜索引擎相关*

* [Apache Lucene](https://lucene.apache.org/) - High-performance, full-featured, cross-platform, text search engine library.
* [Apache Solr](https://lucene.apache.org/solr/) - Enterprise search engine optimized for high-volume traffic.
* [Elasticsearch](https://www.elastic.co/) - Distributed, multitenant-capable, full-text search engine with a RESTful web interface and schema-free JSON documents.

## Security-安全

*Libraries that handle security, authentication, authorization or session management.*

* [Apache Shiro](https://shiro.apache.org/) - Performs authentication, authorization, cryptography and session management.
* [Cryptomator](https://cryptomator.org/) - Multiplatform, transparent, client-side encryption of files in the cloud.
* [jjwt](https://github.com/jwtk/jjwt) - JSON web token for Java and Android.
* [Keycloak](https://keycloak.jboss.org/) - Integrated SSO and IDM for browser apps and RESTful web services.
* [Keywhiz](https://github.com/square/keywhiz) - System for distributing and managing secrets.
* [OACC](http://oaccframework.org/) - Provides permission-based authorization services.
* [pac4j](https://github.com/pac4j/pac4j) - Security engine.
* [PicketLink](http://picketlink.org/) - Umbrella project for security and identity management.
* [Vault](https://www.vaultproject.io/) - Secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets. It handles leasing, key revocation, key rolling, and auditing. Through a unified API, users can access an encrypted Key/Value store and network encryption-as-a-service, or generate AWS IAM/STS credentials, SQL/NoSQL databases, X.509 certificates, SSH credentials, and more.

## Serialization-序列化

*操作序列化*

* [FlatBuffers](https://github.com/google/flatbuffers) - Memory-efficient serialization library that can access serialized data without unpacking and parsing it.
* [FST](https://github.com/RuedigerMoeller/fast-serialization) - JDK-compatible, high-performance object graph serialization.
* [Kryo](https://github.com/EsotericSoftware/kryo) - Fast and efficient object graph serialization framework.

## Server-服务器

*服务器相关*

* [Apache Tomcat](https://tomcat.apache.org/) - Robust, all-round server for Servlet and JSP.
* [Jetty](https://www.eclipse.org/jetty/) - Provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations.
* [nanohttpd](https://github.com/NanoHttpd/nanohttpd) - Tiny, easily embeddable HTTP server.
* [WildFly](http://www.wildfly.org/) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support.

## Template Engine-模板引擎

*模板引擎*

* [Handlebars.java](https://jknack.github.io/handlebars.java/) - Logicless and semantic Mustache templates.
* [Jtwig](http://jtwig.org/) - Modular, configurable and fully tested template engine.
* [Thymeleaf](http://www.thymeleaf.org/) - Aims to be a substitute for JSP and works for XML files.

## Testing-测试

*测试相关*

### Asynchronous-异步服务

*测试异步服务*

* [Awaitility](https://github.com/jayway/awaitility) - DSL for synchronizing asynchronous operations.
* [GreenMail](http://www.icegreen.com/greenmail/) - In-memory email server for integration testing. Supports SMTP, POP3 and IMAP including SSL.
* [REST Assured](https://github.com/jayway/rest-assured) - DSL for easy testing of REST/HTTP services.

### BDD

*BDD*

* [Cucumber](https://github.com/cucumber/cucumber-jvm) - Provides a way to describe features in a plain language which customers can understand.
* [JBehave](http://jbehave.org/) - Extensively configurable framework that describes stories.
* [JGiven](http://jgiven.org) - Provides a fluent API which allows for simpler composition.
* [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave) - Aims to provide a fluent API to write tests in long and descriptive sentences that read like plain English.

### Fixtures-随机数据

*生成随机数据*

* [Fixture Factory](https://github.com/six2six/fixture-factory) - Generates fake objects from a template.
* [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) - JUnit test runner and plugins for running JUnit tests with pseudo-randomness.

### Frameworks-框架

*提供测试框架*

* [ArchUnit](https://github.com/TNG/ArchUnit) - Test library for specifying and asserting architecture rules.
* [Apache JMeter](http://jmeter.apache.org/) - Functional testing and performance measurements.
* [Arquillian](http://arquillian.org/) - Integration and functional testing platform for Java EE containers.
* [Citrus](https://citrusframework.org/) - Integration testing framework that focuses on both client- and server-side messaging.
* [Gatling](https://gatling.io/) - Load testing tool designed for ease of use, maintainability and high performance.
* [JUnit](http://junit.org/) - Common testing framework.
* [Pact JVM](https://github.com/DiUS/pact-jvm/) - Consumer-driven contract testing.
* [PIT](http://pitest.org) - Fast mutation-testing framework for evaluating fault-detection abilities of existing JUnit or TestNG test suites.

### Matchers-匹配

*提供匹配支持.*

* [AssertJ](https://joel-costigliola.github.io/assertj/) - Fluent assertions that improve readability.
* [JSONAssert](http://jsonassert.skyscreamer.org/) - Simplifies testing JSON strings.
* [Truth](https://github.com/google/truth) - Google's assertion and proposition framework.


### Mocking-虚拟

*虚拟相关对象.*


* [Mockito](https://github.com/mockito/mockito) - Mocking framework that lets you write tests with a clean and simple API.
* [MockServer](https://www.mock-server.com/) - Allows mocking of systems integrated with HTTPS.
* [Moco](https://github.com/dreamhead/moco) - Concise web services for stubs and mocks.
* [PowerMock](https://github.com/jayway/powermock) - Mocks static methods, constructors, final classes and methods, private methods, and removal of static initializers.
* [WireMock](http://wiremock.org/) - Stubs and mocks web services.

### Parameterization-参数化

*提供参数化测试方法*

* [Burst](https://github.com/square/burst) - A unit testing library for varying test data.
* [JUnitParams](https://pragmatists.github.io/JUnitParams/) - Creates readable and maintainable parametrised tests.

## Utility-工具

*Libraries which provide general utility functions.*

* [Apache Commons](https://commons.apache.org/) - Provides configuration, validation, collections, file uploading, XML processing and other general-purpose functions.
* [CRaSH](http://www.crashub.org) - Provides a shell into a JVM that's running CRaSH. Used by Spring Boot and others.
* [Dex](https://github.com/PatMartin/Dex) - Java/JavaFX tool capable of powerful ETL and data visualization.
* [Gephi](https://github.com/gephi/gephi/) - Cross-platform for visualizing and manipulating large graph networks.
* [Guava](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and more.
* [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) - Library that helps with constructing difficult regular expressions.
* [Protégé](https://protege.stanford.edu/) - Provides an ontology editor and a framework to build knowledge-based systems.

## Version Managers-版本管理

*配置不同的JDK版本.*

* [jabba](https://github.com/shyiko/jabba) - Java Version Manager inspired by nvm. Supports Mac OS X, Linux and Windows.
* [jenv](https://github.com/gcuisinier/jenv) - Java Version Manager inspired by rbenv. Can configure globally or per project. Tested on Debian and Mac OS X.
* [SDKMan](https://github.com/sdkman/sdkman-cli) - Java Version Manager inspired by RVM and rbenv. Supports UNIX-based platforms and Windows.

## Web Crawling-爬虫

*爬虫.*

* [Apache Nutch](https://nutch.apache.org/) - Highly extensible, highly scalable web crawler for production environments.
* [Crawler4j](https://github.com/yasserg/crawler4j) - Simple and lightweight web crawler.
* [jsoup](https://jsoup.org/) - Scrapes, parses, manipulates and cleans HTML.
* [StormCrawler](http://stormcrawler.net/) - SDK for building low-latency and scalable web crawlers.

## Web Frameworks-Web框架

*Web开发框架.*

* [Apache Tapestry](https://tapestry.apache.org/) - Component-oriented framework for creating dynamic, robust, highly scalable web applications.
* [Apache Wicket](https://wicket.apache.org/) - Component-based web application framework similar to Tapestry, with a stateful GUI.
* [Blade](https://github.com/biezhi/blade) - Lightweight, modular framework that aims to be elegant and simple.
* [Firefly](http://www.fireflysource.com/) - Asynchronous framework for rapid development of high-performance web application.
* [Jooby](http://jooby.org) - Scalable, fast and modular micro-framework that offers multiple programming models.
* [Play](https://www.playframework.com/) - Built on Akka, it provides predictable and minimal resource consumption (CPU, memory, threads) for highly-scalable applications in Java and Scala.
* [Ratpack](https://ratpack.io/) - Set of libraries that facilitate fast, efficient, evolvable and well-tested HTTP applications.
* [Vaadin](https://vaadin.com/home) - Event-driven framework built on top of GWT. Uses server-side architecture with Ajax on the client side.

# Resources-资源


## Communities-社区

*Active discussions.*

* [r/java](https://www.reddit.com/r/java) - Subreddit for the Java community.
* [stackoverflow](https://stackoverflow.com/questions/tagged/java) - Question/answer platform.
* [VirtualJUG](https://virtualjug.com/) - Virtual Java User Group.


## Influential Books-相关书籍

*必读书籍*

* [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
* [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
* [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
* [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
* [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)




## Websites-网站

*网站.*

* [Google Java Style](https://google.github.io/styleguide/javaguide.html)
* [InfoQ](https://www.infoq.com/)
* [Java Algorithms and Clients](https://algs4.cs.princeton.edu/code/)
* [Java, SQL, and jOOQ](https://blog.jooq.org/)
* [Java.net](https://community.oracle.com/community/java)
* [Javalobby](https://dzone.com/java-jdk-development-tutorials-tools-news)
* [JavaWorld](https://www.javaworld.com/)
* [JAXenter](https://jaxenter.com/)
* [RebelLabs](https://zeroturnaround.com/rebellabs/)
* [The Takipi Blog](http://blog.takipi.com/)
* [TheServerSide.com](http://www.theserverside.com/)
* [Vanilla Java](https://vanilla-java.github.io/)
* [Voxxed](https://www.voxxed.com/)
