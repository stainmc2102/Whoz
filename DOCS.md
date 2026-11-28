# 📖 Whoz Bot — Documentation & User Guide

Welcome to the official documentation for **Whoz**. This guide covers command usage, server configuration, and gameplay mechanics.

---

## 1. Getting Started

### Prerequisites & Permissions
Whoz requires only standard Discord permissions to operate:
- `View Channels`
- `Send Messages`
- `Embed Links`
- `Use Application Commands`

> **Note on Privileged Gateway Intents:**  
> Whoz requires **Zero Privileged Intents** (`MESSAGE_CONTENT` and `GUILD_MEMBERS` are both disabled: `intents.message_content = False`). Whoz operates 100% on Discord Slash Commands (`/`) and Components V2, never reading or storing guild chat messages.

### Adding Whoz to Your Server
1. Use the [Invite Link](https://discord.com/oauth2/authorize?client_id=1574394999389429781&permissions=277025778752&scope=bot%20applications.commands).
2. Choose a server where you have `Manage Server` or `Administrator` permissions.
3. Once authorized, Whoz is immediately available to all members.

---

## 2. Gameplay Mechanics

### Starting a Game
Type `/whoz start` (or mention `@Whoz start`). Whoz will initiate a game session and display Question #1.

### Answering Questions
Whoz uses **Discord Components V2 Select Menus**. Select one of the 5 options:
- **Yes (Đúng / Có):** Matches your character.
- **No (Sai / Không):** Does not match your character.
- **Don't Know (Không biết):** You are unsure.
- **Probably (Có lẽ đúng):** Likely true.
- **Probably Not (Có lẽ không):** Likely false.

### Correcting Mistakes
If you misclicked, click the **Back** button to return to the previous question.

### The Guess
When Whoz reaches high confidence (usually between 15–25 questions), it reveals the character with a photo and name.
- Click **Yes / Correct** if Whoz guessed correctly.
- Click **No / Wrong** if Whoz got it wrong, allowing the bot to continue asking further questions.

---

## 3. Server Configuration

### Language Settings (`/whoz language`)
Server administrators can change the default language used for all members:
1. Run `/whoz language` (or `/whoz` and choose language option).
2. Select your preferred language from the dropdown menu (11 languages supported).
3. The bot immediately applies the language server-wide.

---

## 4. Player Statistics

Track your personal achievements via `/whoz stats`:
- **Total Games Played:** Number of matches completed.
- **Accuracy Rate:** Percentage of correct guesses made by Whoz against your characters.
- **Rank & Level:** Community standing.

---

## 5. Support & Links

- **Official Web Portal:** [https://whoz.sotarstudio.online](https://whoz.sotarstudio.online)
- **Features Guide:** [https://whoz.sotarstudio.online/features](https://whoz.sotarstudio.online/features)
- **Commands List:** [https://whoz.sotarstudio.online/commands](https://whoz.sotarstudio.online/commands)
