# Grails plugins 

## json-api

### Edit BuildConfig.groovy

```groovy
grails.project.dependency.resolution = {
    repositories {
        ...
        mavenRepo "https://github.com/mathpere/mvn-repo/raw/master/releases"
        ...
    }
    
    plugins {
        compile ":json-api:0.1"
    }
}
```

