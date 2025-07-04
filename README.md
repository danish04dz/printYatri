# printYatri
Smart bus ticketing and printing solution for private bus operators and conductors. Generate, preview, and print passenger tickets on-the-go using portable Bluetooth thermal printers.


---

# 🚌 PrintYatri – Smart Bus Ticketing & Printing App 🎟️🖨️

Welcome to **PrintYatri** – A lightweight, mobile-first app specially built for 🚍 Private Bus Operators, 👨‍✈️ Conductors, and 🏢 Travel Agencies.

With PrintYatri, conductors can easily generate tickets, preview them 📄, and print 🖨️ receipts for passengers on the spot using any 58mm Bluetooth thermal printer!

---

## 🚀 Features at a Glance

✅ JWT Secured Agency/Conductor Login 🔐
✅ Select Bus & Route easily 🗺️
✅ Quick Passenger Ticket Generation 🎫
✅ Add Fare, Seat Number, Source, Destination 💺
✅ Live Ticket Preview (Text Layout / PDF style) 👀
✅ One-Tap Print (External Printer Apps Support) 📲
✅ Ticket History & Daily Report 📅
✅ Agency-wise Bus Management 🎛️
✅ Offline-Friendly Lite App ⚡

---

## 🏗️ Tech Stack Used 🛠️

| Layer    | Technology                                                       |
| -------- | ---------------------------------------------------------------- |
| Frontend | React Native (Expo CLI) 📱                                       |
| Backend  | Node.js + Express.js 🌐                                          |
| Database | MongoDB Atlas ☁️                                                 |
| Auth     | JWT (JSON Web Token) 🔐                                          |
| Printing | Via Share Intent → Printer Apps (HiPrint / PrinterPlus etc.) 🖨️ |

---

## 🗂️ Folder Structure Overview

### Frontend 📱

```
PrintYatri-App/
├── components/
├── screens/
├── services/ (API calls)
├── utils/
└── App.js
```

### Backend 🌐

```
backend/
├── controllers/
├── models/
├── routes/
├── middleware/
└── server.js
```

---

## 🧾 Sample Printed Ticket (58mm Format)

```
---------------------------------
           PrintYatri
---------------------------------
Bus Name: Baba Mail
Route: Gorakhpur → Lucknow
Passenger: 1
Fare: ₹300
Seat: 12
Date: 25 June 2025
Conductor: Ram Singh
---------------------------------
Thank you for traveling with us!
```

---

## 🖨️ Supported Printers ✅

* MPT-II Thermal Printer
* Panda PRJ-58
* Rongta RP58
* Generic 58mm Bluetooth Thermal Printers
  (Printing via external apps like HiPrint, PrintHand, etc.)

---

## 🔮 Future Roadmap ✨

🟢 Offline Ticket Caching
🟢 QR Code Ticket Generation
🟢 UPI Payment Integration
🟢 Admin Web Dashboard (Agency Level)
🟢 Passenger Feedback Collection

---



---



---

👉 Follow the journey of PrintYatri and help digitize India's bus travel industry! 🇮🇳

---

