

![01.png](img/01.png)

```groovy
plugins {
    id 'java'
    id 'org.springframework.boot' version '3.1.2'
}

apply plugin: 'io.spring.dependency-management'

group = 'com.cashwu'
version = '1.0-SNAPSHOT'

repositories {
    mavenCentral()
}

dependencies {
    implementation 'org.springframework.boot:spring-boot-starter-web'
}
```

![02.png](img/02.png)