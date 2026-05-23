# 🏠 Home Budget Tracker

A mobile-first, single-file web app for tracking shared household bills and personal expenses between two users. No installation, no server, no login — just open the HTML file in any browser.

***

## ✨ Features

- **Two-user support** — switch between User 1 and User 2 to view each person's summary independently
- **Household Bills** — log shared bills (Rent, Council Tax, Electricity, etc.) with a configurable split percentage per bill
- **Personal Expenses** — each user tracks their own expenses (Gym, Mobile, Travel, Monthly General, and more)
- **Summary tab** — instant overview with:
  - 🏠 My Share card showing your household bill contribution and % of shared bills
  - 👤 Personal card showing your total personal spending
  - Breakdown table with Bills and Other Expenses rows
- **Monthly navigation** — browse any past or future month with the arrow controls
- **Delete confirmation** — accidental taps on the ✕ button trigger a confirmation modal before any entry is removed
- **Persistent storage** — data is saved automatically in the browser's local storage, per month
- **Installable as a PWA** — add to your Android or iOS home screen via Chrome/Safari for a full-screen app experience

***

## 📱 How to Install on Your Phone

### Android (Chrome)
1. Open the app URL in Chrome
2. Tap ⋮ → **Add to Home screen**
3. Tap **Add** — the app icon appears on your home screen

### iPhone (Safari)
1. Open the app URL in Safari
2. Tap the **Share** button → **Add to Home Screen**
3. Toggle **Open as Web App** → tap **Add**

***

## 🗂️ Default Bill Categories

| Bill | Default Split |
|------|--------------|
| Rent | 50 / 50 |
| Council Tax | 50 / 50 |
| Electricity | 50 / 50 |
| Hot Water | 50 / 50 |
| Internet | 50 / 50 |
| Groceries | 50 / 50 |

Splits are fully customisable per bill entry.

***

## 💡 Default Personal Expense Categories

- Gym
- Mobile
- Travel
- Monthly General

New entries can be added or removed at any time.

***

## 🛠️ Tech Stack

- Pure HTML, CSS, and JavaScript — zero dependencies, zero frameworks
- Single `.html` file — no build tools required
- LocalStorage for data persistence
- Works fully offline once cached
