# AsGradleUpdate
Android Studio gradle update(帮助你免翻墙更新gradle，避免升级卡死问题)

## Gradle 版本

Version|Url
---|---
3.3|`http\://7xqba8.com1.z0.glb.clouddn.com/gradle-3.3-all.zip`

## 配置教程

1、找到并打开 `gradle-wrapper.properties` 文件

```
$Project > gradle > wrapper > gradle-wrapper.properties
```
2、替换 `gradle-wrapper.properties` 中的 `distributionUrl` 为 上面列出的Gradle 版本对应版本的url，如
```
$old ==> distributionUrl=https\://services.gradle.org/distributions/gradle-3.3-all.zip
$new ==> distributionUrl=http\://7xqba8.com1.z0.glb.clouddn.com/gradle-3.3-all.zip
```


