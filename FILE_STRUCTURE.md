# File Structure Guide

## Current Repository Structure

```
hydra-terra-world/
├── index.html                 ✅ Your website (ready to deploy!)
├── Cname                      ✅ Custom domain config
├── README.md                  ✅ Updated with instructions
├── QUICK_START.md            ✅ 5-minute deployment guide
├── SETUP_GUIDE.md            ✅ Complete setup guide
├── DEPLOYMENT_CHECKLIST.md   ✅ Track your progress
├── GOOGLE_SITES_GUIDE.md     ✅ Google Sites alternative
├── FILE_STRUCTURE.md         ✅ This file
├── logo_original.png          ✅ Your logo (1024x1024)
├── logo_800.png              ✅ Your logo (800x800)
├── logo_400.png              ✅ Your logo (400x400)
├── icon_512.png              ✅ Your icon (512x512)
├── icon_256.png              ✅ Your icon (256x256)
├── whatsapp-qr.png           ❌ MISSING - You need to add this
├── instagram-qr.png          ❌ MISSING - You need to add this
├── facebook-qr.png           ❌ MISSING - You need to add this
├── tiktok-qr.png             ❌ MISSING - You need to add this
└── google-qr.png             ❌ MISSING - You need to add this
```

---

## What You Need to Add

### Missing QR Code Images

Your `index.html` file references these 5 QR code images. You need to create and add them:

#### 1. whatsapp-qr.png
- **Purpose:** QR code for WhatsApp contact
- **Target URL:** https://wa.me/61426398510
- **Create with:** QR code generator (link the WhatsApp URL)
- **Specs:** PNG, 500x500 to 1000x1000 pixels

#### 2. instagram-qr.png
- **Purpose:** QR code for Instagram profile
- **Target URL:** https://www.instagram.com/hydraterra.com.au
- **Create with:** Instagram app (Profile → Menu → QR Code) or QR generator
- **Specs:** PNG, 500x500 to 1000x1000 pixels

#### 3. facebook-qr.png
- **Purpose:** QR code for Facebook page
- **Target URL:** https://www.facebook.com/share/16xa7NGbyY/
- **Create with:** Facebook page settings or QR generator
- **Specs:** PNG, 500x500 to 1000x1000 pixels

#### 4. tiktok-qr.png
- **Purpose:** QR code for TikTok profile
- **Target URL:** https://www.tiktok.com/@hydraterra.com.au
- **Create with:** TikTok app (Profile → Menu → QR Code) or QR generator
- **Specs:** PNG, 500x500 to 1000x1000 pixels

#### 5. google-qr.png
- **Purpose:** QR code for Google Business profile
- **Target URL:** https://share.google/TRU7GbzRkTfh3Wued
- **Create with:** QR code generator (link the Google URL)
- **Specs:** PNG, 500x500 to 1000x1000 pixels

---

## How to Add Files to Repository

### Method 1: GitHub Web Interface (Easiest)

1. Go to: https://github.com/hydraterralandscapesolutions-ai/hydra-terra-world
2. Click "Add file" button
3. Click "Upload files"
4. Drag and drop your QR code PNG files
5. Scroll down and click "Commit changes"

### Method 2: Git Command Line

If you have the repository cloned locally:

```bash
# Navigate to repository
cd hydra-terra-world

# Copy your QR code images to the repository folder
# Make sure they're named exactly:
#   whatsapp-qr.png
#   instagram-qr.png
#   facebook-qr.png
#   tiktok-qr.png
#   google-qr.png

# Add files
git add whatsapp-qr.png instagram-qr.png facebook-qr.png tiktok-qr.png google-qr.png

# Commit
git commit -m "Add QR code images for social media"

# Push to GitHub
git push
```

---

## Where Files Are Used

### In index.html

Your website code references these files:

