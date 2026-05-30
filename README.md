# SCRIPCCP — VPN Autoscript Premium

Script otomatis instalasi server VPN multi-protokol untuk Ubuntu 20.04 / Debian 10.

---

## ⚡ INSTALL SCRIPT
```bash
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/xyzstoree/scripccp/main/ubu20-deb10-stable.sh && chmod +x ubu20-deb10-stable.sh && ./ubu20-deb10-stable.sh
```

## 🔄 UPDATE SCRIPT
```bash
wget -q https://raw.githubusercontent.com/xyzstoree/scripccp/main/update.sh && chmod +x update.sh && ./update.sh
```

## 🤖 INSTALL BOT TELEGRAM
```bash
wget -q https://raw.githubusercontent.com/xyzstoree/scripccp/main/bot/bot.sh && chmod +x bot.sh && ./bot.sh
```

---

## ✅ OS yang Didukung
- **Debian 10** *(Disarankan)*
- Ubuntu 20.04 LTS

## 🛡️ Protokol yang Tersedia
- VLESS WebSocket & gRPC
- VMess WebSocket & gRPC
- Trojan WebSocket
- Shadowsocks WebSocket
- SSH + Dropbear + SlowDNS
- OpenVPN (TCP/UDP)
- UDP Custom

## 🔧 Layanan Pendukung
- HAProxy (Multi-port: 80, 443, 8080, 8443, dll)
- Nginx Reverse Proxy
- BBR Congestion Control
- Fail2Ban
- Limit IP & Quota Bandwidth
- Bot Panel Telegram

---

> **Author:** xyzstoree  
> **Arsitektur:** x86_64 (KVM/XEN only, OpenVZ tidak didukung)
