# 🚀 Deploying Anu & Rabbi's Anniversary Site to Vercel (Free & Instant)

Everything in this folder is configured and ready for Vercel deployment!

---

## 📸 How Photos & Uploads Work on Vercel Live

### 1. Browser Uploads (In-App Tap/Upload)
- When anyone taps **"Upload Real Photo"** or drops a note into the **Wish Jar**, it gets saved in their **browser's storage (`localStorage`)**.
- **Will it stay?** YES! Every time you open the live link on that device/phone, your uploaded photos and notes will stay saved.

### 2. Live Permanent Photos (Visible to Everyone on All Devices)
- If you want photos to appear automatically for **both Anu and Rabbi on all devices** without needing to upload from your phone:
  1. Simply create an `images` folder in this directory.
  2. Add your photos named: `photo1.jpg`, `photo2.jpg`, `photo3.jpg`, `photo4.jpg`, `photo5.jpg`, `photo6.jpg`.
  3. Deploy to Vercel! They will automatically show up everywhere.

---

## ⚡ Option A: Deploy with Vercel CLI (Fastest - 1 Command)

1. Open PowerShell or Command Prompt in this folder (`d:\Product Development\HAN`).
2. Run:
   ```bash
   npx vercel
   ```
3. Follow the prompts:
   - **Set up and deploy?** Type `y` and press Enter.
   - **Log in / Sign up** (if prompted, login with GitHub or email).
   - Press Enter for all default options.
4. Done! You will get a live link like `https://anu-rabbi-anniversary.vercel.app`! 🎉

---

## 🌐 Option B: Deploy via Vercel Website (No terminal needed)

1. Go to **[vercel.com](https://vercel.com)** and log in or sign up for a free account.
2. Click **"Add New"** -> **"Project"**.
3. Push this project folder to a **GitHub repository** or drag & drop the folder into Vercel.
4. Click **Deploy**.
5. Within 10 seconds, your site will be live!

---

## 🎵 Music Note
- The background song is powered by the **YouTube IFrame API** (playing your chosen track: `https://youtu.be/uWoYIOcOpwU`).
- It will stream smoothly online on your Vercel live link!
