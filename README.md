# 澜台发布仓库

[English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md)

这里是澜台桌面客户端的公开发布仓库，用于承载 GitHub Releases、自动更新元数据和安装包资产。

源码仓库保持私有；普通用户只需要从本仓库的 Releases 页面下载或等待客户端自动更新。

## 下载

- [Releases](https://github.com/shenyangs/lantai3-releases/releases)

## 自动更新

澜台桌面端会在后台静默检查更新。发现新版本后会后台下载，并在下次正常退出应用时安装，不会在使用中弹窗打扰。

## 文件说明

- `latest-mac.yml`：macOS 自动更新元数据
- `*.dmg`、`*.zip`：macOS 安装和更新资产
- `latest.yml`、`*.exe`：Windows 安装和更新资产

## 许可

Apache-2.0
