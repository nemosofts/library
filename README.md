## nemosofts.com
![GitHub release (latest by date)](https://img.shields.io/github/v/release/nemosofts/library)
![Jacoco Result](/.github/badges/jacoco.svg?raw=true&sanitize=true)
![Branch coverage](/.github/badges/branches.svg?raw=true&sanitize=true)
![Java CI](https://github.com/nemosofts/library/workflows/Java%20CI/badge.svg?branch=master)
![GitHub Super-Linter](https://github.com/nemosofts/library/workflows/Lint%20Code%20Base/badge.svg)

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
