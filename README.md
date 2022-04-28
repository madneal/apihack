# apihack

## 微信公众号

必要参数：

* APPID
* APPSECRET

```
curl https://api.weixin.qq.com/cgi-bin/token?grant_type=client_credential&appid={APPID}&secret={APPSECRET}
```

## 企业微信

必要参数：

* corpid
* corpsecret

```
curl https://qyapi.weixin.qq.com/cgi-bin/gettoken?corpid={corpid}&corpsecret={corpsecret}
```
