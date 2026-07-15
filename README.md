# MindShift Daily — Website Starter

## یہ فائلز کیا ہیں؟
یہ آپ کی مکمل ویب سائٹ ہے — 6 صفحات (Home, About, Contact, Privacy, Disclaimer, Terms)، لوگو، اور ڈیزائن۔

## GitHub Pages پر اپلوڈ کرنے کا طریقہ (Zero سے شروع)

### Step 1 — GitHub اکاؤنٹ بنائیں
اگر پہلے سے نہیں ہے تو https://github.com پر جا کر فری اکاؤنٹ بنائیں۔

### Step 2 — نیا Repository بنائیں
1. GitHub پر لاگ ان ہونے کے بعد اوپر دائیں طرف **+** پر کلک کریں → **New repository**
2. نام دیں: `mindshiftdaily` (یا آپ جو چاہیں)
3. **Public** سلیکٹ کریں
4. **Create repository** پر کلک کریں

### Step 3 — فائلز اپلوڈ کریں
1. نئے repository کے صفحے پر **"uploading an existing file"** پر کلک کریں
2. اس فولڈر کی تمام فائلز (index.html, css/, js/, images/ وغیرہ) ڈریگ اینڈ ڈراپ کریں
   - **اہم:** فولڈر اسٹرکچر برقرار رکھیں — یعنی `css` فولڈر الگ، `images` فولڈر الگ اپلوڈ ہو
3. نیچے **Commit changes** پر کلک کریں

### Step 4 — GitHub Pages فعال کریں
1. Repository میں **Settings** پر جائیں
2. بائیں مینو میں **Pages** پر کلک کریں
3. **Source** میں "Deploy from a branch" منتخب کریں، branch = `main`, folder = `/root`
4. **Save** کریں

چند منٹ بعد آپ کی ویب سائٹ اس لنک پر لائیو ہو جائے گی:
`https://yourusername.github.io/mindshiftdaily/`

## اگلے ضروری اقدامات
- [ ] `robots.txt` اور `sitemap.xml` میں `YOURDOMAIN.com` کو اپنے اصل ڈومین سے بدلیں
- [ ] Privacy/Disclaimer/Terms صفحات کسی وکیل سے چیک کروائیں (خاص طور پر AdSense اپلائی کرنے سے پہلے)
- [ ] `index.html` میں موجود 3 placeholder آرٹیکلز کو اپنے اصل مضامین سے بدلیں
- [ ] Contact فارم کو کام کرنے کے لیے Formspree یا Getform جیسی فری سروس سے کنیکٹ کریں
- [ ] Google Search Console اور Google Analytics سیٹ اپ کریں
- [ ] کم از کم 15-20 اصل آرٹیکلز پبلش کرنے کے بعد ہی AdSense کے لیے اپلائی کریں

## فائل اسٹرکچر
```
mindshiftdaily/
├── index.html          (ہوم پیج)
├── about.html
├── contact.html
├── privacy.html
├── disclaimer.html
├── terms.html
├── robots.txt
├── sitemap.xml
├── css/
│   └── style.css
├── js/
│   └── script.js
└── images/
    ├── logo.svg
    └── favicon.svg
```
