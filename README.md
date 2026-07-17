<div align="center">

<img src="assets/dryft-logo.png" alt="Dryft logo" width="360"/>

### Know what you're paying for.

**Dryft is a mobile app that finds, tracks, and helps you cancel your subscriptions — automatically.**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Gmail API](https://img.shields.io/badge/Gmail_API-EA4335?style=flat&logo=gmail&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-lightgrey?style=flat)

</div>

---

## The Problem

The average person pays for **10+ recurring subscriptions** and underestimates their monthly subscription spend by hundreds of dollars. Free trials roll into paid plans, prices creep up, and forgotten services keep charging — because no one reads their billing emails.

**Dryft turns your inbox into a subscription dashboard.** Connect your Gmail once, and Dryft finds every recurring charge, tells you exactly what you're spending, and shows you what you'd save by cancelling.

## 🎥 Demo

**[▶ Watch the full demo video](Final_Demo_Dryft.mp4)**

*(Click the link above — GitHub will play the video in the browser.)*

## Features

### One-tap Gmail import
Connect your Gmail account and Dryft scans your inbox for subscription and billing emails. A rule-based parsing engine matches sender, subject, and payment patterns to detect recurring charges - each detection comes with a **confidence score**, and you choose exactly which ones to import. No manual data entry.

### Spending dashboard
See your total monthly subscription spend at a glance, track month-over-month changes, and follow your **spending trend over time**. Dryft also totals up what you've saved through cancellations.

### "What would I save?" cancellation insights
Every subscription gets a detailed view with monthly and yearly cost, next billing date, and full billing history - plus a **projected-savings breakdown** showing what cancelling today saves you over 3, 6, and 12 months.

### All your subscriptions, one list
A searchable, sortable list of every active and cancelled subscription with live status, price, and upcoming billing dates — so nothing renews without you knowing.

## 📱 Screenshots

| Dashboard | Gmail Import | Subscription Details | My Subscriptions |
|:---:|:---:|:---:|:---:|
| <img src="assets/dashboard.png" width="200"/> | <img src="assets/gmail-import.png" width="200"/> | <img src="assets/subscription-details.png" width="200"/> | <img src="assets/subscriptions-list.png" width="200"/> |
| Monthly spend, trends & savings | Auto-detected subscriptions with confidence scores | Costs, billing history & cancellation savings | Search, sort & status at a glance |

## 🛠 How It's Built

| Layer | Technology |
|---|---|
| Mobile app | **Flutter** (iOS & Android from a single codebase) |
| Auth & data | **Firebase** (authentication, cloud data storage) |
| Email import | **Gmail API** (OAuth) + rule-based email parsing engine |
| Detection | Pattern matching on senders, subjects & payment amounts, with per-match confidence scoring |

**How the import works:** after the user grants Gmail access via OAuth, Dryft scans billing-related emails and runs them through a parsing engine that recognizes recurring-payment patterns — subscription confirmations, receipts, renewal notices. Each candidate subscription is scored by confidence and presented to the user for review before anything is imported, keeping the user in control of their data.

## 👥 Team

Dryft was built as a startup venture by a small founding team. I led the design and development of the mobile app.

---

<div align="center">

*Built with Flutter & Firebase · Dryft © 2026*

</div>
