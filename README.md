# kwon37xi's Maven2 Repository

## Gradle
```groovy
repositories {
    maven {
        url 'https://raw.github.com/kwon37xi/m2repos/master/releases'
    }
}
```
## Maven
```xml
<repositories>
    <repository>
        <id>kwon37xi-github-m2-repos</id>
        <url>https://raw.github.com/kwon37xi/m2repos/master/releases</url>
    </repository>
</repositories>
```

## Sonatype Nexus
If you want to proxy this repository with [Sonatype Nexus](http://www.sonatype.org/nexus/), then,

* "Remote Repository Access > Download Remote Indexes" : false
* "Remote Repository Access > Auto blocking active" : false
* then refresh,
* "Repository Status" will be changed to "Attempting to Proxy and Remote Unavailable".
