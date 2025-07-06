# 🎮 Hubdex Game Servers

Welcome to the official Hubdex self-hosted game servers repository.

All servers listed below are hosted on a private machine and are accessible **only via Tailscale**. This setup ensures secure, peer-to-peer connections between players and servers.

---

## 🔐 Access Requirements

To join any server, you **must** be connected to the Tailscale network.

- **Tailscale IP**: `100.117.199.89`
- Request access by contacting an admin
- Some servers may require a password

---

## 🌐 Available Servers

### 🧱 Minecraft (Java Edition)
- **IP**: `100.117.199.89:25565`
- **Version**: Latest Vanilla
- **Status**: Online 24/7

---

### ⚙️ Satisfactory Dedicated Server
- **Game Port**: `100.117.199.89:7777` (UDP)
- **Beacon Port**: `100.117.199.89:8888` (TCP)
- **Steam App ID**: `1690800`

---

### 🦇 V Rising
- **Game Port**: `100.117.199.89:9876` (UDP)
- **Query Port**: `100.117.199.89:9877` (UDP)

---

### 🔫 Rust (Test Server)
- **Game Port**: `100.117.199.89:28015` (UDP)
- **Admin Panel**: `100.117.199.89:9112` (TCP)

---

### 🛡️ Conan Exiles
- **Game Port**: `100.117.199.89:7778` (UDP)
- **Query Port**: `100.117.199.89:7779` (UDP)

---

## 🧭 How to Connect

1. Install and sign in to [Tailscale](https://tailscale.com)
2. Ensure you are connected to the same Tailscale network as the host
3. Launch your game
4. Use the provided IP and port to join
5. Ask an admin if a password is required

---

## 📢 Discord Integration

All updates and support are handled via our [Discord Server](https://discord.gg/TfQUXnus).

- `#game-servers`: Server list and connection info
- `#satisfactory`, `#v-rising`, `#conan-exiles`: Game-specific chats and updates
- `#general`: Support, questions, announcements

---

## 🧑‍💻 Admin Notes

This setup uses Docker containers on a bridged network. All ports are mapped securely and monitored. Tailscale ensures private access without exposing public IPs.

---

## 🛠 Future Plans

- ✅ Auto-updates for all servers via Docker
- ✅ Daily backup of worlds/save data
- 🔲 Web dashboards for each game (coming soon)
- 🔲 Event scheduling & custom mods

---

Happy gaming! 🎉  
— *Hubdex Admin Team*
