# AO3 汉化插件

一个简单的用户脚本，旨在中文化 [Archive of Our Own](https://archiveofourown.org/) 界面，集成了 AI 翻译功能，让你的阅读体验更加流畅。

## ✨ 主要功能

- **界面汉化**
  - 对 AO3 网站的导航、按钮、表单、提示信息等进行本地化处理。
- **可配置项**
  - 可按需启用 AI 翻译功能。
  - 支持自定义 AI 翻译术语表，确保人名、地名等专有名词翻译准确。

## 🔧 安装

1. 在浏览器中安装一个用户脚本管理器，推荐使用 [Tampermonkey](https://www.tampermonkey.net/) 。
2. 开启浏览器 `管理扩展程序` 中的 `开发者模式` 。
3. 点击 `篡改猴` -> `详情` -> `允许运行用户脚本` 。
4. 选择一个版本进行安装：
   - 主用
     - [远程版](https://raw.githubusercontent.com/V-Lipset/ao3-chinese/main/main.user.js)
     - [本地版](https://raw.githubusercontent.com/V-Lipset/ao3-chinese/main/local.user.js)
   - 备用
     - [远程版](https://cdn.jsdelivr.net/gh/V-Lipset/ao3-chinese@main/main.user.js)
     - [本地版](https://cdn.jsdelivr.net/gh/V-Lipset/ao3-chinese@main/local.user.js)

## 📖 使用说明

- 安装脚本后，访问/刷新 [AO3 网站](https://archiveofourown.org/) ，界面将自动变为中文。
- 如需使用翻译功能，请点击 `悬浮球` 或者 `Tampermonkey 图标` -> `AO3 汉化插件` -> `打开设置面板` -> `启用翻译功能`。在作品页面，你会看到新增的 `翻译简介` 、`翻译注释` 、`翻译正文` 等按钮，点击即可使用。
- 教程相关：
  - [常见问题](https://v-lipset.github.io/docs/support/faq)
  - [翻译服务介绍](https://v-lipset.github.io/docs/support/service)
  - [在镜像站点上使用](https://v-lipset.github.io/docs/guides/mirror)
  - [添加接口地址域名白名单](https://v-lipset.github.io/docs/guides/whitelist)
- 术语表相关：
  - [在线术语库](https://github.com/V-Lipset/ao3-chinese/wiki/%E5%9C%A8%E7%BA%BF%E6%9C%AF%E8%AF%AD%E8%A1%A8)
  - [术语表编写指南](https://v-lipset.github.io/docs/guides/glossary/write)
  - [分享你的术语表](https://v-lipset.github.io/docs/guides/glossary/share)
  - [创建在线术语表-桌面端](https://v-lipset.github.io/docs/guides/glossary/create)
  - [创建在线术语表-移动端](https://v-lipset.github.io/ao3-chinese/guide/online-mobile.mp4)
- 网盘链接：
  - [相关文件](https://pan.baidu.com/s/1JVAj6vEVVrxu4h86sBNkVw?pwd=o1je)

## 🤝 贡献与反馈

如果你发现了任何翻译错漏、脚本 Bug，或者有功能建议，欢迎通过 [Issues](https://github.com/V-Lipset/ao3-chinese/issues) 页面提交反馈！

## 📄 许可证

1. 本项目基于 [GPL-3.0 License](./LICENSE) 许可证开源。  
2. 项目中集成的部分代码源自以下开源项目，并遵循其原始许可证。详情请参阅源代码中的注释以及 `LICENSES` 目录。
    - [Traduzir-paginas-web](https://github.com/FilipePS/Traduzir-paginas-web)

## 🙏 特别鸣谢

- [V-Lipset](https://github.com/V-Lipset)
- [JiangxianEden](https://github.com/JiangxianEden)
- [github-chinese](https://github.com/maboloshi/github-chinese)
- 谷歌翻译接入参考：[Traduzir-paginas-web](https://github.com/FilipePS/Traduzir-paginas-web)
- UI 参考：[kiss-translator](https://github.com/fishjar/kiss-translator)
- 部分图标来自：[Google Material Symbols](https://fonts.google.com/icons)
