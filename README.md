# shadowrocket-ad

Shadowrocket 定向去广告模块，统一维护 `AD.sgmodule`。

## 远程模块地址

```
https://raw.githubusercontent.com/TURBOzxt/shadowrocket-ad/main/AD.sgmodule
```

在小火箭的模块页面通过 URL 添加该模块。若已启用同名本地模块，请替换为远程模块，避免重复加载。

启用模块、重写和 HTTPS 解密，并沿用设备上已经安装且受信任的证书。模块以追加方式声明 MITM 主机。

## 更新方式

维护任务核对上游实际规则和相关提交，仅在存在有效变化、检查通过后发布新版本；无变化时不重复提交。

GitHub 发布与手机获取更新是两个步骤。小火箭需通过上述远程模块地址获取新版，可使用客户端提供的模块自动更新功能或手动更新。

## 维护范围

重点覆盖淘宝、闲鱼开屏及异步预加载，保留高德地图、B站、智行火车票、百度网盘、贴吧、斗鱼等已有规则。实机效果仍需验证。

本仓库只发布去广告模块，不存放主配置、节点凭据或证书。

## 规则来源

保留模块内的来源注释，主要参考 fmz200/wool_scripts、Thelongdarkorg/loon-plugins、QingRex/LoonKissSurge、ddgksf2013、app2smile/rules 和 Biliverse/ADBlock 等维护源。

