# CDN

CDN 内容分发网络 本意在于尽可能避开互联网上有可能影响数据传输速度和稳定性的瓶颈和环节，使内容传输的更快、更稳定。

主要目的:

- 解决因分布、带宽、服务器性能带来的访问延迟问题，适用于站点加速、点播、直播等场景。
- 使用户可就近取得所需内容，解决 Internet 网络拥挤的状况，提高用户访问网站的响应速度和成功率。

## 题外话

腾讯云的 cdn 收到 post 请求回源, 不知道别家是不是这样(试了不会吃牢饭 8️⃣). 攻击者可以通过大量 post 请求 cc 攻击到源机器或者 cos 源, 我超. [三角洲 cdn 被攻击]

## 加强版

边缘云计算: 加强版的 cdn, 参考腾讯云 edgeone.
