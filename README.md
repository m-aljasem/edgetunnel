# 🚀 edgetunnel 2.1
![Admin Panel](./img.png)

[![Stars](https://img.shields.io/github/stars/cmliu/edgetunnel?style=flat-square&logo=github)](https://github.com/cmliu/edgetunnel/stargazers)
[![Forks](https://img.shields.io/github/forks/cmliu/edgetunnel?style=flat-square&logo=github)](https://github.com/cmliu/edgetunnel/network/members)
[![License](https://img.shields.io/github/license/cmliu/edgetunnel?style=flat-square)](https://github.com/cmliu/edgetunnel/blob/main/LICENSE)
[![Telegram](https://img.shields.io/badge/Telegram-Group-blue?style=flat-square&logo=telegram)](https://t.me/CMLiussss)
[![YouTube](https://img.shields.io/badge/YouTube-Channel-red?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=LeT4jQUh8ok)
[![zread](https://img.shields.io/badge/Ask_Zread-_.svg?style=flat-square&color=00b0aa&labelColor=000000&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTQuOTYxNTYgMS42MDAxSDIuMjQxNTZDMS44ODgxIDEuNjAwMSAxLjYwMTU2IDEuODg2NjQgMS42MDE1NiAyLjI0MDFWNC45NjAxQzEuNjAxNTYgNS4zMTM1NiAxLjg4ODEgNS42MDAxIDIuMjQxNTYgNS42MDAxSDQuOTYxNTZDNS4zMTUwMiA1LjYwMDEgNS42MDE1NiA1LjMxMzU2IDUuNjAxNTYgNC45NjAxVjIuMjQwMUM1LjYwMTU2IDEuODg2NjQgNS4zMTUwMiAxLjYwMDEgNC45NjE1NiAxLjYwMDFaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00Ljk2MTU2IDEwLjM5OTlIMi4yNDE1NkMxLjg4ODEgMTAuMzk5OSAxLjYwMTU2IDEwLjY4NjQgMS42MDE1NiAxMS4wMzk5VjEzLjc1OTlDMS42MDE1NiAxNC4xMTM0IDEuODg4MSAxNC4zOTk5IDIuMjQxNTYgMTQuMzk5OUg0Ljk2MTU2QzUuMzE1MDIgMTQuMzk5OSA1LjYwMTU2IDE0LjExMzQgNS42MDE1NiAxMy43NTk5VjExLjAzOTlDNS42MDE1NiAxMC42ODY0IDUuMzE1MDIgMTAuMzk5OSA0Ljk2MTU2IDEwLjM5OTlaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik0xMy43NTg0IDEuNjAwMUgxMS4wMzg0QzEwLjY4NSAxLjYwMDEgMTAuMzk4NCAxLjg4NjY0IDEwLjM5ODQgMi4yNDAxVjQuOTYwMUMxMC4zOTg0IDUuMzEzNTYgMTAuNjg1IDUuNjAwMSAxMS4wMzg0IDUuNjAwMUgxMy43NTg0QzE0LjExMTkgNS42MDAxIDE0LjM5ODQgNS4zMTM1NiAxNC4zOTg0IDQuOTYwMVYyLjI0MDFDMTQuMzk4NCAxLjg4NjY0IDE0LjExMTkgMS42MDAxIDEzLjc1ODQgMS42MDAxWiIgZmlsbD0iI2ZmZiIvPgo8cGF0aCBkPSJNNCAxMkwxMiA0TDQgMTJaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00IDEyTDEyIDQiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIxLjUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPgo8L3N2Zz4K&logoColor=ffffff)](https://zread.ai/cmliu/edgetunnel)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/cmliu/edgetunnel)

---

## 📖 Project Overview

**edgetunnel** is an edge-computing tunnel solution built on the CF Workers/Pages platform. It efficiently handles network traffic and provides a powerful admin panel with flexible node configuration.

- 🖥️ **Demo Site**: [https://EDT-Pages.github.io/admin](https://EDT-Pages.github.io/admin)

### ✨ Core Features

- 🛡️ **Protocol Support**: Supports VLESS, Trojan, Shadowsocks and other mainstream protocols with deep encryption integration.
- 📊 **Admin Panel**: Built-in visual dashboard supporting real-time config edits, log viewing, and traffic statistics.
- 🛠️ **Flexible Deployment**: Fully compatible with CF Workers and CF Pages (GitHub / file upload).
- 🔄 **Subscription System**: Built-in automatic subscription generation and obfuscation conversion, compatible with mainstream clients (Clash, Sing-box, Surge, etc.).
- ⚡ **Performance Boost**: Supports custom ProxyIP, SOCKS5/HTTP chained proxies, and preferred API for lower latency.
- 🌐 **Multi-Platform**: Perfectly compatible with Windows, Android, iOS, MacOS, and various soft-router firmware.

---

## 💡 Quick Deployment
>[!TIP]
> 📖 **Detailed Tutorial**: [edgetunnel Deployment Guide](https://cmliussss.com/p/edt2/)

>[!WARNING]
> ⚠️ **Error 1101 Issue**: [Video Explanation](https://www.youtube.com/watch?v=r4uVTEJptdE)

### ⚙️ Workers Deployment

<details>
<summary><code><strong>「 Workers Deployment Text Guide 」</strong></code></summary>

1. Deploy CF Worker:
   - Create a new Worker in the CF Worker console.
   - Paste the contents of [worker.js](https://github.com/cmliu/edgetunnel/blob/main/_worker.js) into the Worker editor.
   - In the left `Settings` tab, select `Variables` > `Add Variable`.
     Set the variable name to **ADMIN** and the value to your admin password, then click `Save`.

2. Bind KV Namespace:
   - In the `Bindings` tab, select `Add Binding +` > `KV Namespace` > `Add Binding`, then choose an existing namespace or create a new one.
   - Set the `Variable name` to **KV**, then click `Add Binding`.

3. Bind a Custom Domain to Workers:
   - In the `Triggers` tab of the Workers console, click `Add Custom Domain` at the bottom.
   - Enter a subdomain that is already using CF DNS, e.g. `vless.google.com`, then click `Add Custom Domain` and wait for the certificate to take effect.

4. Access the Admin Panel:
   - Visit `https://vless.google.com/admin` and enter your admin password to log in.

</details>

### 🛠 Pages Upload Deployment **BEST RECOMMENDED!!!** [Illustrated Guide](https://cmliussss.com/p/edt2/)

<details>
<summary><code><strong>「 Pages File Upload Deployment Text Guide 」</strong></code></summary>

1. Deploy CF Pages:
   - Download the [main.zip](https://github.com/cmliu/edgetunnel/archive/refs/heads/main.zip) file and give the project a Star !!!
   - In the CF Pages console, select `Upload Assets`, name your project, click `Create Project`, then upload the downloaded [main.zip](https://github.com/cmliu/edgetunnel/archive/refs/heads/main.zip) file and click `Deploy Site`.
   - After deployment, click `Continue to Site`, then go to `Settings` > `Environment Variables` > **Create** variable for production > `Add Variable`.
     Set the variable name to **ADMIN** and the value to your admin password, then click `Save`.
   - Go back to the `Deployments` tab, click `Create New Deployment` in the bottom right, re-upload [main.zip](https://github.com/cmliu/edgetunnel/archive/refs/heads/main.zip) and click `Save and Deploy`.

2. Bind KV Namespace:
   - In the `Settings` tab, select `Bindings` > `+ Add` > `KV Namespace`, then choose an existing namespace or create a new one.
   - Set the `Variable name` to **KV**, then click `Save` and retry deployment.

3. Bind a CNAME Custom Domain to Pages: [Video Tutorial](https://www.youtube.com/watch?v=LeT4jQUh8ok&t=851s)
   - In the `Custom Domains` tab of the Pages console, click `Set up a custom domain` at the bottom.
   - Enter your custom subdomain — do not use your root domain. For example:
     If your assigned domain is `fuck.cloudns.biz`, enter `lizi.fuck.cloudns.biz` as the custom domain.
   - Follow CF's instructions to go to your DNS provider and add a CNAME record for `lizi` pointing to `edgetunnel.pages.dev`, then click `Activate Domain`.

4. Access the Admin Panel:
   - Visit `https://lizi.fuck.cloudns.biz/admin` and enter your admin password to log in.

</details>

### 🛠 Pages + GitHub Deployment

<details>
<summary><code><strong>「 Pages + GitHub Deployment Text Guide 」</strong></code></summary>

1. Deploy CF Pages:
   - First, fork this project on GitHub and give it a Star !!!
   - In the CF Pages console, select `Connect to Git`, choose the `edgetunnel` project, and click `Begin Setup`.
   - At the bottom of the `Set up builds and deployments` page, select `Environment Variables (Advanced)` and click `Add Variable`.
     Set the variable name to **ADMIN** and the value to your admin password, then click `Save and Deploy`.

2. Bind KV Namespace:
   - In the `Settings` tab, select `Bindings` > `+ Add` > `KV Namespace`, then choose an existing namespace or create a new one.
   - Set the `Variable name` to **KV**, then click `Save` and retry deployment.

3. Bind a CNAME Custom Domain to Pages: [Video Tutorial](https://www.youtube.com/watch?v=LeT4jQUh8ok&t=851s)
   - In the `Custom Domains` tab of the Pages console, click `Set up a custom domain` at the bottom.
   - Enter your custom subdomain — do not use your root domain. For example:
     If your assigned domain is `fuck.cloudns.biz`, enter `lizi.fuck.cloudns.biz` as the custom domain.
   - Follow CF's instructions to go to your DNS provider and add a CNAME record for `lizi` pointing to `edgetunnel.pages.dev`, then click `Activate Domain`.

4. Access the Admin Panel:
   - Visit `https://lizi.fuck.cloudns.biz/admin` and enter your admin password to log in.

</details>

---

## 🔑 Environment Variables

| Variable | Required | Example | Description |
| :--- | :---: | :--- | :--- |
| **ADMIN** | ✅ | `123456` | Admin panel login password |
| **KEY** | ❌ | `CMLiussss` | Quick subscription path key — visit `/CMLiussss` to quickly retrieve nodes |
| **UUID** | ❌ | `90cd4a77-141a-43c9-991b-08263cfe9c10` | Force a fixed UUID (must be **UUIDv4** format) |
| **PROXYIP** | ❌ | `proxyip.cmliussss.net:443` | Global custom reverse proxy IP |
| **URL** | ❌ | `https://cloudflare-error-page-3th.pages.dev` | Default homepage disguise URL (can be a webpage URL or `1101`) |
| **GO2SOCKS5** | ❌ | `blog.cmliussss.com`,`*.ip111.cn`,`*google.com` | Force-SOCKS5 domain list (`*` for global, comma-separated) |
| **DEBUG** | ❌ | `1` or `true` | **Developer mode** — debug logging (console.log) is off by default; set `1` or `true` to enable |
| **OFF_LOG** | ❌ | `1` or `true` | Logging is on by default; set `1` or `true` to disable |
| **BEST_SUB** | ❌ | `1` or `true` | **Preferred subscription generator** mode is off by default; set `1` or `true` to enable |

---

## 🔧 Advanced Tips

To change the **TOKEN in the subscription URL** and the **UUID used for node authentication**, modify the variables:
1. Changing the `ADMIN` or `KEY` variable value will randomly regenerate the **subscription URL token** and the **node authentication UUID**.
2. Setting the `UUID` variable forces a fixed **subscription URL token** and **node authentication UUID** — it must be in **UUIDv4** format, otherwise nodes will not work.

This tool supports dynamically switching the underlying proxy method via **URL path**:

- Specify `PROXYIP`
   ```url
   /proxyip=proxyip.cmliussss.net
   /?proxyip=proxyip.cmliussss.net
   ```

- Specify `SOCKS5`
   ```url
   /socks5=user:password@127.0.0.1:1080
   /?socks5=user:password@127.0.0.1:1080
   /socks://dXNlcjpwYXNzd29yZA==@127.0.0.1:1080 (activates global SOCKS5 by default)
   /socks5://user:password@127.0.0.1:1080 (activates global SOCKS5 by default)
   ```

- Specify `HTTP Proxy`
   ```url
   /http=user:password@127.0.0.1:1080
   /http://user:password@127.0.0.1:8080 (activates global SOCKS5 by default)
   ```

---

## 💻 Client Compatibility

| Platform | Recommended Clients | Notes |
| :--- | :--- | :--- |
| **Windows** | [v2rayN](https://github.com/2dust/v2rayN), [FlClash](https://github.com/chen08209/FlClash), [mihomo-party](https://github.com/mihomo-party-org/mihomo-party), [Clash Verge Rev](https://github.com/ClashVerge/ClashVerge-Rev) | Full support |
| **Android** | [ClashMetaForAndroid](https://github.com/MetaCubeX/ClashMetaForAndroid), [FlClash](https://github.com/chen08209/FlClash), [v2rayNG](https://github.com/2dust/v2rayNG) | Meta core recommended |
| **iOS** | [Surge](https://surgeapp.com/), [Shadowrocket](https://shadowrocket.com/), [Stash](https://stashapp.com/) | Perfect compatibility |
| **MacOS** | [FlClash](https://github.com/chen08209/FlClash), [mihomo-party](https://github.com/mihomo-party-org/mihomo-party), [Clash Verge Rev](https://github.com/ClashVerge/ClashVerge-Rev), [Surge](https://surgeapp.com/) | M1/M2 fully compatible |

---

## ⭐ Project Popularity

[![Stargazers over time](https://starchart.cc/cmliu/edgetunnel.svg?variant=adaptive)](https://starchart.cc/cmliu/edgetunnel)

---

## 🙏 Special Thanks
### 💖 Sponsors — providing cloud servers to maintain the [subscription conversion service](https://sub.cmliussss.net/)
- [NodeLoc](https://www.nodeloc.com/)
- [Alice](https://url.cmliussss.com/alice)
- [EasyLinks](https://www.vmrack.net?ref_code=5Zk7eNhbgL7)
- [ZMTO(VTEXS)](https://zmto.com/?affid=1532)

### 🛠 Open Source References
- [zizifn/edgetunnel](https://github.com/zizifn/edgetunnel)
- [3Kmfi6HP/EDtunnel](https://github.com/6Kmfi6HP/EDtunnel)
- [SHIJS1999/cloudflare-worker-vless-ip](https://github.com/SHIJS1999/cloudflare-worker-vless-ip)
- [Stanley-baby](https://github.com/Stanley-baby)
- [ACL4SSR](https://github.com/ACL4SSR/ACL4SSR/tree/master/Clash/config)
- [Stock Guru](https://t.me/CF_NAT/38889)
- [Workers/Pages Metrics](https://t.me/zhetengsha/3382)
- [Free Resources Guy](https://t.me/bestcfipas)
- [Mingyu](https://github.com/ymyuuu/workers-vless)
- [Alexandre Kojève](https://t.me/Enkelte_notif/784)
- [eooce](https://github.com/eooce/Cloudflare-proxy)
- [Sukka](https://ip.skk.moe/)
- [zhangtaile](https://github.com/cmliu/edgetunnel/pull/999)
- [1345695](https://github.com/1345695/edcloudwasm)

---

## ⚠️ Disclaimer

1. This project ("edgetunnel") is intended solely for **educational, scientific research, and personal security testing** purposes.
2. Users who download or use this project's code must strictly comply with the laws and regulations of their jurisdiction.
3. The author **cmliu** bears no responsibility for any actions or consequences resulting from misuse of this project's code.
4. This project is not liable for any direct or indirect damages arising from the use of its code.
5. It is recommended to delete all deployments related to this project within 24 hours of completing your tests.

---

**If you find this project helpful, please give it a Star 🌟 — it's the greatest encouragement for me!**