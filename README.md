# Google 冠军岛运动会 小游戏合集

[English](README-en.md) | **简体中文**

我在四年前这个小游戏刚出的时候就去玩了，还录屏了，但是因为电脑太差，帧数极低。虽然 Google Doodle 有归档，但是就国内这个速度吧，下载 CG 速度因人而异，反正我下载很慢。之前我还不太会爬 HTML5 游戏，现在会得更多一点了，于是想要把冠军岛运动会给爬下来保存到本地，以便日后没事做折磨自己（

原地址：https://www.google.com/logos/2020/kitsune/rc6/kitsune20.html?hl=zh-CN

顺便一提，不管是通过[永久归档链接](https://doodles.google/doodle/doodle-champion-island-games-begin/)，还是搜索 [google 2021 games](https://www.google.com/search?q=google+2021+game)，在它们的 iframe 内嵌的页面地址，参数是 `?hl=zh`，这是归档版本没有中文语言的重要原因，也是我想制作这个备份的一个原因。

## 变更

所有来自外部的资源全部保存到本地，也包括了一些接口的缺省返回结果。部分资源移动到了特定的文件夹。
+ `https://www.google.com/async/ddllog` -> `./async/ddllog`
+ `https://www.google.com/gen_204` -> `./gen_204` (我注释掉了请求 gen_204 的代码，以防万一还是留一个缺省文件)
+ `https://www.gstatic.com/external_hosted/*` -> `./external_hosted/*`
+ `https://storage.googleapis.com/kitsune-scores/scores.json` -> `./kitsune-scores/scores.json`
+ `https://www.google.com/logos/2020/kitsune/rc6/messages-*.json` -> `./messages/messages-*.json` (本地化文件太多了)

以下是其它变更
+ 默认使用简体中文语言，在 `kitsune20.html` 开头可以更改默认语言
+ 可自定义复制的分享链接，在 `kitsune20.html` 开头可以更改
+ 对视频播放器进行一点点偏移，修正边框没有完全包裹视频的问题

## 版权声明

《冠军岛运动会》由 [Google LLC](https://www.google.com/) 和 [STUDIO4°C](https://www.studio4c.co.jp/) 版权所有。本仓库、仓库主以及贡献者，与版权所有者无从属关系。
