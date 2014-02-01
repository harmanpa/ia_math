ia_math
=======

Mavenised fork of Java interval arithmetic library by Tim Hickey

To use from Maven, add the following to pom.xml:

```
    <repositories>
        <repository>
            <id>ia_math-mvn-repo</id>
            <url>https://raw.github.com/harmanpa/ia_math/mvn-repo/</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>
```

and

```
    <dependency>
            <groupId>net.sourceforge.interval</groupId>
            <artifactId>ia_math</artifactId>
            <version>1.0-SNAPSHOT</version>
    </dependency>
```
