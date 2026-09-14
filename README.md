# A.S Footwear — Storefront & POS

A premium footwear storefront, point-of-sale (POS) and inventory management system with an embedded AI shopping assistant (**ASbot**). Built as a React + Vite frontend backed by a Django REST API.

> **Real-world project:** this system was built to solve a real business problem — automating the day-to-day operations of a footwear store that was previously run on spreadsheets, paper bills and manual stock counts. It replaces hours of repetitive admin work with a single, always-available dashboard so the owner can spend their time serving customers instead of managing paperwork.

---

## 🎯 The Problem It Solves

Running a footwear business manually is slow and error-prone. This project automates the full lifecycle of a small retail operation:

- **Manual inventory tracking** → live stock levels, SKUs, low-stock alerts and one-click restocking. No more guessing what's in the back room.
- **Paper billing** → digital orders with automatic totals, printable / downloadable PDF invoices, and a full digital history of every sale.
- **No visibility into performance** → built-in analytics (revenue, top sellers, average order value, units sold) with daily, weekly, monthly, yearly and custom date-range views.
- **Time lost to questions** → **ASbot**, an AI assistant trained on the store's live data, answers stock, order and invoice queries instantly — for staff and customers — without hunting through files.
- **No internet? No problem** → offline-first design keeps the store running even when the network or server is down; changes sync back automatically when online.

The result: the business runs faster, decisions are based on real data, and the owner saves hours every week.

## ✨ Features

- **Inventory POS** — add / edit / delete / restock items, low-stock alerts, SKU tracking, cost vs. price margins.
- **Billing & Invoices** — create orders, auto-compute totals, print or download polished PDF invoices.
- **Analytics dashboard** — revenue, average order value, top sellers, units sold — daily, weekly, monthly, yearly or a custom date range.
- **Order history** — full digital log of every sale with search by invoice ID or customer.
- **ASbot AI assistant** — answers stock, order, invoice and analytics questions using live store data (powered by Groq's LLM API, with an offline fallback so it works even without a backend).
- **Staff login** — admin-only access to POS / billing / analytics via a discreet footer link.
- **Offline-first** — admin changes are mirrored to `localStorage`, so the app keeps working even when the API is unreachable; the backend remains the source of truth when online.


## 📄 License

Private project — all rights reserved. Contact the owner before reuse.
