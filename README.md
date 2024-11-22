# Captain Tsubasa - RIVALS Bot  

---

## Table of Contents  
- [Features](#features)  
- [Requirements](#requirements)  
- [Setup Instructions](#setup-instructions)  
  - [Creating Data Files](#creating-data-files)  
  - [Proxy Configuration (Optional)](#proxy-configuration-optional)  
  - [Configuration Options](#configuration-options)  
- [Running the Tool](#running-the-tool)  
- [Support](#support)  

---

## Features  

✔️ Stamina recovery  
✔️ Upgrade Multitap and Stamina options  
✔️ Multi-threading support (`bot.js`)  
✔️ Tap fix functionality  
✔️ Skip upgrading expired cards  

Join here: [Tsubasa Rivals Bot](https://t.me/TsubasaRivalsBot/start?startapp=inviter_id-1719410244)

---

## Requirements  

- **Node.js** (must be installed on your system)  
  - [Download Node.js](https://nodejs.org/)  

Run the following command to install the necessary modules:  
```bash
npm install
```  

---

## Setup Instructions  

### Creating Data Files  

1. Create the following files in your project directory:  
   - `data.txt`  
   - `proxy.txt` (only required for multiple accounts)  

2. Add your account details to `data.txt` using this format:  
   ```txt
   query_id=xxx  
   user=xxxx  
   ```  

---

### Proxy Configuration (Optional)  

For multiple accounts, you’ll need to configure a proxy. Add your proxies to `proxy.txt` in this format:  
```txt
http://user:pass@ip:port  
```  

If using a single account, you don’t need a proxy.  

---

### Configuration Options  

Modify the `config.json` file to customize tool behavior. Example:  
```json
{
  "enableCardUpgrades": true,
  "enableTapUpgrades": true,
  "enableEnergyUpgrades": true,
  "maxUpgradeCost": 1000000,
  "maxTapUpgradeLevel": 5,
  "maxEnergyUpgradeLevel": 5
}
```  
Options:  
- **`enableCardUpgrades`**: Enable/disable card upgrades.  
- **`enableTapUpgrades`**: Enable/disable multitap upgrades.  
- **`enableEnergyUpgrades`**: Enable/disable stamina upgrades.  
- **`maxUpgradeCost`**: Limit the maximum cost for upgrades.  
- **`maxTapUpgradeLevel`**: Set the maximum multitap upgrade level.  
- **`maxEnergyUpgradeLevel`**: Set the maximum stamina upgrade level.  

---

## Running the Tool  

Run the bot with or without a proxy:  

**Without Proxy:**  
```bash
node bot.js
```  

**With Proxy:**  
```bash
node bot-proxy.js
```  

---

## Support  

For issues or questions, feel free to reach out to the project contributors or community.  

Join the support group: [Shadow Scripters](https://t.me/shadowscripters)  