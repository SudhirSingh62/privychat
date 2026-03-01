# 🔐 PrivyChat : Private Real-Time Chat Platform  
💼 Secure ephemeral chat rooms powered by Redis and Next.js

PrivyChat is a production-grade real-time private chat application featuring invite-only rooms, Redis-powered pub/sub messaging, and automatic room self-destruction using TTL-based lifecycle management.

Built with Next.js 16, TypeScript, Upstash Redis, and Tailwind CSS, the system demonstrates scalable event-driven architecture and privacy-focused full-stack engineering.

> Private rooms. Instant messaging. Automatic expiry.

---

## 🚀 Live Demo

🔗 https://privychat.sudhirsingh.dev

> Note: Chat rooms automatically self-destruct after 10 minutes for privacy.

---

## ✨ Key Features

### 🔐 Private Room System
- Invite-only secure chat rooms  
- Strict room membership validation  
- One-click secure room creation  
- Manual room destruction support  

### ⚡ Real-Time Messaging
- Redis pub/sub powered live chat  
- Low-latency message delivery  
- Event-driven architecture  
- Automatic message synchronization  

### ⏳ Ephemeral Privacy
- Automatic room expiry using Redis TTL  
- Live self-destruct countdown timer  
- Permanent message deletion on expiry  
- Real-time room destruction broadcast  

### 🛡 Privacy Safeguards
- Tab-switch blur protection  
- Window focus detection  
- Interaction deterrents  
- Secure client-server validation  

### 🎨 Modern UX
- Fully responsive interface  
- Terminal-inspired chat UI  
- Optimistic message sending  
- Clean minimal Tailwind design  

---

## 🏗 Tech Stack

**Frontend**
- Next.js 16 (App Router)  
- TypeScript  
- Tailwind CSS  
- TanStack Query  

**Realtime & Backend**
- Upstash Redis (pub/sub + TTL)  
- Event-driven messaging  
- Next.js API routes  

**Utilities**
- date-fns  
- Custom realtime client  
- Modern React hooks  

---

## 🧠 Architecture Overview

PrivyChat follows an event-driven real-time architecture:

User sends message  
→ API validates room membership  
→ Message stored  
→ Redis publish to room channel  
→ Subscribers receive instantly  
→ UI updates via realtime client  

Room lifecycle is managed using Redis TTL to enable automatic expiry and scalable cleanup.

---


