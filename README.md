# 📱 Pedometer App

*A fun Ionic React app to experiment with mobile features — pedometer, background tasks, QR code scanning, authentication and more!*

---

## 🚀 Overview

This is a hobby / experimental mobile app project built with **Ionic + React + Capacitor**.  
It demonstrates how to create a cross–platform mobile app that also runs as a PWA.

### Planned features:
✅ Pedometer — count steps using device sensors  
✅ Run in background — keep tracking while minimized  
✅ Dummy QR Code scanner — just for testing  
✅ User accounts — register, login, email confirmation, password reset  
✅ Nice responsive UI — works on mobile and desktop

---

## 🧰 Tech Stack

- [Ionic](https://ionicframework.com/) — UI framework
- [React](https://reactjs.org/) — Frontend framework
- [Capacitor](https://capacitorjs.com/) — Native runtime
- [TypeScript](https://www.typescriptlang.org/) — Optional
- Backend: *(TBD — possibly .NET or Django)*

---

## 📦 Installation

Clone the repository:
```bash
git clone https://github.com/pudelosha/Pedometer-App.git
cd Pedometer-App
```

Install dependencies:
```bash
npm install
```

Run locally:
```bash
ionic serve
```

---

## 📱 Run on device

Build web assets:
```bash
ionic build
```

Sync to native platform:
```bash
npx cap sync android
```

Open in Android Studio:
```bash
npx cap open android
```

Run on your USB–connected device from Android Studio.

---

## 🌐 Run as PWA

Just serve/build normally and host the `/build/` folder — it works in the browser as a Progressive Web App:
```bash
ionic build
npx serve ./build
```

---

## 📝 Roadmap

- [x] Setup Ionic React project
- [x] Basic PWA & Android build
- [ ] Implement pedometer functionality
- [ ] Add background service support
- [ ] Add dummy QR code scanning feature
- [ ] Build authentication screens
- [ ] Connect to backend for auth & data

---

## 🤝 Contributions

This is just a fun experimental app — feel free to fork it or open issues/PRs if you want to improve it!

---

## 📄 License

MIT License.
