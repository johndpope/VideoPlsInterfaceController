# VideoPlsInterfaceContronller
###1.7.2
1. 修复直播发通知未接收到的bug

###1.7.1
1. 修复直播platformID未设置成功的bug

###1.5.0
1. 新增对外曝光通用接口 vp_interfaceActionNotify 详见 VPinterfaceStatusNotifyDelegate.h
2. 添加webP支持,设置appKey参数接口变成 setAppKey:platformID:useWebP: ,如果对接使用了Pod的SDWebImage/webP, 则可以将useWebP置为YES,减少加载图片的流量开销
3. 平台层已移除公用Pod库,dependency中包含AFNetworking~>3.0, SDWebImage~>4.0


###1.4.0
1. 移除对接层对外暴露点播枚举参数


###1.3.6
1. 对接层项目初始化