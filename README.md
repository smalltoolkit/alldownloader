# AllDownloader / 全能下载器

**One app for everything: WeChat articles & videos, Douyin, Bilibili, Xiaohongshu, Kuaishou, Haokan**

一个软件搞定微信文章 & 视频号、抖音、B站、小红书、快手、好看视频下载

---

## ✨ Features / 功能

### 📄 WeChat Article Export / 微信文章导出

| PDF | JPG | HTML | Word (DOCX) |
|-----|-----|------|------------|
| TXT | EPUB | Markdown | Excel (XLSX) |


### 🎬 Video Download / 视频下载

微信视频号 · 抖音 · 哔哩哔哩 · 小红书 · 快手 · 好看视频
WeChat Channels · Douyin · Bilibili · Xiaohongshu · Kuaishou · Haokan

---

## 💡 Highlights / 特点

###  8 formats, great for e-book reading & research / 8种文字格式，方便电子书阅读或研究分析

###  Smart Link Parsing, WYSIWYG / 智能链接清洗，所见即所得

###  Multi-Language / 多语言（简体中文 / 繁體中文 / English）

###   No watermarks, multiple resolutions available / 无水印，多种清晰度

---

## 📥 Download / 下载

### Official Site：https://wechatdl.com/downloads

### GitHub Releases: https://github.com/smalltoolkit/alldownloader/releases

---

## 🛠️ Install / 安装

The app is **not code-signed** — a security warning on first launch is normal, **not a virus**.
应用**未做代码签名**，首次启动的系统拦截属正常保护，**不是病毒**。

### macOS

**First install / 首次安装：**

```bash
hdiutil attach -noverify ~/Downloads/AllDownloader-macOS.dmg   # 1. Mount / 挂载
cp -R "/Volumes/AllDownloader 4/AllDownloader.app" /Applications/   # 2. Copy to Applications / 复制到应用程序
xattr -cr /Applications/AllDownloader.app && open /Applications/AllDownloader.app   # 3. Allow & open / 放行并打开
```

> 挂载点带数字后缀（如 `AllDownloader 4`）时，请使用带后缀的路径。

**Update / 更新：** delete the old app first, then install. License, settings and downloads are kept — nothing is lost.
**更新：** 先删除旧版再安装。授权、设置、已下载文件都保留，不会丢失。

```bash
killall AllDownloader 2>/dev/null
rm -rf /Applications/AllDownloader.app
hdiutil attach -noverify ~/Downloads/AllDownloader-macOS.dmg
cp -R "/Volumes/AllDownloader 4/AllDownloader.app" /Applications/
xattr -cr /Applications/AllDownloader.app
open /Applications/AllDownloader.app
```

> 必须先删除旧版再复制——直接覆盖会残留旧文件导致混合版本。数据都在用户目录，删除旧 app 不影响。

### Windows / Linux

| Platform / 平台 | What to do / 操作 |
|---|---|
| Windows | 安装后直接运行 / Run directly after installation |
| Linux | `chmod +x AllDownloader` then run / 赋执行权限后运行 |

---

## ⚠️ Disclaimer / 免责声明

下载内容版权归原作者所有，仅供个人学习、研究、欣赏使用，请勿商用或二次传播。
Downloaded content belongs to its original authors. For personal study and research only — no redistribution or commercial use without permission.

---

## 📬 Contact / 联系

🌐 https://wechatdl.com · 📧 app@wechatdl.com
