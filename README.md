# 🏗️ System Design - HLD Collection

## 🚀 Overview

This repository contains my **High-Level System Design (HLD)** implementations for commonly asked real-world systems.

The goal of this repo is to:

* Practice scalable system design
* Document design decisions and trade-offs
* Prepare for SDE-1 / SDE-2 backend interviews

---

## 📂 System Designs

### 📩 Notification System

* Supports SMS, Email, and Push notifications
* Built using event-driven architecture (Kafka)
* Includes retry, DLQ, and idempotency handling

👉 [View Design](./Notification_System/)

---

*(More designs will be added soon)*

---

## 🧠 Concepts Covered

* Event-driven architecture (Kafka)
* Microservices design
* Scalability & fault tolerance
* Retry mechanisms & DLQ
* Caching (Redis)
* Rate limiting
* High availability vs consistency trade-offs

---

## ⚙️ Tech Stack (Conceptual)

* **Kafka** → asynchronous messaging
* **Redis** → caching & fast lookup
* **PostgreSQL** → persistent storage
* **External APIs** → Twilio, SES, FCM/APNS

---

## 📈 Future Additions

* URL Shortener
* Rate Limiter
* Chat System
* Payment System
* Search Autocomplete

---

## 🎯 Why This Repo?

This repository demonstrates my ability to:

* Design scalable distributed systems
* Think in terms of real-world constraints
* Handle failures and edge cases
* Make engineering trade-offs

---

## 📌 Note

These are high-level designs intended for learning and interview preparation.
Not production-ready implementations.

---

## ⭐ If you found this useful

Feel free to star ⭐ the repo!
