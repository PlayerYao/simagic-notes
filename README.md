# SIMAGIC 模拟赛车技术资料

速魔基座接口、DIY 踏板与固件型号配置的中文资料集。

## 文章

| 内容 | 阅读入口 | 来源 |
| --- | --- | --- |
| Alpha EVO 接口、快拆与硬件资料 | [中文译文](translations/simracing/Hardware/Simagic.md) | [Linx-ESP / Simracing-thoughts-and-docs](https://github.com/Linx-ESP/Simracing-thoughts-and-docs/blob/main/Hardware/Simagic.md) |
| P2000 控制盒连接 DIY 踏板 | [中文译文](translations/p2000/P2000.zh-CN.md) · [英文正文](translations/p2000/P2000-original.en.md) | [DIY-SIM / StuyoADM](https://www.diy-sim.com/guides/how-to/item/universal-lc-pedal-controller-simagic-p2000-control-box) |
| Alpha EVO Sport 型号解锁 | [技术文章](articles/alpha-evo-sport-unlock.md) | 本地固件研究与实验记录的脱敏整理 |

## 其他仓库译文

- [原仓库介绍与目录](translations/simracing/README.md)
- [SimHub MQTT](translations/simracing/Software/SimHub/mqtt.md)
- [Playnite 设置与启动脚本](translations/simracing/Software/Playnite/readme.md)
- [用户样式表](translations/simracing/Software/user-stylesheets.md)

## 目录

```text
articles/                       原创整理文章
translations/simracing/          GitHub 仓库中文译文与许可
translations/simracing/assets/   11 张正文图片及许可徽章
translations/p2000/             P2000 博客中英文 Markdown、网页源文件
translations/p2000/assets/      9 张博客图片
LICENSES.md                     各部分来源与许可
```

正文图片均已保存在仓库内，通过相对路径引用；下载整个仓库后可离线阅读。图片保留原貌，未改动接线方向或针脚标注。交互式 3D 模型、视频及其他外部参考链接仍需联网。

两份 `assets-sources.json` 分别记录图片的原始地址、字节数和 SHA-256；其中 `file` 相对于该清单所在目录。博客的 `source.html` 用于保留网页源文，不是包含全站样式和脚本的离线网页包。

翻译依据上游快照 `f003bf0c9a5d14e2aab1551820480b41df22c000`，整理日期为 2026-10-25。原文的推测、未验证项和代码示例保留；原文错误或歧义以译注说明。解锁文章已去除设备标识、密钥和完整通信报文。

本仓库各部分许可不同，详见 [来源与许可](LICENSES.md)。
