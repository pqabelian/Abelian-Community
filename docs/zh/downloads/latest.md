---
outline: deep
---

<style>
.button-container { 
  display: flex;
  flex-wrap: wrap; /* 允许按钮换行 */
  gap: 8px; /* 确保有间距 */
  margin-left: 18px; /* 左侧间距 */
}

.button-container .btn {
  display: inline-block;
  background-color: #007AFF;
  color: white !important; /* 使用 !important 确保颜色应用 */
  font-size: 16px !important; /* 同样使用 !important */
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-family: Arial, sans-serif !important;
  padding: 10px 20px;
  border: 1px solid #666; /* 灰色边框 */
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none !important;
  transition: background-color 0.3s, transform 0.3s, font-weight 0.3s;
  /* 设定按钮的最小宽度，防止按钮太小 */
  min-width: 80px; /* 可根据需要调整最小宽度 */
}

.button-container .btn:hover {
  background-color: #0056b3; /* 更深的蓝色 */
  transform: scale(1.02); /* 放大效果 */
}
</style>

# Abelian 最新发布应用程序

## Abelian Pro (移动应用)

🔥 我们很高兴宣布：新的移动钱包 Abelian Pro 现已可供下载。

**下载链接**：

##### iOS
<div class="button-container">
  <a href="https://apps.apple.com/us/app/abelian-pro/id6475756639" class="btn">从苹果应用商店下载</a>
</div>

##### 安卓 (Android)
<div class="button-container">
  <a href="https://play.google.com/store/apps/details?id=info.abelian.walletpro" class="btn" style="background-color: #28A745;">从谷歌应用商店下载</a>
  <a href="https://download.pqabelian.io/release/android/abelian-mobile-wallet-pro-v1.0.9.apk" class="btn" style="background-color: #2DBD6E;">下载 APK 安装包文件</a>
</div>

::: info 特点介绍
新的移动钱包是对之前移动钱包的全面重写，旨在更加用户友好和功能丰富。它可在 iOS 和 Android 平台上使用。
:::

## Abelian 桌面应用程序

隐私增强 —— 隐藏钱包地址和金额

### Abelian 桌面钱包 (传统版)
- **发布日期**： `2024-08-04`
- **软件包**： `abelian-desktop-wallet-v4.1.1`
- **下载链接**：
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-windows-amd64-v4.1.1.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-macos-amd64-v4.1.1.zip" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-macos-arm64-v4.1.1.zip" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-linux-amd64-v4.1.1.zip" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-linux-arm64-v4.1.1.zip" class="btn">Linux (ARM)</a>
</div>

::: info 发布说明
  1. 升级 Abec 到 1.0.0 版本， abewallet 升级为 abewalletlegacy 1.0.0 版本。
  2. 我们建议所有现有桌面钱包用户安装新的 Abelian 桌面钱包（Legacy），并重新导入所有账户。
:::

---

### Abelian 全节点
- **发布日期**： `2024-07-14`
- **软件包**： `abec-v1.0.0`
- **下载链接**：
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abec/abec-windows-amd64-v1.0.0.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/abec/abec-macos-amd64-v1.0.0.tar.gz" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/abec/abec-macos-arm64-v1.0.0.tar.gz" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/abec/abec-linux-amd64-v1.0.0.tar.gz/" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/abec/abec-linux-arm64-v1.0.0.tar.gz" class="btn">Linux (ARM)</a>
</div>

::: info 发布说明
1. MLPAUT 硬分叉：多级隐私（MLP）和 Abelian 用户代币（AUT）将在高度 300000 启用。
2. 当高度达到 340000 之后，版本 1 的交易将不再被打包到区块中。

**了解更多详情，请查看以下链接：**
- https://pqabelian.medium.com/abelian-network-hard-fork-introducing-multi-level-privacy-and-user-token-protocol-at-block-height-add96dacdcce
- https://community.pqabelian.io/guide/get-started.html
:::

---

### Abelian 显卡矿池客户端
- **发布日期**： `2023-05-31`
- **软件包**： `abelminer-v2.0.3`
- **下载链接**：
<div class="button-container">
  <a href="https://download.pqabelian.io/release/pool/abelminer-windows-amd64-v2.0.3.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/pool/abelminer-linux-amd64-v2.0.3.tar.gz" class="btn">Linux</a>
</div>

