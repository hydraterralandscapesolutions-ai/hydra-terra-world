# HYDRA-TERRA Website Setup Guide

This guide will help you set up your HYDRA-TERRA website. **Important Note**: Your code is currently designed as a standalone HTML website, which works perfectly with GitHub Pages but has limitations with Google Sites.

## Table of Contents
1. [Understanding Your Options](#understanding-your-options)
2. [Option 1: GitHub Pages (Recommended)](#option-1-github-pages-recommended)
3. [Option 2: Google Sites (Limited)](#option-2-google-sites-limited)
4. [Missing Assets](#missing-assets)
5. [Troubleshooting](#troubleshooting)

---

## Understanding Your Options

### Your Current Setup
- You have a complete HTML website (`index.html`) with inline styles
- You have logo images in various sizes
- Your code references QR code images that are **not yet in the repository**
- You have a `Cname` file indicating a custom domain setup

### Important Limitation with Google Sites
**Google Sites does NOT support uploading custom HTML files directly.** Google Sites uses its own page builder and doesn't allow you to upload or embed complete HTML pages like `index.html`. You can only:
- Embed small HTML snippets using the "Embed" feature (limited functionality)
- Use Google Sites' built-in page builder tools

### Recommended Solution: GitHub Pages
Since you already have a complete HTML website, **GitHub Pages is the recommended hosting solution**. It's:
- **Free**
- Supports custom domains (like HYDRA-TERRA.COM.AU)
- Works perfectly with your existing code
- No code changes needed

---

## Option 1: GitHub Pages (Recommended)

### Step 1: Verify Your Repository
Your code is already in a GitHub repository. Good! 

### Step 2: Add Missing QR Code Images
Your HTML file references these QR code images that are currently missing:
- `whatsapp-qr.png`
- `instagram-qr.png`
- `facebook-qr.png`
- `tiktok-qr.png`
- `google-qr.png`

**How to create QR codes:**
1. **WhatsApp**: Go to https://wa.me/61426398510 and use a QR code generator like https://www.qr-code-generator.com/
2. **Instagram**: Generate QR from Instagram app (Profile → Menu → QR Code) or use a URL QR generator with your Instagram link
3. **Facebook**: Generate from Facebook page settings or use a QR code generator
4. **TikTok**: Generate from TikTok app (Profile → Menu → QR Code)
5. **Google**: Use a QR code generator with your Google Business link

Once you have the QR code images:
```bash
# Place them in the root directory of your repository
# They should be named exactly as referenced in index.html:
# - whatsapp-qr.png
# - instagram-qr.png
# - facebook-qr.png
# - tiktok-qr.png
# - google-qr.png
```

### Step 3: Enable GitHub Pages
1. Go to your GitHub repository: https://github.com/hydraterralandscapesolutions-ai/hydra-terra-world
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under "Source", select **Deploy from a branch**
5. Under "Branch", select **main** (or **master**) and **/ (root)**
6. Click **Save**

### Step 4: Wait for Deployment
- GitHub will automatically build and deploy your site
- This usually takes 1-3 minutes
- Your site will be available at: `https://hydraterralandscapesolutions-ai.github.io/hydra-terra-world/`

### Step 5: Set Up Custom Domain (Optional)
Since you have `HYDRA-TERRA.COM.AU` in your Cname file:

1. **In GitHub Repository Settings > Pages:**
   - Enter your custom domain: `HYDRA-TERRA.COM.AU` or `www.hydra-terra.com.au`
   - Click Save
   - Enable "Enforce HTTPS" (recommended)

2. **In Your Domain Registrar:**
   Configure DNS settings:
   
   **For apex domain (HYDRA-TERRA.COM.AU):**
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   
   Type: A
   Host: @
   Value: 185.199.109.153
   
   Type: A
   Host: @
   Value: 185.199.110.153
   
   Type: A
   Host: @
   Value: 185.199.111.153
   ```
   
   **For www subdomain:**
   ```
   Type: CNAME
   Host: www
   Value: hydraterralandscapesolutions-ai.github.io
   ```

3. **Wait for DNS Propagation** (can take up to 48 hours, usually much faster)

---

## Option 2: Google Sites (Limited)

If you still want to use Google Sites despite the limitations, here's what you can do:

### What You CAN Do:
1. **Recreate the page manually** using Google Sites' page builder
2. **Embed individual sections** as HTML snippets (limited)

### Step-by-Step for Google Sites:

#### Method A: Recreate Using Page Builder (Recommended for Google Sites)

1. **Go to Google Sites**: https://sites.google.com/
2. **Create a new site**
3. **Add sections manually:**
   - Add a "Text box" for the heading "Connect with HYDRA-TERRA"
   - Add a "Text box" for the description
   - Add a "Button" block for each social link:
     - Instagram: https://www.instagram.com/hydraterra.com.au
     - Facebook: https://www.facebook.com/share/16xa7NGbyY/
     - TikTok: https://www.tiktok.com/@hydraterra.com.au
     - Google: https://share.google/TRU7GbzRkTfh3Wued
     - WhatsApp: https://wa.me/61426398510
   - Upload your QR code images and add them in a grid layout
   - Add placeholder images for the gallery

#### Method B: Embed HTML (Very Limited)

1. In Google Sites, click **Insert** → **Embed**
2. Click **Embed code**
3. Paste a **simplified version** of your HTML (Google Sites strips most styling)
4. Click **Insert**

**Important**: Google Sites will remove most of your inline styles and may break the layout.

### Limitations You'll Face:
- Loss of custom styling
- Layout may not match your design
- Cannot upload `index.html` directly
- More manual work required
- Less flexibility than GitHub Pages

---

## Missing Assets

### QR Code Images
Your `index.html` file references these QR codes that need to be added:

1. **whatsapp-qr.png** - QR code for https://wa.me/61426398510
2. **instagram-qr.png** - QR code for your Instagram
3. **facebook-qr.png** - QR code for your Facebook page
4. **tiktok-qr.png** - QR code for your TikTok
5. **google-qr.png** - QR code for your Google Business

**How to Generate QR Codes:**
- Use free tools like:
  - https://www.qr-code-generator.com/
  - https://www.qrcode-monkey.com/
  - Instagram/TikTok/Facebook apps have built-in QR code generators

**Image Specifications:**
- Format: PNG
- Recommended size: 500x500 to 1000x1000 pixels
- Make sure they scan correctly before uploading

### Gallery Images
Replace the placeholder gallery items with actual photos of your work:
- Format: JPG or PNG
- Recommended size: 500-1000px wide
- Optimize for web (compress to reduce file size)

---

## Troubleshooting

### GitHub Pages Issues

**Site not loading after enabling GitHub Pages?**
- Wait 2-5 minutes for the first deployment
- Check the Actions tab in your repository for build status
- Ensure `index.html` is in the root directory

**Custom domain not working?**
- Verify DNS settings with your domain registrar
- Wait up to 48 hours for DNS propagation
- Check that Cname file contains your domain exactly as configured
- Make sure HTTPS is enabled in GitHub Pages settings

**Images not showing?**
- Ensure image file names match exactly (case-sensitive)
- Check that images are in the same directory as `index.html`
- Verify images are committed and pushed to the repository

### Google Sites Issues

**HTML embed not working?**
- Google Sites strips most HTML/CSS - use page builder instead
- Try embedding smaller sections individually
- Consider using Google Sites native components

**Custom domain on Google Sites?**
- Requires Google Workspace subscription
- Or manually set up domain forwarding to your Google Site URL

---

## Quick Start Checklist

- [ ] Decide: GitHub Pages or Google Sites?
- [ ] **If GitHub Pages:**
  - [ ] Add missing QR code images to repository
  - [ ] Enable GitHub Pages in repository settings
  - [ ] (Optional) Set up custom domain
  - [ ] Wait for deployment and test the site
- [ ] **If Google Sites:**
  - [ ] Create new Google Site
  - [ ] Manually recreate layout using page builder
  - [ ] Upload QR codes and logos
  - [ ] Configure buttons and links
  - [ ] Publish the site

---

## Recommendation

**Use GitHub Pages!** Your code is already perfect for it, and it will work exactly as designed with zero code changes. Google Sites would require you to manually recreate everything and you'd lose your custom styling.

## Need Help?

If you need assistance:
1. Check the GitHub Pages documentation: https://docs.github.com/pages
2. Review Google Sites help: https://support.google.com/sites
3. For DNS/domain issues, contact your domain registrar

---

*Last updated: January 2026*
