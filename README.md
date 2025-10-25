# [友情链接](https://blog.chriskyo08.moe/friends/)

## 友链交换须知

1. 友链友链，先友才能后链。
2. 原则上只接受博客类型的友链申请。
3. 网站的域名是很重要的，如果你的域名是免费域名的话就请不要来申请友链啦。
   - 免费域名 **包括但不限于** 下述定义：
     - 由 Freenom 公司运营的免费域名后缀，如 `.ml`、`.tk`。
     - 其他不包含在 Public Suffix List 中的 **免费子域名** 服务。
     - 由于下述免费子域名服务拒绝提交至 Public Suffix List，根据第二条的定义将会被拒绝：`oschina.io`、`gitee.io`、`coding.me`、`coding.io`、`coding-pages.com`。
   - 免费域名 **不包括** 下述定义：
     - 向 Freenom 公司付费购买的 `.ml`、`.tk` 等域名
     - 其他任何包含于 [Public Suffix List](https://publicsuffix.org/list/) 的免费子域名服务，如 `github.io`，`gitlab.io`，`now.sh` 等。
4. 原创很重要！博客可以长草，但不要滥竽充数，没有实质性内容的博客是不受欢迎的哦~
5. 会正确使用 Git 和 GitHub 。
6. 最终解释权归 chriskyo08 所有。

## 友链交换流程

1. 先添加本站的友链。
   - 名称
     - `Chriskyo08`
   - URL
     - `https://blog.chriskyo08.moe`
   - Logo
     - Favicon
       - [`256x256`, ico](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/favicon/favicon.ico)
     - 头像（推荐）
       - [`96x96`, png](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/avatar-round/96x96-round.png)
       - [`128x128`, png](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/avatar-round/128x128-round.png)
       - [`144x144`, png](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/avatar-round/144x144-round.png)
       - [`192x192`, png](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/avatar-round/192x192-round.png)
       - [`256x256`, png](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/avatar-round/256x256-round.png)
       - [`512x512`, png](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/avatar-round/512x512-round.png)
       - [`1024x1024`, png](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/avatar-round/1024x1024-round.png)
       - 更多大小及格式请 [点此](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/avatar-round/) 查看，另有 [方形版本](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/avatar-square/)。
     - [Banner](https://cdn.jsdelivr.net/gh/Chriskyo08/Chriskyo08@main/banner/banner.png)
     - 如果你的友链页面没有放 Logo 或 Banner 的地方就可以不用放了哦~
   - Slogan
     - 简体中文：`看见未见的脉络，连接孤立的光点。`
     - English: `The hidden order, the lights interwoven.`
2. 准备一个自己站点的 Logo。
   - Logo 的外形应为正方形或圆形
   - 长度与宽度应小于 **`512px`**、大于等于 **`100px`**，以 `128px` 为佳
   - 使用常见文件格式，如 **`png`（推荐）**、`jpg`、`svg` 等（不包括 `tiff`、`icns`）
   - 文件大小应小于 **512 KiB** ，以 256 KiB 以内为佳
   - Logo 应符合 Gravater **G 分级** 要求（即适合在任何网站上展示给任何年龄段的任何人）
3. 准备一个 Banner
   - 长宽比以 **`4:1`** 为佳
   - 长度不应小于 **100px**
   - 使用常见文件格式，如 **`png`（推荐）**、`jpg`、`svg` 等（不包括 `tiff`、`icns`）
   - 文件大小应小于 **1024 KiB** ，以 512 KiB 以内为佳
4. 准备需要展示的名称，长度应小于 20 个半角字符或 10 个全角字符，否则在展示时可能会被截断。
   - 站点名称应适合在任何网站上展示给任何年龄段的任何人
5. （可选）准备一条 Slogan，长度建议小于 60 个半角字符或 30 个全角字符，否则在展示时可能会被截断。
   - Slogan 应适合在任何网站上展示给任何年龄段的任何人
6. 在 GitHub 上 Fork 这个仓库。
7. 在 `avatar` 下提交 Logo 文件，在 `banner` 下提交 Banner 文件。
   - 文件名格式为 `[domain].[format]`，如 `example.com.png`，`blog.example.com.jpg`
   - Commit 的标题应为 `Add: [filename] ( [url] )`，如 `Add: example.com.png ( https://example.com )`
8. 修改 `friends.yml` 文件。
   - 按照如下格式将你的网站信息添加到 `links.yml` 文件的末尾：
     ```yml
     - name: "Friend Name" #名称，请使用双引号包裹
       link: https://example.com # 网站链接
       avatar: https://cdn.jsdelivr.net/gh/Chriskyo08/Friends@main/avatar/example.com.png # Logo 的文件路径
       slogan: "Slogan" # Slogan，请使用双引号包裹
       banner: https://cdn.jsdelivr.net/gh/Chriskyo08/Friends@main/banner/example.com.png # Banner 的文件路径
     ```
   - Commit 的标题应为 `Add: [sitename] ( [url] )`，如 `Add: example blog ( https://example.com )`
9.  完成上述步骤后，请新建一个 Pull Request。
   
   - Pull Request 标题应为 `Add: [sitename] ( [url] )`，如 `Add: example blog ( https://example.com )`
10. 当你发起的 Pull Request 被 Review 并被通过、合并后，你的网站将会在 CDN 缓存更新后显示在 [友链页面](https://blog.chriskyo08.moe/friends/)。

---

<sub>本仓库灵感来源于 <a href="https://github.com/renbaoshuo/Friends">renbaohuo/Friends</a> ，在此表示感谢。</sub><br>
<sub>&copy; 2025 Chriskyo08. All rights reserved.</sub>
