![GitHub release (latest by date)](https://img.shields.io/github/v/release/gradle-dependency-analyze/gradle-dependency-analyze)
## nemosofts.com

#### 1. Add module dependencies
For example you can add dependencies on the modules like this:

`build.gradle.kts`

```kotlin
implementation("com.github.nemosofts:library:1.X.X")
```

Or in Gradle Groovy DSL `build.gradle`:

```groovy
implementation 'com.github.nemosofts:library:1.X.X'
```
where `1.X.X` is your preferred version. All modules must be the same version.
