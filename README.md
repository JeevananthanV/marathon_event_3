# 🏃 Run Beyond Limits Marathon Series — Edition 3

[![Repository](https://img.shields.io/badge/GitHub-JeevananthanV%2Fmarathon__event__3-blue?logo=github)](https://github.com/JeevananthanV/marathon_event_3)
[![Framework](https://img.shields.io/badge/Frontend-TanStack%20%2B%20Vite%20Nitro-61DAFB?logo=react&logoColor=white)](https://tanstack.com)
[![Backend](https://img.shields.io/badge/Backend-Node.js%20%2B%20WhatsApp%20Web-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Deployment](https://img.shields.io/badge/Deploy-Vercel%20%2F%20Cloudflare-black?logo=vercel&logoColor=white)](https://vercel.com)

A specialized marathon event registration, live runner check-in, and WhatsApp ticket dispatch platform engineered with TanStack Router/Query, Nitro server engine, and WhatsApp automation.

---

## 🔗 Repository Links

| Detail | Link |
|---|---|
| **GitHub Repository** | [https://github.com/JeevananthanV/marathon_event_3](https://github.com/JeevananthanV/marathon_event_3) |
| **Author** | [Jeevananthan V](https://github.com/JeevananthanV) |

---

## 🏗️ Architecture Overview

- **Frontend**: TanStack Router & Query with Vite and Nitro server generation, styled with custom UI theme package.
- **Backend**: Node.js microservice integrated with WhatsApp Web JS (`.wwebjs_auth`) for automated runner ticket delivery and digital bib alerts.
- **Deployment**: Configured for Vercel and Cloudflare Wrangler edge deployment.

---

## 📁 Repository Structure

```
Marathon_Event_3/
├── backend/
│   └── .wwebjs_auth/       # WhatsApp Web authenticated session storage
│
└── marathon frontend/
    ├── src/
    │   └── components/     # High-performance marathon UI components
    ├── theme-package/      # Design system and brand asset definitions
    ├── .output/            # Nitro production server build output
    └── .vercel/            # Vercel deployment metadata
```

---

## 🚀 Setup & Installation

### Clone

```bash
git clone https://github.com/JeevananthanV/marathon_event_3.git
cd marathon_event_3
```

### Frontend Development

```bash
cd "marathon frontend"
npm install
npm run dev
```

### Backend / WhatsApp Service

```bash
cd backend
npm install
npm start
```

---

## 👨‍💻 Author

**Jeevananthan V** — [@JeevananthanV](https://github.com/JeevananthanV)

## License

MIT
