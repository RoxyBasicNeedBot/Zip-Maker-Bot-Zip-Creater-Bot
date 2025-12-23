<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=header&animation=twinkling" width="100%" />
</p>

<p align="center">
  <img src="https://i.ibb.co/Rph1Bs8q/file-29680.jpg" alt="Zip Maker Bot Advanced" width="700" style="border-radius: 20px; box-shadow: 0 0 30px #00d9ff;" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="700" />
</p>

<h1 align="center">⚡ ADVANCED ZIP MAKER BOT ⚡</h1>

<h3 align="center">🤖 Powerful Telegram File Archiver & Downloader Bot</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pyrogram-2.0+-FF6B6B?style=for-the-badge&logo=telegram&logoColor=white" alt="Pyrogram" />
  <img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/Build-Passing-brightgreen?style=flat-square" alt="Build" />
  <img src="https://img.shields.io/badge/Maintained-Yes-blue?style=flat-square" alt="Maintained" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=18&pause=1000&color=F75C7E&center=true&vCenter=true&width=700&lines=Create+ZIP%2C+RAR%2C+7z+Archives+from+Telegram+Files!;Download+from+Direct+Links+%26+Cloud+Services!;Premium+Features+%7C+Custom+Thumbnails+%7C+Folders!" alt="Features Typing" />
</p>

<p align="center">
  <a href="https://t.me/ZipMakerroxyBot">
    <img src="https://img.shields.io/badge/🚀_TRY_BOT_NOW-00D9FF?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0088cc" alt="Try Bot" height="50" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=14&duration=2000&pause=500&color=00D9FF&center=true&vCenter=true&width=400&lines=👆+Click+above+to+try+the+bot+live!+👆" alt="Try Bot Hint" />
</p>

---

<div align="center">

## ✨ Features at a Glance

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

</div>

<div align="center">

| 🚀 Feature | 📝 Description |
|:---:|:---:|
| 📦 **Archive Creator** | Create ZIP, RAR, 7z archives from Telegram files |
| 🔗 **Direct Link Support** | Download from multiple cloud services & direct links |
| 📁 **Folder Manager** | Organize files into custom folders |
| 🖼️ **Custom Thumbnails** | Set personalized thumbnails for your archives |
| 🔐 **Password Protection** | Secure your archives with passwords |
| 📊 **Progress Tracking** | Real-time progress bars with time estimates |
| 👥 **Multi-User Support** | Handle multiple users simultaneously |
| 📢 **Admin Controls** | Ban/Unban users, Broadcast messages |
| ⚡ **Force Subscribe** | Optional channel subscription verification |

</div>

---

<div align="center">

## 🎮 Bot Commands

<img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="100">

</div>

<div align="center">

### 👤 User Commands

| Command | Description |
|:---:|:---:|
| `/start` | ⚡ Start the bot and get welcome message |
| `/help` | 🆘 Get help guide and usage instructions |
| `/create` | 📦 Create Archive (ZIP/RAR/7z) from your files |
| `/files` | 📁 View queued files in your list |
| `/addthumb` | 🖼️ Set custom thumbnail for archives |
| `/delthumb` | 🗑️ Delete your saved thumbnail |
| `/viewthumb` | 👀 View your current thumbnail |
| `/stats` | 📊 View bot statistics |
| `/cancel` | 🚫 Cancel current operation |

### 👑 Admin Commands

| Command | Description |
|:---:|:---:|
| `/ban` | ⛔ Ban a user from using the bot |
| `/unban` | ✅ Unban a previously banned user |
| `/cast` | 📢 Broadcast message to all users |

</div>

---

<div align="center">

## ⚙️ Environment Variables

</div>

### 📝 How to Get Your Credentials

