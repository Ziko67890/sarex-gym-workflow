# 🏋️ SareX Gym — Automated Membership Management System

> From registration to renewal — fully automated. This n8n workflow handles every stage of a gym member's lifecycle without any manual work from the team.


---

## 💡 The Problem It Solves

Managing gym memberships manually is slow, error-prone, and hard to scale. Members sign up, check in, and renew constantly — and keeping track of all of it in spreadsheets or notebooks just doesn't cut it. This system automates the entire process end to end.

---

## ⚡ What It Does

### 📋 Registration
Captures member details from a form, uploads their profile photo, and creates their record in Airtable instantly.

### 📧 Welcome Email
Sends a branded welcome email with plan details, start date, and expiry date — automatically on signup.

### 🚪 Check-In
Logs every gym visit, updates total check-in count, and blocks expired members from checking in.

### ⏰ Expiry Reminder
Automatically sends a reminder email 3 days before a membership expires.

### 🔄 Renewal
Handles membership renewals — updates the plan, recalculates end dates, and sends a confirmation email.

---

## 📦 Membership Plans

| Plan | Duration |
|------|----------|
| **Weekly** | 7 days |
| **1 Month** | 30 days |
| **3 Months** | 90 days |
| **6 Months** | 180 days |

---

## 🛠️ Tech Stack

| Tool | Role |
|------|------|
| **n8n** | Workflow automation engine |
| **Airtable** | Member database and records |
| **ImgBB** | Profile photo hosting |
| **Gmail** | Automated email notifications |
| **Tally / Form** | Member registration and check-in forms |

---

## 🚀 Getting Started

1. Import `Sarex_Gym.json` into your n8n instance via **Workflows → Import from file**
2. Add your credentials — Airtable Personal Access Token, Gmail account, and ImgBB API key
3. Update the Airtable base ID and table IDs to match your own setup
4. Connect your registration and check-in forms to the n8n webhook URLs
5. Activate all three workflows — Registration, Check-In, and Renewal


---

