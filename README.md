# 陀螺竞技场

四个分别标有 TYL、JDG、EDG、XLG 的陀螺，支持旋转、自动抽打、相互碰撞、手动挥鞭、暂停和力度调节。

纯静态网页，无需后端或登录。字体与音效随站点一起提供，运行时不请求 Google Fonts 或其他第三方 CDN。

## 操作

- 点击竞技场：抽打最近的陀螺。
- 点击“全部抽打”或按空格：给四个陀螺加速。
- 按 P 或点击暂停：暂停或继续。
- 点击音效开关：启用击杀音效，默认关闭。

## 部署

GitHub Pages 从 main 分支根目录提供网站，`.nojekyll` 禁用 Jekyll 处理。也可以将本目录的 `index.html`、`audio/` 和 `fonts/` 上传到任意静态网站托管平台。

## 素材来源

- 击杀音效来源与说明见 [audio/SOURCES.txt](audio/SOURCES.txt)。游戏音效权利归其相应权利人所有；本项目与 Riot Games 无隶属关系。
- Barlow Condensed 字体来自 [Google Fonts](https://github.com/google/fonts/tree/main/ofl/barlowcondensed)，许可证见 [fonts/OFL.txt](fonts/OFL.txt)。

GitHub Pages 公网发布不代表已验证中国大陆各地区、各运营商的网络可达性。
