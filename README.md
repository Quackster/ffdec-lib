# ffdec-lib Maven Repository

This repository is structured as a **static Maven repository** and can be used directly in Maven or Gradle builds.

It allows [JPEXS](https://github.com/jindrapetrik/jpexs-decompiler) to be used as a library for projects.

All files are from: https://github.com/jindrapetrik/jpexs-decompiler/releases

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
      <id>ffdec</id>
      <url>https://github.com/Quackster/ffdec-lib/raw/master/lib</url>
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
  maven { url "https://github.com/Quackster/ffdec-lib/raw/master/lib" }
}

dependencies {
  implementation "com.jpexs:ffdec-lib:24.1.1"
}
```
