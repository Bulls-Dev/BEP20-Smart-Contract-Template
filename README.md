# 🚀 BEP20 Smart Contract Template

A professional, standard **BEP20 Smart Contract** for the Binance Smart Chain (BSC). This template is ready for deployment and easy to customize.

---

## 🛠 Customization Guide

Follow these steps to personalize your token before deployment. Open the contract file and modify the following lines:

| Line | Action | Description |
| :--- | :--- | :--- |
| **339** | `BSCToken` | Change to your **Token Name** (No spaces). |
| **352** | `BSC Token` | Change to your **Token Name** (With spaces). |
| **353** | `BSCT` | Set your **Token Symbol/Ticker**. |
| **354** | `Decimals` | Set to **8** (Standard Crypto) or **18** (Standard ERC20). |
| **355** | `Total Supply` | Set your supply (Include your decimals in the total). |

### 💡 Supply Calculation Example:
If you want **100,000** tokens:
- **Decimal 8:** Write `100000` + `00000000` → `10000000000000`
- **Decimal 18:** Write `100000` + `000000000000000000` → `100000000000000000000000`

---

## 🛡 Contract Verification Details

When verifying your contract on BscScan, use these settings:
* **License:** MIT
* **Solidity Version:** 0.5.16
* **Optimization:** Enabled (Runs: 200)

---

## 🌟 Support & Development

If this template helps you launch your project, please give it a **Star**! ⭐️

[![GitHub stars](https://img.shields.io/github/stars/votre-username/votre-repo.svg?style=social&label=Star)](https://github.com/votre-username/votre-repo)

### 🔗 Services & Community
Need a custom token or professional Web3 development?

* 🛒 **Web3 Shop:** [Visit Shop-Block-S-Dev](https://shop-block-s-dev.vercel.app/)
* 📢 **Telegram Support:** [Join @dev_web3_blocks](https://t.me/dev_web3_blocks)

---

### ⚠️ Disclaimer
*This code is provided for educational purposes. Always audit your smart contracts before deploying them with real funds on the Mainnet.*
