# MC Launcher

A Minecraft launcher for Windows (WPF, .NET 10, own launch engine).

Windows 版 Minecraft 启动器，使用自研启动引擎。

## Download / 下载

Get the latest `MCLauncher-*-win-x64.zip` from the [Releases](../../releases/latest) page, extract it to a folder, and run `MCLauncher.exe`. No installation or separate .NET runtime is required.

从 [Releases](../../releases/latest) 页面下载最新的 `MCLauncher-*-win-x64.zip`，解压到任意文件夹后运行 `MCLauncher.exe`，无需安装，也不需要另装 .NET。

## Updates / 更新

The launcher checks `release.json` from the latest release for new versions. Each update package is verified by size and SHA-256 before it is installed.

启动器会读取最新 Release 中的 `release.json` 检查新版，更新包安装前会校验大小和 SHA-256。

This repository currently hosts release files only. / 本仓库目前仅用于发布安装包。
