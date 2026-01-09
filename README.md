# ffdec-lib Maven Repository

This repository is structured as a **static Maven repository** and can be used directly in Maven or Gradle builds.

## Maven Coordinates

- **groupId:** `com.jpexs`
- **artifactId:** `ffdec-lib`
- **version:** `24.1.1`

---

## Maven (pom.xml)

Add the repository:

```xml
<repositories>
  <repository>
    <id>ffdec-github</id>
    <url>https://raw.githubusercontent.com/Quackster/ffdec-lib/master/lib</url>
  </repository>
</repositories>
```

Add the dependency:

```xml
<dependency>
  <groupId>com.jpexs</groupId>
  <artifactId>ffdec-lib</artifactId>
  <version>24.1.1</version>
</dependency>
```

## Gradle

```groovy
repositories {
  maven { url "https://raw.githubusercontent.com/Quackster/ffdec-lib/master/lib" }
}

dependencies {
  implementation "com.jpexs:ffdec-lib:24.1.1"
}
```
