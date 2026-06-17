# 💡 Bulb Finance 2026

**A personal finance desktop application inspired by Microsoft Money 2005 and Windows Vista, built with pure HTML5, CSS3, and Vanilla JavaScript.**  
Runs entirely in your browser – no installation, no server, no external libraries. Data is stored locally in your browser's `localStorage`.

![Bulb Finance 2026 Dashboard](https://via.placeholder.com/800x450?text=Bulb+Finance+2026+Dashboard)  
*(Replace with actual screenshot if available)*

---

## ✨ Features

- **Dashboard** – Net worth, monthly income/expenses, savings progress, recent transactions, upcoming bills, and budget status at a glance.
- **Accounts** – Manage Checking, Savings, Cash, Credit Card, Loan, and Investment accounts with real‑time balance updates.
- **Transactions** – Add, edit, delete, search, and filter transactions by type or account.
- **Budgets** – Set monthly spending limits per category and track your progress with visual bars.
- **Savings Goals** – Create goals with target amounts, deadlines, and progress tracking.
- **Bills** – Track due dates, payment status, and recurring bills.
- **Reports** – Visual charts: spending by category (pie) and monthly income vs. expense trends (line).
- **Settings** – Toggle Light/Dark theme, backup/restore data (JSON), export/import XML, and reset all data.

---

## 🖥️ Technology & Compatibility

- **Pure HTML5 / CSS3 / Vanilla JS** – No frameworks, no dependencies.
- **LocalStorage** – All data is saved in your browser; no cloud or server required.
- **Silverlight Detection** – The app detects if Silverlight is installed. If present, the status bar shows "Silverlight"; otherwise, it gracefully falls back to HTML5 (the app always uses HTML5 for functionality).
- **Responsive** – Adapts to desktop, tablet, and mobile screens.
- **Offline Support** – Once loaded, the app works without an internet connection.

---

## 🚀 Getting Started

1. **Download** the `index.html` file (or the full code from this repository).
2. **Open** `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari, etc.).
3. **Start managing your finances!** All changes are automatically saved to your browser's local storage.

> ⚠️ **Important:** Data is stored locally per browser. Clearing your browser's site data will erase your finances. Use the **Backup** feature in Settings to export your data.

---

## 📁 Data Import / Export

- **Backup (JSON)** – Download a complete backup of all data.
- **Restore (JSON)** – Upload a previously backed‑up JSON file to restore your data.
- **Export XML** – Export all data in a structured XML format.
- **Import XML** – Import data from an XML file (format compatible with the app's export).

---

## 🧩 Example XML Format

```xml
<finance>
    <account>
        <name>Checking</name>
        <type>checking</type>
        <balance>10000</balance>
    </account>
    <transaction>
        <accountId>a1</accountId>
        <category>Salary</category>
        <amount>3200</amount>
        <date>2026-01-05</date>
        <description>Monthly salary</description>
        <type>income</type>
    </transaction>
    <!-- ... more accounts, transactions, budgets, goals, bills ... -->
</finance>