```html
<!-- QR Code Images -->
<img src="whatsapp-qr.png" alt="WhatsApp QR">    <!-- Line 23 -->
<img src="instagram-qr.png" alt="Instagram QR">  <!-- Line 28 -->
<img src="facebook-qr.png" alt="Facebook QR">    <!-- Line 33 -->
<img src="tiktok-qr.png" alt="TikTok QR">        <!-- Line 38 -->
<img src="google-qr.png" alt="Google QR">        <!-- Line 43 -->
```

**Important:** File names must match EXACTLY (including capitalization and `.png` extension).

### Logo Images

Already included and ready to use:
- `logo_original.png` - Full resolution (1024x1024)
- `logo_800.png` - Medium size (800x800)
- `logo_400.png` - Small size (400x400)
- `icon_512.png` - Icon large (512x512)
- `icon_256.png` - Icon small (256x256)

These are ready for:
- Website favicon
- Social media profile images
- Marketing materials
- Print materials

---

## Deployment Files

### index.html
**Purpose:** Your complete website code
**Status:** ✅ Ready to deploy
**What it contains:**
- Social media links
- QR code section
- Photo gallery placeholders
- Inline CSS styling

### Cname
**Purpose:** Custom domain configuration for GitHub Pages
**Status:** ✅ Configured with HYDRA-TERRA.COM.AU
**Used by:** GitHub Pages automatic custom domain setup

---

## Documentation Files (Created for You)

### README.md
Overview and quick links to get started

### QUICK_START.md
Fast 5-minute deployment guide - start here!

### SETUP_GUIDE.md
Comprehensive guide covering:
- GitHub Pages setup
- Google Sites limitations
- Custom domain configuration
- Troubleshooting

### DEPLOYMENT_CHECKLIST.md
Interactive checklist to track your deployment progress

### GOOGLE_SITES_GUIDE.md
Step-by-step guide if you want to use Google Sites instead (requires manual recreation)

### FILE_STRUCTURE.md
This file - explains what everything is and where it goes

---

## File Naming Rules

**Important:** GitHub Pages and web browsers are case-sensitive!

### ✅ Correct:
```
whatsapp-qr.png
instagram-qr.png
facebook-qr.png
tiktok-qr.png
google-qr.png
```

### ❌ Wrong (won't work):
```
WhatsApp-QR.png        # Wrong capitalization
whatsapp-qr.PNG        # Wrong extension case
whatsapp_qr.png        # Wrong separator (underscore vs dash)
whatsapp qr.png        # Spaces not allowed
whatsapp-qr.jpg        # Wrong format (.jpg instead of .png)
```

---

## After Adding QR Codes

Once you add the 5 QR code PNG files, your repository will be complete:

```
hydra-terra-world/
├── index.html                 ✅ Ready
├── Cname                      ✅ Ready
├── README.md                  ✅ Ready
├── QUICK_START.md            ✅ Ready
├── SETUP_GUIDE.md            ✅ Ready
├── DEPLOYMENT_CHECKLIST.md   ✅ Ready
├── GOOGLE_SITES_GUIDE.md     ✅ Ready
├── FILE_STRUCTURE.md         ✅ Ready
├── logo_original.png          ✅ Ready
├── logo_800.png              ✅ Ready
├── logo_400.png              ✅ Ready
├── icon_512.png              ✅ Ready
├── icon_256.png              ✅ Ready
├── whatsapp-qr.png           ✅ ADDED!
├── instagram-qr.png          ✅ ADDED!
├── facebook-qr.png           ✅ ADDED!
├── tiktok-qr.png             ✅ ADDED!
└── google-qr.png             ✅ ADDED!
```

Then simply enable GitHub Pages and you're live! 🚀

---

## Next Steps

1. **Create 5 QR codes** using free online tools
2. **Upload them to GitHub** with exact file names
3. **Enable GitHub Pages** in repository settings
4. **Visit your live site!**

**See:** [QUICK_START.md](QUICK_START.md) for step-by-step instructions
