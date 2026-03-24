<div align="center">

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/No_Dependencies-00C853?style=for-the-badge&logo=checkmarx&logoColor=white" />
<img src="https://img.shields.io/badge/Single_File-6C63FF?style=for-the-badge&logo=files&logoColor=white" />

<br/><br/>

# 🖥️ Kaido Helpdesk System 

### A pixel-perfect, fully interactive dual-platform simulation of  
### **Salesforce Service Cloud** and **BMC Helix ITSM** — in a single HTML file.

<br/>

[![Live Demo](https://img.shields.io/badge/▶%20Live%20Demo-Open%20in%20Browser-FF6B3D?style=for-the-badge)](https://reaishma.github.io/kaido-helpdesk-system/)
[![Platform 1](https://img.shields.io/badge/Platform%201-Salesforce%20Service%20Cloud-0176D3?style=for-the-badge&logo=salesforce&logoColor=white)
[![Platform 2](https://img.shields.io/badge/Platform%202-BMC%20Helix%20ITSM-CC0000?style=for-the-badge&logo=bmcsoftware&logoColor=white)

<br/>

</div>

---

## 📌 Overview

This project is a **self-contained, zero-dependency HTML simulation** of two industry-leading IT service platforms built for demonstration, portfolio, and learning purposes. Everything — HTML, CSS, and JavaScript — lives in a **single file** that opens directly in any browser.

> **No build tools. No frameworks. No backend. Just open and explore.**

<br/>

<div align="center">

| Feature | Salesforce Service Cloud | BMC Helix ITSM |
|:---|:---:|:---:|
| Interactive Dashboard | ✅ | ✅ |
| Time Period KPI Filtering | ✅ | ✅ |
| Live Data Rendering | ✅ | ✅ |
| Modals & Detail Panels | ✅ | ✅ |
| Create / Submit Forms | ✅ | ✅ |
| Export Report (Download) | ✅ | ✅ |
| Settings Persistence (localStorage) | ✅ | ✅ |
| Platform Switcher | ✅ | ✅ |

</div>

---

## 🟣 Platform 1 — Salesforce Service Cloud

<img src="https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white" /> <img src="https://img.shields.io/badge/CRM-Customer%20Service-032D60?style=flat-square" />

A full-fidelity simulation of the Salesforce Service Cloud experience, featuring:

<details>
<summary><b>📊 Service Dashboard</b></summary>

- 5 live KPI cards: Total Cases, Open Cases, Resolved, Avg Resolution, SLA Compliance  
- Case volume bar chart (This Week / This Month / This Quarter)  
- Case status donut chart with legend  
- Top Agents leaderboard with performance bars  
- SLA risk breakdown with counts and percentages  

</details>

<details>
<summary><b>🎫 Case Management</b></summary>

- Search cases by keyword in real time  
- Filter by Status (Open / In Progress / Resolved)  
- Filter by Priority (High / Medium / Low)  
- Create new cases via modal form  
- View full case details in expanded modal  
- Update status, priority, and agent assignment  
- Resolve and close cases with confirmation  

</details>

<details>
<summary><b>👤 Customer Management</b></summary>

- Search customers by name, email, or company  
- Filter by company with dynamic dropdown  
- Add new customers via form  
- View customer profile and linked case history  
- Edit contact details and company info  

</details>

<details>
<summary><b>📚 Knowledge Base</b></summary>

- Browse articles by category with pill navigation  
- Search across all articles by keyword  
- Filter by category with dropdown  
- Article count badge updates dynamically  
- Open full article content in modal  

</details>

<details>
<summary><b>📞 Omnichannel Inbox</b></summary>

- Switch between Email, Chat, Phone, Social channels  
- Inbox list renders per channel with unread indicators  
- Mark all items as read  
- Compose and send replies within the inbox  
- Live chat simulation with typing indicator and AI responses  

</details>

<details>
<summary><b>📈 Reports & Analytics</b></summary>

- Period selector: Last 30 Days / Last 90 Days / This Quarter  
- All KPI cards update with period-specific data  
- Bar chart updates for case volume trends  
- Agent performance bars and percentages update  
- SLA compliance breakdown updates  
- **Export to text file downloads** with full report content  
- Schedule reports modal with email and frequency options  

</details>

<details>
<summary><b>⚙️ Settings</b></summary>

- SLA policy targets per priority tier  
- Toggle switches for 9 automation & notification options  
- Saves to `localStorage` and restores on next visit  
- Save Changes button with visual confirmation  

</details>

<details>
<summary><b>📖 Documentation & Help</b></summary>

- Getting Started, Onboarding, Quick Start guides  
- Full API Reference with endpoint docs  
- Webhooks & Events documentation  
- Admin Guide with role matrix  
- Video tutorials with chapter breakdowns  
- Release notes for v3.0 / v3.1 / v3.2  

</details>

---

## 🔴 Platform 2 — BMC Helix ITSM

<img src="https://img.shields.io/badge/BMC%20Helix-CC0000?style=flat-square&logoColor=white" /> <img src="https://img.shields.io/badge/ITSM-IT%20Service%20Management-1A2233?style=flat-square" />

A pixel-accurate simulation of BMC Helix ITSM with all core ITSM modules fully interactive:

<details>
<summary><b>📊 ITSM Dashboard</b></summary>

- 5 KPI cards: Total Incidents, Open Incidents, Resolved, Avg Resolution, Change Success  
- Period selector: **Last 30 Days / Last 7 Days / This Quarter** — all cards update with different data  
- Refresh button updates the "Last updated" timestamp and re-renders all KPIs  
- Incident Trends bar chart, Service Performance metrics, System Health progress bars  

</details>

<details>
<summary><b>🚨 Incident Management</b></summary>

- Full incident table rendered from JavaScript data array  
- Filter by Priority (Critical / High / Medium / Low)  
- Filter by Status (Open / In Progress / Resolved)  
- **View button** opens a detail modal with: title, category, priority, status, technician, created time, and activity log  
- Resolve button marks incident resolved and removes the button  
- **Create Incident** form adds new rows to the live table  

</details>

<details>
<summary><b>⚠️ Problem Management</b></summary>

- View button opens a Problem Detail modal with root cause, related incidents, status, and workaround  
- **Schedule / Approve / Reject** action buttons update the status badge inline  
- **Create Problem** form appends new rows to the problem table  

</details>

<details>
<summary><b>🔁 Change Management</b></summary>

- Approve / Reject / Deploy Now / Schedule buttons with toast feedback  
- **Create Change Request** form with type, risk, scheduled date, and rollback plan  
- New change requests appear in the table with Approve/Reject actions  

</details>

<details>
<summary><b>🧾 Assets & CMDB</b></summary>

- **Type filter dropdown** (Hardware / Software / Network) hides/shows rows instantly  
- Each asset has a contextual action button:
  - **Config Map** — shows CI specs and relationships  
  - **Licenses** — shows seat count, renewal date, and cost  
  - **Dependencies** — shows uplinks, VLANs, and downstream CIs  
  - **Lifecycle** — shows lifecycle stage, upgrade plans, and support dates  
  - **Retire** — shows retirement schedule and workload migration status  
- All actions open a dedicated detail modal  
- **Add Asset** button triggers an asset form  

</details>

<details>
<summary><b>🛎️ Service Requests</b></summary>

- Quick-access cards for Access Request, Software Installation, Password Reset  
- **Approve** button updates status badge to "Approved" and shows toast  
- **Assign** button opens a modal to choose team and add a note — updates status to "In Progress"  
- **Update** button opens a status update modal with notes — updates status badge  
- **View** button shows full request detail modal  
- **New Request** form adds a new row to the live table  

</details>

<details>
<summary><b>📊 Reports & Analytics</b></summary>

- Period selector: **Last 30 Days / Last 90 Days / This Quarter**  
- All 5 KPI cards, incident trend bars, and change success rates update per period  
- **Export PDF button** downloads a full ITSM report as a `.txt` file  

</details>

<details>
<summary><b>⚙️ Settings — 6 Panels</b></summary>

| Panel | Content |
|:---|:---|
| 👥 User Roles & Permissions | Role matrix table — ITSM Admin, Change Manager, Incident Manager, Technician |
| ⏱️ SLA Policies | Resolution targets per priority + escalation toggle |
| 🔄 Automation Workflows | 6 automation toggles — AI classification, auto-assign, freeze windows |
| 🔔 Notification Settings | 6 notification toggles — email, SMS, push, digest, exec summary |
| 🔗 Integrations | ServiceNow, Slack, Jira, PagerDuty, Microsoft Teams — with status and Configure/Connect buttons |
| 🔒 Security & Audit | 2FA, SSO, IP allowlisting, session timeout, View Logs, Run Scan |

- Clicking each nav item switches the panel  
- **Save Changes** persists all settings to `localStorage` with visual confirmation  

</details>

---

## 🏗️ Project Structure

```
📄 BMC_Helix_Modified.html       ← Single self-contained file (all platforms)
│
├── 🎨 <style>                    ← All CSS (Salesforce + BMC design systems)
│   ├── Salesforce Lightning Design System variables
│   ├── BMC Helix dark theme variables
│   ├── Shared component styles (modals, tables, badges, toggles)
│   └── Responsive utilities
│
├── 🟣 #marketingView             ← Salesforce Service Cloud
│   ├── Header & Navigation
│   ├── Dashboard, Cases, Customers, Knowledge Base
│   ├── Omnichannel, Reports, Settings, Docs, Help
│   └── Platform Shell (full in-browser app simulation)
│
├── 🔴 #bmcView                   ← BMC Helix ITSM
│   ├── Header (Product Nav)
│   ├── Hero + Value Proposition
│   ├── Module Nav Bar (sticky)
│   ├── Dashboard, Incidents, Problems, Changes
│   ├── Assets & CMDB, Service Requests, Reports, Settings
│   └── CTA + Footer
│
└── 📜 <script>                   ← All JavaScript (~64 functions)
    ├── Shared utilities (modal, toast, openModal, closeModal)
    ├── Salesforce JS (cases, customers, KB, omnichannel, reports)
    └── BMC Helix JS (incidents, problems, changes, assets, requests, reports)
```

---

## 🚀 Getting Started

**No installation required.** Just open the file in a browser.

```bash
# Clone the repository
git clone https://github.com/your-username/itsm-platform-simulation.git

# Navigate to the folder
cd itsm-platform-simulation

# Open the file directly in your browser
open attached_assets/BMC_Helix_Modified.html       # macOS
start attached_assets/BMC_Helix_Modified.html      # Windows
xdg-open attached_assets/BMC_Helix_Modified.html   # Linux
```

Or simply **download the HTML file** and double-click it — it works offline with no server needed.

---

## 🧰 Tech Stack

<div align="center">

| Technology | Role |
|:---|:---|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure and semantic layout |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Full design systems for both platforms |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | All interactivity — no libraries or frameworks |
| ![Google Fonts](https://img.shields.io/badge/Inter%20Font-Google%20Fonts-4285F4?style=flat-square&logo=google&logoColor=white) | Inter typeface (loaded via CDN) |
| ![localStorage](https://img.shields.io/badge/localStorage-Settings%20Persistence-34A853?style=flat-square) | Settings saved across browser sessions |

</div>

---

## ✨ Key Interactive Features

```
✅  64 JavaScript functions powering all interactivity
✅  Dynamic table rendering from in-memory data arrays
✅  Real-time search and multi-filter support
✅  Modal system with open/close for all detail views
✅  Toast notification system (success / error / info)
✅  Settings persistence via localStorage (both platforms)
✅  File download (Export Report as .txt)
✅  Period-driven data updates (no page reload)
✅  Inline status badge updates (Approve / Reject / Resolve)
✅  Platform switcher (Salesforce ↔ BMC Helix) with smooth scroll
```

---

## 📸 Platform Highlights

### Salesforce Service Cloud
- Mimics the **Salesforce Lightning Design System** color palette (`#0176D3`, `#032D60`, `#2E844A`)
- Sticky top navigation with hamburger side nav
- Full platform shell with tabs, sidebar icons, and content panels
- Live chat widget with typing indicator simulation

### BMC Helix ITSM
- Dark navy theme (`#060C1C`, `#1A2233`, `#252A3D`) with BMC orange accents (`#FF6B3D`)
- Colorful SVG dot-mesh hero background (matches BMC's design language)
- Sticky module nav bar with 8 section shortcuts
- 6-panel settings system with individual content views

---

## 🎯 Use Cases

| Use Case | Description |
|:---|:---|
| 🎓 **Portfolio Project** | Showcase full-stack UI design and vanilla JS skills |
| 📚 **Learning Tool** | Study ITSM/CRM workflows and terminology |
| 🎤 **Demo / Presentation** | Walk through live features in any meeting |
| 🧪 **UI Prototyping** | Use as a reference for design patterns |
| 📝 **Training Material** | Help teams understand platform capabilities |

---

## ⚠️ Disclaimer

> This project is a **fan-made simulation for demonstration and portfolio purposes only**.  
> It is **not affiliated with, endorsed by, or connected to** Salesforce, Inc. or BMC Software, Inc.  
> All trademarks, product names, and logos belong to their respective owners.  
> No real data is collected, transmitted, or stored beyond the user's own browser `localStorage`.

---

## 📄 License

This project is released under the **MIT License** — free to use, modify, and distribute with attribution.

---

<div align="center">

Made with ❤️ for the ITSM and CRM community

[![HTML](https://img.shields.io/badge/HTML5-Only-E34F26?style=flat-square&logo=html5&logoColor=white)](.)
[![Zero Dependencies](https://img.shields.io/badge/Zero-Dependencies-00C853?style=flat-square)](.)
[![Offline Ready](https://img.shields.io/badge/Works-Offline-6C63FF?style=flat-square)](.)
[![Open in Browser](https://img.shields.io/badge/Open%20in-Any%20Browser-FF6B3D?style=flat-square)](.)

</div>
