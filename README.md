# SupportProject

# 使用注意(高版本Gradle)

* 项目根目录的build.gradle 需要加上apply from: "config.gradle" 引入配置依赖文件config是文件名称
* settings.gradle 中 dependencyResolutionManagement 添加maven { url 'https://jitpack.io' }
* gradle.properties 根目录的gradle配置信息里面需要配置支持AndroidX相关的  
  android.enableJetifier = true和android.useAndroidX=true
* config.gradle 中可以修改配置依赖库中的版本信息

# key信息(高版本Gradle)
https://www.jianshu.com/p/25e9c71fe43e
public and secret key created and signed.

pub   ed25519 2022-06-14 [SC] [expires: 2024-06-13]
041BB3CA1D5C649B365945D5AF8C5A3399A96C37
uid                      ww <wangweitikou1994@gmail.com>
sub   cv25519 2022-06-14 [E] [expires: 2024-06-13]

public and secret key created and signed.

pub   rsa3072 2022-06-14 [SC]
9BAD4509CC70AD18DD612B9A318CEC64682F6672
uid                      tikou <wangweitikou1994@gmail.com>
sub   rsa3072 2022-06-14 [E]

