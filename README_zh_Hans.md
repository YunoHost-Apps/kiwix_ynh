<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Kiwix

[![集成程度](https://dash.yunohost.org/integration/kiwix.svg)](https://dash.yunohost.org/appci/app/kiwix) ![工作状态](https://ci-apps.yunohost.org/ci/badges/kiwix.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/kiwix.maintain.svg)

[![使用 YunoHost 安装 Kiwix](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Kiwix。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Kiwix is an offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks. It makes knowledge available to people with no or limited internet access. The software as well as the content is free to use for anyone.

### Features

- Full text search engine
- Search suggestions
- Compatible with almost all browsers
- Available as command line executable
- Embedded in Kiwix UI
- Able to deal with one ZIM file or XML library files


**分发版本：** 3.6.0~ynh2

**演示：** <http://library.kiwix.org/>

## 截图

![Kiwix 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://www.kiwix.org/>
- 官方管理文档： <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- 上游应用代码库： <https://github.com/kiwix/kiwix-tools>
- YunoHost 商店： <https://apps.yunohost.org/app/kiwix>
- 报告 bug： <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
或
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
