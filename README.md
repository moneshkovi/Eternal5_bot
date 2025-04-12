# Eternal5_bot 🎷🤖

**Eternal5_bot** is a full-featured Discord music and moderation bot built using Python and the `discord.py` library. It supports streaming from YouTube and Spotify, automates role-based server tasks, and provides an interactive experience through user-friendly commands. Designed for gaming and community servers, it offers private support communication, announcement broadcasting, and anti-spam control.

---

## 🔥 Features

- 🎵 Music playback from **YouTube** and **Spotify** playlists  
- 🛡️ Role-based permissions and command restrictions  
- 🛉 Auto DM system for anonymous user support  
- 📢 Role-based announcement broadcasting  
- 🪼 Message purge and spam control  
- ⎯️ Volume, pause, resume, skip, queue, now-playing  
- 🔐 Admin-only commands for secure server management  

---

## 📦 Requirements

### 🐍 Python Dependencies

```bash
aiohttp==3.6.2
async_timeout==3.0.1
asyncio==3.4.3
discord.py==1.5.1
requests==2.24.0
selenium==3.141.0
spotipy==2.13.0
youtube_dl==2020.9.14
discord.py[voice]~=0.16.0
colorlog
PyNaCl
wheel
ffmpeg
```

### 🖥️ Linux System Dependencies (Ubuntu-based)

```bash
sudo apt-get install libopus0 git libopus-dev libssl-dev libffi-dev libsodium-dev
sudo add-apt-repository ppa:mc3man/xerus-media -y
```

---

## ⚙️ Setup

1. **Clone the repository**
```bash
git clone https://github.com/moneshkovi/Eternal5_bot.git
cd Eternal5_bot
```

2. **Install Python packages**
```bash
pip install -r requirements.txt
```

3. **Set your bot token**
- Open `my_bot.py` and replace `client.run("YOUR_TOKEN")` with your bot token.

4. **Run the bot**
```bash
python my_bot.py
```

---

## 🧠 Skills & Tools Used

- **Programming Language**: Python  
- **Libraries**: `discord.py`, `asyncio`, `aiohttp`, `selenium`, `spotipy`, `youtube_dl`, `requests`  
- **APIs**: Spotify API, YouTube via youtube_dl  
- **System Tools**: `ffmpeg`, `libopus`, `libsodium`  
- **Deployment**: Heroku-compatible (Procfile, Aptfile, runtime.txt)  
- **Discord Features**: Voice streaming, role control, command routing  

---

## 📜 License

This project is licensed under the MIT License.

---

> Built with ❤️ for Eternal5 Discord Community

