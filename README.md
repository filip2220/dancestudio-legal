# 🌐 Legal Pages - Deployment Guide

These HTML pages are ready to deploy to **GitHub Pages** (free hosting accepted by app stores).

## 📂 Files Included

```
legal-pages/
├── index.html           # Landing page with links to all documents
├── privacy-policy.html  # Privacy Policy (Polish + English)
├── terms-of-service.html # Terms of Service (Polish + English)  
├── support.html         # Support/Help page
└── README.md            # This file
```

## ✅ Business Information (Already Filled In)

| Field | Value |
|-------|-------|
| **Company Name** | Balet Klasyczny - Nora Cotter-Szymik |
| **Address** | ul. Akacjowa 6i, 37-403 Pysznica |
| **NIP** | 8652590977 |
| **Email** | balet.z.nora@gmail.com |
| **Phone** | +48 732 577 948 |

---

## 🚀 Deploy to GitHub Pages (5 minutes)

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create free account)
2. Click **"New repository"** (green button)
3. Name it: `legal` (or `balet-legal`)
4. Make it **Public**
5. Click **"Create repository"**

### Step 2: Upload Files

**Option A: Web Upload (Easiest)**
1. In your new repository, click **"uploading an existing file"**
2. Drag and drop ALL files from this `legal-pages` folder:
   - `index.html`
   - `privacy-policy.html`
   - `terms-of-service.html`
   - `support.html`
3. Click **"Commit changes"**

**Option B: Git Command Line**
```bash
cd docs/legal-pages
git init
git add .
git commit -m "Add legal pages"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/legal.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings** → **Pages**
2. Under "Source", select **"Deploy from a branch"**
3. Select branch: **main** and folder: **/ (root)**
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 4: Get Your URLs

Your pages will be available at:

```
https://YOUR_USERNAME.github.io/legal/
https://YOUR_USERNAME.github.io/legal/privacy-policy.html
https://YOUR_USERNAME.github.io/legal/terms-of-service.html
https://YOUR_USERNAME.github.io/legal/support.html
```

---

## 📱 Add URLs to App Stores

When submitting to app stores, use these URLs:

### Google Play Console
- **Privacy Policy URL**: `https://YOUR_USERNAME.github.io/legal/privacy-policy.html`
- **Support URL**: `https://YOUR_USERNAME.github.io/legal/support.html`

### Apple App Store Connect
- **Privacy Policy URL**: `https://YOUR_USERNAME.github.io/legal/privacy-policy.html`
- **Support URL**: `https://YOUR_USERNAME.github.io/legal/support.html`
- **Marketing URL** (optional): `https://YOUR_USERNAME.github.io/legal/`

---

## 🔄 How to Update Pages Later

1. Go to your GitHub repository
2. Click on the file you want to edit
3. Click the pencil icon (Edit)
4. Make your changes
5. Click **"Commit changes"**
6. Changes will be live in 1-2 minutes

---

## ✅ Checklist Before App Store Submission

- [x] All business information filled in
- [ ] Pages uploaded to GitHub
- [ ] GitHub Pages enabled
- [ ] Tested all URLs in browser
- [ ] URLs added to app store listings

---

## 🆘 Need Help?

If you have issues with GitHub Pages:
- Check [GitHub Pages Documentation](https://docs.github.com/en/pages)
- Make sure repository is **Public**
- Wait 5 minutes after enabling Pages (sometimes takes time)

---

**Your legal pages are ready to deploy! 🎉**
