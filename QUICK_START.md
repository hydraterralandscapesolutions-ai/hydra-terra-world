# Quick Start - Deploy Your HYDRA-TERRA Website in 5 Minutes

## ⚠️ Important: Google Sites vs GitHub Pages

**Your HTML code cannot be directly uploaded to Google Sites.** Google Sites only allows their page builder.

**✅ Recommended: Use GitHub Pages** - Your code works perfectly with it!

---

## GitHub Pages Setup (Easiest Option)

### Step 1: Add Missing QR Codes (5 minutes)
Your website needs these QR code images. Create them using any free QR code generator:

1. **WhatsApp QR** (`whatsapp-qr.png`): QR code for https://wa.me/61426398510
2. **Instagram QR** (`instagram-qr.png`): QR code for https://www.instagram.com/hydraterra.com.au
3. **Facebook QR** (`facebook-qr.png`): QR code for https://www.facebook.com/share/16xa7NGbyY/
4. **TikTok QR** (`tiktok-qr.png`): QR code for https://www.tiktok.com/@hydraterra.com.au
5. **Google QR** (`google-qr.png`): QR code for https://share.google/TRU7GbzRkTfh3Wued

**Free QR Code Tools:**
- https://www.qr-code-generator.com/
- https://www.qrcode-monkey.com/
- Mobile apps: Instagram, TikTok, and Facebook have built-in QR generators

Save all QR codes as PNG files with the exact names above.

### Step 2: Upload QR Codes to GitHub
1. Go to your repository: https://github.com/hydraterralandscapesolutions-ai/hydra-terra-world
2. Click "Add file" → "Upload files"
3. Drag and drop all 5 QR code PNG files
4. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. In your repository, click **Settings**
2. Click **Pages** (left sidebar)
3. Under "Branch", select **main** and **/ (root)**
4. Click **Save**
5. Wait 2-3 minutes

### Step 4: View Your Website! 🎉
Your site will be live at:
```
https://hydraterralandscapesolutions-ai.github.io/hydra-terra-world/
```

---

## Optional: Use Your Custom Domain

You have `HYDRA-TERRA.COM.AU` ready to use!

### In GitHub (Settings → Pages):
1. Enter custom domain: `www.hydra-terra.com.au`
2. Click Save
3. Enable "Enforce HTTPS"

### In Your Domain Registrar:
Add these DNS records:

**CNAME Record:**
```
Type: CNAME
Host: www
Value: hydraterralandscapesolutions-ai.github.io
```

**A Records (for root domain):**
```
Type: A, Host: @, Value: 185.199.108.153
Type: A, Host: @, Value: 185.199.109.153
Type: A, Host: @, Value: 185.199.110.153
Type: A, Host: @, Value: 185.199.111.153
```

Wait 1-24 hours for DNS to update.

---

## What About Google Sites?

**Google Sites Limitation:** You cannot upload HTML files to Google Sites. You can only:
1. Use their drag-and-drop page builder (manual work)
2. Embed small HTML snippets (very limited)

**If you want to use Google Sites anyway**, you'll need to:
- Manually recreate your page using their builder
- Add each button and link individually
- Upload images through their interface
- Lose your custom styling

**See `SETUP_GUIDE.md` for detailed Google Sites instructions.**

---

## Summary

| Feature | GitHub Pages | Google Sites |
|---------|-------------|--------------|
| Upload HTML directly | ✅ Yes | ❌ No |
| Custom styling | ✅ Full control | ❌ Limited |
| Setup time | ⚡ 5 minutes | 🐌 30+ minutes |
| Free custom domain | ✅ Yes | ⚠️ Requires Google Workspace |
| Your code works as-is | ✅ Yes | ❌ No - needs recreation |

**Recommendation: Use GitHub Pages** 🚀

---

## Need More Help?

Read the full guide: **SETUP_GUIDE.md**
