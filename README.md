# AsGradleUpdate
Android Studio gradle update(帮助你免翻墙更新gradle，避免升级卡死问题)

## Gradle 版本

Version|Url
---|---
3.3|`http\://ome2s08jl.bkt.clouddn.com/gradle-3.3-all.zip`
2.14.1|`http\://ome2s08jl.bkt.clouddn.com/gradle-2.14.1-all.zip.zip`

## 配置教程

1、找到并打开 `gradle-wrapper.properties` 文件

```
$Project > gradle > wrapper > gradle-wrapper.properties
```
2、替换 `gradle-wrapper.properties` 中的 `distributionUrl` 为 上面列出的Gradle 版本对应版本的url，如
```
$old ==> distributionUrl=https\://services.gradle.org/distributions/gradle-3.3-all.zip
$new ==> distributionUrl=http://ome2s08jl.bkt.clouddn.com/gradle-3.3-all.zip
```
![old](https://github.com/yy1300326388/AsGradleUpdate/blob/master/image/gradle_url_simple.png)
![old](https://github.com/yy1300326388/AsGradleUpdate/blob/master/image/gradle_url_simple2.png)

