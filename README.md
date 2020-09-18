# 自动注册插件

最新版本:[ ![Download](https://api.bintray.com/packages/ooftf/maven/autoregister/images/download.svg) ](https://bintray.com/ooftf/maven/autoregister/_latestVersion)

## 前言

此项目和原AutoRegister相比较要解决的问题是：

* 解决原AutoRegister和kotlin 1.4.0+并不兼容导致的[(This feature requires ASM6)错误](https://github.com/luckybilly/AutoRegister/issues/29)
* 解决原AutoRegister和gson 1.4.0+并不兼容导致的[(Execution failed for task ':app:transformClassesWithAuto-registerForDebug'.)错误](https://github.com/luckybilly/AutoRegister/issues/23)

## 相关文档请参考原AutoRegister

## 使用方式

- 在工程根目录的build.gradle中添加依赖：
```groovy
 repositories {
        maven {
            url "https://dl.bintray.com/ooftf/maven"
        }
    }
buildscript {
    dependencies {
        classpath 'com.android.tools.build:gradle:3.0.0'
        classpath 'com.ooftf:autoregister:x.x.x'
    }
}
```
    

    
