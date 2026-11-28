# Privacy Policy

**Effective Date: November 2026 | Version 2.2**

This Privacy Policy describes how **Whoz** ("we", "our", or "the Bot") handles data when you interact with our services on Discord and our official web portal ([https://whoz.sotarstudio.online](https://whoz.sotarstudio.online)).

---

## 1. Zero Privileged Gateway Intents (100% Privacy-First Architecture)

Whoz is designed from the ground up to respect user privacy and adhere strictly to the **Discord Developer Policy** and **Discord Developer Terms of Service**:

* **No Message Content Intent:** Whoz operates with standard gateway intents (`intents.message_content = False`). We **do not** request, enable, or utilize Discord's privileged Message Content Intent.
* **No Chat Reading or Scraping:** Whoz cannot read, process, monitor, or log private messages, channel chat history, or messages sent by users in any Discord server.
* **Modern Interaction Model:** All gameplay interactions occur exclusively via Discord Application Commands (Slash Commands such as `/whoz start`) and Discord Components V2 (interactive Buttons and Select Menus). The bot only receives interactions that users intentionally initiate.
* **Zero Guild Members Intent:** Whoz does not track, store, or scrape server member lists or presence data.

---

## 2. Information We Collect

Whoz adheres to a strict data minimization principle. We only collect the minimum technical data necessary to deliver the character-guessing game experience:

* **Discord User ID:** Stored to associate personal game statistics (total games played, akinator accuracy rate, and win/loss records) for the `/whoz stats` command.
* **Discord Server (Guild) ID:** Stored to remember server-wide configuration settings (such as the preferred language configured by administrators via `/whoz language`).
* **Active Gameplay Session State:** Temporarily held in volatile server memory (RAM) during an active game session (such as current question index and Akinator API progression).
* **We strictly NEVER collect:** Message contents, direct messages (DMs), user email addresses, IP addresses, real names, passwords, voice data, financial/payment information, or any Personally Identifiable Information (PII).

---

## 3. Data Retention & Storage Policy

* **Temporary Session Data:** In-memory game sessions are automatically purged immediately upon game conclusion, cancellation, or after 10 minutes of inactivity.
* **Persistent Gameplay Statistics:** User game statistics and server language preferences are stored until the user or server administrator requests deletion or executes a reset.
* **Data Encryption at Rest:** In strict compliance with Discord Developer Policy, all persistent data stored outside the Discord platform is encrypted at rest using industry-standard encryption protocols on secured cloud servers with restricted access controls.

---

## 4. User Rights & Data Deletion (GDPR Compliance)

Users and server owners retain full ownership and control over their data:

* **Instant Self-Service Reset:** You can permanently erase your stored gameplay statistics at any time by executing the in-game command:
  ```
  /whoz reset
  ```
* **Formal Deletion Requests:** You can request the complete and immediate erasure of all records associated with your Discord User ID or Server ID by:
  1. Joining our official Discord Support Server: [https://discord.gg/wYn5m8629q](https://discord.gg/wYn5m8629q)
  2. Submitting an erasure request via our web portal: [https://whoz.sotarstudio.online/terms#erasure](https://whoz.sotarstudio.online/terms#erasure)
  3. Contacting our support team via email: `support@whoz.sotarstudio.online`
  
  All formal deletion requests are processed and verified within 24 hours.

---

## 5. Third-Party Sharing

We do not sell, trade, license, or share user data with any third-party advertisers, data brokers, or commercial entities. API communication is limited strictly to upstream character-guessing engine queries without transmitting user personal identifiers.

---

## 6. Contact Information

For any inquiries, data privacy questions, or assistance, please reach out through our official channels:
* **Web Portal:** [https://whoz.sotarstudio.online](https://whoz.sotarstudio.online)
* **Terms & Privacy Page:** [https://whoz.sotarstudio.online/terms#privacy](https://whoz.sotarstudio.online/terms#privacy)
* **Discord Community:** [https://discord.gg/wYn5m8629q](https://discord.gg/wYn5m8629q)
* **Email:** `support@whoz.sotarstudio.online`
