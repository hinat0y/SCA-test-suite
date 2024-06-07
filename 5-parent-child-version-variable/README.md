# Ground truth
## Direct dependencies and associated CVEs
| Dependency | CVE |
| --- | --- |
| axis-1.4 |  CVE-2023-40743, CVE-2019-0227, CVE-2018-8032, CVE-2012-5784, CVE-2014-3596, CVE-2007-2353 |
| clojure-1.11.1 | CVE-2024-22871 |
| commons-beanutils-1.8.3 | CVE-2024-22871 |
| clojure-1.11.1 | CVE-2014-0114, CVE-2019-10086 |
| commons-collections-3.2 | CVE-2015-6420 |
| commons-io-2.4 | CVE-2021-29425 |
| fastjson-1.2.22 | CVE-2017-18349, CVE-2022-25845 |
| gson-2.8.6 | CVE-2022-25647 |
| guava-24.1.1-jre | CVE-2023-2976, CVE-2020-8908 |
| h2-2.0.204 | CVE-2021-42392, CVE-2022-23221, CVE-2022-45868, CVE-2018-14335 |
| httpclient-4.5.11 | CVE-2020-13956 |
| jackson-databind-2.13.1 | CVE-2020-36518, CVE-2022-42003, CVE-2022-42004, CVE-2023-35116 |
| json-20200518 | CVE-2022-45688, CVE-2023-5072 |
| junit-4.12 | CVE-2020-15250 |
| kotlin-stdlib-0.6.22 | CVE-2019-10101, CVE-2019-10102, CVE-2019-10103, CVE-2020-29582, CVE-2022-24329 |
| log4j-core-2.17.0 | CVE-2021-44832 |
| logback-classic-1.1.11 | CVE-2017-5929, CVE-2023-6378, CVE-2021-42550 |
| logback-core-1.3.5 | CVE-2023-6378 |
| mysql-connector-java-8.0.11 | CVE-2018-3258, CVE-2023-22102, CVE-2022-21363, CVE-2019-2692, CVE-2021-2471, CVE-2020-2934, CVE-2020-2875 |
| okhttp-3.1.0 | CVE-2021-0341, CVE-2016-2402, CVE-2018-20200, CVE-2023-0833 |
| protobuf-java-3.21.5 | CVE-2022-3171, CVE-2022-3509, CVE-2022-3510 |
| retrofit-2.3.0 | CVE-2018-1000850 |
| scala-library-2.13.0 | CVE-2022-36944 |
| spring-beans-5.3.4 | CVE-2022-22965, CVE-2021-22118, CVE-2023-20860, CVE-2022-22950, CVE-2022-22971, CVE-2023-20861, CVE-2023-20863, CVE-2022-22968, CVE-2022-22970, CVE-2021-22060, CVE-2021-22096 |
| spring-boot-autoconfigure-3.0.3 | CVE-2023-20873, CVE-2023-20883, CVE-2023-34055 |
| spring-boot-starter-web-2.6.0 | CVE-2023-20873, CVE-2023-20883, CVE-2023-22602 |
| spring-context-5.3.12 | CVE-2022-22965, CVE-2023-20860, CVE-2022-22950, CVE-2022-22971, CVE-2023-20861, CVE-2023-20863, CVE-2022-22968, CVE-2022-22970, CVE-2021-22060 |
| spring-core-6.0.3 | CVE-2023-20860, CVE-2023-34053, CVE-2024-22233, CVE-2023-20861, CVE-2023-20863 |
| spring-web-6.1.3 | CVE-2024-22243, CVE-2024-22262 |
| spring-webmvc-6.0.10 | CVE-2023-34053 |
| testng-7.4.0.jar | CVE-2022-4065 |

## Direct and transitive dependencies
| Direct | Transitive |
| --- | --- |
| axis-1.4 | spec.alpha-0.3.218, org.specs.alpha-0.2.62 |
| clojure-1.11.1 |  |
| commons-beanutils-1.8.3 |  |
| clojure-1.11.1 |  |
| commons-collections-3.2 |  |
| commons-io-2.4 |  |
| fastjson-1.2.22 |  |
| gson-2.8.6 |  |
| guava-24.1.1-jre | jsr305-1.3.9, error_prone_annotations-2.1.3, j2objc-annotations-1.1, checker-compat-qual-2.0.0, animal-sniffer-annotations-1.14 |
| h2-2.0.204 |  |
| httpclient-4.5.11 | commons-codec-1.11, commons-logging-1.2, httpcore-4.4.13 |
| jackson-databind-2.13.1 | jackson-annotations-2.13.1, jackson-core-2.13.1 |
| json-20200518 |  |
| junit-4.12 | hamcrest-core-1.3 |
| kotlin-stdlib-0.6.22 | kotlin-runtime-0.6.22 |
| log4j-core-2.17.0 | log4j-api-2.17.0 |
| logback-classic-1.1.11 | slf4j-api-1.7.22 |
| logback-core-1.3.5 |  |
| mysql-connector-java-8.0.11 |  |
| okhttp-3.1.0 | okio-1.6.0 |
| protobuf-java-3.21.5 |  |
| retrofit-2.3.0 |  |
| scala-library-2.13.0 |  |
| spring-beans-5.3.4 |  |
| spring-boot-autoconfigure-3.0.3 | spring-boot-3.0.3 |
| spring-boot-starter-web-2.6.0 | spring-boot-starter-2.6.0, spring-boot-starter-json-2.6.0, spring-boot-starter-tomcat-2.6.0, spring-boot-starter-logging-2.6.0, snakeyaml-1.29, jakarta.annotation-api-1.3.5, jackson-datatype-jdk8-2.13.0, jackson-datatype-jsr310-2.13.0, jackson-module-parameter-names-2.13.0, tomcat-embed-core-9.0.55, tomcat-embed-el-9.0.55, tomcat-embed-websocket-9.0.55, log4j-to-slf4j-2.14.1, jul-to-slf4j-1.7.32 |
| spring-context-5.3.12 | spring-aop-5.3.12, spring-expression-5.3.12 |
| spring-core-6.0.3 | spring-jcl-6.0.3 |
| spring-web-6.1.3 | micrometer-observation-1.12.2, micrometer-commons-1.12.2 |
| spring-webmvc-6.0.10 |  |
| testng-7.4.0.jar | jcommander-1.78, jquery-3.5.1 |
