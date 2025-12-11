# 🛡️ Nexus OS
> **Secure Enterprise Workspace & Employee Management System**

Nexus OS is a robust, multi-tenant internal tool designed for organizations to manage employees, secure company secrets, and streamline operations. Built with a mobile-first approach, it works seamlessly as a Web Dashboard and a native Android App.

[![Download for Android](https://img.shields.io/badge/Download-Android_APK-3DDC84?style=for-the-badge&logo=android&logoColor=white)]([PASTE_YOUR_LINK_HERE](https://drive.google.com/file/d/1-_TCn2621hPPy4L-xBwRX1raR0T59cXY/view?usp=sharing))

---

## 📸 Screenshots
| Login Screen | Admin Dashboard | Secure Vault |
|:---:|:---:|:---:|
| ![Login](https://placehold.co/200x400?text=Login+Screen) | ![Dashboard](https://placehold.co/200x400?text=Admin+Panel) | ![Vault](https://placehold.co/200x400?text=Secure+Vault) |
---

## 🚀 Key Features

### 🔐 Security & Authentication
- **Multi-Tenant Architecture:** Secure login using unique **Company Codes** (e.g., `TES-942`) combined with Employee IDs.
- **Role-Based Access Control (RBAC):** Distinct dashboards and permissions for **Admins** vs. **Employees**.
- **Hybrid Password Recovery:**
  - **Admins:** Use a secret **Master Recovery Key** to reset their own access.
  - **Employees:** Send a "Reset Request" that admins must verify and approve inside the dashboard.

### 👥 Team Management
- **Live Employee Directory:** Admins can view, add, and remove team members in real-time.
- **One-Click Onboarding:** Automatically generates credentials and Company Codes for new hires.
- **Admin Controls:** Reset employee passwords instantly from the settings panel.

### 💎 The Vault
- **Encrypted Storage:** A secure space to store sensitive company assets (API Keys, WiFi passwords, etc.).
- **Row Level Security (RLS):** Ensures data is strictly isolated between different companies.

---

## 🛠️ Tech Stack

- **Framework:** [Next.js 14](https://nextjs.org/) (App Router)
- **Database:** [Supabase](https://supabase.com/) (PostgreSQL + Auth)
- **Styling:** Tailwind CSS + Shadcn/ui
- **Mobile Build:** [Capacitor](https://capacitorjs.com/) (Converted to Android APK)
- **State Management:** React Hooks & LocalStorage

---

## 💻 Getting Started (For Developers)

To run this project locally on your machine:

1. **Clone the repository**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/nexus-os.git](https://github.com/YOUR_USERNAME/nexus-os.git)
   cd nexus-os
