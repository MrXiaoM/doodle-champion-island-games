# Google Champion Island Games

**English** | [简体中文](README.md)

I played this game when it just out, and recorded it with OBS. But I have a bad computer at that time, frame rate is low. Though there is a archive from Google Doodle, but the loading speed in my country... The speed of downloading video is confusing, I was downloading it slowly. I was poor at crawling HTML5 games in the previous, now is better. So I want to crawl the Champion Island Games to local and play it for torture myself in my free time (

Original link：https://www.google.com/logos/2020/kitsune/rc6/kitsune20.html?hl=en

By the way, no matter via [Perma Archive Link](https://doodles.google/doodle/doodle-champion-island-games-begin/) or just search [google 2021 games](https://www.google.com/search?q=google+2021+game), the query parameter after the src link in `iframe` is `?hl=zh`. It is the reason of the archive version have no Chinese language. And also the reason that I want to make this backup.

## Changes

All external resources have save to local, and also some default response of API. And some resources have been moved to specific folder.
+ `https://www.google.com/async/ddllog` -> `./async/ddllog`
+ `https://www.google.com/gen_204` -> `./gen_204` (I have commented the code to request gen_204, but keep the default file in case.)
+ `https://www.gstatic.com/external_hosted/*` -> `./external_hosted/*`
+ `https://storage.googleapis.com/kitsune-scores/scores.json` -> `./kitsune-scores/scores.json`
+ `https://www.google.com/logos/2020/kitsune/rc6/messages-*.json` -> `./messages/messages-*.json` (There are too many files of i10n.)

Other changes below
+ Use Simplified Chinese default. You can change it in the beginning of `kitsune20.html`.
+ Customizable copy share link. You can change it in the beginning of `kitsune20.html`.
+ Offset the video player, to fix the issues that the preload frame not covered the whole video.

## Copyright Notice

The Champion Island Games is copyright by [Google LLC](https://www.google.com/) and [STUDIO4°C](https://www.studio4c.co.jp/). This repository, repository owner and contributers have no affiliation with the copyright owner.
