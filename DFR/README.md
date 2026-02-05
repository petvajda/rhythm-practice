# 🎸 DFR Setlist Manager

A Progressive Web App (PWA) for managing band setlists with real-time Firebase sync across all band members' devices.

## 🚀 GitHub Pages Setup Guide

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository name: `dfr-setlist` (or any name you like)
4. Make it **Public**
5. ✅ Check **"Add a README file"**
6. Click **"Create repository"**

### Step 2: Upload Files

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop these 3 files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Scroll down and click **"Commit changes"**

### Step 3: Enable GitHub Pages

1. In your repository, click **"Settings"** tab
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"main"** branch
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

Your app will be live at:
```
https://YOUR-USERNAME.github.io/dfr-setlist/
```

### Step 4: Configure Firebase

1. Open your live app URL
2. Click the **⚙️ gear icon** in the top right
3. Paste your Firebase config:

```json
{
  "apiKey": "AIzaSyCCikhG4kT9VbU-nQKAXGE-P8atCjZNLbw",
  "authDomain": "dfr-setlist.firebaseapp.com",
  "databaseURL": "https://dfr-setlist-default-rtdb.europe-west1.firebasedatabase.app",
  "projectId": "dfr-setlist",
  "storageBucket": "dfr-setlist.firebasestorage.app",
  "messagingSenderId": "267999497306",
  "appId": "1:267999497306:web:251725c14cc964f1b09c63"
}
```

4. Click **"Save & Connect"**
5. You should see **"✅ Successfully connected!"**

### Step 5: Share with Band Members

Send your band members:
1. Your app URL: `https://YOUR-USERNAME.github.io/dfr-setlist/`
2. The Firebase config (same one from Step 4)

They should:
1. Open the URL
2. Click ⚙️ gear icon
3. Paste the Firebase config
4. Click "Save & Connect"

Now everyone's setlists will sync in real-time! 🎉

---

## 📱 Install as App (iOS)

1. Open the app in **Safari**
2. Tap the **Share** button
3. Tap **"Add to Home Screen"**
4. Tap **"Add"**

The app will appear on your home screen like a native app!

---

## ✨ Features

- ✅ Real-time sync across all devices
- ✅ Drag & drop to reorder songs
- ✅ Multiple setlists (Set 1, Set 2, Spares)
- ✅ Long press to move songs between sets
- ✅ Create/copy/delete setlists
- ✅ Works offline
- ✅ Install as PWA
- ✅ Dark theme

---

## 🔧 Updating the App

To make changes:

1. Edit the files locally
2. Go to your GitHub repository
3. Click on the file you want to update
4. Click the **pencil icon** (Edit)
5. Make your changes
6. Click **"Commit changes"**
7. Wait 1-2 minutes for changes to go live

---

## 💡 Troubleshooting

**Firebase not connecting?**
- Make sure you're accessing via `https://` URL (not `file://`)
- Check Firebase config has all fields in quotes
- Verify your internet connection

**App not updating?**
- Clear browser cache
- Force refresh: Ctrl+Shift+R (PC) or Cmd+Shift+R (Mac)

**Changes not syncing?**
- Check connection status in ⚙️ settings
- Make sure all band members used the same Firebase config

---

## 📞 Support

If you need help:
1. Check the Firebase setup guide: `FIREBASE_SETUP_GUIDE.md`
2. Check browser console for errors (F12)
3. Verify all 3 files are uploaded to GitHub

---

## 🎵 Enjoy your gigs!

Made with ❤️ for DFR Band