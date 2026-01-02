# HYDRA-TERRA Website Deployment Checklist

Use this checklist to track your progress in getting your website live!

## Pre-Deployment Tasks

### 1. QR Code Images ⏳
- [ ] Generate WhatsApp QR code for https://wa.me/61426398510
  - Save as: `whatsapp-qr.png`
- [ ] Generate Instagram QR code for https://www.instagram.com/hydraterra.com.au
  - Save as: `instagram-qr.png`
- [ ] Generate Facebook QR code for https://www.facebook.com/share/16xa7NGbyY/
  - Save as: `facebook-qr.png`
- [ ] Generate TikTok QR code for https://www.tiktok.com/@hydraterra.com.au
  - Save as: `tiktok-qr.png`
- [ ] Generate Google QR code for https://share.google/TRU7GbzRkTfh3Wued
  - Save as: `google-qr.png`

**QR Code Tools:**
- https://www.qr-code-generator.com/
- https://www.qrcode-monkey.com/
- Instagram/TikTok/Facebook apps (built-in QR generators)

### 2. Upload QR Codes to GitHub ⏳
- [ ] Go to: https://github.com/hydraterralandscapesolutions-ai/hydra-terra-world
- [ ] Click "Add file" → "Upload files"
- [ ] Upload all 5 QR code PNG files
- [ ] Commit changes

### 3. Gallery Images (Optional) ⏳
- [ ] Replace placeholder gallery images with photos of your work
- [ ] Optimize images for web (compress if needed)
- [ ] Upload to repository

## GitHub Pages Deployment

### 4. Enable GitHub Pages ⏳
- [ ] Go to repository Settings
- [ ] Click "Pages" in left sidebar
- [ ] Under "Branch", select "main" and "/ (root)"
- [ ] Click "Save"
- [ ] Wait 2-3 minutes for deployment

### 5. Test Your Website ⏳
- [ ] Visit: https://hydraterralandscapesolutions-ai.github.io/hydra-terra-world/
- [ ] Check that all links work
- [ ] Verify QR codes display correctly
- [ ] Test social media buttons
- [ ] Check on mobile device

## Custom Domain Setup (Optional)

### 6. Configure GitHub Pages Custom Domain ⏳
- [ ] In GitHub Settings → Pages
- [ ] Enter custom domain: `www.hydra-terra.com.au` or `HYDRA-TERRA.COM.AU`
- [ ] Click "Save"
- [ ] Enable "Enforce HTTPS" (after DNS propagates)

### 7. Configure DNS Records ⏳
Log into your domain registrar and add these DNS records:

**For www subdomain:**
- [ ] Add CNAME record:
  - Type: CNAME
  - Host: www
  - Value: hydraterralandscapesolutions-ai.github.io
  - TTL: 3600 (or automatic)

**For root domain (optional):**
- [ ] Add A record: 185.199.108.153
- [ ] Add A record: 185.199.109.153
- [ ] Add A record: 185.199.110.153
- [ ] Add A record: 185.199.111.153

### 8. Wait for DNS Propagation ⏳
- [ ] Wait 1-24 hours (usually much faster)
- [ ] Check DNS with: https://dnschecker.org/
- [ ] Test your custom domain
- [ ] Enable HTTPS in GitHub Pages settings

## Post-Deployment

### 9. Final Checks ✅
- [ ] Website loads on custom domain
- [ ] HTTPS is working (green lock icon)
- [ ] All images display correctly
- [ ] All QR codes are scannable
- [ ] All social media links work
- [ ] Website works on mobile
- [ ] Website works on desktop

### 10. Promote Your Website 🎉
- [ ] Update social media bios with website link
- [ ] Add to Google Business Profile
- [ ] Share on Instagram/Facebook/TikTok
- [ ] Add to business cards

## Troubleshooting

### Common Issues

**QR codes not showing?**
- Check file names match exactly (case-sensitive)
- Verify files are in root directory
- Clear browser cache and refresh

**Website not loading?**
- Wait a few more minutes for GitHub Pages deployment
- Check Actions tab for build errors
- Verify index.html is in root directory

**Custom domain not working?**
- Wait longer for DNS propagation (up to 48 hours)
- Verify DNS records with domain registrar
- Check DNS with https://dnschecker.org/
- Ensure no typos in domain name

**Need help?**
- Read SETUP_GUIDE.md for detailed instructions
- Check GitHub Pages docs: https://docs.github.com/pages
- Verify DNS with your domain registrar

---

## Your Current Status

**Decision:** 
- [ ] Using GitHub Pages (recommended)
- [ ] Using Google Sites (requires manual recreation)

**Progress:**
- [ ] Not started
- [ ] QR codes created
- [ ] QR codes uploaded
- [ ] GitHub Pages enabled
- [ ] Website is live
- [ ] Custom domain configured
- [ ] Everything working perfectly! 🎉

---

**Next Step:** Read **[QUICK_START.md](QUICK_START.md)** to begin!
