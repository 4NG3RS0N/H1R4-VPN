
> **H1R4 VPN** is a lightweight Python-based VPN controller that leverages **OpenVPN** to establish secure, encrypted connections.  
Built for simplicity, speed, and low-resource environments.

---

# 🚀 Features

- 🔐 Secure VPN connection via OpenVPN  
- ⚡ Lightweight and fast (minimal dependencies)  
- 🧠 CLI-based control (simple and intuitive)  
- 🌍 Supports `.ovpn` configuration files  
- 🔎 Public IP check (before & after connection)  
- 📡 Connection status monitoring  
- 🧩 Easily extendable  

---

# 📦 Requirements

- Python 3.x  
- OpenVPN installed on your system  

# Install OpenVPN

- **Linux (Debian/Ubuntu):**
  ```bash
  sudo apt update
  sudo apt install openvpn

# ⚙️ Installation
git clone https://github.com/4ng3rs0n/h1r4-vpn.git
cd h1r4-vpn
pip install -r requirements.txt


# 🖥️ Usage

# ▶️ Connect to VPN
python h1r4_vpn.py connect config.ovpn

# ⛔ Disconnect VPN
python h1r4_vpn.py disconnect

# 📊 Check Status
python h1r4_vpn.py status

---

# 🔍 Example Output
[+] Launching H1R4 VPN...
[+] Current IP: 192.168.1.10
[~] Connecting...
[✓] Connected successfully!
[+] New IP: 185.x.x.x

---

# 🧠 How It Works

H1R4 VPN acts as a wrapper around the OpenVPN client:

Uses Python's subprocess module to start/stop OpenVPN
Reads .ovpn config files provided by the user
Monitors connection status
Fetches public IP using external API

# 🧩 Optional Features

🔄 Auto-reconnect on drop
📝 Logging system
🕶️ Stealth mode (minimal output)

---

# ⚠️ Disclaimer

This project is for educational and personal use only & I'm not responsable for your actions.

# 🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss your ideas.

# 📜 License

No License lol hhhh

---

# 💡 Vision

H1R4 VPN is designed as a foundation, nothing big
a small spark that can evolve into a full-featured privacy tool.
