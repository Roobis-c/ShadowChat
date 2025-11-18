# ShadowChat

ShadowChat is a **peer-to-peer, password-protected, one-to-one chat room** built with [PeerJS](https://peerjs.com/) and vanilla HTML/CSS/JS.

No account, no database, no server-side messages – just host, share a link, and chat.

---

## Features

- 🔐 **Password-protected rooms** – Guest must enter the correct room password.
- 🧑‍💻 **Named host & guest** – Both sides choose display names.
- 🔗 **One-click invite link**  
  - Room link is auto-generated and copied to clipboard when host creates a room.
  - Link includes `host` and `pw` as URL params to autofill for guests.
- ✅ **Host approval flow**
  - Host sees incoming join request with guest name.
  - Host can **Accept** or **Reject**.
  - Only one guest can be connected at a time.
- 💬 **Simple chat UI**
  - Bubble-style messages.
  - “You” alignment for your own messages.
  - System messages for status (joined, disconnected, rejected, etc.).
- 📱 **Responsive layout** – Works on desktop and mobile.

---

## Tech Stack

- **Frontend:** HTML5, CSS3, vanilla JavaScript
- **P2P communication:** [PeerJS](https://peerjs.com/) via CDN
- **Fonts:** Google Fonts – Kumbh Sans

There is **no backend server** for messages. PeerJS uses its own signaling server to establish direct P2P connections between browser clients.

---