::: info 矿工指南
1. 矿池网站：https://maxpool.org/
2. 请下载压缩包，然后访问矿池网站阅读 [快速入门指南](https://maxpool.org/home/guide)。
3. 请加入我们的 [Discord 服务器](https://discord.com/invite/5rrDxP29hx)，并前往挖矿频道（在 “verify-yourself” 之后前往 “how-to-mine-abel” 子频道）获取 GPU 矿工的最新指南。
:::

---

### Abelian CPU 矿池客户端
- **发布日期**： `2023-05-28`
- **软件包**： `abe-miningpool-client-v0.13.0`
- **下载链接**：
<div class="button-container">
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-windows-amd64-v0.13.0.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-macos-amd64-v0.13.0.tar.gz" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-macos-arm64-v0.13.0.tar.gz" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-linux-amd64-v0.13.0.tar.gz" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-linux-arm64-v0.13.0.tar.gz" class="btn">Linux (ARM)</a>
</div>

::: info 矿工指南
矿池网站：https://maxpool.org/
:::

---

### Abelian 多层隐私钱包 (CLI)
- **发布日期**： `2024-08-13`
- **软件包**： `abewalletmlp-v1.0.1`
- **下载链接**：
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-windows-amd64-v1.0.1.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-macos-amd64-v1.0.1.tar.gz" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-macos-arm64-v1.0.1.tar.gz" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-linux-amd64-v1.0.1.tar.gz" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-linux-arm64-v1.0.1.tar.gz" class="btn">Linux (ARM)</a>
</div>

::: info 发布说明
**有什么新功能？**
- 两种创新的钱包地址类型：
  1. 完全私密地址：您的交易是加密且无法追踪的，确保最大程度的安全性和匿名性。
  2. 隐私地址：享受类似比特币的隐私级别，具有公开可见的币值和可追踪的交易，同时还享有更低费用和更高吞吐量。

**为什么要升级？**
- 告别 “最大可恢复钱包数量” 要求，我们的新完全私密钱包用户友好且直观。
- 强烈建议现有 CLI 用户将其 `abewalletlegacy` 钱包中的 ABEL 代币创建一个新的完全私密钱包并转移资产以增强安全性。
- 矿工以及那些优先考虑交易速度和成本效益的人可以选择假名钱包，这提供了比完全私密选项更易于访问的替代方案。

**主要特点：**
- 使用 `abewalletmlp` CLI命令在完全私密和假名钱包之间无缝转移代币。
- 敬请期待即将推出的教程和示例，以专业方式掌握管理MLP Wallet 的艺术！

**重要提示：**
- 不要将 `abewallet/abewalletlegacy` 中的助记词导入或恢复到 `abewalletmlp` 中，这是不支持的。

**更多详情，请查看以下链接：**
- https://pqabelian.medium.com/abelian-multi-layer-privacy-wallet-cli-user-guide-0a6dfe3a937d
:::

---

### Abelian 传统钱包 (CLI)
- **发布日期**： `2024-08-04`
- **软件包**： `abewalletlegacy-v1.0.0`
- **下载链接**：
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-windows-amd64-v1.0.0.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-macos-amd64-v1.0.0.tar.gz" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-macos-arm64-v1.0.0.tar.gz" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-linux-amd64-v1.0.0.tar.gz" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-linux-arm64-v1.0.0.tar.gz" class="btn">Linux (ARM)</a>
</div>

::: info 发布说明
1. 将 `abewallet` 重命名为 `abewalletlegacy`，仅支持旧地址格式。
2. 我们建议所有现有的 `abewallet` 用户在安装新的 `abewalletlegacy` 后重新导入他们的所有账户。
:::

---

### Abelian 轻量钱包 (CLI)
- **发布日期**： `2023-09-15`
- **软件包**： `abewallet-lite-v0.11.13`
- **下载链接**：
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abewallet-lite/v0.12.5/abec_certs.zip" class="btn">证书文件</a>
  <a href="https://download.pqabelian.io/release/abewallet-lite/v0.12.5/abewallet.conf" class="btn">配置文件</a>
</div>

::: warning 对于新用户
如果您想尝试 Abelian 钱包（CLI），且不想下载完整的区块链数据，请使用 Abelian 轻量钱包（CLI）。更多详情请查看 Abelian 轻量 CLI 钱包手册。
:::

::: info 发布说明
自 2023-09-15版本起，Abelian 轻量钱包（CLI）不再提供独立软件包。它本质上是 Abelian 钱包（CLI）软件包，仅附带了一些证书，用于访问由 Abelian 基金会维护的现有全节点，通过默认配置文件，无需运行全节点即可连接到 Abelian 主网。
:::
