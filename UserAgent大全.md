# UserAgent大全

## 支付宝APP
>支付宝app下user-agent
### Android
`Mozilla/5.0 (Linux; U; Android 10; zh-CN; YAL-AL00 Build/HUAWEIYAL-AL00) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/69.0.3497.100 UWS/3.21.0.73 Mobile Safari/537.36 UCBS/3.21.0.73_191223133912 NebulaSDK/1.8.100112 Nebula AlipayDefined(nt:WIFI,ws:360|0|3.0) AliApp(AP/10.1.85.7000) AlipayClient/10.1.85.7000 Language/zh-Hans useStatusBar/true isConcaveScreen/true Region/CN`
### IOS
`Mozilla/5.0 (iPhone; CPU iPhone OS 13_3 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/17C54 NebulaSDK/1.8.100112 Nebula WK PSDType(1) AlipayDefined(nt:WIFI,ws:414|832|3.0) AliApp(AP/10.1.85.6000) AlipayClient/10.1.85.6000 Language/zh-Hans Region/CN`
### 如何判断是否为支付宝
[const matchResult = window.navigator.userAgent.match(/AliApp\(AP\/([\d\.]+)\)/i)](https://docs.open.alipay.com/20181012100420932508/quickstart)
以上只是个
