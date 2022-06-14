# SupportProject

# 使用注意(高版本Gradle)

* 项目根目录的build.gradle 需要加上apply from: "config.gradle" 引入配置依赖文件config是文件名称
* settings.gradle 中 dependencyResolutionManagement 添加maven { url 'https://jitpack.io' }
* gradle.properties 根目录的gradle配置信息里面需要配置支持AndroidX相关的  
  android.enableJetifier = true和android.useAndroidX=true
* config.gradle 中可以修改配置依赖库中的版本信息
