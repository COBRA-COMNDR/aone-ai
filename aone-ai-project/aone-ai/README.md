# AONE AI — Sharp MFP Diagnostics

Internal tool for authorized Sharp MFP service technicians.
Covers Section 7 (Self Diagnostics & Trouble Codes) for:
- BP-70M65 Series
- BP-70C45 Series
- MX-5071 / MX-6071 Series
- MX-M6071 Series
- MX-4071 Series

---

## Deploy to Vercel (Recommended — Free)

### Option A: Drag & Drop (No coding required)

1. Open a terminal in this folder and run:
   ```
   npm install
   npm run build
   ```
2. Go to https://vercel.com and sign up (free)
3. Click "Add New Project" → "Deploy without Git"
4. Drag the `dist/` folder into the Vercel upload box
5. Done — you get a live URL instantly

### Option B: GitHub + Vercel (Auto-deploys on updates)

1. Create a free GitHub account at github.com
2. Create a new repository called `aone-ai`
3. Upload all these files to the repo
4. Go to vercel.com → "Add New Project" → Import from GitHub
5. Select the repo → click Deploy
6. Done — every time you push to GitHub, Vercel auto-updates the site

---

## Local Development

```bash
npm install
npm run dev
```
Opens at http://localhost:5173

---

## Access Code
Default: `SHARP2025`
To change it, edit line 3 of `src/App.jsx`:
```js
const ACCESS_CODE = "SHARP2025";
```
