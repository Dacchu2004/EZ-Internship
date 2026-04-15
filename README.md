# DIS88 — Online Casino Web App

A mobile-first, responsive online casino frontend built with **React + Vite**, developed during my internship at **EZ StartUp Futurio**.

---

## Overview

DIS88 is a full-featured casino platform UI covering everything from authentication to in-app wallet management, VIP tiers, reward systems, referrals, and game browsing — all optimized for mobile screens with responsive scaling to desktop.

---

## Features

| Module | Description |
|---|---|
| **Auth** | Sign Up, Login, Forgot Password with username / mobile / email tabs |
| **Home** | Auto-scrolling carousel, game category menu bar, hero game grid, news ticker |
| **Account** | User profile, credit balance, quick actions, settings menu |
| **Profile** | Editable email and date of birth, verification banner |
| **Security Center** | Security level tracker, ID/mobile/email verification flows |
| **Wallet** | Full wallet screen with 10+ game provider sections (Slot, Live Casino, Fishing, Sports, etc.) |
| **Deposit** | Payment method selector, channel picker, quick amount buttons, fee preview |
| **Withdrawal** | Withdraw flow, weekly turnover tracker, transaction history |
| **Bank Account** | View and add linked bank accounts |
| **Reward Center** | Sign-In Task, Bonus, Rebate, Mission Diary, Lucky Spin, VIP, Invite Friends |
| **Referral** | Income tracker, paid-out counter, animated reward section, full FAQ with T&C |
| **VIP** | Card carousel with tier stack (Regular → Diamond), upgrade conditions, privilege grid |
| **Rebate** | Daily / Weekly / Monthly rebate cards |
| **Mission Diary** | Daily and accumulative missions with progress rings |
| **Notifications** | Notification center with auto-delete notice |
| **Sidebar** | Full-screen slide-in menu with animated item entrance |

---

## Tech Stack

- **React 18** with functional components and hooks
- **Vite** for fast dev server and build
- **React Router v6** for client-side routing
- **react-icons** for icon sets (FontAwesome)
- **CSS Modules** (per-component `.css` files, mobile-first with responsive breakpoints)
- Responsive design from **360px → 1024px+**

---

## Project Structure

```
src/
├── components/
│   ├── Carousel.jsx / .css       # Auto-sliding image carousel
│   ├── Navbar.jsx / .css         # Referral section navbar with tabs
│   └── Sidebar.jsx / .css        # Full-screen animated sidebar menu
├── AccountPage.jsx / .css
├── BankAccountPage.jsx / .css
├── DepositPage.jsx / .css
├── ForgotPasswordPage.jsx / .css
├── LoginPage.jsx / .css
├── MissionDiaryPage.jsx / .css
├── NotificationPage.jsx / .css
├── Profile.jsx
├── RebatePage.jsx / .css
├── ReferralPage.jsx / .css       (referralpage.jsx)
├── RewardCenterPage.jsx / .css
├── SecurityCenter.jsx / .css
├── SignupPage.jsx / .css
├── VIPPage.jsx / .css
├── WalletScreen.css              (walletscreen.jsx)
├── WithdrawalPage.jsx / .css
├── actionRow.jsx / ActionRow.css
├── announcement.jsx / NewsTicker.css
├── footer.jsx
├── header.jsx / header.css
├── heroSection.jsx / heroSection.css
├── menuBar.jsx / MenuBar.css
├── Mydata.jsx / Mydata.css
├── App.jsx / App.css
├── main.jsx
└── index.css
```

---

## Getting Started

### Prerequisites

- Node.js >= 18
- npm >= 9

### Install & Run

```bash
git clone https://github.com/your-username/dis88-casino-app.git
cd dis88-casino-app
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```bash
npm run build
```

---

## Routes

| Path | Component |
|---|---|
| `/` | Home (Carousel + ActionRow + HeroSection) |
| `/login` | LoginPage |
| `/signup` | SignupPage |
| `/forgot-password` | ForgotPasswordPage |
| `/account` | AccountPage |
| `/profile` | Profile |
| `/security` | SecurityCenter |
| `/bank-account` | BankAccountPage |
| `/wallet` | WalletScreen |
| `/deposit` | DepositPage |
| `/withdrawal` | WithdrawalPage |
| `/referral` | ReferralPage |
| `/reward-center` | RewardCenterPage |
| `/rebate` | RebatePage |
| `/mission-diary` | MissionDiaryPage |
| `/vip` | VIPPage |
| `/notifications` | NotificationPage |
| `/Mydata` | Mydata |

---

## Responsive Design

All pages are built **mobile-first** and scale through defined breakpoints:

- `≤360px` — extra small phones
- `361px–480px` — standard mobile
- `481px–768px` — tablet (max-width capped at 480px for app-like feel)
- `769px+` — desktop (max-width capped at 600px)

---

## Internship Context

Built as a frontend developer intern at **EZ StartUp Futurio**. This project covers end-to-end UI implementation of a production-grade casino platform — from design system consistency (red/black theme, MYR currency) to component architecture and routing.

---

## License

This project was built for internal/commercial use at EZ StartUp Futurio. Not for redistribution.
