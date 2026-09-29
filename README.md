# DiscordBotAuth

A clean, modern web interface and authentication pipeline for Discord bot integrations.

![DiscordBotAuth Interface](/images/auth.png)

---

## 🔗 Live Demo & Documentation

Check out the interactive portal and documentation:
👉 **[DiscordBotAuth Official Site](https://absentservices.github.io/DiscordBotAuth)**

---

## 📌 Overview

**DiscordBotAuth** provides a simple and secure solution for authenticating users via Discord OAuth2. It allows developers to verify Discord accounts, check server/guild memberships, and manage bot authorizations through a streamlined user web flow.

---

## ✨ Features

- **Discord OAuth2 Integration:** Single sign-on (SSO) with official Discord credentials.
- **Clean UI Interface:** Modern, user-friendly authentication screen.
- **Guild & Account Verification:** Verify active user accounts and server memberships.
- **Hosted Landing Page:** Fast, lightweight deployment via GitHub Pages.

---

## 🛠️ Quick Setup

### 1. Discord Developer Portal Setup
1. Go to the [Discord Developer Portal](https://discord.com/developers/applications).
2. Create a **New Application** and navigate to the **OAuth2** tab.
3. Add your Redirect URI (e.g., `https://absentservices.github.io/DiscordBotAuth` or `http://localhost:3000/callback`).
4. Save your **Client ID** and **Client Secret**.

### 2. Local Installation

```bash
# Clone the repository
git clone [https://github.com/AbsentServices/DiscordBotAuth.git](https://github.com/AbsentServices/DiscordBotAuth.git)

# Navigate into the project directory
cd DiscordBotAuth
