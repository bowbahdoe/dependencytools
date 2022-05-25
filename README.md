# Getting Started

1. Download jar from [here](https://jitpack.io/dev/mccue/dependencytools/main-dae6dbf08a-1/dependencytools-main-dae6dbf08a-1.jar)
2. Add jar to classpath when building code
```java
DependencyResolver.usingMavenCentral()
        .build()
        .path();
```

