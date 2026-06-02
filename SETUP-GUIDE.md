# 🌸 Palak Tailor — Website Setup Guide
## From Zero to Live Admin Panel in ~15 Minutes

---

## What Palak Will Be Able to Do (After Setup)

| Feature | How |
|---|---|
| Upload gallery photos | Admin Panel → Gallery → Add New |
| Edit services & prices | Admin Panel → Services |
| Change website colors/theme | Admin Panel → Theme |
| Add/remove testimonials | Admin Panel → Testimonials |
| Edit her bio & stats | Admin Panel → About Me |
| Login securely | Email + password via Netlify Identity |

---

## STEP 1 — Create a GitHub Account (Free)
> GitHub stores your website files safely in the cloud.

1. Go to **https://github.com** → Sign Up (free)
2. Verify your email
3. Done ✓

---

## STEP 2 — Create a New GitHub Repository

1. Click the **+** button (top right) → **New repository**
2. Name it: `palak-tailor-portfolio`
3. Set it to **Public**
4. Click **Create repository**
5. Upload ALL files from the `palak-site` folder:
   - `index.html`
   - `netlify.toml`
   - `admin/` folder (with `index.html` and `config.yml`)
   - `_data/` folder
   - `images/` folder
6. Click **Commit changes** ✓

---

## STEP 3 — Deploy on Netlify (Free)

1. Go to **https://netlify.com** → Sign Up with GitHub (free)
2. Click **Add new site** → **Import an existing project**
3. Choose **GitHub** → select `palak-tailor-portfolio`
4. Leave all settings as default
5. Click **Deploy site**
6. In ~60 seconds, your site is live at a URL like:
   `https://palak-tailor.netlify.app` ✓

---

## STEP 4 — Enable Netlify Identity (Login System)

1. In Netlify dashboard → go to **Site settings**
2. Click **Identity** in the left sidebar
3. Click **Enable Identity**
4. Under **Registration**, select **Invite only**
   *(so only Palak can log in — no random people)*
5. Scroll to **Git Gateway** → click **Enable Git Gateway** ✓

---

## STEP 5 — Invite Palak as Admin

1. Still in **Identity** → click **Invite users**
2. Enter Palak's email address
3. She'll receive an email → she clicks the link → sets her password
4. Done! She can now log in ✓

---

## STEP 6 — Palak Logs Into Her Admin Panel

1. Go to: `https://your-site-name.netlify.app/admin`
2. Click **Login with Netlify Identity**
3. Enter her email + password
4. She's inside her admin panel! 🎉

---

## How Palak Uses the Admin Panel

### 📸 Upload New Gallery Photo
1. Admin Panel → click **Gallery**
2. Click **New Gallery**
3. Fill in: Title, upload image, pick category
4. Click **Publish** → appears on website within 1–2 mins

### 🎨 Change Website Theme/Colors
1. Admin Panel → **Site Settings** → **Website Theme**
2. Pick a color scheme OR use the color picker
3. Click **Publish** → website updates automatically

### 💅 Edit a Service Price
1. Admin Panel → **Services** → click the service
2. Change the price/description
3. **Publish** → live immediately

### ⭐ Add a New Testimonial
1. Admin Panel → **Testimonials** → **New Testimonial**
2. Fill in client name, review, stars
3. **Publish** → appears on website

---

## Optional: Custom Domain (palaktailor.in)

1. Buy domain at **https://godaddy.com** or **https://namecheap.com**
   (`.in` domains cost ~₹800–1200/year)
2. In Netlify → **Domain settings** → **Add custom domain**
3. Follow Netlify's DNS instructions (copy 2 values to your domain registrar)
4. Free SSL/HTTPS is set up automatically ✓

---

## Summary of Costs

| Item | Cost |
|---|---|
| GitHub | Free |
| Netlify hosting | Free |
| Netlify CMS | Free |
| Custom domain (optional) | ~₹800–1200/year |
| **Total to get started** | **₹0** |

---

## Need Help?

Share this guide with your developer or just message Claude with any step
you're stuck on — every step can be done with guided prompts! 🌸
