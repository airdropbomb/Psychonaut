# 🚀 Psychonaut BOT

> Automated daily check-in solution for efficient crypto farming and multi-account management

[![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/vonssy/Psychonaut-BOT.svg)](https://github.com/vonssy/Psychonaut-BOT/stargazers)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Proxy Recommendation](#proxy-recommendation)
- [Support](#support)
- [Contributing](#contributing)

## 🎯 Overview

Psychonaut BOT is an automated tool designed to claim daily check-in operations across multiple accounts. It provides seamless integration and offers robust proxy support for enhanced security and reliability.

**🔗 Get Started:** [Register on Psychonaut](https://psy.xyz/psychonaut?icode=AF7F17A6)
**🎁 Use My Code:** `AF7F17A6`

> **Important:** Connect new evm wallet.

## ✨ Features

- 🔄 **Automated Account Management** - Retrieve account information automatically
- 🌐 **Flexible Proxy Support** - Run with or without proxy configuration
- 🔀 **Smart Proxy Rotation** - Automatic rotation of invalid proxies
- ⏰ **Daily Check-In** - Automated daily check-in
- 👥 **Multi-Account Support** - Manage multiple accounts simultaneously

## 📋 Requirements

- **Python:** Version 3.9 or higher
- **pip:** Latest version recommended
- **Compatible libraries:** eth-account and eth-utils (see requirements.txt)
- **2captcha Key:** For automated captcha turnstile solving

## 🛠 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/airdropbomb/Psychonaut.git && cd Psychonaut
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
# or for Python 3 specifically
pip3 install -r requirements.txt
```

### 3. Library Version Management

> ⚠️ **Important:** Ensure library versions match those specified in `requirements.txt`

**Check installed library version:**
```bash
pip show library_name
```

**Uninstall conflicting library:**
```bash
pip uninstall library_name
```

**Install specific library version:**
```bash
pip install library_name==version
```

## ⚙️ Configuration

### 2captcha Key Setup

Create or edit `2captcha_key.txt` in the project directory:

```
your_2captcha_key
```

### Account Setup

Create or edit `accounts.txt` in the project directory:

```
your_private_key_1
your_private_key_2
your_private_key_3
```

### Proxy Configuration (Optional)

Create or edit `proxy.txt` in the project directory:

```
# Simple format (HTTP protocol by default)
192.168.1.1:8080

# With protocol specification
http://192.168.1.1:8080
https://192.168.1.1:8080

# With authentication
http://username:password@192.168.1.1:8080
```

## 🚀 Usage

Run the bot using one of the following commands:

```bash
python bot.py
# or for Python 3 specifically
python3 bot.py
```

### Runtime Options

When starting the bot, you'll be prompted to choose:

1. **Proxy Mode Selection:**
   - Option `1`: Run with proxy
   - Option `2`: Run without proxy

2. **Auto-Rotation:** 
   - `y`: Enable automatic invalid proxy rotation
   - `n`: Disable auto-rotation

**Made with ❤️ by [vonssy](https://github.com/vonssy)**

*Thank you for using Psychonaut BOT! Don't forget to ⭐ star this repository.*

</div>
