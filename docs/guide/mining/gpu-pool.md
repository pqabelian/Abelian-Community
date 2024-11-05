---
outline: deep
---

# Abelian GPU Mining Manual

This document describes how to run a SOLO GPU mining software.

Please refer to Abelian Software Basics to understand the software architecture and the SOLO mining or mining pool choices.

Please visit the Abeian official website download page to download [Abelian GPU Mining Pool Client](/downloads/latest#abelian-gpu-mining-pool-client). To interact with other miners, developers and users, visit the [Official Discord Server](https://discord.com/invite/5rrDxP29hx).

All the operations are carried out via the Command Line Interface (CLI). For Linux, open Terminal; and for Windows, open PowerShell or any of your favorite shell application.

## Installation

Download two compressed files, something like `abelminerlinux-amd64-v2.0.3.tar.gz` for Linux running on an x86 architecture (e.g. Intel chips).

Unzip them and put them under the same folder ~/abel/:

```txt
~/abel/abelminer-linux-amd64-v2.0.3/
```

## Create a wallet address

Assuming you have already created a wallet account using the Mobile Wallet Pro version.

The easiest way is to download the [Abelian Pro](/downloads/latest#abelian-pro-mobile) from the official download page, and create a wallet. Then follow these steps to obtain your wallet address:

1. In the `Abelian Pro` main interface, tap the `Profile` icon in the top right corner.
2. Navigate to `Profile -> Account details` page.
3. Click the `Eye` icon next to the string of characters under the `Address` field.
4. In the pop-up window, click the `Copy` button to copy the address to your clipboard.

## Join Official Mining Pool

- Please visit the official mining pool Maxpool to read the [Quickstart Guide](https://maxpool.org/home/guide);

- The original Abelian Foundation mining pool (pool.abelian.info) is still available, but the URL has changed to: [https://legacy.maxpool.org/home](https://legacy.maxpool.org/home). Please use this URL for access. It is strongly recommended to migrate to the new Maxpool mining pool before the hard fork is completed.

- Maxpool mining pool needs to update the client to [Abelian GPU Mining Pool Client v2.0.3](/downloads/latest#abelian-gpu-mining-pool-client)

## Run a GPU miner - abelminer

The Maxpool user guide includes mining helper scripts and programs for various platforms. Here's a brief introduction to the command for running the `abelminer` binary program:

Go to `~/abel/abelminer-linux-amd64-v2.0.3/` and run the GPU mining client (`abelminer`):

::: code-group
```shell [Windows]
$ .\abelminer.exe -P http://[Pool Server Domain or IP address]:8668
```
```shell [macOS and Linux]
$ ./abelminer -P http://[Pool Server Domain or IP address]:8668
```
:::