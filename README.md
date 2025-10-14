<div align="center">

# 🔍 Anveshak

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=The+Explorer+%2F+Detector;Securing+Critical+Infrastructure;AI+%2B+Blockchain+Powered;Smart+India+Hackathon+2025" alt="Typing SVG" />

### 🛡️ *Real-Time Threat Detection for Nation's Critical Security*

[![Made with Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Blockchain](https://img.shields.io/badge/Blockchain-121D33?style=for-the-badge&logo=blockchain.com&logoColor=white)](https://blockchain.com/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

**Developed by Team BruteForce Coders 🇮🇳**

[🚀 Get Started](#-quick-start) • [📖 Documentation](#-about-the-project) • [🎯 Features](#-key-features) • [🏗️ Architecture](#️-system-architecture)

</div>

---

## 📖 About the Project

<img align="right" src="https://user-images.githubusercontent.com/74038190/229223156-0cbdaba9-3128-4d8e-8719-b6b4cf741b67.gif" width="300">

**Anveshak** (*Sanskrit: अन्वेषक* - meaning *Explorer/Detector*) is a cutting-edge **cybersecurity platform** engineered for **real-time threat detection** in:

- 🏭 **Nuclear Plants**
- 🎖️ **Defense Systems** 
- 🏛️ **Critical Infrastructure**

Our platform ensures **secure monitoring**, **transparent incident tracking**, and **tamper-proof storage** through the powerful combination of **Blockchain technology** and **AI-driven analytics**.

> 🏆 Built for **Smart India Hackathon (SIH) 2025**

<br clear="right"/>

---

## 🚨 The Problem

<div align="center">

```ascii
╔══════════════════════════════════════════════════════════════╗
║           ⚠️  CRITICAL INFRASTRUCTURE UNDER SIEGE            ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  🦠  Malware Injections & Ransomware Attacks                ║
║  🔑  Insider Threats & Unauthorized Access                  ║
║  📝  Tampered or Deleted System Logs                        ║
║  ⏱️  Delayed Detection & Response Times                     ║
║  🔓  Weak Log Integrity Systems                             ║
║  🎯  No Unified Monitoring System                           ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

Cyber threats to **critical infrastructure** are escalating at an alarming rate. Traditional security systems fail due to fragmented monitoring, poor log integrity, and lack of real-time response capabilities.

---

## ✅ Our Solution

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="500">
</div>

**Anveshak** provides a **unified security ecosystem** that bridges the gap between threat detection and response:

<table>
<tr>
<td width="50%">

### 🎯 Core Capabilities
- 🔹 **Real-time Incident Monitoring**
- 🔹 **Live Dashboard & Analytics**
- 🔹 **Blockchain-backed Logs** 🔒
- 🔹 **Automated Alerts & Notifications**

</td>
<td width="50%">

### 🚀 Key Benefits
- ⚡ **Instant Threat Detection**
- 📊 **Data-Driven Insights**
- 🛡️ **Tamper-Proof Security**
- 🌐 **Multi-Agency Scalability**

</td>
</tr>
</table>

---

## 🌟 Key Features

<div align="center">

| Feature | Description |
|---------|-------------|
| 📝 **Incident Reporting** | Securely log anomalies, intrusions, or threats with timestamp verification |
| 📊 **Admin Dashboard** | Interactive charts, real-time updates & comprehensive analytics |
| ⛓️ **Blockchain Integration** | Immutable, verifiable incident storage with cryptographic proof |
| 👥 **Role-based Access Control** | Granular permissions for Admins, Operators & Analysts |
| 🕵️ **Forensic Analysis** | Complete historical traceability for security audits |
| 🔔 **Smart Notifications** | Automated alerts via multiple channels |
| 📈 **Predictive Analytics** | AI-powered threat pattern recognition |

</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284136-03988914-d899-44b4-b1d9-4eeccf656e44.gif" width="600">
</div>

---

## 🏗️ System Architecture

```mermaid
flowchart TB
    subgraph Frontend["🌐 Frontend Layer"]
        A[HTML/CSS/JavaScript]
        B[Dashboard UI]
        C[Incident Forms]
    end
    
    subgraph API["⚡ API Gateway"]
        D[Express.js Router]
        E[Authentication Middleware]
        F[Request Validator]
    end
    
    subgraph Backend["⚙️ Backend Services"]
        G[Node.js Core]
        H[Business Logic]
        I[Data Processor]
    end
    
    subgraph Storage["💾 Data Layer"]
        J[(MongoDB)]
        K[Incident Records]
        L[User Logs]
    end
    
    subgraph Blockchain["⛓️ Blockchain Layer"]
        M[Smart Contracts]
        N[Immutable Ledger]
        O[Cryptographic Proof]
    end
    
    subgraph Analytics["📊 Analytics Engine"]
        P[Real-time Processing]
        Q[Alert System]
        R[Report Generator]
    end
    
    A --> D
    B --> D
    C --> D
    D --> G
    E --> G
    F --> G
    G --> J
    H --> J
    I --> J
    J --> M
    K --> M
    L --> M
    M --> P
    N --> P
    O --> P
    P --> Q
    P --> R
    
    style Frontend fill:#00d4ff,stroke:#0099cc,stroke-width:3px
    style API fill:#ff9900,stroke:#cc7700,stroke-width:3px
    style Backend fill:#00ff88,stroke:#00cc66,stroke-width:3px
    style Storage fill:#ff66ff,stroke:#cc44cc,stroke-width:3px
    style Blockchain fill:#ffff00,stroke:#cccc00,stroke-width:3px
    style Analytics fill:#ff4444,stroke:#cc0000,stroke-width:3px
```

---

## 💻 Tech Stack

<div align="center">

### 🌐 Frontend Technologies

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Clean UI/UX with dynamic dashboards, interactive charts, and real-time incident logs**

### ⚙️ Backend Technologies

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**RESTful APIs with MongoDB for incident & log storage**

### 🔗 Blockchain Layer

![Blockchain](https://img.shields.io/badge/Blockchain-121D33?style=for-the-badge&logo=blockchain.com&logoColor=white)

</div>

<details>
<summary><b>🔒 Why Blockchain? Click to expand</b></summary>

<br>

| Advantage | Benefit |
|-----------|---------|
| ⛓️ **Tamper-proof Logs** | No unauthorized modifications possible |
| 🔑 **Decentralized Trust** | Ensures transparency across agencies |
| 🛡️ **Audit-friendly** | Easy verification during cyber audits |
| 📜 **Immutable Records** | Complete historical integrity |
| 🔐 **Cryptographic Security** | Military-grade protection |

</details>

---

## 📂 Project Structure

```
Anveshak/
│
├── 📁 backend/                     # Server-side architecture
│   ├── 🚀 server.js                # Application entry point
│   ├── 🔐 .env                     # Environment configuration
│   │
│   ├── 📁 models/                  # Database schemas
│   │   ├── Incident.js             # Incident data model
│   │   └── Log.js                  # Activity log model
│   │
│   ├── 📁 utils/                   # Utility modules
│   │   └── db.js                   # Database & blockchain helpers
│   │
│   └── 📁 routes/                  # API endpoints
│       ├── incidents.js            # Incident management APIs
│       └── logs.js                 # Log retrieval APIs
│
├── 📁 frontend/                    # Client-side interface
│   ├── 🏠 block.html               # Blockchain visualization
│   ├── 📊 dashboard.html           # Main analytics dashboard
│   ├── 🔑 login.html               # Authentication page
│   ├── ➕ addincident.html         # Incident submission form
│   ├── 📄 surces.html              # Resource management
│   ├── 📋 incidents.html           # Incident list view
│   ├── 📝 logs.html                # Activity logs viewer
│   │
│   └── 📁 assets/                  # Static resources
│       ├── 🎨 CSS files
│       ├── ⚡ JavaScript modules
│       └── 🖼️ Images & icons
│
└── 📖 README.md                    # You are here!
```

---

## ⚡ Quick Start

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="100">
</div>

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/anveshak.git
cd anveshak
```

### 2️⃣ Setup Backend

```bash
cd backend
npm install
```

### 3️⃣ Configure Environment

Create a `.env` file in the `backend` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
PRIVATE_KEY=your_blockchain_private_key
```

### 4️⃣ Run Backend Server

```bash
# Standard mode
node server.js

# Development mode (with auto-reload)
nodemon server.js
```

### 5️⃣ Launch Frontend

Open any of the following pages in your browser 🌍:

```
frontend/login.html        → Authentication
frontend/dashboard.html    → Main Dashboard
frontend/addincident.html  → Report Incidents
frontend/incidents.html    → View All Incidents
frontend/logs.html         → System Logs
frontend/block.html        → Blockchain Viewer
frontend/surces.html       → Resources
```

<div align="center">

**🎉 You're all set! Anveshak is now running locally.**

</div>

---

## 📊 How Anveshak Works

<div align="center">

```mermaid
sequenceDiagram
    participant User
    participant Frontend
    participant API
    participant MongoDB
    participant Blockchain
    participant Dashboard
    
    User->>Frontend: Report Incident
    Frontend->>API: Submit Incident Data
    API->>MongoDB: Store Incident
    MongoDB-->>API: Confirmation
    API->>Blockchain: Create Immutable Record
    Blockchain-->>API: Block Hash
    API->>Dashboard: Trigger Real-time Update
    Dashboard-->>User: Display Alert & Analytics
    
    Note over Blockchain: Tamper-Proof<br/>Storage Ensured
    Note over Dashboard: Real-time<br/>Monitoring Active
```

</div>

### 🔄 Workflow

1. 🚦 **Incident Reported** → Securely stored in **MongoDB**
2. ⛓️ **Blockchain Validation** → Creates immutable cryptographic record
3. 📡 **Dashboard Update** → Real-time analytics and alerts displayed
4. 🛠️ **Admin Action** → Role-based threat management and response

---

## 📈 SWOT Analysis

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### 💪 Strengths
- ✅ Real-time threat detection
- ✅ Blockchain security
- ✅ Scalable architecture
- ✅ User-friendly interface
- ✅ Multi-agency support

</td>
<td width="50%" valign="top">

### 🎯 Opportunities
- 🌟 AI/ML integration
- 🌟 IoT sensor networks
- 🌟 Cloud deployment
- 🌟 Global threat sharing
- 🌟 Predictive analytics

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚠️ Weaknesses
- 🔸 Initial setup complexity
- 🔸 Blockchain latency
- 🔸 Resource requirements
- 🔸 Learning curve

</td>
<td width="50%" valign="top">

### 🛡️ Threats
- 🔸 Advanced persistent threats
- 🔸 Zero-day vulnerabilities
- 🔸 Quantum computing risks
- 🔸 Social engineering

</td>
</tr>
</table>

</div>

---

## 🚀 Future Roadmap

<div align="center">

```mermaid
timeline
    title Anveshak Evolution Roadmap
    section Phase 1
        Q1 2025 : Core Platform Launch
               : Blockchain Integration
               : Basic Dashboard
    section Phase 2
        Q2 2025 : AI Anomaly Detection
               : Advanced Analytics
               : Mobile App
    section Phase 3
        Q3 2025 : IoT Sensor Integration
               : Cloud-Native Deployment
               : Multi-Region Support
    section Phase 4
        Q4 2025 : Quantum-Safe Encryption
               : Global Threat Intelligence
               : Autonomous Response System
```

</div>

### 🎯 Upcoming Features

- 🤖 **AI-Powered Anomaly Detection** - Machine learning models for predictive threat analysis
- 📡 **IoT Sensor Integration** - Direct monitoring of physical infrastructure
- ☁️ **Cloud-Native Deployment** - Kubernetes orchestration and auto-scaling
- 🔍 **Threat Intelligence Network** - Collaborative multi-agency threat sharing
- 🎮 **Interactive Simulations** - Security training and response drills
- 📱 **Mobile Applications** - iOS and Android native apps

---

## 🏆 Acknowledgements

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="200" />

### Built for Smart India Hackathon 2025 🇮🇳

**Team BruteForce Coders**

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">

---

### 🌟 If you find Anveshak useful, please consider giving it a ⭐!

[![GitHub stars](https://img.shields.io/github/stars/your-username/anveshak?style=social)](https://github.com/your-username/anveshak/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/your-username/anveshak?style=social)](https://github.com/your-username/anveshak/network/members)

---

**Made with ❤️ by BruteForce Coders for a Secure India**

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

</div>

---

<div align="center">

### 📬 Connect With Us

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:team@anveshak.dev)

**© 2025 Anveshak | Securing Tomorrow's Critical Infrastructure Today**

</div>
