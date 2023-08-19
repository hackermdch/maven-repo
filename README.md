# maven-repo

My personal maven repository.

## Usage

Gradle

```gradle
    repositories {
        maven { url = "https://raw.githubusercontent.com/hackermdch/maven-repo/master/repository" }
    }
```

Maven:

```xml
    <repositories>
        <repository>
            <id>hackermdch-maven-repo</id>
            <url>https://raw.githubusercontent.com/hackermdch/maven-repo/master/repository</url>
        </repository>
    </repositories>
```
