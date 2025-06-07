# 🩸 Blood Buddy – Real-Time Blood Donation App

**Blood Buddy** is a real-time, location-aware mobile application built to connect blood donors, patients, hospitals, and blood banks. It aims to minimize the delay and communication gap in emergency blood donation scenarios by offering seamless features powered by Flutter and Firebase.

---

## 📱 Features

- 🔐 **Secure Login & Authentication** – Sign in via OTP or Google.
- 🗺️ **Real-Time Location Tracking** – Find nearby donors and hospitals using Google Maps API.
- 📩 **Blood Request System** – Patients can send blood requests to registered donors.
- 📍 **Shortest Path Navigation** – Donors get optimized directions to reach the patient.
- 🚨 **Panic Button** – One-tap emergency alert notifies all nearby users instantly.
- 📲 **Admin Dashboard** – Centralized control over user activities and data.

---

## 🧑‍💻 Tech Stack

| Layer         | Technology       |
|---------------|------------------|
| **Frontend**  | Flutter, Dart    |
| **Backend**   | Firebase (Firestore, Auth) |
| **Map API**   | Google Maps SDK  |
| **Database**  | Firebase Realtime DB |
| **Auth**      | OTP / Gmail-based |

---

## 🧩 Architecture

- **Modular Flutter app** using MVC pattern.
- Firebase Firestore stores users, requests, and locations.
- Notifications and panic alerts use Firebase Cloud Messaging (FCM).
- Role-based UI: Admin, Donor, Patient, Blood Bank.

---

## 📸 Screenshots

> *(Include screenshots here: Home Page, Request Flow, Panic Button, etc.)*  
> *(Use image markdown if hosted, or add a `screenshots/` folder)*

---

## 📈 Future Scope

- 🧭 Integrate with ride-hailing APIs (e.g., Ola/Uber) for donor transport.
- 🎁 Donor rewards system for regular contributions.
- 🔐 Advanced privacy controls & in-app messaging system.

---

## 📂 Project Structure

```bash
/lib
  /screens        # UI Screens
  /services       # Firebase & Auth logic
  /models         # Data models (User, Request, etc.)
  /widgets        # Reusable components
````

---

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/blood-buddy.git
   cd blood-buddy
   ```
2. Install dependencies:

   ```bash
   flutter pub get
   ```
3. Run the app:

   ```bash
   flutter run
   ```

---

## 📃 License

This project is licensed under the MIT License.
Feel free to fork, customize, and use for non-commercial or educational purposes.

---

## 👨‍💻 Authors

* [Vivek Joshi](https://github.com/vivekvj18)
* [Kshitij Sharma](#) *(co-developer)*

---

## 📫 Contact

For queries, suggestions, or collaborations:
📧 [2001vivekjoshi@gmail.com](mailto:2001vivekjoshi@gmail.com)
🔗 [LinkedIn – Vivek Joshi](https://www.linkedin.com/in/vivek-joshi-181201)

```

---

## ✅ Next Step

- Replace `https://github.com/your-username/blood-buddy.git` with your real repo URL.
- Add images in a `screenshots/` folder if you want to display visuals.
- You can copy this to your `README.md` directly in GitHub or from your local IDE.

Would you like me to help format or upload it to your GitHub directly (if you add me as a collaborator), or do you want a `.md` file version to download and upload manually?
```
