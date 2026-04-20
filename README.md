# 🚀 BEP20 Smart Contract Template

A professional, standard **BEP20 Smart Contract** for the Binance Smart Chain (BSC). This template is ready for deployment and easy to customize.

---

## 🛠 Customization Guide

Follow these steps to personalize your token before deployment. Open the contract file and modify the following lines:

| Line | Action | Description |
| :--- | :--- | :--- |
| **339** | `BSCToken` | Change to your **Contract Name** (No spaces). |
| **352** | `BSC Token` | Change to your **Full Token Name** (With spaces). |
| **353** | `BSCT` | Set your **Token Symbol/Ticker**. |
| **354** | `Decimals` | Set to **8** (Standard Crypto) or **18** (Standard ERC20). |
| **355** | `Total Supply` | Set your supply (Include your decimals in the total). |

### 💡 Supply Calculation Example:
To get **100,000** tokens:
* **Decimal 8:** Write `100000` + `00000000` → `10000000000000`
* **Decimal 18:** Write `100000` + `000000000000000000` → `100000000000000000000000`

---

## 🛡 Contract Verification (BscScan)

When verifying your contract, use these exact settings:
* **Compiler Type:** Single File
* **Solidity Version:** 0.5.16
* **License:** MIT
* **Optimization:** Enabled (200 Runs)

---

## 🌟 Support the Project

If this template helps you launch your project, please consider giving it a **Star**! ⭐️

[![GitHub stars](https://img.shields.io/github/stars/Bulls-Dev/BEP20-Smart-Contract-Template.svg?style=social&label=Star)](https://github.com/Bulls-Dev/BEP20-Smart-Contract-Template)

---

## 🔗 Web3 Services & Community

Need a custom token, a dApp, or professional Web3 development?

* 🛒 **Web3 Shop:** [Visit Shop-Block-S-Dev](https://shop-block-s-dev.vercel.app/)
* 📢 **Telegram:** [Join @dev_web3_blocks](https://t.me/dev_web3_blocks)

---

### ⚠️ Disclaimer
*This code is provided for educational purposes. Always audit your smart contracts before deploying them with real funds on the Mainnet. The author is not responsible for any financial loss.*
