# 💳 OmniPay

> A Multi-Platform Digital Wallet & Merchant POS Ecosystem built for seamless digital payments and merchant transactions.

![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile%20%7C%20POS-blue)
![Backend](https://img.shields.io/badge/Backend-Elixir%20%2B%20Phoenix-purple)
![Mobile](https://img.shields.io/badge/Mobile-Kotlin-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 About the Project

**OmniPay** is a fintech platform that provides a complete digital payment ecosystem for both consumers and merchants.

The platform enables users to manage their finances digitally while allowing merchants to accept and process payments through a dedicated Point of Sale (POS) application.

The system is built around a centralized **Elixir Phoenix Backend**, powering multiple client applications with real-time communication, scalability, and shared business logic.

---

## ✨ Features

### 👤 User Features

- 🔐 Create and manage accounts
- 🪪 Identity verification (KYC)
- 💰 Deposit and withdraw funds
- 💸 Send money to other users
- 📱 Generate QR codes for payments
- 📜 View transaction history
- 📊 View spending analytics and insights
- 🔔 Receive real-time notifications

### 🏪 Merchant Features

- 💳 Accept payments via a POS application
- 📈 Monitor transactions in real time
- 📊 View analytics and reports
- 🧾 Process QR-based and wallet-based payments

---

## 🏗️ System Architecture

```text
                           +----------------------+
                           |    Elixir Backend    |
                           |     Phoenix API      |
                           |        PubSub        |
                           +----------+-----------+
                                      |
              ------------------------------------------------
              |                      |                       |
              |                      |                       |
      +-------+--------+     +-------+--------+     +--------+--------+
      |   React Web    |     |   Kotlin App   |     |   KMP Shared    |
      |   Dashboard    |     |  Mobile Wallet |     |  Business Logic |
      +----------------+     +----------------+     +--------+--------+
                                                               |
                                                      +--------+--------+
                                                      |     Java POS     |
                                                      |   Merchant App   |
                                                      +------------------+
```

---

## 🧩 Technology Stack

| Layer | Technology |
|-------|------------|
| Backend API | Elixir |
| Framework | Phoenix |
| Real-Time Communication | Phoenix PubSub |
| Web Application | React |
| Mobile Application | Kotlin |
| Shared Logic | Kotlin Multiplatform (KMP) |
| Merchant POS | Java |
| Database | PostgreSQL |
| Authentication | JWT & Refresh Tokens |
| Notifications | Real-time PubSub |

---

## 🚀 Platform Components

### Backend
- Elixir
- Phoenix Framework
- REST APIs
- Authentication & Authorization
- Real-time Event Processing
- Phoenix PubSub

### Web Dashboard
- React
- Administrative dashboards
- Transaction monitoring
- Analytics and reporting

### Mobile Wallet
- Kotlin
- Account management
- Money transfers
- QR code generation
- Notifications

### Shared Business Logic
- Kotlin Multiplatform (KMP)
- Shared domain models
- Shared validation logic
- Shared business rules

### Merchant POS
- Java
- Payment processing
- QR scanning
- Transaction management
- Merchant analytics

---

## 🎯 Project Vision

OmniPay aims to build a unified financial ecosystem where:

- Users can securely manage and transfer money.
- Merchants can easily accept digital payments.
- Real-time communication keeps all platforms synchronized.
- Shared business logic ensures consistency across applications.
- The platform scales efficiently to support high transaction volumes.

---

## 🌟 Key Capabilities

✅ Digital Wallet  
✅ Money Transfers  
✅ QR Payments  
✅ Merchant POS  
✅ Real-Time Notifications  
✅ Transaction Analytics  
✅ Multi-Platform Support  
✅ Shared Business Logic via KMP

---

## 📂 Repository Structure

```text
omnipay/
├── backend/          # Elixir Phoenix API
├── web/              # React Dashboard
├── mobile/           # Kotlin Mobile Wallet
├── shared/           # KMP Shared Business Logic
└── pos/              # Java Merchant POS Application
```

---

## 🔮 Future Enhancements

- Card payments integration
- Bank account linking
- Multi-currency support
- Offline POS transactions
- AI-powered spending insights
- Merchant settlement reports
- International remittances

---

## 📄 License

This project is licensed under the MIT License.