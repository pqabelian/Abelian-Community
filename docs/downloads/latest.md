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

# Abelian Latest Applications

## Abelian Pro (Mobile)

🔥 We are pleased to announce that the new mobile wallet, Abelian Pro, is now available for download.

**Download Links:**

- iOS
<div class="button-container">
  <a href="https://apps.apple.com/us/app/abelian-pro/id6475756639" class="btn">Download from App Store</a>
</div>

- Android
<div class="button-container">
  <a href="https://play.google.com/store/apps/details?id=info.abelian.walletpro" class="btn" style="background-color: #28A745;">Download from Play Store</a>
  <a href="https://download.pqabelian.io/release/android/abelian-mobile-wallet-pro-v1.0.9.apk" class="btn" style="background-color: #2DBD6E;">Download from APK file</a>
</div>

::: info Features
The new mobile wallet is a complete rewrite of the previous mobile wallet and is designed to be more user-friendly and feature-rich.
It is available on both iOS and Android platforms.
:::

## Abelian Desktop Applications

Privacy enhancing — wallet address and amount hiding

### Abelian Desktop Wallet (Legacy)
- **Release Date**: `2024-08-04`
- **Package**: `abelian-desktop-wallet-v4.1.1`
- **Download Links**:
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-windows-amd64-v4.1.1.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-macos-amd64-v4.1.1.zip" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-macos-arm64-v4.1.1.zip" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-linux-amd64-v4.1.1.zip" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/abelwallet-desktop/abelian-desktop-wallet-linux-arm64-v4.1.1.zip" class="btn">Linux (ARM)</a>
</div>

::: info Release Notes
  1. Upgrade Abec to version 1.0.0, and upgrade abewallet to abewalletlegacy version 1.0.0.
  2. We recommend all existing Desktop Wallet users to re-import all of their accounts after installing the new Abelian Desktop Wallet (Legacy).
:::

---

### Abelian Full Node
- **Release Date**: `2024-07-14`
- **Package**: `abec-v1.0.0`
- **Download Links**:
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abec/abec-windows-amd64-v1.0.0.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/abec/abec-macos-amd64-v1.0.0.tar.gz" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/abec/abec-macos-arm64-v1.0.0.tar.gz" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/abec/abec-linux-amd64-v1.0.0.tar.gz" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/abec/abec-linux-arm64-v1.0.0.tar.gz" class="btn">Linux (ARM)</a>
</div>

::: info Release Notes
  1. Hard Fork for MLPAUT: Multi-Level Privacy(MLP) and Abelian User Token(AUT) would be enabled at height 300000.
  2. Transactions with version 1 no longer are packaged to block after height 340000.

**For more details, Please view the link below:**
- https://pqabelian.medium.com/abelian-network-hard-fork-introducing-multi-level-privacy-and-user-token-protocol-at-block-height-add96dacdcce
- https://community.pqabelian.io/guide/get-started.html
:::

---

### Abelian GPU Mining Pool Client
- **Release Date**: `2023-05-31`
- **Package**: `abelminer-v2.0.3`
- **Download Links**:
<div class="button-container">
  <a href="https://download.pqabelian.io/release/pool/abelminer-windows-amd64-v2.0.3.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/pool/abelminer-linux-amd64-v2.0.3.tar.gz" class="btn">Linux</a>
</div>

