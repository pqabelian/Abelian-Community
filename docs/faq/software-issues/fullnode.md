---
outline: deep
---

# Abelian Full Node FAQ

## ABEC Issues

### <Badge type="warning" text="QUESTION" /> How to move mainnet data to another location?

::: info <Badge type="tip" text="ANSWER" />
To change the folder, you can try this method (Windows only)

1. Close desktop wallet

2. System Properties ->Advanced ->Environment Variables ->New User/System Environment Variables

Variable name: ABELWALLET_HOME

Variable value: (Select a folder path)

3. Move the following files from the 
C:\Users\\[username]\AppData\Roaming\Abelian Wallet path to a new path

Abec, Abewallet, ans cache. json, config. json, state.json

4. Restart the system
:::

---

### <Badge type="warning" text="QUESTION" /> The error log is: "Database corruption detected"
```txt
ABEC: Version 0.12.6
ABEC: Loading block database from '/root/.abec/data/mainnet/blocks_ffldb'
ABDB: ***Database corruption detected***: metadata claims file 37, offset 176759509, but witness data is at file 0, offset 0
ABEC: metadata claims file 37, offset 176759509, but witness data is at file 0, offset 0
ABEC: Shutdown complete
```

::: info <Badge type="tip" text="ANSWER" />
That's mainnet database corruption. You need to delete the "/[user_home_dir]/.abec/data/mainnet" folder, and start the resync again.

Or [View this page](/downloads/mainnet-db) and follow the steps to download the latest mainnet data, Then resync again.
:::

---

### <Badge type="warning" text="QUESTION" /> What are the hardware requirements for running a full node (ABEC)?

::: info <Badge type="tip" text="ANSWER" />
Full nodes (ABEC) have currently released versions for almost all commonly used hardware platforms, with minimal hardware requirements. However, there are minimum requirements for the speed of synchronizing and reading mainnet data as well as storage space size. The storage space should be no less than 150GB, and it is recommended to use a 240GB solid-state drive.
:::

---