# 🚀 Bright Aside SACCO Management System

Comprehensive SACCO management system with a Google Sheets backend.

## 🛠️ Setup Instructions

### Step 1: Database (Google Sheets)
1. Create a new Google Sheet named `BrightAside DB`.
2. Go to **Extensions > Apps Script**.
3. Copy the content of `Code.gs` from this repository into the script editor.
4. Click **Deploy > New Deployment**.
    - Type: **Web App**
    - Execute as: **Me**
    - Who has access: **Anyone**
5. Copy the **Web App URL**.

### Step 2: Connect Frontend
1. Open the app in your browser (or your GitHub Pages URL).
2. The first time you open it, a **Setup Guide** will appear.
3. Paste the **Web App URL** from Step 1 into the setup box and click **Connect**.
4. The system will automatically seed your Google Sheet with the initial 22 members and settings.

## 🔐 Logins
- **Admin Username:** `admin`
- **Admin Password:** `brightaside2024`
- **Member PIN (Default):** `1234`

## 📦 Deployment
This repository is configured to deploy to **GitHub Pages** automatically via GitHub Actions.
1. Go to **Settings > Pages** in this repository.
2. Select **GitHub Actions** as the source.
3. Every push to the `main` branch will build and update the site.