::: info Guide for Miners:
1. Mining Pool Website: https://maxpool.org/
2. Please download the compressed package and then visit the mining pool website to read the [Quickstart Guide](https://maxpool.org/home/guide).
3. Please join our [Discord Server](https://discord.com/invite/5rrDxP29hx) and go to the mining channel (under 'how-to-mine-abel' after 'verify-yourself') to get the latest guide for GPU miners.
:::

---

### Abelian CPU Mining Pool Client
- **Release Date**: `2023-05-28`
- **Package**: `abe-miningpool-client-v0.13.0`
- **Download Links**:
<div class="button-container">
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-windows-amd64-v0.13.0.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-macos-amd64-v0.13.0.tar.gz" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-macos-arm64-v0.13.0.tar.gz" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-linux-amd64-v0.13.0.tar.gz" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/pool/abe-miningpool-client-linux-arm64-v0.13.0.tar.gz" class="btn">Linux (ARM)</a>
</div>

::: info Guide for Miners:
Mining Pool Website: https://maxpool.org/
:::

---

### Abelian Multi-layer Privacy Wallet (CLI)
- **Release Date**: `2024-08-13`
- **Package**: `abewalletmlp-v1.0.1`
- **Download Links**:
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-windows-amd64-v1.0.1.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-macos-amd64-v1.0.1.tar.gz" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-macos-arm64-v1.0.1.tar.gz" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-linux-amd64-v1.0.1.tar.gz" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/abewalletmlp/abewalletmlp-linux-arm64-v1.0.1.tar.gz" class="btn">Linux (ARM)</a>
</div>

::: info Release Notes
**What's New?**
- Two innovative wallet address types:
  1. Fully-Private Address: Your transactions are encrypted and untraceable, ensuring maximum security and anonymity.
  2. Pseudonymous Address: Enjoy a Bitcoin-like privacy level with publicly visible coin values and traceable transactions, all while benefiting from lower fees and increased throughput.

**Why Should You Upgrade?**
- Say goodbye to the "maximum recoverable number of wallets" requirement, as our new fully-private wallet is user-friendly and intuitive.
- Existing CLI users with ABEL tokens in their `abewalletlegacy` wallets are strongly encouraged to create a new fully-private wallet and transfer their assets for enhanced security.
- Miners and those who prioritize transaction speed and cost-effectiveness can opt for a pseudonymous wallet, offering a more accessible alternative to the fully-private option.

**Key Features:**
- Seamless token transfer between fully-private and pseudonymous wallets using the `abewalletmlp` CLI command.
- Stay tuned for upcoming tutorials and examples to master the art of managing your MLP Wallet like a pro!

**Important Notes:**
- Do not import or restore the mnemonic from the `abewallet/abewalletlegacy` into the `abewalletmlp`, which is not supported.

**For more details, Please view the link below:**
- https://pqabelian.medium.com/abelian-multi-layer-privacy-wallet-cli-user-guide-0a6dfe3a937d
:::

---

### Abelian Legacy Wallet (CLI)
- **Release Date**: `2024-08-04`
- **Package**: `abewalletlegacy-v1.0.0`
- **Download Links**:
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-windows-amd64-v1.0.0.zip" class="btn">Windows</a>
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-macos-amd64-v1.0.0.tar.gz" class="btn">macOS</a>
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-macos-arm64-v1.0.0.tar.gz" class="btn">macOS (Apple Silicon)</a>
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-linux-amd64-v1.0.0.tar.gz" class="btn">Linux</a>
  <a href="https://download.pqabelian.io/release/abewallet/abewalletlegacy-linux-arm64-v1.0.0.tar.gz" class="btn">Linux (ARM)</a>
</div>

::: info Release Notes
1. Rename abewallet to abewalletlegacy, which only supports the old address format.
2. We recommend all existing abewallet users to re-import all of their accounts after installed the new abewalletlegacy.
:::

---

### Abelian Lite Wallet (CLI)
- **Release Date**: `2023-09-15`
- **Package**: `abewallet-lite-v0.11.13`
- **Download Links**:
<div class="button-container">
  <a href="https://download.pqabelian.io/release/abewallet-lite/v0.12.5/abec_certs.zip" class="btn">Certificate</a>
  <a href="https://download.pqabelian.io/release/abewallet-lite/v0.12.5/abewallet.conf" class="btn">Configuration</a>
</div>

::: warning FOR NEW USERS
If you would like to try out Abelian Wallet (CLI) without having to download the full blockchain, please use the Abelian Lite Wallet (CLI). Check out the Abelian Lite CLI Wallet Manual for more details.
:::

::: info Release Notes
Since version 2023-09-15, there is no standalone package for Abelian Lite Wallet (CLI). It is essentially the Abelian Wallet (CLI) package coupled with a bunch of certificates to access existing full nodes maintained by Abelian Foundation and a default configuration file to connect to the Abelian Mainnet network without running a full node.
:::
