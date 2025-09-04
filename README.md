# Chereka Pay 

Chereka Pay is a payment and identity gateway built for Ethiopia.  
It connects global crypto rails with local financial systems so merchants and miners can accept Bitcoin and stablecoins, convert them to Ethiopian Birr (ETB) through Chapa, and receive verified payouts — all with intelligent assistance from Chereka AI.

This repository contains the alpha MVP: an in-development implementation intended for pilot partners, contributors, and early feedback.

---

## What Chereka Pay does 

Chereka Pay accepts crypto payments, converts them to ETB via Chapa, verifies users with Fayda National ID and AfroSMS OTP, and provides an intelligent interface through Chereka AI so users can manage payments in Amharic, Afaan Oromo, and English.

---

## Why this matters

Ethiopia has a fast-growing, digital-native population and a strong entrepreneurial spirit, but local merchants and small operators face real friction when dealing with international payments:

- Merchants want to sell globally but struggle to receive reliable local currency payouts.  
- Miners and small operators need faster, trustworthy ways to cash out.  
- Identity and compliance checks slow onboarding and prevent scaling.

Chereka Pay solves these problems by linking Bitcoin and stablecoin payments directly to local bank rails and by making the whole flow understandable and usable through multilingual AI support. This is not just a payment product — it is an accessibility and inclusion platform that can help Ethiopia participate more fully in the global digital economy.

---

## MVP Features 

- Accept Bitcoin and supported stablecoins via QR code and wallet connect.  
- Auto-convert crypto to ETB and payout via Chapa API.  
- Identity verification through Fayda National ID API.  
- Two-factor authentication via AfroSMS OTP.  
- Merchant dashboard: view transactions, request payouts, and see status.  
- Miner payout scheduler: set weekly/monthly payouts to bank accounts.  
- Chereka AI integration: multilingual assistant for payments, onboarding, and education (Amharic / Afaan Oromo / English).

---

## How it works

1. A customer pays the merchant in BTC or a supported stablecoin.  
2. Chereka Pay quotes and converts the received crypto to ETB using a trusted on-ramp.  
3. The converted ETB amount is settled to the merchant’s bank account using Chapa.  
4. Identity checks are performed using Fayda National ID and OTP via AfroSMS when required.  
5. Merchants and miners can ask Chereka AI questions like “show my last 10 payouts” or “when is my next scheduled payout,” and receive answers in their preferred language.

From crypto payment to ETB settlement, the process is designed to be fast, auditable, and easy to use.

---

## Chereka AI integration

Chereka AI is embedded into Chereka Pay to make the system accessible and intelligent:

- Natural language queries: ask for balances, payout schedules, or transaction details.  
- Multilingual support: responds in Amharic, Afaan Oromo, and English.  
- Educational guidance: explains how to accept crypto, how conversion works, and how to keep accounts secure.  
- Operational assistance: helps merchants troubleshoot common issues without needing deep technical knowledge.

This integration makes Chereka Pay a tool not only for payments but for learning and inclusion.

---

## Tech snapshot

  
- Authentication: Better Auth and Fayda national Id.  
- Payments/On-ramps: Bitcoin and stablecoin gateway integrations + Chapa API for ETB payouts.  
- Identity: Fayda National ID API.  
- OTP: AfroSMS for two-factor authentication.  
- AI Layer: Chereka AI API (multilingual assistant).  
- Security: TLS/HTTPS, encrypted payloads, minimal personal data retention, and audit logs.

---
Under Chereka AI
