---
# ⚠️ 已停用（draft）—— 原因：/friends/ 友情链接：与职业形象无关
#
# 这个页面已从导航摘除，且因 published: false 不再生成到 public/。
# 旧 URL 会 404，这没问题：它本来就不是给 HR / 面试官看的入口。
#
# 恢复方法：把下面的 published 改成 true，并在
# themes/hexo-theme-stun/_config.yml 的 menu / submenu 里加回对应入口。
# 注意 menu 的 key 名要和 i18n（source/_data/languages/zh-CN.yml）里的
# menu.<key> 对应，否则导航会显示成英文 key 本身。

title: 友情链接
date: 2021-09-08 13:16:02
published: false
---


## 友链列表（排名不分先后）

{% friends _data/friends.json %}
## 如何申请友链

> 想要添加友链，可以评论处贴出你的信息~ 💖

请先添加本站链接后，在下方 评论留言 或 QQ（点击直接聊天） 联系我添加友链。
（友链既可以交友、学习，也可以用于SEO【搜索引擎优化】 ）

> 最好直接提供json 格式，例如:

```json
{
    "avatar": "https://cdn.jsdelivr.net/cjh0613/blog/CJHicon.jpg",
    "name": "未读消息",
    "introduction": "世上本没有路",
    "url": "https://adymilk.github.io/"
}

```

