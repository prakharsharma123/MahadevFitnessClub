# 🔱 MAHADEV FITNESS CLUB

## Website Overview
A modern, high-performance fitness club website for **Mahadev Fitness Club** located in Lucknow, Uttar Pradesh, India. Built with pure HTML, CSS, and JavaScript—no frameworks needed!

---

## 📋 Table of Contents
- [Features](#features)
- [Live Demo](#live-demo)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [How to Deploy on GitHub Pages](#how-to-deploy-on-github-pages)
- [File Guide](#file-guide)
- [Customization Guide](#customization-guide)
- [Contact & Support](#contact--support)
- [Credits](#credits)

---

## ✨ Features

### 🎯 Core Sections
- **Hero Section** - Eye-catching landing with animated gradient backgrounds and particle effects
- **About Us** - Gym legacy, features, and statistics with animated counters
- **Programs** - 5 training programs with hover effects (Weight Training, Fat Loss, Muscle Building, Personal Training, HIIT)
- **Trainers** - Featured trainer cards with stats and booking buttons
- **Reviews** - Auto-scrolling testimonials carousel from members
- **Membership Plans** - 4 pricing tiers (1M, 3M, 6M, 1Y) with feature comparison
- **Special Offers** - Limited-time deals and promotions
- **Gallery** - 9 gym images in responsive grid
- **Contact Form** - Email integration for inquiries
- **Interactive Map** - Google Maps embedded location

### 🎨 Design Highlights
- **Dark Theme** - Modern black & orange color scheme (#FF4500, #FFD700)
- **Responsive Design** - Mobile-first approach (works on all devices)
- **Animations** - Smooth transitions, particle effects, scroll reveals
- **Mobile Menu** - Hamburger navigation for tablets/phones
- **WhatsApp Integration** - Floating button for quick contact
- **Toast Notifications** - User feedback for form submissions

### ⚡ Performance
- Pure vanilla JavaScript (no dependencies)
- Optimized CSS with custom properties
- Smooth scrolling behavior
- Intersection Observer for lazy animations
- Font Awesome icons (CDN loaded)
- Google Fonts integration

---

## 🌐 Live Demo
**Coming Soon!** Once deployed to GitHub Pages or your hosting provider.

---

## 📁 Project Structure

```
mahadev-fitness-club/
│
├── index.html              # Main website file (all-in-one)
├── photos/                 # Gym images folder
│   ├── i1.png             # Gym interior 1
│   ├── i2.png             # Gym interior 2
│   ├── i3.png             # Gym interior 3
│   ├── i4.png             # Gym interior 4
│   ├── i5.png             # Gym interior 5
│   ├── i6.png             # Gym interior 6
│   ├── i7.png             # Gym interior 7
│   ├── i8.png             # Gym interior 8
│   ├── i9.png             # Gym interior 9
│   └── trainer.png        # Trainer image
│
├── README.md              # This file
├── .gitignore             # Git ignore rules
└── LICENSE                # License file (optional)
```

---

## 🚀 Installation & Setup

### Option 1: Local Development (Recommended)

#### 1. **Clone the Repository**
```bash
git clone https://github.com/YOUR_USERNAME/mahadev-fitness-club.git
cd mahadev-fitness-club
```

#### 2. **Add Your Images**
Place your gym photos in the `photos/` folder:
```
photos/
├── i1.png through i9.png  (gym interior shots)
└── trainer.png            (head trainer photo)
```

#### 3. **Run Locally**
You have several options:

**Option A: Using Python (Recommended)**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Option B: Using Node.js**
```bash
# Install http-server globally
npm install -g http-server

# Start server
http-server
```

**Option C: Using VS Code Live Server**
- Install "Live Server" extension in VS Code
- Right-click `index.html` → "Open with Live Server"

#### 4. **Access in Browser**
```
http://localhost:8000
```

---

## 📤 How to Deploy on GitHub Pages

### **Method 1: Using GitHub Pages (FREE & EASY)**

#### Step 1: Push Code to GitHub
```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit: Mahadev Fitness Club website"

# Add remote (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/mahadev-fitness-club.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll down to **"Pages"** section (left sidebar)
4. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

#### Step 3: Access Your Live Website
Your site will be available at:
```
https://mahadevfitnessclub.in
```

✅ **Done!** Your website is now live!

---

### **Method 2: Using Custom Domain (Optional)**

If you have a custom domain (e.g., `mahadevrfitness.com`):

1. Go to **Settings → Pages**
2. Under **Custom Domain**, enter your domain
3. Update your domain's DNS settings (ask your domain provider):
   - Add `A` records pointing to GitHub's IP addresses:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - Or add `CNAME` record: `YOUR_USERNAME.github.io`
4. Wait 15-30 minutes for DNS propagation

---

## 📝 File Guide

### **index.html** (Main File)
Everything is in this single file:
- **Lines 1-70**: External fonts & CDN links
- **Lines 70-600**: CSS styling (dark theme, animations, responsive)
- **Lines 600-800**: HTML structure (navbar, hero, sections)
- **Lines 800-900**: JavaScript functionality (scroll effects, form handling)

### **Key Sections in index.html**

| Section | Lines | Purpose |
|---------|-------|---------|
| Navbar | 600-650 | Navigation menu |
| Hero | 650-700 | Landing banner |
| About | 700-750 | Gym info & stats |
| Programs | 750-800 | Training programs |
| Gallery | 800-850 | Gym photos |
| Trainers | 850-900 | Trainer profiles |
| Reviews | 900-1000 | Member testimonials |
| Membership | 1000-1100 | Pricing plans |
| Offers | 1100-1150 | Special deals |
| Contact | 1150-1250 | Contact form & map |
| Footer | 1250-1300 | Credits & links |

---

## 🎨 Customization Guide

### **1. Change Colors**
Edit the CSS variables at the top of `index.html`:

```css
:root {
  --fire: #FF4500;      /* Primary orange */
  --gold: #FFD700;      /* Accent yellow */
  --ember: #FF8C00;     /* Dark orange */
  --dark: #0d0d0d;      /* Background */
  --text: #f0f0f0;      /* Text color */
}
```

### **2. Update Gym Information**

**Phone Number** (appears multiple times):
```javascript
// Search for: 9580752023
// Replace with: YOUR_PHONE_NUMBER
```

**Email Address**:
```javascript
// Search for: Ashishrajsngh718@gmail.com
// Replace with: YOUR_EMAIL
```

**Address**:
```html
<!-- Find in Contact section and update -->
<span>Your Gym Address Here</span>
```

**Working Hours**:
```html
<!-- Find Timings section in Contact -->
<strong>Monday – Saturday</strong><br>
Morning: 6:00 AM – 10:30 AM<br>
Evening: 5:00 PM – 10:30 PM<br>
```

### **3. Update Trainer Information**

Find the "ELITE TRAINER" section and update:
```html
<h3>Your Trainer Name</h3>
<div class="tr-spec">⚡ Your Specialty</div>
<p>Your trainer bio here...</p>

<div class="tr-stats">
  <div class="trs"><span class="trs-n">YEARS</span><span class="trs-l">Years Exp</span></div>
  <div class="trs"><span class="trs-n">CLIENTS</span><span class="trs-l">Clients</span></div>
  <div class="trs"><span class="trs-n">AWARDS</span><span class="trs-l">Awards</span></div>
  <div class="trs"><span class="trs-n">RATE</span><span class="trs-l">Success Rate</span></div>
</div>
```

### **4. Update Pricing Plans**

Find the "MEMBERSHIP PLANS" section and modify:
```html
<div class="plan-price">
  <span class="p-cur">₹</span>
  <span class="p-amt">YOUR_PRICE</span>
  <span class="p-per">Duration</span>
</div>
```

### **5. Update Gallery Images**

Replace image paths in the Gallery section:
```html
<img src="photos/i1.png" alt="Your Description">
```

Make sure images are in the `photos/` folder with correct names.

### **6. Update Reviews**

Find the "MEMBER REVIEWS" section and add/edit:
```html
<div class="review-card">
  <div class="review-top">
    <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Name">
    <div>
      <h4>Member Name</h4>
      <span class="stars">⭐⭐⭐⭐⭐</span>
    </div>
  </div>
  <p>Review text here...</p>
</div>
```

### **7. Update Statistics**

In the About section, modify counter values:
```html
<span class="stat-num" data-target="2500">0+</span>
<span class="stat-lbl">Members Strong</span>
```

---

## 📞 Contact & Support

### **Gym Contact Information**
- **Phone**: +91 9580752023
- **Email**: Ashishrajsngh718@gmail.com
- **Address**: Gupta Market, Prem Nagar, Muslim Nagar, Alambagh, Lucknow, UP 226005
- **WhatsApp**: [Chat Now](https://wa.me/919580752023)

### **Website Developer**
- **Name**: Prakhar Sharma
- **Phone**: +91 8318276922
- **WhatsApp**: [Contact](https://wa.me/918318276922)
- **Instagram**: [@prakh.ar16](https://www.instagram.com/prakh.ar16/)
- **LinkedIn**: [Prakhar Sharma](https://www.linkedin.com/in/prakhar-sharma-06april/)
- **GitHub**: [prakharsharma123](https://github.com/prakharsharma123)
- **Email**: prakharsharmawork1@gmail.com

---

## 🛠️ Troubleshooting

### **Images Not Showing?**
1. Ensure `photos/` folder exists in your repository
2. Check image file names match exactly in HTML
3. Images must be in PNG, JPG, or WebP format
4. Upload images to GitHub via:
   ```bash
   git add photos/
   git commit -m "Add gym photos"
   git push
   ```

### **WhatsApp Button Not Working?**
Update the phone number in the button:
```html
<a href="https://wa.me/YOUR_PHONE?text=Hello" class="whatsapp-btn">
```

### **Form Not Submitting?**
The form uses `mailto:` which opens the email client. To enable backend submission, you'll need a backend service (Firebase, Formspree, etc.).

### **Site Not Loading?**
1. Check if repository is set to **Public** (not Private)
2. Wait 1-2 minutes after pushing changes
3. Clear browser cache (Ctrl+Shift+Del)
4. Try incognito/private browsing mode

---

## 📊 SEO & Analytics (Optional)

### **Add Google Analytics**
Add this to the `<head>` section:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

Replace `GA_MEASUREMENT_ID` with your Google Analytics ID.

---

## 📜 License

This project is open source. You can use, modify, and distribute it freely.

---

## ✅ Checklist for Going Live

- [ ] Update phone number (all occurrences)
- [ ] Update email address
- [ ] Update gym address and timings
- [ ] Update trainer information
- [ ] Update pricing (if changed)
- [ ] Add all 9 gym photos to `photos/` folder
- [ ] Add trainer photo to `photos/trainer.png`
- [ ] Update member reviews
- [ ] Update statistics numbers
- [ ] Test all links and buttons locally
- [ ] Push to GitHub
- [ ] Enable GitHub Pages
- [ ] Test live website on mobile & desktop
- [ ] Share live link: `https://YOUR_USERNAME.github.io/mahadev-fitness-club/`

---

## 🚀 Next Steps (Advanced)

### **Backend Features** (If you want forms to actually store data)
- Use **Firebase** for real-time database
- Use **Formspree** for email submissions
- Use **Netlify Forms** for form handling
- Create a separate backend API

### **Additional Pages**
- Blog section for fitness tips
- Client testimonials with videos
- Video tours of the gym
- Workout guides & plans
- Mobile app integration

### **Performance Optimization**
- Compress images (use TinyPNG)
- Minify CSS & JavaScript
- Add service worker for offline support
- Implement lazy loading for images

---

## 💡 Pro Tips

1. **Keep content updated** - Update offers, photos, and testimonials regularly
2. **Mobile testing** - Always test on phones before pushing changes
3. **Backup regularly** - Push changes to GitHub frequently
4. **Monitor analytics** - Add Google Analytics to track visitors
5. **Update reviews** - Add new customer testimonials monthly
6. **Social media** - Share your GitHub Pages link on social media

---

## 📧 Questions?

For any issues or improvements:
1. Check the **Troubleshooting** section above
2. Contact the developer: **prakharsharmawork1@gmail.com**
3. Visit the GitHub repository for latest updates

---

**Made with 💪 by Prakhar Sharma**  
*"No Pain • No Gain • Jai Mahadev 🔱"*

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2025-03-20 | Initial release with all features |

---

**Last Updated**: March 20, 2025
