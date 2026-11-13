# Run Beyond Limits Marathon — Edition 3 Setup Guide

Welcome to the **Run Beyond Limits Marathon Edition 3** setup guide. This edition features TanStack Router frontend architecture, Nitro server build outputs, and a WhatsApp automation microservice.

- **GitHub Repository**: [https://github.com/JeevananthanV/marathon_event_3](https://github.com/JeevananthanV/marathon_event_3)
- **Author**: Jeevananthan V

---

## 📋 System Prerequisites

- **Node.js**: v18.0.0 or higher (v20+ LTS recommended)
- **npm**: v9.0.0 or higher
- **Chromium / Chrome**: Required for WhatsApp Web headless authentication
- **Git**: v2.30.0 or higher

---

## 📥 1. Clone the Repository

```bash
git clone https://github.com/JeevananthanV/marathon_event_3.git
cd marathon_event_3
```

---

## ⚙️ 2. Environment Variables Configuration

Create `.env` in `marathon frontend/`:

```env
VITE_API_URL=http://localhost:5000
VITE_MARATHON_EDITION="Edition 3"
```

---

## 📦 3. Install Dependencies

```bash
# 1. Install frontend dependencies
cd "marathon frontend"
npm install

# 2. Install backend WhatsApp service dependencies
cd ../backend
npm install
cd ..
```

---

## 🚀 4. Running the Application Locally

### Terminal 1: WhatsApp Bot Microservice

```bash
cd backend
npm start
```
*Note: On initial start, scan the terminal QR code using WhatsApp to authenticate the session into `.wwebjs_auth/`.*

### Terminal 2: TanStack Frontend Application

```bash
cd "marathon frontend"
npm run dev
```

---

## 🏗️ 5. Production Build

```bash
cd "marathon frontend"
npm run build
```
The compiled server output is emitted in `.output/server/` and ready for Nitro/Vercel edge deployment.

