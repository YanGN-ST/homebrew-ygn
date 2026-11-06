**[English](README.md) | 简体中文**

<p align="center">
  <img src="./assets/readme/hero-zh-v2.svg" width="100%" alt="homebrew-ygn: 小工具，一个 tap。">
</p>

YanGN 维护的 macOS 工具 Homebrew tap。

## 工具

| 应用 | 用途 | 系统要求 |
|---|---|---|
| [FinderWrap](https://github.com/YanGN-ST/FinderWrap) | Finder 图标视图方向键跨行 | macOS 13+，Apple Silicon |
| [Duty](https://github.com/YanGN-ST/Duty) | 监测并恢复选定的默认文件关联 | macOS 14+，Apple Silicon |

安装命令为 `brew install --cask yangn-st/ygn/<名称>`。

FinderWrap 需要辅助功能和输入监控权限。固定自签名构建未公证，首次打开被拦截时，请核对来源并在「隐私与安全性」中允许打开。macOS 15 和 27 仍需实机验证。

Duty 未经过 Apple 公证，首次打开请核对来源并按系统提示处理。

## 安装

```sh
brew tap yangn-st/ygn
brew install --cask yangn-st/ygn/finderwrap
```

确认第三方 tap 前请核对仓库和 cask。使用 `brew upgrade --cask <名称>` 升级，使用 `brew uninstall --cask <名称>` 卸载。

<details>
<summary>维护</summary>

FinderWrap cask 需要手动更新，并核对固定签名身份与发布附件。cask 位于 `Casks/`，维护工具位于 `Scripts/`。

</details>

## 许可

本仓库见 [LICENSE](LICENSE)，各应用以自己的许可为准。
