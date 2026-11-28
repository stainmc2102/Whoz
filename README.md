<div align="center">

# 🔮 Whoz Bot

**A next-generation, high-performance Akinator Discord Bot powered by Discord Components V2**

<!-- Row 1: Core Stack -->
[![Discord.py](https://img.shields.io/badge/Discord.py-v2.4%2B-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discordpy.readthedocs.io/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![UI Engine](https://img.shields.io/badge/UI-Components%20V2-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/)
[![Architecture](https://img.shields.io/badge/Architecture-Asynchronous-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://docs.python.org/3/library/asyncio.html)

<!-- Row 2: Web & Services -->
[![Web Portal](https://img.shields.io/badge/Website-whoz.sotarstudio.online-FEA166?style=for-the-badge&logo=googlechrome&logoColor=white)](https://whoz.sotarstudio.online)
[![Languages](https://img.shields.io/badge/Languages-11%20Supported-339933?style=for-the-badge&logo=translate&logoColor=white)](https://whoz.sotarstudio.online/features#languages)
[![Engine](https://img.shields.io/badge/Engine-Akinator%20AI-E74C3C?style=for-the-badge&logo=gamepad&logoColor=white)](https://whoz.sotarstudio.online)
[![Session Isolation](https://img.shields.io/badge/Multi--Session-Isolated-47A248?style=for-the-badge&logo=statuspage&logoColor=white)](https://whoz.sotarstudio.online)

<!-- Row 3: Community & Hosting -->
[![Invite Bot](https://img.shields.io/badge/Invite-Add%20Whoz-2ECC71?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1574394999389429781&permissions=277025778752&scope=bot%20applications.commands)
[![Support Server](https://img.shields.io/badge/Support-Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://whoz.sotarstudio.online)
[![Hosting](https://img.shields.io/badge/Hosted%20By-Cloud%20VPS-00C7B7?style=for-the-badge&logo=serverfault&logoColor=white)](https://whoz.sotarstudio.online)
[![Uptime](https://img.shields.io/badge/Uptime-24%2F7%20Active-brightgreen?style=for-the-badge&logo=statuspage&logoColor=white)](https://whoz.sotarstudio.online)

<!-- Row 4: Status & Legal -->
[![Gateway Intents](https://img.shields.io/badge/Intents-Zero%20Privileged-2ECC71?style=for-the-badge&logo=discord&logoColor=white)](PRIVACY_POLICY.md#1-zero-privileged-gateway-intents-100-privacy-first-architecture)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Protected-brightgreen?style=for-the-badge&logo=lock&logoColor=white)](https://whoz.sotarstudio.online/terms#privacy)
[![License](https://img.shields.io/badge/License-Proprietary-E74C3C?style=for-the-badge&logo=git&logoColor=white)](LICENSE)
[![Bot Version](https://img.shields.io/badge/Version-v2.0.0-blueviolet?style=for-the-badge&logo=semver&logoColor=white)](https://github.com/stainmc2102/Whoz)

<br/>

[🌐 Web Portal](https://whoz.sotarstudio.online) • [➕ Invite Whoz](https://discord.com/oauth2/authorize?client_id=1574394999389429781&permissions=277025778752&scope=bot%20applications.commands) • [📖 Documentation](DOCS.md) • [📋 Terms of Service](TERMS_OF_SERVICE.md) • [🔒 Privacy Policy](PRIVACY_POLICY.md)

---

<img src="./assets/banner.png" alt="Whoz Banner" width="100%" />

</div>

## 📌 About Whoz

**Whoz** is a modern, interactive character-guessing game bot for Discord. Inspired by the legendary Akinator mind-reading experience, Whoz leverages the latest **Discord Components V2** architecture to deliver an ultra-responsive, zero-latency gameplay experience right inside your server.

Simply think of any character — whether a real-world celebrity, an anime icon, a game protagonist, a historical figure, or a fictional character — Whoz will ask intuitive questions and pinpoint exactly who you have in mind!

---

## ✨ Key Features

### 🧠 Intelligent Akinator Engine
* **High Guess Accuracy:** Queries a vast, continuously updated database of millions of global and pop-culture characters.
* **Isolated Multi-Session Architecture:** Multiple server members can play simultaneously in different channels or threads without cross-session interference or timeout drops.
* **Smart Fallback & Cloudscraper Integration:** Robust network failover ensures question prompts are delivered consistently without HTTP 429 delays.

### 📱 Discord Components V2 Interactive Interface
* **Sleek Select Menus:** Select answers directly from dropdown lists (`Yes`, `No`, `Don't Know`, `Probably`, `Probably Not`).
* **Instant Action Controls:** Step backwards to previous questions (`Back`), cancel active games (`Stop`), or immediately start rematches (`Play Again`).
* **Clean Channel Footprint:** All gameplay happens within a single updating message container, keeping your text channels clutter-free.

### 🌐 11 Global Languages Supported
* **Native Multi-Language Support:** Play seamlessly in English, French, Spanish, German, Italian, Japanese, Korean, Chinese, Russian, and Portuguese.
* **Smart Vietnamese Translation Engine:** Built-in dictionary and fast-path translation layer for natural, grammatically accurate Vietnamese questions.
* **Server-Wide Language Customization:** Administrators can easily configure the preferred language for their server via `/whoz language`.

### 📊 Player Statistics & Guild Settings
* **Lifetime Gameplay Metrics:** Tracks total matches played, Akinator guess accuracy, and win rates for each player.
* **Persistent Configuration:** Server-level settings are safely preserved across bot restarts.

### 🔒 Privacy-First Architecture (Zero Privileged Intents)
* **Zero Message Content Intent:** Whoz operates with `intents.message_content = False`. It does not request, need, or use Discord's privileged Message Content Intent.
* **Zero Chat Scraping:** The bot never reads, intercepts, or logs channel messages or private DMs. All actions are triggered explicitly through Slash Commands (`/whoz start`) and button interactions.
* **100% Policy Compliant:** Fully complies with Discord Developer Terms of Service, GDPR data minimization, and encryption at rest standards.

---

## 🚀 How to Add Whoz to Your Server

You do not need to host or install any software. Whoz is fully hosted, maintained, and operational 24/7.

1. **Invite the Bot:** Click the [Official Invite Link](https://discord.com/oauth2/authorize?client_id=1574394999389429781&permissions=277025778752&scope=bot%20applications.commands).
2. **Authorize Permissions:** Select your Discord server and confirm the required permissions (`Send Messages`, `Embed Links`, `Use Application Commands`).
3. **Start Playing:** Type `/whoz start` (or mention `@Whoz start`) in any text channel!
4. **Web Portal:** Visit [whoz.sotarstudio.online](https://whoz.sotarstudio.online) to explore features, command guides, and partner communities.

---

## 📖 Command Reference

### Slash Commands (`/`) — Primary & Recommended

| Command | Arguments | Description | Permission |
| :--- | :--- | :--- | :--- |
| `/whoz` | None | Opens the interactive welcome panel and quick-start menu | Everyone |
| `/whoz start` | None | Instantly begins a new character-guessing game session | Everyone |
| `/whoz stop` | None | Cancels your current active game session | Everyone |
| `/whoz back` | None | Steps back to the previous question if you answered by mistake | Everyone |
| `/whoz stats` | None | Displays your personal gameplay statistics and accuracy rate | Everyone |
| `/whoz language` | None | Opens the server language configuration dropdown | Administrator |
| `/whoz help` | None | Displays the comprehensive gameplay and rules guide | Everyone |

### Mention Commands (`@Whoz`)

You can also interact directly in chat by mentioning the bot:
* `@Whoz start` — Starts a new game session.
* `@Whoz whoz` — Launches the main game introduction panel.
* `@Whoz stop` — Ends the current game session.
* `@Whoz back` — Returns to the previous question.
* `@Whoz stats` — Views your gameplay profile.
* `@Whoz help` — Opens the guide menu.

---

## 📄 Policies & Documentation

* [Documentation](DOCS.md) — Comprehensive guide on configuring features and commands.
* [Terms of Service](TERMS_OF_SERVICE.md) — Rules and usage conditions for Whoz Bot and Web Portal.
* [Privacy Policy](PRIVACY_POLICY.md) — Information on data collection, privacy, and compliance.
* [Proprietary License](LICENSE) — Intellectual property rights and copyright notice.

---

<div align="center">

Developed with ❤️ for the Discord Community • **Whoz Team**  
*Whoz Bot is proprietary software. All rights reserved.*

</div>
