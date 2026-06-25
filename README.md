# Deploy to Vercel — Quick Guide

## Option 1: Drag & Drop (Easiest — 2 minutes)

1. Go to https://vercel.com/new
2. Sign in with GitHub (or create a free account)
3. Under "Import Git Repository", scroll down to **"Upload"** section
4. Drag and drop these two files directly onto the upload area:
   - `index.html`
   - `resume.pdf`
5. Click **"Deploy"**
6. Done! Vercel will give you a live URL like `https://yourname-portfolio.vercel.app`

## Option 2: Import from GitHub (Recommended for updates)

1. Go to https://github.com/new
2. Create a new repository named `akanksha-portfolio` (make it **Public**)
3. Upload these two files to the repo:
   - `index.html`
4. Go to https://vercel.com/new
5. Click **"Import Git Repository"** → select your `akanksha-portfolio` repo
6. Vercel auto-detects settings → Click **"Deploy"**
7. Your site is live! Any future changes you push to GitHub will auto-deploy.

## Option 3: Using Vercel CLI (For developers)

```bash
# Install Vercel CLI globally
npm i -g vercel

# Login (one-time)
vercel login

# In this deploy folder, run:
vercel --prod

# Follow prompts → select scope → your project is live!
```

## Custom Domain (Optional)

Once deployed, go to Vercel Dashboard → Your Project → Settings → Domains → Add your custom domain (e.g., `akanksha-portfolio.vercel.app` or your own domain).

---

**Files you need to upload:**
- `index.html` (your portfolio — 80KB, self-contained)
- `resume.pdf` (your CV — will auto-download on click)

That's it! 🚀
