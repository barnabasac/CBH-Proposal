# Casa Bianca Holdings - ITTS Proposal Website

**Status:** Ready for local preview, needs GitHub deployment setup

---

## 🎯 What's Built

Professional proposal website presenting three investment options for Casa Bianca's ITTS platform:

- **Option A:** The Foundation (£4,800-6,400, 4-5 weeks)
- **Option B:** The Professional (£7,000-9,500, 6-8 weeks)  
- **Option C:** The Platform (£15,000-22,000, 12 weeks) ← Recommended

---

## 📁 File Structure

```
Website/
├── index.html          # Main proposal page
├── css/
│   └── style.css       # Italian restaurant aesthetic styling
└── README.md           # This file
```

---

## 🎨 Design Features

**Visual Style:**
- Italian restaurant aesthetic (warm reds, golds)
- Professional but approachable tone
- Partnership framing throughout
- Mobile responsive
- Clean typography (Syne headers, DM Sans body)

**Key Sections:**
1. Hero with partnership framing
2. Partnership philosophy (joint R&D, not vendor)
3. Three investment options (detailed comparison)
4. Why It Matters (connectivity, risk, operations)
5. Timeline & 12-week constraint
6. Discussion CTA

**Placeholder Images:**
- Connectivity Reality (red gradient)
- Risk Understanding (orange gradient)
- Operational Reality (green gradient)
- Can replace with actual Casa Bianca site photos later

---

## 🚀 Next Steps

### 1. **Preview Locally**
Open `index.html` in your browser to see the site

### 2. **Add Real Images (Optional)**
Create `images/` folder and add:
- Casa Bianca site photos (exteriors, interiors)
- Network equipment shots
- Or keep placeholder gradients

### 3. **GitHub Deployment**
Similar to Biba site:

```bash
# Navigate to Website folder
cd "G:\My Drive\Clients\Casa Bianca\Projects\ITTS Upgrade\Website"

# Initialize Git repo
git init
git add .
git commit -m "Initial CBH proposal website"

# Create GitHub repo (manually on GitHub.com)
# Then connect and push:
git remote add origin https://github.com/YOUR_USERNAME/cbh-proposal.git
git branch -M main
git push -u origin main

# Enable GitHub Pages in repo settings
# Settings > Pages > Source: main branch
```

### 4. **Share with Team**
Once deployed, send link to Andreas/Blerim/Alfred:
"Built a proposal website so you can review the options at your own pace: [URL]"

---

## 🎯 Content Strategy

**Tone Calibration:**
- Andreas: Vision + phased approach (enthusiasm management)
- Blerim: Show don't tell, clear costs (financial conservative)
- Alfred: CCTV access highlighted in all options

**Key Messages:**
- ✅ Partnership pilot (not vendor-client)
- ✅ Three clear options (flexibility)
- ✅ Honest about trade-offs (risk, connectivity)
- ✅ 12-week window (urgency without pressure)
- ✅ "Use us or not" (no lock-in)

---

## 📝 Technical Notes

**Fonts:** Google Fonts (Syne, DM Sans)
**CSS Variables:** Easy theme customization
**Mobile First:** Responsive breakpoints at 968px, 640px
**No JavaScript:** Pure HTML/CSS (lightweight, fast)

---

## 🔧 Customization Options

**Colors:** Edit CSS variables in `style.css`:
```css
:root {
    --primary-red: #dc2626;
    --accent-gold: #f59e0b;
    /* etc */
}
```

**Content:** Edit HTML sections directly
**Images:** Replace placeholder gradients in `.why-image`

---

## 💡 Design Inspiration

Adapted from Biba Constructions success:
- Visual dominance (but with content/options)
- Clean professional layout
- Brief compelling copy
- Real project showcase (adapted to proposals)

---

**Ready to deploy when you are!**

*Built by AYWD × Casa Bianca Partnership*
*December 2025*
