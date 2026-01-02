# Google Sites Alternative - Manual Recreation Guide

## ⚠️ Understanding the Limitation

**Google Sites does NOT support uploading HTML files.** Your `index.html` file cannot be used directly with Google Sites. 

You have two options:
1. **Use GitHub Pages instead** (recommended - see QUICK_START.md)
2. **Manually recreate your page in Google Sites** (this guide)

---

## Option: Manually Recreate in Google Sites

If you choose to use Google Sites despite the limitations, follow this guide to recreate your page.

### Step 1: Create a New Google Site

1. Go to https://sites.google.com/
2. Click "Blank" to create a new site
3. Name your site: "HYDRA-TERRA Landscape Solutions"
4. Choose a theme (pick something clean and modern)

### Step 2: Set Up the Header

1. Click on the header area
2. Upload your logo: `logo_800.png`
3. Add site title: "HYDRA-TERRA"
4. Add tagline if desired

### Step 3: Add "Connect with HYDRA-TERRA" Section

1. Click the "+" button to add content
2. Select "Text box"
3. Add heading: "Connect with HYDRA-TERRA"
4. Format as Heading 2
5. Add subtext: "Follow, message, or scan a QR code to get in touch instantly"

### Step 4: Add Social Media Buttons

Google Sites doesn't have a built-in button grid, so we'll use the Button block:

1. Click "+" → **Insert** → **Button**
2. Add each button with these settings:

   **Button 1 - Instagram**
   - Text: "Instagram"
   - Link: https://www.instagram.com/hydraterra.com.au
   - Style: Filled button
   
   **Button 2 - Facebook**
   - Text: "Facebook"
   - Link: https://www.facebook.com/share/16xa7NGbyY/
   - Style: Filled button
   
   **Button 3 - TikTok**
   - Text: "TikTok"
   - Link: https://www.tiktok.com/@hydraterra.com.au
   - Style: Filled button
   
   **Button 4 - Google**
   - Text: "Google"
   - Link: https://share.google/TRU7GbzRkTfh3Wued
   - Style: Filled button
   
   **Button 5 - WhatsApp**
   - Text: "WhatsApp"
   - Link: https://wa.me/61426398510
   - Style: Filled button (try to make it green if theme allows)

**Tip:** Use the layout options to arrange buttons in a row or grid.

### Step 5: Add QR Code Section

1. Add a new Text box
2. Type heading: "Scan a QR Code"
3. Format as Heading 3

4. Click "+" → **Insert** → **Image carousel** (or individual images)
5. Upload your QR code images:
   - `whatsapp-qr.png`
   - `instagram-qr.png`
   - `facebook-qr.png`
   - `tiktok-qr.png`
   - `google-qr.png`

6. Add captions under each QR code:
   - WhatsApp
   - Instagram
   - Facebook
   - TikTok
   - Google

**Layout tip:** Use "Image carousel" for mobile-friendly display, or insert images in a grid layout for desktop.

### Step 6: Add Gallery Section

1. Add a new Text box
2. Type heading: "Recent Work"
3. Format as Heading 2

4. Click "+" → **Insert** → **Image carousel** or **Image gallery**
5. Upload 6 photos of your recent landscaping work
6. Adjust layout to show in a grid

**Alternative:** Use the "Divider" section with images

### Step 7: Customize Design

1. Click **Themes** (paint palette icon)
2. Choose colors that match your brand
3. Try these color settings:
   - Background: Dark (to match your HTML design)
   - Text: Light/White
   - Accent: Blue or your brand color

4. Adjust fonts to system fonts similar to your design

### Step 8: Add a Footer (Optional)

1. Scroll to bottom of page
2. Add Text box with contact information:
   - Phone: +61 426 398 510
   - Email: (if you have one)
   - Location: (your service area)

### Step 9: Configure Site Settings

1. Click **Settings** (gear icon)
2. Go to **Navigation**
   - Set up your menu (if you have multiple pages)
3. Go to **Analytics** (optional)
   - Add Google Analytics if desired

### Step 10: Publish Your Site

1. Click **Publish** (top right)
2. Choose web address:
   - Option A: Use Google subdomain: `your-site-name.site.google.com`
   - Option B: Custom domain (requires Google Workspace subscription)
3. Click **Publish**

---

## Limitations You'll Encounter

### What You Lose from Your HTML Version:
- ❌ Exact custom styling
- ❌ Precise layout control
- ❌ Inline CSS effects
- ❌ Custom button styling (WhatsApp green button)
- ❌ Exact spacing and margins

### What You Keep:
- ✅ Content (text, links)
- ✅ Images and QR codes
- ✅ Social media links
- ✅ Basic functionality

### Workarounds:
- Use Google Sites themes to approximate your design
- Use "Embed" feature for small custom HTML snippets (limited)
- Focus on content over exact styling

---

## Custom Domain with Google Sites

To use `HYDRA-TERRA.COM.AU` with Google Sites:

### Requirements:
- **Google Workspace subscription** (paid, starts ~$6/month per user)

### Setup:
1. Sign up for Google Workspace: https://workspace.google.com/
2. Verify domain ownership
3. In Google Sites settings, map custom domain
4. Update DNS records as instructed by Google

**Alternative:** Use domain forwarding from your registrar to point to your free Google Site URL

---

## Comparison: Google Sites vs GitHub Pages

| Feature | Google Sites (Manual) | GitHub Pages (Your HTML) |
|---------|----------------------|-------------------------|
| Setup time | 30-60 minutes | 5 minutes |
| Exact design match | ❌ No | ✅ Yes |
| Custom HTML | ❌ No | ✅ Yes |
| Free custom domain | ❌ No (requires Workspace) | ✅ Yes |
| Maintenance | Easy (visual editor) | Easy (edit HTML) |
| Your code works | ❌ No - must recreate | ✅ Yes - works as-is |

---

## Recommended: Use GitHub Pages Instead

**Why?** 
- Your code is already perfect
- Setup takes 5 minutes
- Free custom domain support
- No need to recreate anything
- Everything works exactly as designed

**See:** QUICK_START.md for GitHub Pages setup

---

## Still Want Google Sites?

If you're committed to using Google Sites for specific reasons (e.g., integration with other Google services, team collaboration), follow the steps above. However, be aware that you'll spend significantly more time and get a less precise result than using GitHub Pages.

---

## Need Help?

- Google Sites Help: https://support.google.com/sites
- Google Sites Community: https://support.google.com/sites/community
- Full Setup Guide: See SETUP_GUIDE.md in this repository

---

**Our Recommendation:** Save time and use GitHub Pages! See [QUICK_START.md](QUICK_START.md)
