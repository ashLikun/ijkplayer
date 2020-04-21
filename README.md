[![Release](https://jitpack.io/v/ashLikun/ijkplayer.svg)](https://jitpack.io/#ashLikun/ijkplayer)


ijkplayer项目简介
        ijkplayer 的编译库so文件   可以选择播放Https的视频
## 使用方法

build.gradle文件中添加:

```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
并且:

```gradle
dependencies {
    //so文件
    implementation 'com.github.ashLikun.ijkplayer:lib_lite:{latest version}'//最小库
    implementation 'com.github.ashLikun.ijkplayer:lib_lite_https:{latest version}'//最小库 带https的

    implementation 'com.github.ashLikun.ijkplayer:lib_lite_hevc:{latest version}'//最小库（带hevc）
    implementation 'com.github.ashLikun.ijkplayer:lib_lite_hevc_https:{latest version}'//最小库（带hevc）带https的

    implementation 'com.github.ashLikun.ijkplayer:lib_default:{latest version}'//最大库（支持格式多）
    implementation 'com.github.ashLikun.ijkplayer:lib_default_https:{latest version}'//最大库（支持格式多）带https的
}
```


