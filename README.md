<div align="center">

<!-- Animated Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=25D366&height=200&section=header&text=SHEHBAZ-MD&fontSize=80&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=WhatsApp+Multi-Device+Bot+v4.5.6&descAlignY=60&descSize=18&descColor=ffffff" width="100%"/>

<!-- Logo -->
<br/>
<img src="https://files.catbox.moe/9126wm.png" width="120" style="border-radius:50%"/>
<br/><br/>

<!-- Badges Row 1 -->
<img src="https://img.shields.io/badge/Version-4.5.6-brightgreen?style=for-the-badge&logo=github"/>
<img src="https://img.shields.io/badge/Node.js-20+-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge"/>

<br/>

<!-- Badges Row 2 -->
<img src="https://img.shields.io/badge/WhatsApp-Multi--Device-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
<img src="https://img.shields.io/badge/Baileys-Latest-blueviolet?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ES-Modules-yellow?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Free-Open%20Source-orange?style=for-the-badge"/>

<br/><br/>

<!-- Dynamic Stats -->
<a href="https://github.com/YOUR_USERNAME/SHEHBAZ-MD/stargazers">
  <img src="https://img.shields.io/github/stars/YOUR_USERNAME/SHEHBAZ-MD?style=social"/>
</a>
<a href="https://github.com/YOUR_USERNAME/SHEHBAZ-MD/forks">
  <img src="https://img.shields.io/github/forks/YOUR_USERNAME/SHEHBAZ-MD?style=social"/>
</a>
<a href="https://github.com/YOUR_USERNAME/SHEHBAZ-MD/watchers">
  <img src="https://img.shields.io/github/watchers/YOUR_USERNAME/SHEHBAZ-MD?style=social"/>
</a>

<br/><br/>

> ### 🤖 Free • Open Source • Multi-Device WhatsApp Bot
> *Apna khud ka professional WhatsApp bot banao — bilkul free!*

<br/>

