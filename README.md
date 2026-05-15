# Fellowship & Focus ✝️

A Christian-themed discussion starter and icebreaker app for gatherings, small groups, and couples.

**Categories:** Marriage · Pre-Marriage · The Word · Hot Takes · Ice Breakers

---

## 🚀 Deploy to Vercel in 3 Steps (No coding required)

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **+** icon → **New repository**
3. Name it `fellowship-focus`
4. Leave it **Public**, then click **Create repository**

### Step 2 — Upload the Files

On your new (empty) repository page:

1. Click **"uploading an existing file"** (the link in the middle of the page)
2. Drag and drop these two files:
   - `index.html`
   - `vercel.json`
3. Scroll down and click **Commit changes**

Your repository is now ready. ✅

### Step 3 — Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with your GitHub account
2. Click **"Add New…"** → **Project**
3. Find `fellowship-focus` in the list and click **Import**
4. On the configuration screen, leave everything as-is — Vercel auto-detects it as a static site
5. Click **Deploy**

⏱️ In about 30 seconds, you'll get a live URL like:
```
https://fellowship-focus-yourname.vercel.app
```

---

## ✏️ Adding or Editing Questions

Open `index.html` and find the `QUESTIONS` object near the bottom (inside the `<script>` tag).

Each category has entries in this format:

```js
{ text: "Your question here?", verse: null }

// With a Bible verse:
{ text: "Your question here?", verse: "The verse text — Reference" }
```

Just add new `{ text, verse }` objects to any category array and commit the file.
Vercel will automatically re-deploy within seconds.

---

## Tech Stack

- **Pure HTML + CSS + Vanilla JS** — zero dependencies, no build step
- **Fonts:** Playfair Display + EB Garamond (Google Fonts)
- **Hosting:** Vercel (static)
- **Deploy time:** ~30 seconds

---

*Built for small groups, couples, and church gatherings.*
