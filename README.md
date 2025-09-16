# projects-portfolio

**This repository provides an overview of some of my IT projects, home lab setup, tools I've worked with, and technical hobbies.

---

## 🛠 Tools & Platforms I've Worked With

The following tools are part of my professional experience but are not listed on my CV:

- **Support & Collaboration:** Zendesk, RingCentral, Spearline  
- **Remote Access & Troubleshooting:** TeamViewer, VNC, AnyDesk  
- **Testing & Development:** Postman, Nmap  
- **Cloud & Identity Management:** Azure AD / Enterprise Applications (SSO)

---

## 🏠 Home Lab & IT Projects

I maintain a home server running **Proxmox** to explore virtualization, networking, and security concepts.

### Virtual Machines & Containers
- **pfSense VM** – Main firewall  
- **Pi-hole Container** – Ad blocking & local DNS  
- **Home Assistant VM** –  
  - Smart home automation (lights, alarms, Sonos, TVs)
  - LED matrix displays for time/date, events, stock prices, notifications
  - Centralized sensors (temperature, humidity)
  - MQTT broker (Mosquitto)
  - ZigBee gateway integration
- **Wazuh VM** – Monitoring and security event management  
- **Jellyfin Server** – Media streaming  
- **Ubuntu VM** – NFS server  
- **Linux Test VMs** – Ubuntu, Debian for experimentation

### pfSense Configuration Highlights
- Multiple interfaces (WAN, LAN) with **segmented VLANs**:
  - Main VLAN for trusted devices
  - IoT VLAN, VoIP VLAN, IP Camera VLAN, Guest VLAN  
- **Traffic Monitoring:** ntopng integration  
- **VPN:** OpenVPN server for remote access + selective VLAN routing through VPN  
- **Wi-Fi Setup:** Access points mapped to dedicated VLANs for better segmentation

---

## 🎨 Technical Projects & Hobbies

### 🔌 Electronics & Microcontrollers
- Programming **ESP32, ESP8266, Arduino**
- IoT Projects: crypto/stock ticker displays, WS2812B LED lighting setups, synchronized electronic targets for airsoft  
- Basic electronics repair: troubleshooting, component replacement

### 🖨️ 3D Design & Fabrication
- **CAD:** Fusion 360 for modeling
- **3D Printing:** Functional parts and prototypes using Creality printers  
  - Workflow with Cura slicer & OctoPrint server

### 🚁 Drones & Robotics
- Building and tuning custom drones (PID tuning, component selection)
- Programming flight controllers (Betaflight, F4 boards)
- Configuring RC transmitters & receivers (FrSky)
- Flying both assisted drones (DJI) and manual FPV drones (GEPRC, Mobula)
