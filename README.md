# 🟠 BTC Tracker – Minimalistisches Bitcoin DCA Tool

Track your Bitcoin stack. Effortlessly. Privately. Self-hosted.

Ein einfacher, minimalistischer Tracker zur Verwaltung deines Bitcoin-Sparplans (DCA), aufgeteilt nach Stacks (z. B. Haupt-DCA, Rücklagen, Familienstack). Vollständig self-hosted – keine Accounts, keine Cloud, keine Plattform.

---

## ✅ Features

- 🔐 **Self-hosted**: Läuft lokal oder auf deinem Server
- 📈 **Zusammenfassung pro Stack & Wallet** (BTC + EUR + Ø Einstiegskurs)
- 🧾 **CSV-Export & Monatsauswertung** (optional)
- 🟠 **Keine Registrierung, keine KYC-Dienste**
- ⚡️ **Lightning- & BTC-Zahlung (für Support/Donations)**

---

## 🚀 Live-Demo (optional)
👉 [yourtool.vercel.app](https://yourtool.vercel.app) *(Falls du eine gehostete Version anbietest)*

---

## 🛠 Installation (local / self-hosted)

### 🔧 Voraussetzungen
- Node.js + npm (für React-Frontend)
- Python oder SQLite (für API-Backend, je nach Version)

```bash
# Clone Repository
git clone https://github.com/deinbenutzername/btc-tracker.git
cd btc-tracker

# Install Frontend (React)
cd frontend
npm install
npm run dev

# Backend starten (FastAPI / SQLite)
cd ../backend
uvicorn main:app --reload
```

---

## 📦 Struktur
```
btc-tracker/
├── frontend/        # React-Frontend (mit Apple-Stil)
├── backend/         # FastAPI + SQLite
├── README.md
└── LICENSE
```

---

## 💸 Unterstützen / Pay-What-You-Want

Wenn dir dieses Projekt hilft, kannst du freiwillig Sats senden 🙏

**BTC (On-Chain):**  
`bc1qyourbtcaddresshere`

**Lightning:**  
`lnurl1dp68gurn8ghj7mnpw3hxxmmrv9kxztnrdakxvmmnd96xjmn9de6hgctsv9hx6ct5v9ujuerpd3h82unvwqhkxatjd9skx6tn8y3k2cm0d9h82um5v96kzctjv93kucmvd93kz6r0v93kzc3jv96k2ep5v93kz6trv96kueppv96kuepsx3skz` *(ersetzt mit deiner LN-Adresse)*

Alternativ: [Download via Gumroad (PWYW)](https://gumroad.com/deinprojekt)

---

## ⚠️ Haftungsausschluss
Dieses Projekt ist Open Source und wird ohne Garantie bereitgestellt. Du bist für deine eigene Sicherheit und Daten verantwortlich.  
Keep your keys, keep your coins.

---

## 📜 Lizenz
MIT – frei nutzbar, veränderbar, weitergebbar.

---

Made for Bitcoiners.

---

**🧠 Fragen / Feedback?**  
Erstelle ein Issue oder schreib anonym an: `contact@yourbtcpage.proton.me`

---