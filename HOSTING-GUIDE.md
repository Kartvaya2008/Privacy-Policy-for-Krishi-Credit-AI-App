# 📋 Krishi-Credit AI — Hosting & PDF Export Guide

## ✅ Files You Have
- `index.html` — The privacy policy page
- `style.css` — The stylesheet (must be in the same folder as index.html)

---

## 🚀 PART 1: HOST ON GITHUB PAGES (Free, Public URL)

### Step 1 — Create a GitHub Account
1. Go to **https://github.com**
2. Click **Sign up** → enter your email, password, and username
3. Verify your email address

---

### Step 2 — Create a New Repository
1. After logging in, click the **+** icon (top right) → **New repository**
2. Set:
   - **Repository name:** `privacy-policy`
   - **Visibility:** ✅ Public (required for free GitHub Pages)
   - ✅ Check **"Add a README file"**
3. Click **Create repository**

---

### Step 3 — Upload Your Files
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop both:
   - `index.html`
   - `style.css`
3. Scroll down, add commit message: `"Add privacy policy page"`
4. Click **Commit changes**

---

### Step 4 — Enable GitHub Pages
1. Go to your repository → click **Settings** (top menu)
2. In the left sidebar, scroll down → click **Pages**
3. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**

---

### Step 5 — Get Your Public URL
After 1–2 minutes, GitHub will show:

```
✅ Your site is published at:
https://YOUR-USERNAME.github.io/privacy-policy/
```

📌 **This is the URL you submit to Google Play Store.**

> **Example:** `https://johndoe.github.io/privacy-policy/`

---

### Step 6 — Use in Play Store
- In your Play Console, go to **App content → Privacy Policy**
- Paste the GitHub Pages URL
- Click **Save**

---

## 📄 PART 2: EXPORT TO PDF

### Option 1 — Browser Print (Easiest)
1. Open your page in **Google Chrome**
2. Press `Ctrl + P` (Windows) or `Cmd + P` (Mac)
3. In the print dialog:
   - **Destination:** Save as PDF
   - **Layout:** Portrait
   - **Margins:** Default or Minimal
   - ✅ Enable **"Background graphics"** (for green header)
4. Click **Save** → choose location

> 💡 The page includes print-optimised CSS — the navigation bar and Download button are automatically hidden in print/PDF mode.

---

### Option 2 — Online HTML to PDF Tools
Use these free tools for a polished PDF:

| Tool | URL |
|------|-----|
| HTML2PDF.io | https://html2pdf.io |
| PDFShift | https://pdfshift.io |
| ILovePDF | https://www.ilovepdf.com/html-to-pdf |

**Steps:**
1. Upload `index.html` (or paste the GitHub Pages URL)
2. Choose A4 paper size, portrait
3. Download the PDF

---

### Option 3 — In-App Download Button
The page already has a **"Download PDF"** button in the header.  
Clicking it triggers `window.print()` → users can save as PDF directly.

---

## 🔄 How to Update the Policy

1. Edit `index.html` on your computer
2. Update the **"Last Updated"** date near line 48
3. Go to your GitHub repo → click `index.html` → click the ✏️ pencil edit icon
4. Paste your updated code → **Commit changes**
5. The live URL updates automatically within 60 seconds

---

## 🎯 Play Store Checklist

| Requirement | Status |
|------------|--------|
| Publicly accessible URL | ✅ GitHub Pages |
| Mobile responsive | ✅ Built-in |
| HTTPS (secure) | ✅ GitHub Pages auto-HTTPS |
| All required sections present | ✅ 10 sections |
| Contact information | ✅ Section 10 |
| Data deletion method | ✅ Section 9 |
| AI / automated decision disclaimer | ✅ Section 4 |

---

## 📞 Support
If you need to customise the policy text, email, or app name — edit the `index.html` file and re-upload to GitHub.
