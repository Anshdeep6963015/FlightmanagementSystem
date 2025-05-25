 ✈️ Flight Management System – Java Console Application by Anshdeep

A Java-based console project simulating a complete airline ticketing system with Admin, Agent, and Passenger roles. Supports booking, cancellations, seat classes, food options, simulated payments, and email confirmations (v2.0). Future versions will include QR codes and GUI.





## 📧 Version 2.0 – Email Confirmation  🚧 Coming Soon

Implemented email sending using **JavaMail API** on every successful booking:

- Sends an email with:
  - Booking ID
  - Flight ID with route & time (`FL102 (IND-DEL, 6:00PM)`)
  - Food & seat class options
- Uses Gmail SMTP with `mail.properties` config


## 💻 Console vs GUI: Future Comparison

| **Feature** | **Console (Current)** | **GUI (Planned)** |
|-------------|------------------------|--------------------|
| Menu Input | Scanner + Console | Buttons, dropdowns |
| Forms | Text prompt | TextField + ComboBox |
| Output | `System.out.println()` | Tables, popups |
| Login | Text input | Secure fields, GUI login |
| Dashboard | Console tables | Graphical charts & stats |
| QR & Email | Strings/console | Popup + attach images |

### ✅ Console Pros:
- Lightweight
- Easy to test/debug
- No external dependencies

### 🖼 GUI Pros:
- More professional look
- Modern navigation
- Easier for non-technical users

---

## 🔧 Roadmap – Console Features

| Step | Feature | Status | Description |
|------|---------|--------|-------------|
| 1️⃣ | Email Confirmation |  ⏳To Do | Mail on booking |
| 2️⃣ | Admin Analytics | ⏳ To Do | Total bookings, revenue, top routes |
| 3️⃣ | Password Hashing | ⏳ To Do | SHA-256 or bcrypt |
| 4️⃣ | QR Code Generation | ⏳ To Do | ZXing-based QR |
| 5️⃣ | OTP Login | ⏳ To Do | Console OTP |
| 6️⃣ | Search Filters | ⏳ To Do | By date, route, class |
| 7️⃣ | Booking History | ⏳ To Do | View user’s booking list |
| 8️⃣ | CSV Export | ⏳ To Do | Export all data to CSV |
| 9️⃣ | Seat Tracker | ⏳ To Do | Prevent overbooking |

