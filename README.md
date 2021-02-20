# 中国地质大学（北京）-北地战疫-每日健康打卡

该代码为PHP源码，主要内容为模拟登录和每日健康打卡的模拟请求。

需在源码中填写以下信息：

1. 账号
2. 密码
3. 位置经度
4. 位置纬度
5. 位置名称

该代码使用了以下类库：

```sh
composer require guzzlehttp/guzzle
```

请注意，请勿短时间内多次模拟登录，否则账号将会被冻结，冻结大概一天后账号将恢复正常。（别问我怎么知道的）