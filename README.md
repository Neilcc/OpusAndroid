# OpusAndroid

Opus Android NDK Build Script
Opus Android 依赖库编译脚本 mk libopus.so libopus.a

### Tested in [opus-1.2.1](http://opus-codec.org/release/stable/2017/06/26/libopus-1_2_1.html)

## How to use

#### 1 Download [Opus Source Code](http://opus-codec.org/downloads/) and unzip it.

#### 2 Add this to opus root directory.

#### 3 Run this with

```
ndk-build NDK_APPLICATION_MK=Application.mk NDK_PROJECT_PATH=.
```
Out put is at ./obj/local

Current build is static library. Change it to shared library by modifying Android.mk

### Causion
Add ndk-build to your $PATH


