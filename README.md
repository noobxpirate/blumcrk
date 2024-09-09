# 🎉 Blum Crack

Blumcrk is an automated tool designed for auto-claiming rewards and completing tasks on the Blum platform (@blum). With proxy support, multi-account management, and task automation, Blumtod makes the process easier and faster.

## ⚠️ Warning

All risks are borne by the user. Use this script responsibly and at your own discretion.

## ✨ Features

- ✅ Auto-Claim (Daily Rewards, Referral Bonuses)
- ✅ Auto-Task Completion
- ✅ Auto Play Game (Random Inputs)
- ✅ Multi-Account Support
- ✅ Proxy Integration (Optional)
- ✅ Customizable via Config.json

## 🚀 Installation

### Requirements

- Python 3.8 or higher
- Git

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/noobxpirate/blumcrk.git
   cd blumcrk
   ```

2. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Edit the `data.txt` file to include your account tokens. Each line should contain one token.

4. Run the bot:

   ```bash
   python bot.py
   ```

## 🌐 Proxy Setup

To use a proxy, add your proxy details to the `proxies.txt` file. The format should be like this:

```
http://user:pass@host:port
```

### Example:

```
http://127.0.0.1:6969
http://user:pass@127.0.0.1:6969
```

## 💻 Run 24/7

To keep the bot running 24/7, use a VPS or terminal screen utility for Linux:

```bash
screen -S blumtod python bot.py
```

## 🛠️ How to Extract Data

To extract Telegram data on Desktop:

1. Open Telegram Desktop.
2. Run the following JavaScript command in the browser console to get your data:

   ```javascript
   copy(Telegram.WebApp.initData)
   ```

3. Paste the data in your `data.txt` file.

## 📥 Update the Repository

To update your local copy of the Blumcrk repository, run:

```bash
git pull origin main
```

## 💬 Discussion

Join the discussion here: [@piratexchat](https://t.me/piratexchat)

