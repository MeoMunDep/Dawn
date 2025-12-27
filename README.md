DISCLAIMER: THIS PAGE WAS MADE AS A PERSONAL EDUCATIONAL PROJECT. This is NOT the official site of the company or brand identified on the page. The creator of this page is NOT affiliated with the company or brand in any way. This page is a personal project made in connection with an educational exercise.

---

📞 Contact

[Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux)


If you encounter any issues or have questions, feel free to reach out:

- Contact: [Link](t.me/MeoMunDep)
- Group: [Link](t.me/KeoAirDropFreeNe)
- Channel: [Link](t.me/KeoAirDropFreeNee)

 Help me with your referral > Referral Code: `fsls9vm7`

## 🚀 Getting Started

To get started with the bot, follow these steps:

0. **Dowload NodeJS to run the bot**

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

-> Double click on `setup.bat` for windows or `setup.sh` for linux/mac if you want to run automatically, remember to fill all the necessary data.

1. **Install Dependencies and Modules:**

   ```
   npm i user-agents axios meo-forkcy-proxy meo-forkcy-utils meo-forkcy-logger meo-forkcy-colors
   ```

2. **Prepare Configuration Files:**

   > You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜 - Adjust configuration

```json
{
  "rotateProxy": true,
  "skipInvalidProxy": false,
  "proxyRotationInterval": 2,
  "delayEachAccount": [5, 8],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 100,
}
```

### 1. `tokens.txt` ✔️ - How to get token >>> [Link](https://t.me/KeoAirDropFreeNee/1955)

```txt
abc...xyz
abc...xyz
abc...xyz
```

### 2. `wallets.txt` 💼 - Cannot update yet.


- [Get it from here](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)

```txt - wallet address
abc...xyz
abc...xyz
abc...xyz
```

### 3. `proxies.txt` 🌐 - Proxy is an option. If you have one, fill it in; otherwise, leave it blank.
- [Get it from here](https://www.webshare.io/?referral_code=4l5kb3glsce7)

```txt
http://host:port
https://host:port
socks4://host:port
socks5://host:port
http://user:pass@host:port
https://user:pass@host:port
socks4://user:pass@host:port
socks5://user:pass@host:port
```

💡 Usage:

> You need to `cd` to the file after extract it
> To run the bot, use the following command: `cd dawn; node meomundep `

 ⚠️ **Disclaimer**

This project was created solely as a **personal educational exercise**.  
It is **not an official product**, website, or service of any company or brand referenced in this repository.  
The creator is **not affiliated, associated, endorsed by, or connected** with any such company or brand in any way.

The code is provided **"as is"** without any warranties or guarantees.  
Certain parts of the source are intentionally **obfuscated** to protect personal research, custom logic, and implementation techniques developed during learning and experimentation.

Use this project responsibly and at your own risk.  
**Redistribution, resale, or commercial use** of any part of this code—whether original or modified—is **not permitted**.
