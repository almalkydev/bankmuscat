# BankMuscat React Native App

Welcome to the BankMuscat mobile app repository! This project is a modern, full-featured React Native application for managing your finances, wallets, and transactions. Built with Expo, Firebase, and a beautiful UI. 🚀

---

## 📱 Screenshots

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/858709542539493406/1486672982972825721/Apple_iPhone_16_Pro_Max_Screenshot_4.png?ex=69c65b9c&is=69c50a1c&hm=642062b9bc9d65be173cee4a8fb7157ce79aef54caec4ef34079e3472819f5de&" width="18%" />
  <img src="https://cdn.discordapp.com/attachments/858709542539493406/1486672983484272651/Apple_iPhone_16_Pro_Max_Screenshot_1.png?ex=69c65b9c&is=69c50a1c&hm=3c472c0a594e8ba27e27263d10f2772fbed20a3643c96a4b6dd1900a11b0ef46&" width="18%" />
  <img src="https://cdn.discordapp.com/attachments/858709542539493406/1486672983895572571/Apple_iPhone_16_Pro_Max_Screenshot_2.png?ex=69c65b9c&is=69c50a1c&hm=e78b70cf3d7ec3a9908ce9af1e660370099856dd82becbe6ebdcfb260a84da85&" width="18%" />
  <img src="https://cdn.discordapp.com/attachments/858709542539493406/1486672984604278794/Apple_iPhone_16_Pro_Max_Screenshot_3.png?ex=69c65b9c&is=69c50a1c&hm=519ba025925c75a8fca1b971a29a886d6c451f4984ec0d97217459cef0e7885c&" width="18%" />
</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/858709542539493406/1486673322241560706/Apple_iPhone4.png?ex=69c65bed&is=69c50a6d&hm=ab601d0935d39302e88b3c88f1b4d65e2ae4b60f4f305d5790fe7038a0bb96c4&" width="18%" />
  <img src="https://cdn.discordapp.com/attachments/858709542539493406/1486673322673442826/Apple_iPhone.png?ex=69c65bed&is=69c50a6d&hm=491c377641438cbbe4c6754d005d718f172c86528af5ab797013360dde62495b&" width="18%" />
  <img src="https://cdn.discordapp.com/attachments/858709542539493406/1486673323105714281/Apple_iPhone2.png?ex=69c65bed&is=69c50a6d&hm=d9b9f95422b03472ad22ca0f34fdb78fa2af95e19b5609bafc9d496ba7f2b489&" width="18%" />
  <img src="https://cdn.discordapp.com/attachments/858709542539493406/1486673323520823416/Apple_iPhone3.png?ex=69c65bed&is=69c50a6d&hm=8b1fd8927513e842d7561a960eaf83708902d56cdf1f98110a8dc97f85bbd337&" width="18%" />
</p>

---

## Features

- Authentication (Login/Register)
- Wallet management
- Transaction tracking
- Statistics & analytics
- Profile & image upload
- Modern, responsive UI

## Requirements

- Node.js (v16 or newer recommended)
- npm or yarn
- Expo CLI
- Git

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/9ozz/bankmuscat.git
cd bankmuscat/bankmuscat
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Set Up Environment Variables

Copy `.env.example` to `.env` and fill in your Firebase and other API keys.

### 4. Start the App

```bash
npx expo start
```

- Scan the QR code with the Expo Go app on your phone 📱
- Or run on an emulator: `a` (Android) or `i` (iOS)

## Project Structure

```
bankmuscat/
  app/           # Main app code (screens, modals, tabs)
  components/    # Reusable UI components
  constants/     # Theme, colors, spacing, data
  services/      # API and Firebase services
  hooks/         # Custom React hooks
  contexts/      # React Context providers
  assets/        # Images, fonts
  utils/         # Utility functions
```

## Firebase Setup

1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
2. Enable Authentication, Firestore, and Storage
3. Add your Firebase config to `constants/firebase.ts` or your `.env` file

## 🧑‍💻 Useful Scripts

- `npm run start` — Start Expo dev server
- `npm run android` — Run on Android emulator
- `npm run ios` — Run on iOS simulator
- `npm run web` — Run on web browser

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.

## FAQ

**How do I reset the project?**
```bash
node scripts/reset-project.js
```

**Where do I add new screens?**
Add new files in `app/(tabs)/` or `app/(modals)/`.

**How do I update the theme?**
Edit `constants/theme.ts`.

---

## 🌟 Happy Coding!

If you like this project, give it a ⭐ on GitHub!