| Variable | Where to Get |
|:---------|:-------------|
| `API_ID` | Go to [my.telegram.org](https://my.telegram.org) → Login → API Development Tools → Copy **App api_id** |
| `API_HASH` | Same page as above → Copy **App api_hash** |
| `BOT_TOKEN` | Open [@BotFather](https://t.me/BotFather) on Telegram → `/newbot` → Copy the token |
| `MONGODB_URI` | Create free cluster at [MongoDB Atlas](https://www.mongodb.com/atlas) → Connect → Copy connection string |
| `OWNER_ID` | Open [@useridroxybot](https://t.me/useridroxybot) on Telegram → It will show your user ID |
| `LOG_CHANNEL` | Create a channel → Add bot as admin → Forward any message to [@useridroxybot](https://t.me/useridroxybot) to get channel ID |

### 🔧 Configuration

```env
# Get API_ID and API_HASH from https://my.telegram.org
API_ID=your_api_id
API_HASH=your_api_hash

# Get BOT_TOKEN from @BotFather on Telegram
BOT_TOKEN=your_bot_token

# MongoDB connection string (get from MongoDB Atlas or your MongoDB server)
MONGODB_URI=your_mongodb_connection_string
DATABASE_NAME=your_database_name

# Server settings
PORT=8080
HOST=0.0.0.0

# Your Telegram user ID (get from @userinfobot)
OWNER_ID=your_telegram_user_id

# Log channel ID (create a channel and get its ID)
LOG_CHANNEL=your_log_channel_id

# Admin IDs (space or comma separated for multiple admins)
ADMIN_IDS=admin_id_1 admin_id_2

# Force Subscribe Settings (set to true to enable)
FORCE_SUB_ENABLED=false
# Channel IDs for force subscribe (max 3, space or comma separated)
# Use channel ID like -1001234567890 or username like @channelname
FORCE_SUB_CHANNELS=-1001234567890 -1009876543210
```

---

<div align="center">

## 🚀 Deployment

<img src="https://user-images.githubusercontent.com/74038190/212750147-854a394f-fee9-4080-9770-78a4b7ece53f.gif" width="400">

### Deploy to your favorite platform

</div>

<p align="center">
  <a href="https://dashboard.heroku.com/new?template=https://github.com/RoxyBasicNeedBot/zip-maker-bot">
    <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku" height="40" />
  </a>
</p>

<p align="center">
  <a href="https://dashboard.render.com/select-repo?type=web">
    <img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render" height="40" />
  </a>
</p>

<p align="center">
  <a href="https://app.koyeb.com/deploy?type=git&repository=github.com/RoxyBasicNeedBot/zip-maker-bot">
    <img src="https://www.koyeb.com/static/images/deploy/button.svg" alt="Deploy to Koyeb" height="40" />
  </a>
</p>

<p align="center">
  <a href="https://railway.app/template">
    <img src="https://railway.app/button.svg" alt="Deploy on Railway" height="40" />
  </a>
</p>

<div align="center">

### Other Deployment Options

<p>
  <a href="https://heroku.com">
    <img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white" alt="Heroku" />
  </a>
  &nbsp;
  <a href="https://render.com">
    <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white" alt="Render" />
  </a>
  &nbsp;
  <a href="https://koyeb.com">
    <img src="https://img.shields.io/badge/Koyeb-121212?style=for-the-badge&logo=koyeb&logoColor=white" alt="Koyeb" />
  </a>
  &nbsp;
  <a href="https://railway.app">
    <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" alt="Railway" />
  </a>
</p>

<p>
  <a href="https://www.docker.com">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  </a>
  &nbsp;
  <a href="https://www.linux.org">
    <img src="https://img.shields.io/badge/VPS_Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="VPS" />
  </a>
</p>

</div>

---

<div align="center">

## 🐳 Docker Deployment

</div>

```bash
# Clone the repository
git clone https://github.com/RoxyBasicNeedBot/zip-maker-bot.git
cd zip-maker-bot

# Create .env file with your variables
cp .env.example .env

# Run with Docker Compose
docker-compose up -d
```

---

<div align="center">

## 📱 Connect With Me

<img src="https://user-images.githubusercontent.com/74038190/235294012-0a55e343-37ad-4b0f-924f-c8431d9d2483.gif" width="300">

</div>

<p align="center">
  <a href="https://t.me/roxybasicneedbot1">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  &nbsp;
  <a href="https://youtube.com/@roxybasicneedbot">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
  &nbsp;
  <a href="https://instagram.com/roxybasicneedbot1">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/RoxyBasicNeedBot">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  &nbsp;
  <a href="https://roxybasicneedbot.unaux.com/?i=1">
    <img src="https://img.shields.io/badge/Website-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" />
  </a>
  &nbsp;
  <a href="https://aratt.ai/@roxybasicneedbot">
    <img src="https://img.shields.io/badge/Portfolio-00D9FF?style=for-the-badge&logo=aboutdotme&logoColor=white" alt="Portfolio" />
  </a>
</p>

---

<div align="center">

## 🛠️ Tech Stack

<img src="https://skillicons.dev/icons?i=python,mongodb,docker,linux,git,github&theme=dark" />

</div>

---

<div align="center">

## 🙏 Support

If you found this project helpful, please consider:

<a href="https://github.com/RoxyBasicNeedBot/zip-maker-bot">
  <img src="https://img.shields.io/badge/⭐_Star_this_Repo-FFD700?style=for-the-badge" alt="Star Repo" />
</a>
&nbsp;
<a href="https://t.me/roxybasicneedbot1">
  <img src="https://img.shields.io/badge/📢_Join_Telegram-2CA5E0?style=for-the-badge" alt="Join Telegram" />
</a>

</div>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=150&section=footer&text=Made%20with%20❤️%20by%20RoxyBasicNeedBot&fontSize=24&fontColor=fff&animation=twinkling" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=14&pause=1000&color=F75C7E&center=true&vCenter=true&width=500&lines=Bot+%26+Website+Developer+🤖;Creator+of+Roxy+BasicNeedBot;Python+%7C+APIs+%7C+Web+Development" alt="Typing SVG" />
</p>

<h3 align="center">
  <img src="https://img.shields.io/badge/©_2025-RoxyBasicNeedBot-FF6B6B?style=for-the-badge" alt="Copyright" />
</h3>

<p align="center">
  <b>© 2025 RoxyBasicNeedBot. All Rights Reserved.</b>
</p>

---

<p align="center">
  <sub>
    ⚡ Created with passion by <a href="https://t.me/roxybasicneedbot1">RoxyBasicNeedBot</a> ⚡
  </sub>
</p>
