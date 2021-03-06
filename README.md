!> `api.bzqll.com` 此域名由于不知名网友在微信使用 API,导致微信认为诱导分享 :angry: 目前在微信已经被封禁，仅做保留，5 月底将停止该域名访问，如果使用此域名请尽快更换新的域名 `api.itooi.cn`,`api.itooi.cn`已经不再更新,请使用新版 API,新版请往下看.

## 新版特性

1. 相对更加稳定,服务器不再过滤参数内容,用户自行解析参数,减少参数解析出错几率
2. 支持平台：网易云音乐,QQ 音乐,酷狗音乐,酷我音乐,咪咕音乐，百度音乐，具体音乐音质支持往下看
3. 接口更加丰富,增加部分接口和平台
4. 参数控制数据是否格式化,数据更加简洁(format 字段)
5. 降低门槛,参数简单统一,支持 GET,POST 等请求,支持跨域调用
6. 支持输出格式化后的数据

!> 由于空闲时间较少，文档中的实例纯属复制粘贴出来的，很多都不能用，可能有很多错误的信息，请求直接在文档项目提[issue](https://github.com/mrdong916/mess-api-doc/issues)

> 音乐平台音质： 未注明则为官方不支持或未找到该音质资源,`免费版不支持无损音乐`,付费版本请加群了解

| 支持平台 | 普通(48) | 标准(96) | 标准（128） | 较高（192） | 极高（320）    | 无损（ape） | 无损（flac）   |
| -------- | -------- | -------- | ----------- | ----------- | -------------- | ----------- | -------------- |
| 网易     |          |          | 支持        | 支持        | 支持           |             | 支持           |
| Q Q      | 支持     | 支持     | 支持        | 支持        | 支持           | 支持        | 支持           |
| 酷狗     |          |          | 支持        |             | 付费音乐不支持 |             | 付费音乐不支持 |
| 酷我     | 支持     |          | 支持        | 支持        | 支持           | 支持        | 支持           |
| 咪咕     |          |          | 支持        | 支持        | 支持           |             | 支持           |
| 百度     |          |          | 支持        |             | 支持           |             |                |

!> 捐赠说明：免费的东西不长久，请自觉捐赠，无论金额大小，捐赠请往下滑

1. 天下没有免费午餐,不喜欢和认为不好用请左转右拐
2. 没有任何利益也就没有动力去更新,失效很快,因为抓取数据的平台也在更新
3. 服务器也需要花钱,请求量比你想象中的要大的多,目前日请求量上 100+W
4. 开发这个东西耗费了大量的时间,更何况想要更好用也要付出很多时间和精力,技术付费不是很应该吗?
5. 捐赠可以不是金钱,福利什么的都 OK,只是图个开心,当然金钱我更开心

## 当前版本

MessAPI V1.0.6

> 2019.05.27 更新内容

-   新增百度音乐平台
-   修复分页导致获取数据不正确
-   新增百度音乐，修复错误信息

更多更新日志，请前往 [更新日志](changeLog.md) 查看

## 请求说明

以下所有接口请求域名为 `v1.itooi.cn`,为了降低使用门槛，所有请求为`GET`请求,你也可以试用其他请求方式

注意: 请求头中 `Content-type` 为 `application/x-www-form-urlencoded`

请求地址 = 域名 + 接口地址 + 参数

域名：`https://v1.itooi.cn`

接口地址：`netease/song`

参数：`id=37239038`

示例： `https://v1.itooi.cn/netease/song?id=37239038`

## 支持平台

-   网易云音乐 http://music.163.com
-   QQ 音乐 http://y.qq.com
-   酷狗音乐 http://www.kugou.com
-   酷我音乐 http://www.kuwo.cn
-   咪咕音乐 http://www.migu.cn
-   百度音乐 http://music.taihe.com/

## 联系方式

-   QQ 群 ①：579621905（技术探讨）
-   QQ 群 ②：261097396（群友交流）
-   邮箱： mrdong916@163.com
-   Github： http://github.com/mrdong916
-   Telegram: https://t.me/joinchat/L0YKYkTRL-EGMpC7rTshgg

## 关于项目

目前没有打算开源的想法，不过有个旧版的开源项目，右上角项目地址可以访问到旧版 API [MessMusic](http://github.com/MessMusic)，如果真的想要源码，带着你的诚意来找群主！

## 捐赠

图片若不显示请点击这里 [二维码](https://i.loli.net/2019/04/26/5cc2a151aebe2.png)

[![pay.png](https://i.loli.net/2019/04/26/5cc2a151aebe2.png)](https://i.loli.net/2019/04/26/5cc2a151aebe2.png)

## 免责声明

1. 以上开发接口仅限于技术研究和项目开发练习使用，禁止商业用途，如有发现直接禁 IP 和域名
2. 音乐版权归各音乐平台所有，若有侵犯版权，请联系我删除
