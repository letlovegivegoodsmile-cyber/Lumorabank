# Lumora Bank ✦

Lumora Bank is a modern, high-performance digital banking platform built with a sleek deep-navy and gold branding identity. It includes a responsive public-facing web experience, an interactive customer dashboard powered by Supabase, and a secure administration console.

---

## 🚀 Features

### 🌐 Public Website (`index.html`)
- **Modern Fintech UI:** Responsive design with dynamic CSS variables, custom typography, and smooth scrolling.
- **Interactive Ticker:** Real-time asset pricing and market ticker tape.
- **Dynamic Media Showcase:** Auto-playing photo galleries with interactive thumbnail selectors.
- **Customer Testimonial Carousel:** Smooth transition slider showcasing verified reviews.
- **Smartsupp Live Chat Integration:** Out-of-the-box live customer support widget.

### 💳 Customer Dashboard & Portal
- **Supabase Authentication:** Secure user sign-up, login, and password reset flows.
- **Dynamic Account Management:** Real-time balance visibility toggles and multiple currency selections (over 200 world currencies).
- **Interactive Profile Editor:** Avatar upload tool with custom zoom, fit/fill cropping capabilities.
- **Instant Transfers (LumoraPay):** Secure transfer form supporting IBAN/SWIFT validations.
- **Protected Verification Flow:** 6-digit OTP verification system for completing fund transfers.
- **Digital Receipts:** Comprehensive printable/shareable transaction breakdown receipts.

### 🛡️ Administrator Console (`admin.html`)
- **Secure Admin Portal:** Restricted access interface requiring administrator credentials.
- **Customer Management:** View profiles, track account statuses, lock/unlock accounts, and trigger password reset emails.
- **New Account Approvals:** Review and authorize pending registrations, and generate custom **2FA security codes** for users.
- **Transaction Manager:** Monitor customer transfers and update transaction statuses (*Pending*, *Processing*, *On Hold*, *Completed*).
- **Fund Depositing / Backdating:** Credit customer accounts instantly with custom backdated timestamps and tailored transaction details.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid layouts), Vanilla JavaScript (ES6+).
- **Backend & Database:** [Supabase](https://supabase.com/) (Auth, PostgreSQL Database).
- **Visuals & Charts:** [Chart.js](https://www.chart.js/) for logarithmic portfolio analytics.
- **Live Support:** Smartsupp Live Chat plugin.

---

## 📁 Project Structure

```text
├── index.html       # Public landing page, auth modals, and customer application portal
├── admin.html       # Secure administration dashboard for monitoring users and transactions
└── README.md        # Project documentation
