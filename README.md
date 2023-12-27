## 介绍
青桔API-公益性质的接口快速响应，qq昵称获取、指定IPv4/IPv6地址信息查询、客户端IPv4/IPv6地址查询，优先支持IPv6地址查询、一言、提取图片主题色、天气指定地区查询、米游社随机头像
## API接口列表
- https://api.qjqq.cn/api/district?ip=2408:820c:681b:5ad0:585f:2fc:346a:4bb4 (指定IPv4/IPv6地址信息查询)
- https://api.qjqq.cn/api/Img（默认）
- - https://api.qjqq.cn/api/Img?sort=acg (动漫)
- - https://api.qjqq.cn/api/Img?sort=belle (小姐姐)
- - https://api.qjqq.cn/api/Img?sort=scenery (风景)
- - https://api.qjqq.cn/api/Img?sort=bd_acg (白底动漫)
- - https://api.qjqq.cn/api/Img?sort=acg&random=691 (随机数接口示例，添加不同的随机数来实现)
- https://api.qjqq.cn/api/Imgcolor?img=URL (用于获取图片的主题色)
- https://api.qjqq.cn/api/Local (客户端IP信息查询，支持IPv4/IPv6，优先查询IPv6)
- https://api.qjqq.cn/api/MiYouShe
- - https://api.qjqq.cn/api/MiYouShe?stor=大别野 (米游社默认头像)
- - https://api.qjqq.cn/api/MiYouShe?stor=绝区零
- https://api.qjqq.cn/api/qqinfo?qq=1645253 (QQ昵称获取)
- https://api.qjqq.cn/api/Weather?city_name=上海 (天气指定地区查询)
- https://api.qjqq.cn/api/Yi （从7种分类中随机抽取）
- - https://api.qjqq.cn/api/Yi?c=b （请求获得一个分类是漫画的句子）
- - https://api.qjqq.cn/api/Yi?c=f&encode=text （请求获得一个来自网络的句子，并以纯文本格式输出））
- - https://api.qjqq.cn/api/Yi?c=f&encode=json （请求获得一个来自网络的句子，并以json格式输出）
