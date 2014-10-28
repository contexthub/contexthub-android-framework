contexthub-android-framework
============================

Android Framework for ContextHub http://app.contexthub.com

## Download

Gradle

```groovy
repositories {
    jcenter()
    maven { url "https://raw.github.com/contexthub/contexthub-android-framework/master" }
}

dependencies {
    compile 'com.chaione:contexthub:1.+'
}
```

Maven

```xml
<dependency>
  <groupId>com.chaione</groupId>
  <artifactId>contexthub</artifactId>
  <version>LATEST</version>
</dependency>
```

## Register

```java
public class MyContextHubApp extends Application {

    @Override
    public void onCreate() {
        super.onCreate();

        // Register with ContextHub
        ContextHub.init(this, "YOUR-APP-ID-HERE");
    }
}
```

## Documentation

http://docs.contexthub.com/contexthub-android-framework/

##Support

If you have questions, bugs, or feature requests, please open an issue with us.  We are working hard to make this framework great and would love to hear from you.

https://github.com/contexthub/contexthub-android-framework/issues
