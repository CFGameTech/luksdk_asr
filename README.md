# LUKSDK ASR功能版接入指南

本文为LUKSDK ASR功能版集成指南文档，主要包括安卓端和iOS端
（语音识别功能使用微软的语音识别库）

## 一、快速集成：

### 1.0、将SDK导入到工程中

可以只把项目中的luksdk文件夹下载下来，导入到工程中

### Android:
*    把cfg_lib_v1.8.2.1.aar拷贝到工程app/libs目录下
*    参考: [第一步：集成 LUKSDK](https://wiki.luk.live/docs/quick-start/client?env=android) 添加其他的依赖文件以及设置相关配置
*     还需要再build.gradle的dependencies中添加依赖implementation 'com.microsoft.cognitiveservices.speech:client-sdk:1.42.0'

    
### iOS:
*    找到 CFGameSDK.xcframework和MicrosoftCognitiveServicesSpeech.xcframework文件，并将它们拷贝到您的工程的 app 目录下。
*    在Project -> General栏目下找到Framework，Libraries,and Embedded Content分类找到上面提到的两个库，将Embed属性改为 Embed & Sign
*    参考: [第一步：集成 LUKSDK](https://wiki.luk.live/docs/quick-start/client?env=ios) 添加其他的依赖文件以及设置相关配置


## 二、主要业务流程：

可以参考SDK文档：[语音识别功能](https://wiki.luk.live/docs/client-api/sdk_asr)