<!-- Navigation -->
[![Installation](https://img.shields.io/badge/📦-Installation-25D366?style=flat-square)](#-installation)
[![Commands](https://img.shields.io/badge/📋-Commands-blue?style=flat-square)](#-commands)
[![Config](https://img.shields.io/badge/⚙️-Configuration-orange?style=flat-square)](#-configuration)
[![Plugins](https://img.shields.io/badge/🔌-Plugins-purple?style=flat-square)](#-add-your-own-plugin)
[![Support](https://img.shields.io/badge/💬-Support-red?style=flat-square)](#-support)

</div>

---

## 🌟 Feature Highlights

<div align="center">

|  | Feature | Status |
|:---:|---|:---:|
| 🔗 | Multi-Device Support | ✅ |
| 📱 | QR-less Phone Pairing | ✅ |
| ☁️ | MongoDB Cloud Sessions | ✅ |
| 👥 | Multi-Session (Multiple Numbers) | ✅ |
| ♻️ | Anti-Delete — catch deleted messages | ✅ |
| 📵 | Anti-Call — auto reject calls | ✅ |
| 🔗 | Anti-Link — block links in groups | ✅ |
| ⚡ | Auto-React with random emojis | ✅ |
| 👁️ | Auto-Read all messages | ✅ |
| 🤖 | Auto-Reply to DMs | ✅ |
| 📺 | Auto-View Statuses | ✅ |
| 🔄 | Auto-Reconnect on disconnect | ✅ |
| 🛡️ | Owner-Only command protection | ✅ |
| 🔌 | 20+ Built-in Plugins | ✅ |

</div>

---

## 📋 Commands

<details>
<summary><b>👥 Group Management Commands</b> — click to expand</summary>

<br/>

| Command | Description | Permission |
|---|---|:---:|
| `.tagall` | Tag all group members | 👑 Admin |
| `.tagall <message>` | Tag all with a custom message | 👑 Admin |
| `.kick @user` | Remove a member from group | 👑 Admin |
| `.promote @user` | Give admin rights to a member | 👑 Admin |
| `.demote @user` | Remove admin rights | 👑 Admin |
| `.hidetag <message>` | Tag all silently (list hidden) | 👑 Admin |
| `.mute on` | Lock the group (only admins can send) | 👑 Admin |
| `.mute off` | Unlock the group | 👑 Admin |
| `.grouplink` | Get the group invite link | 👑 Admin |
| `.warn @user` | Give a warning (3 warnings = auto kick) | 👑 Admin |
| `.resetwarn @user` | Clear all warnings for a user | 👑 Admin |
| `.warnlist` | View all active warnings in group | 👑 Admin |

</details>

<details>
<summary><b>🛠️ Tools & Utility Commands</b> — click to expand</summary>

<br/>

| Command | Description | Example |
|---|---|---|
| `.tiktok <url>` | Download TikTok video (no watermark) | `.tiktok https://vt.tiktok.com/xxx` |
| `.calc <expr>` | Calculator | `.calc 5*3+100/4` |
| `.wiki <topic>` | Wikipedia search | `.wiki Elon Musk` |
| `.fancy <text>` | 90+ fancy text styles | `.fancy Hello World` |
| `.weather <city>` | Live weather information | `.weather Karachi` |
| `.shorturl <link>` | Shorten any URL | `.shorturl https://example.com` |
| `.getpp @user` | Get a user's profile picture | `.getpp @919001234567` |

</details>

<details>
<summary><b>📸 Media Commands</b> — click to expand</summary>

<br/>

| Command | Description | How to use |
|---|---|---|
| `.sticker` | Convert image/video to sticker | Reply to image or video |
| `.take` | Rename an existing sticker | Reply to sticker with `.take Name Pack` |

</details>

<details>
<summary><b>👑 Owner-Only Commands</b> — click to expand</summary>

<br/>

| Command | Description |
|---|---|
| `.broadcast <message>` | Send a message to all groups at once |
| `.restart` | Restart the bot remotely |

> 🔐 These commands only work if your number is set as owner in `.env`

</details>

---

## 📦 Installation

<details>
<summary><b>✅ Requirements — what you need before starting</b></summary>

<br/>

| Requirement | Download | Notes |
|---|---|---|
| **Node.js v20+** | [nodejs.org](https://nodejs.org) | Check: `node --version` |
| **MongoDB Atlas** | [mongodb.com/atlas](https://mongodb.com/atlas) | Free tier is enough |
| **Git** | [git-scm.com](https://git-scm.com) | For cloning |
| **WhatsApp account** | — | The number you want to use for the bot |

</details>

<details open>
<summary><b>🚀 Step-by-Step Installation</b></summary>

<br/>

**Step 1 — Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/SHEHBAZ-MD.git
cd SHEHBAZ-MD
```

**Step 2 — Install dependencies**

```bash
npm install
```

> ⏳ This takes 1–2 minutes. Don't close the terminal.

**Step 3 — Set up your environment**

Rename `.env.example` to `.env`:

```bash
cp .env.example .env
```

Then open `.env` and fill in your values:

```env
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/shehbazmd
OWNER_NUMBER=923XXXXXXXXX
PORT=8000
```

<details>
<summary>📌 How to get your MongoDB URI</summary>

1. Go to [mongodb.com/atlas](https://mongodb.com/atlas) and sign up (free)
2. Create a new **Cluster** (free tier — M0)
3. Click **Connect → Drivers**
4. Copy the connection string
5. Replace `<password>` with your database password
6. Paste it as `MONGODB_URI` in your `.env` file

</details>

**Step 4 — Start the bot**

```bash
node index.js
```

</details>

---

## ⚡ Quick Pairing Guide

<details open>
<summary><b>📱 How to connect your WhatsApp number</b></summary>

<br/>

```
1. Run:  node index.js
2. Open: http://localhost:8000  in your browser
3. Enter your WhatsApp number with country code (no +)
         Example: 923001234567
4. A PAIRING CODE will appear on screen
5. On your phone:
   WhatsApp → Settings → Linked Devices
   → Link a Device → Link with Phone Number
6. Type the pairing code → Done! ✅
```

> 💡 **Tip:** The bot stores your session in MongoDB, so you won't need to pair again even after restart.

</details>

---

## ⚙️ Configuration

<details>
<summary><b>🔧 All settings explained — click to expand</b></summary>

<br/>

Open `setting.js` and customize everything:

```js
export default {

    // ── Basic Info ─────────────────────────────────────────
    BOT_NAME:        "SHEHBAZ-MD",     // Name shown in bot messages
    OWNER_NAME:      "Shehbaz",        // Your name
    PREFIX:          ".",               // Command prefix: . / ! / # etc.
    MODE:            "public",          // "public" = everyone can use
                                        // "private" = only owner

    // ── Auto Features ──────────────────────────────────────
    AUTO_REACT:       "true",          // React with random emoji to messages
    READ_MESSAGE:     "true",          // Auto-read all incoming messages
    AUTO_STATUS_SEEN: "true",          // Auto-view WhatsApp statuses

    // ── Protection ─────────────────────────────────────────
    ANTI_DELETE:      "true",          // Forward deleted messages to owner DM
    ANTI_CALL:        "true",          // Auto-reject incoming calls
    ANTI_LINK:        "false",         // Block links sent in groups

    // ── Auto Reply (DMs only) ──────────────────────────────
    AUTO_REPLY:       "false",         // Enable auto-reply in DMs
    AUTO_REPLY_MSG:   "Bot is active! Please wait.",
    AUTO_REPLY_DELAY: "60",            // Cooldown between replies (seconds)
}
```

</details>

---

## 🗂️ Project Structure

<details>
<summary><b>📁 Full folder structure explained</b></summary>

<br/>

```
SHEHBAZ-MD/
│
├── 📄 index.js              Main entry point — starts the bot
├── 📄 setting.js            Bot configuration (edit this!)
├── 📄 pair.js               Pairing web server
├── 📄 package.json          Node dependencies
├── 📄 .env                  Your secrets (never share this!)
├── 📄 .env.example          Template for new users
├── 📄 .gitignore            Excludes node_modules, sessions, .env
│
├── 📁 lib/
│   ├── command.js           cmd() helper for plugins
│   ├── commandRegistry.js   Routes commands to correct plugin
│   ├── mongoAuth.js         Saves/loads WhatsApp session in MongoDB
│   └── sessionManager.js    Handles multiple WhatsApp sessions
│
├── 📁 plugins/              All bot commands live here
│   ├── tiktok.js            📱 TikTok downloader (no watermark)
│   ├── sticker.js           🎨 Sticker maker
│   ├── group.js             👥 tagall, kick, promote, mute...
│   ├── warn.js              ⚠️  Warning system
│   ├── tools.js             🛠️  calc, wiki, weather, shorturl...
│   └── ...                  ➕ Add more plugins here!
│
└── 📁 public/
    └── pair.html            Web page for pairing
```

</details>

---

## 🔌 Add Your Own Plugin

<details>
<summary><b>💻 Plugin development guide — click to expand</b></summary>

<br/>

Create a new `.js` file inside the `plugins/` folder:

```js
// plugins/myplugin.js
import { cmd } from '../lib/command.js';

cmd({
    pattern: 'hello',            // Triggers on: .hello
    alias: ['hi', 'hey'],        // Also triggers on: .hi / .hey
    desc: 'Sends a greeting',
    category: 'fun',             // group / utility / download / fun / owner
    use: '.hello <name>'
}, async (sock, msg, ctx) => {

    const { from, reply, args, sender, isOwner, isGroup } = ctx;

    // Example: owner-only check
    if (!isOwner) return reply('❌ Only owner can use this!');

    // Example: group-only check
    if (!isGroup) return reply('❌ Use this inside a group!');

    // Get arguments the user typed after the command
    const name = args.join(' ') || 'World';

    reply(`👋 Hello, ${name}!`);

    // Send a media message
    await sock.sendMessage(from, {
        image: { url: 'https://example.com/image.jpg' },
        caption: 'Here is your image!'
    }, { quoted: msg });

});
```

**Available `ctx` properties:**

| Property | Type | Description |
|---|---|---|
| `from` | `string` | Chat ID (group or DM) |
| `reply(text)` | `function` | Send a quoted reply |
| `args` | `string[]` | Words after the command |
| `sender` | `string` | Sender's WhatsApp JID |
| `isGroup` | `boolean` | Is the chat a group? |
| `isOwner` | `boolean` | Is sender the owner? |
| `prefix` | `string` | The command prefix (`.`) |
| `command` | `string` | The command word used |

> ✅ Restart the bot after adding a new plugin — `node index.js`

</details>

---

## 🐛 Troubleshooting

<details>
<summary><b>Bot doesn't start or connect</b></summary>

- Check your `MONGODB_URI` in `.env` is correct and the cluster is active
- Run `node --version` — must be **v20 or higher**
- Look at the error message in terminal carefully

</details>

<details>
<summary><b>Commands are not responding</b></summary>

- Make sure you're using the correct prefix (default: `.`)
- In `private` MODE, only the owner number can use commands
- Check if your plugin loaded on startup (no error shown)

</details>

<details>
<summary><b>Pairing code not appearing</b></summary>

- Open `http://localhost:8000` in browser after starting bot
- Enter number **with country code, without `+`**
  - ✅ Correct: `923001234567`
  - ❌ Wrong: `+923001234567` or `03001234567`

</details>

<details>
<summary><b>My plugin doesn't load</b></summary>

Check for syntax errors:
```bash
node --check plugins/myplugin.js
```

Make sure it uses ES module syntax (`import`, not `require`).

</details>

<details>
<summary><b>Bot keeps disconnecting</b></summary>

- The bot auto-reconnects — wait 10–30 seconds
- If it keeps happening, check MongoDB connection
- Make sure your server/PC stays online 24/7

</details>

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=nodejs,mongodb,js,git,github&theme=dark"/>

| Technology | Version | Purpose |
|---|---|---|
| **Node.js** | 20+ | JavaScript runtime |
| **Baileys** | Latest | WhatsApp Web API |
| **MongoDB** | Atlas | Session & data storage |
| **Mongoose** | Latest | MongoDB ODM |
| **Express** | 5 | Web server (pairing UI) |
| **Axios** | Latest | HTTP requests in plugins |
| **wa-sticker-formatter** | Latest | Sticker creation |

</div>

---

## 🤝 Contributing

<details>
<summary><b>How to contribute to this project</b></summary>

<br/>

We welcome all contributions!

```bash
# 1. Fork this repo on GitHub
# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/SHEHBAZ-MD.git

# 3. Create a branch
git checkout -b feature/your-feature

# 4. Make changes and test them
# 5. Commit with a clear message
git commit -m "feat: add YouTube downloader plugin"

# 6. Push and open a Pull Request
git push origin feature/your-feature
```

**Commit message format:**
- `feat:` — new plugin or feature
- `fix:` — bug fix
- `docs:` — documentation
- `chore:` — maintenance

See [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines.

</details>

---

## 💬 Support

<div align="center">

| Platform | Link |
|---|:---:|
| 💬 WhatsApp Developer | [![Chat](https://img.shields.io/badge/Chat-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/923212844383) |
| 🐛 Report a Bug | [![Issues](https://img.shields.io/badge/Open_Issue-red?style=for-the-badge&logo=github)](../../issues/new?template=bug_report.md) |
| 💡 Request a Feature | [![Feature](https://img.shields.io/badge/Request_Feature-blue?style=for-the-badge&logo=github)](../../issues/new?template=feature_request.md) |

</div>

---

## 📜 License

This project is licensed under the **[MIT License](LICENSE)** — free to use, modify, and share.
Credit is appreciated but not required. 🙏

---

<div align="center">

<!-- Footer Wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=25D366&height=120&section=footer" width="100%"/>

**Made with ❤️ by [Shehbaz Dev](https://wa.me/923212844383)**

<br/>

*If this project helped you, give it a* ⭐ *— it means a lot!*

<br/>

> ⚡ *Powered by Shehbaz—Dev*

</div>
