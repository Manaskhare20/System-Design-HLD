# 📩 Notification System Design (HLD)

## 🚀 Overview

Scalable notification system supporting SMS, Email, and Push notifications.

---

## 🧱 Architecture

![HLD](notification-system-hld.png)

---

## ⚙️ Features

* Template-based notifications
* Kafka-based async processing
* Retry + DLQ
* Idempotency
* Status tracking

---

## 📡 Tech Stack

* Kafka
* Redis
* PostgreSQL
* Twilio, SES, FCM/APNS

---

## 🚧 Improvements

* Scheduler service
* Fanout system
* OTP fast-path
