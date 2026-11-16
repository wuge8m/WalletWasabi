<p align="center">
  <a href="https://wasabiwallet.io">
    <img src="https://github.com/WalletWasabi/WalletWasabi/blob/master/ui-ww.png">
  </a>
</p>

<h3 align="center">
    An open-source, non-custodial, privacy-focused Bitcoin wallet for desktop.
</h3>

<h3 align="center">
    开源、非托管、注重隐私的桌面端 Bitcoin 钱包。
</h3>

<h3 align="center">
  <a href="https://wasabiwallet.io">
    Website
  </a>
  <span> | </span>
  <a href="https://docs.wasabiwallet.io/">
    Documentation
  </a>
  <span> | </span>
  <a href="https://github.com/WalletWasabi/WalletWasabi/discussions/5185">
    Support
  </a>
  <span> | </span>
  <a href="https://www.youtube.com/c/WasabiWallet">
    YouTube
  </a>
  <span> | </span>
  <a href="https://github.com/WalletWasabi/WalletWasabi/blob/master/PGP.txt">
    PGP
  </a>
</h3>

<h3 align="center">
  <a href="https://wasabiwallet.io">
    网站
  </a>
  <span> | </span>
  <a href="https://docs.wasabiwallet.io/">
    文档
  </a>
  <span> | </span>
  <a href="https://github.com/WalletWasabi/WalletWasabi/discussions/5185">
    支持
  </a>
  <span> | </span>
  <a href="https://www.youtube.com/c/WasabiWallet">
    YouTube
  </a>
  <span> | </span>
  <a href="https://github.com/WalletWasabi/WalletWasabi/blob/master/PGP.txt">
    PGP
  </a>
</h3>
<br>

# [Download Wasabi](https://github.com/WalletWasabi/WalletWasabi/releases)

# [下载 Wasabi](https://github.com/WalletWasabi/WalletWasabi/releases)

<br>

# Build From Source Code

# 从源代码构建

### Get The Requirements

### 获取所需依赖

1. Get Git: https://git-scm.com/downloads
2. Get .NET 10.0 SDK: https://dotnet.microsoft.com/download
3. Optionally disable .NET's telemetry by executing in the terminal `export DOTNET_CLI_TELEMETRY_OPTOUT=1` on Linux and macOS or `setx DOTNET_CLI_TELEMETRY_OPTOUT 1` on Windows.

1. 安装 Git: https://git-scm.com/downloads
2. 安装 .NET 10.0 SDK: https://dotnet.microsoft.com/download
3. 如果需要，可在终端中执行 `export DOTNET_CLI_TELEMETRY_OPTOUT=1`（Linux/macOS）或 `setx DOTNET_CLI_TELEMETRY_OPTOUT 1`（Windows）来禁用 .NET 遥测。

### Get Wasabi

### 获取 Wasabi

Clone & Restore & Build

克隆、还原并构建：

```sh
git clone --depth=1 --single-branch --branch=master https://github.com/WalletWasabi/WalletWasabi.git
cd WalletWasabi/WalletWasabi.Fluent.Desktop
dotnet build
```

### Run Wasabi

### 运行 Wasabi

Run Wasabi with `dotnet run` from the `WalletWasabi.Fluent.Desktop` folder.

在 `WalletWasabi.Fluent.Desktop` 目录中执行 `dotnet run` 来运行 Wasabi。

### Update Wasabi

### 更新 Wasabi

```sh
git pull
```

更多中文说明：

Wasabi Wallet 是一个面向桌面端的开源、非托管、重视隐私的 Bitcoin 钱包。它旨在帮助用户在不依赖第三方托管的前提下管理比特币资产，并尽量减少链上可追踪信息泄露。

如果你想从源码编译并运行该项目，请先安装 Git 和 .NET 10.0 SDK，并在本地克隆仓库后执行 `dotnet build`。如需参与开发、测试或自行修改代码，建议在 `WalletWasabi.Fluent.Desktop` 目录内使用 `dotnet run` 进行本地启动。
