# BaiduYunTransfer
 百度云分享链接转存

## 优点

基于OAuth2.0，接口很稳定，不必担心web接口经常发生变化，也无需担心输入验证码、cookie过期等问题。

## 如何使用

| key        | value            |
| ---------- | ---------------- |
| api_key    | 应用id           |
| secret_key | 应用secret       |
| share_link | 分享链接         |
| password   | 分享链接的提取码 |
| dir        | 转存路径         |

api_key和secret_key可以直接使用我程序里写好的，但是出于安全和QPS的考量，我推荐你自己再去申请一个，可以参考<https://pan.baidu.com/union/document/entrance#%E7%AE%80%E4%BB%8B>。

修改好以上几项后直接运行，第一次运行时需要你按照程序提示对应用进行授权。

## TODO

refresh token