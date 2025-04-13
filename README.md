# 🌐 Public Proxy Lists

Frequently updated proxy lists sorted by protocol, providing easy access to free HTTP, HTTPS, SOCKS, and mixed proxies.

## ✨ Description

This repository offers a collection of frequently updated public proxy lists, categorized by protocol. The proxies are tested for their validity every 20 minutes to ensure they remain fresh and reliable.

## 🚀 Features

- **Multiple Protocol Support**: Access to HTTP, HTTPS, SOCKS4, and SOCKS5 proxies.
- **Elite and Anonymous Proxies**: Filtered lists of elite and anonymous level public proxies.
- **Transparent Proxies**: List for transparent proxies.
- **Refresh Rate**: All proxy lists are refreshed every 20 minutes.

## 🛠️ Installation

No installation is required. Simply clone the repository to access the proxy files:

```sh
git clone https://github.com/gag3301v/public-proxy-lists.git
```

## 📦 Usage

To use a proxy from one of the provided lists, simply read the file and select a proxy at random. Here’s an example in Python:

```python
import random

# Read proxies from all.txt
with open('all.txt', 'r') as file:
    proxies = file.readlines()

# Select a random proxy
proxy = random.choice(proxies).strip()
print(f"Using proxy: {proxy}")
```

## 🔧 Configuration

No configuration is required. The files are plain text and can be used directly.

## 🧪 Tests

There are no tests available for this repository as it is a collection of static data.

## 📁 Project Structure

- `all.txt`: All working proxies (mixed types)
- `http.txt`: Only working HTTP proxies
- `https.txt`: Only working HTTPS proxies
- `socks5.txt`: Only working SOCKS5 proxies
- `socks4.txt`: Only working SOCKS4 proxies
- `elite.txt`: Elite level public proxies
- `anonymous.txt`: Anonymous Level Proxies
- `transparent.txt`: Transparent Level Proxies

## 🙌 Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue. Pull requests are also appreciated.

## 📄 License

This list is free to use and redistribute under the [MIT License](LICENSE).

---

> ⚠️ Use proxies responsibly. Do not use them for illegal activities.

---

If you find this helpful, consider starring the repo or contributing back! You can also support the project by donating here:
👉 [Buy me a coffee](https://ko-fi.com/photowizard99)