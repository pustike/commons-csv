Apache Commons CSV   [![][Maven Central img]][Maven Central] [![][Javadocs img]][Javadocs] [![][license img]][license]
==================
This library is a fork of the [Apache Commons CSV](https://github.com/apache/commons-csv).

Additionally, it has following changes:
* Added ```module-info.java``` and requires Java 11.
* Replace Assertions notNull() usage with Objects requireNonNull()
* Remove dependency on java.sql module and remove unnecessary boxing

**Documentation:** Latest javadocs is available [here](https://pustike.github.io/commons-csv/docs/api/).

Download
--------
To add a dependency using Maven, use the following:
```xml
<dependency>
    <groupId>io.github.pustike</groupId>
    <artifactId>commons-csv</artifactId>
    <version>1.6.0</version>
</dependency>
```
To add a dependency using Gradle:
```
dependencies {
    compile 'io.github.pustike:commons-csv:1.6.0'
}
```
Or, download the [latest JAR](https://search.maven.org/remote_content?g=io.github.pustike&a=commons-csv&v=LATEST)

License
-------
This library is published under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

[Maven Central]:https://maven-badges.herokuapp.com/maven-central/io.github.pustike/commons-csv
[Maven Central img]:https://maven-badges.herokuapp.com/maven-central/io.github.pustike/commons-csv/badge.svg

[Javadocs]:https://javadoc.io/doc/io.github.pustike/commons-csv
[Javadocs img]:https://javadoc.io/badge/io.github.pustike/commons-csv.svg

[license]:LICENSE
[license img]:https://img.shields.io/badge/license-Apache%202-blue.svg
