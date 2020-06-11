# sample_library

build.gradle(app)

```
dependencies {
    implementation 'tech.landland.util_kit:util_view:0.0.1'
}

repositories {
    maven { url 'http://raw.github.com/m-saeki0926/sample_library/master/' }
}
```

# command

```
./gradlew assembleRelease
```

```
tree app/build/outputs
```

```
./gradlew uploadArchives
```

```
tree repository
```
