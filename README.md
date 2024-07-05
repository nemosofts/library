## Nemosofts UI Library
![GitHub release (latest by date)](https://img.shields.io/github/v/release/nemosofts/library)
<a href="https://github.com/nemosofts/library">
    <img src="https://komarev.com/ghpvc/?username=nemosofts&style=flat&color=red">
</a>

`ColorUtils`
`BlurImage`
`CustomImageView`
`CustomCheckBox`
`CustomProgressBar`
`CustomSwitchButton`

#### 1. Add module dependencies
For example you can add dependencies on the modules like this:
`build.gradle.kts`


```kotlin
implementation("com.github.nemosofts:library:2.X.X")
```

Or in Gradle Groovy DSL `build.gradle`:

```groovy
implementation 'com.github.nemosofts:library:2.X.X'
```
where `2.X.X` is your preferred version. All modules must be the same version.

https://nemosofts.com


`ColorUtils`
xml
```xml
android:background="?ns_body"
android:textColor="?ns_title"

?ns_body
?ns_body_sub
?ns_body_dark

?ns_primary
?ns_primary_sub

?ns_border

?ns_title
?ns_title_sub

?ns_black
?ns_white
```

java
```java

ColorUtils.colorWhite(this)
ColorUtils.colorBlack(this)

ColorUtils.colorPrimary(this)
ColorUtils.colorPrimarySub(this)

ColorUtils.colorTitle(this)
ColorUtils.colorTitleSub(this)

ColorUtils.colorBody(this)
ColorUtils.colorBodySub(this)

ColorUtils.colorBorder(this)

```



