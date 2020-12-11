# umeng_sdk
友盟官方统计的sdk，原来采用本地集成，为了便于维护，将依赖修改为远程获取，并且上传至github

###修改：
1. 将原项目的本地依赖改为远程依赖
2. 修复安卓端统计无效问题
3. 升级项目依赖到官方最新，common：9.3.2

### 使用
pubspec.yaml依赖
```
  umeng_sdk:
    git:
      url: git://github.com/ZXQ-Kyle/umeng_sdk.git
      ref: master
```


