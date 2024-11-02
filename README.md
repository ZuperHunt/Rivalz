Penulis: [Naufal](https://x.com/0xfal)

> [!NOTE]
> **WHAT IS Rivalz?**\
> .

# Tutorial Rivalz rClient CLI

## 1. Requirement

Kamu bisa gunakan VPS atau PC pribadi dengan kebutuhan:

| ✅ Linux | ✅ macOS | ✅ Windows (WSL) |
| ------------- | ------------- | ------------- |

| Part | Minimum | Recommended |
| ------------- | ------------- | ------------- |
| CPU | - | 4 Cores |
| RAM | - | 4 GB |
| SSD | - | 50 GB |

Tutorial ini dibuat menggunakan Linux (Ubuntu), untuk sistem operasi lainnya mungkin akan sedikit berbeda.

## 2. Dependency

### 2.1 Install Node Version Manager

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

### 2.2 Install Node.js

```
nvm install node
```

### 2.3 Install `rivalz-node-cli`

```
npm i -g rivalz-node-cli
```

## 3. Execution

### 3.1 Connect Wallet to Dashboard

Go to [Rivalz dashboard](https://rivalz.ai?r=fal), connect your EVM wallet and sign.

### 3.2 Run rClient

```
rivalz run
```

Enter your EVM wallet that you've connected to Rivalz dashboard. Enter 25 GB ~ 50 GB for disk size.

---

Reach us if you have any question:\
ZuperHunt's [Discord server](https://discord.gg/ZuperHunt) | [X(Twitter)](https://twitter.com/ZuperHunt)

# Acknowledgements

* [Rivalz Docs](https://docs.rivalz.ai/rclients-ocy-depin/rclient-cli-guide)
