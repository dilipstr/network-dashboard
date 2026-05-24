# Network Dashboard

An interactive **network topology dashboard** built with **Vue.js** and **Electron**.  
Design, monitor, and manage your network visually — with real‑time ping checks and automatic email alerts.

---

## Features
- **Interactive Topology Builder**: Create and edit network diagrams with drag‑and‑drop nodes and connections.
- **Custom Styling**: Change colors, labels, and layouts to suit your visualization needs.
- **Node Monitoring**: Each node is continuously pinged to check connectivity.
- **SMTP Notifications**: If a node fails (no ping), an email alert is sent to the configured address.
- **Cross‑Platform**: Works seamlessly on Windows, macOS, and Linux.
- **Vue + Bootstrap + Electron Integration**: Modern frontend with desktop packaging.

---

## ScreenShots
<img width="1918" height="1016" alt="image" src="https://github.com/user-attachments/assets/5399222a-efbd-47a1-ae77-09de6043fab2" />
<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/81ec7663-ca28-44ac-b1c7-da0a2c8885d7" />
<img width="1918" height="1023" alt="image" src="https://github.com/user-attachments/assets/0a500c4d-748d-48a4-b198-d129cfcf0a5e" />



### Prerequisites
- Node.js (>= 18.x)
- npm or yarn

### Installation
```bash
git clone https://github.com/dilipstr/network-dashboard.git
cd network-dashboard
npm install
npm run electron:serve
