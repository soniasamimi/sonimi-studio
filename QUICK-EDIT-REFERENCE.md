# Quick Edit Reference Sheet

## 🎯 Most Common Edits - Copy & Paste Ready

### 1. PERSONAL INFORMATION

**Navigation Logo (Line ~151)**
```html
<a href="#" class="logo">Your Full Name</a>
```

**Hero Title (Line ~165)**
```html
<h1>
    Visual Content Creator
    <strong>& Digital Artist</strong>
</h1>
```

**Hero Subtitle (Line ~169)**
```html
<p>Write your personal tagline here. Keep it to 2-3 sentences about what you do and who you work with.</p>
```

**Footer (Line ~423)**
```html
<p>&copy; 2025 Your Name. All rights reserved. • Based in Melbourne, Australia</p>
```

---

### 2. HERO STATS (Line ~172)

Change numbers to match your experience:

```html
<div class="stat">
    <span class="stat-number">20+</span>
    <span class="stat-label">Years in Tech</span>
</div>
<div class="stat">
    <span class="stat-number">200+</span>
    <span class="stat-label">Original Paintings</span>
</div>
<div class="stat">
    <span class="stat-number">∞</span>
    <span class="stat-label">Creative Ideas</span>
</div>
```

---

### 3. PORTFOLIO ITEMS

**Template for Each Portfolio Item:**

```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="images/portfolio/your-image.jpg" alt="Project description" 
             style="width: 100%; height: 100%; object-fit: cover;">
    </div>
    <div class="portfolio-info">
        <div class="portfolio-category">YOUR CATEGORY</div>
        <h3 class="portfolio-title">Project Name</h3>
        <p class="portfolio-description">Brief description of the project and results achieved.</p>
    </div>
</div>
```

**Good Category Examples:**
- Social Media Campaign
- Video Production
- Brand Design
- Motion Graphics
- Content Strategy
- Photography & Editing
- Illustration
- Web Design

---

### 4. ART GALLERY ITEMS

**Template for Each Painting:**

```html
<div class="art-item">
    <div class="art-image">
        <span class="available-badge">Available</span>
        <img src="images/art/painting-name.jpg" alt="Painting title" 
             style="width: 100%; height: 100%; object-fit: cover;">
    </div>
    <div class="art-info">
        <h3 class="art-title">Painting Title</h3>
        <p class="art-details">Watercolor on paper • 16" x 20"</p>
        <p class="art-price">$85</p>
        <a href="#" class="btn btn-buy">Purchase</a>
    </div>
</div>
```

**Medium Options:**
- Watercolor on paper
- Acrylic on canvas
- Mixed media on paper
- Oil on canvas
- Gouache on paper

**Badge Options:**
```html
<span class="available-badge">Available</span>
<span class="available-badge">Commission</span>
<span class="available-badge">Sold</span>
```

For sold items, change button to:
```html
<a href="#" class="btn btn-buy" style="background: #999; cursor: not-allowed;">Sold</a>
```

---

### 5. ABOUT SECTION (Line ~313)

**Your Story - Template:**

```html
<div class="about-text">
    <p>First paragraph: How you got started and your background transition.</p>
    
    <p>Second paragraph: Your location, who you work with, and your unique approach.</p>
    
    <p>Third paragraph: Your art practice and how it influences your commercial work.</p>
    
    <div class="skills-list">
        <!-- Skills go here -->
    </div>
</div>
```

**Skills Template:**

```html
<div class="skill-item">
    <strong>Category Name</strong>
    Specific skills, tools, or services you offer in this category
</div>
```

**Example Skills:**

```html
<div class="skill-item">
    <strong>Visual Content</strong>
    Instagram Reels, TikTok videos, carousel posts, Stories, YouTube thumbnails
</div>

<div class="skill-item">
    <strong>Software</strong>
    Adobe Premiere Pro, After Effects, Photoshop, Illustrator, Figma, Canva
</div>

<div class="skill-item">
    <strong>Art Mediums</strong>
    Watercolor, acrylic, digital painting, mixed media, custom commissions
</div>

<div class="skill-item">
    <strong>Industries</strong>
    Healthcare, startups, SaaS, e-commerce, small business, nonprofits
</div>
```

---

### 6. CONTACT INFORMATION (Line ~388)

```html
<div class="contact-method">
    <h3>Email</h3>
    <a href="mailto:your.email@example.com">your.email@example.com</a>
</div>

<div class="contact-method">
    <h3>LinkedIn</h3>
    <a href="https://linkedin.com/in/yourprofile" target="_blank">Connect with me</a>
</div>

<div class="contact-method">
    <h3>Instagram</h3>
    <a href="https://instagram.com/yourhandle" target="_blank">@yourhandle</a>
</div>
```

**Add More Contact Methods:**

```html
<div class="contact-method">
    <h3>Portfolio</h3>
    <a href="https://behance.net/yourname" target="_blank">View on Behance</a>
</div>

<div class="contact-method">
    <h3>Phone</h3>
    <a href="tel:+61400000000">+61 400 000 000</a>
</div>

<div class="contact-method">
    <h3>Calendar</h3>
    <a href="https://calendly.com/yourname" target="_blank">Schedule a Call</a>
</div>
```

---

### 7. PAYMENT BUTTONS

**Gumroad Integration:**
```html
<a href="https://yourname.gumroad.com/l/painting-name" 
   class="btn btn-buy">Purchase - $85</a>
```

**Stripe Payment Link:**
```html
<a href="https://buy.stripe.com/xxxxx" 
   class="btn btn-buy">Purchase - $85</a>
```

**Email Inquiry:**
```html
<a href="mailto:your@email.com?subject=Art Inquiry: Sunset Reflections&body=I'm interested in purchasing this painting." 
   class="btn btn-buy">Inquire to Purchase</a>
```

**Etsy Link:**
```html
<a href="https://www.etsy.com/listing/12345" 
   class="btn btn-buy">View on Etsy</a>
```

---

### 8. ADD MORE PORTFOLIO ITEMS

**Copy this entire block and paste before the closing `</div>` of portfolio-grid:**

```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="images/portfolio/new-project.jpg" alt="New project" 
             style="width: 100%; height: 100%; object-fit: cover;">
    </div>
    <div class="portfolio-info">
        <div class="portfolio-category">NEW CATEGORY</div>
        <h3 class="portfolio-title">New Project Title</h3>
        <p class="portfolio-description">Description of the new project.</p>
    </div>
</div>
```

---

### 9. ADD MORE PAINTINGS

**Copy this entire block and paste in the gallery-grid section:**

```html
<div class="art-item">
    <div class="art-image">
        <span class="available-badge">Available</span>
        <img src="images/art/new-painting.jpg" alt="New painting" 
             style="width: 100%; height: 100%; object-fit: cover;">
    </div>
    <div class="art-info">
        <h3 class="art-title">New Painting Title</h3>
        <p class="art-details">Medium • Size</p>
        <p class="art-price">$XXX</p>
        <a href="#" class="btn btn-buy">Purchase</a>
    </div>
</div>
```

---

### 10. COLOR CUSTOMIZATION

**Find this section in the CSS (around line 14):**

```css
:root {
    --color-primary: #1a1a1a;      /* Main dark text/sections */
    --color-accent: #d4a574;        /* Gold/bronze highlights */
    --color-secondary: #4a5f4e;     /* Green buttons/sections */
    --color-light: #f5f3ef;         /* Cream background */
    --color-white: #ffffff;
    --color-gray: #6b6b6b;
}
```

**Alternative Color Schemes:**

**Bold & Modern:**
```css
--color-primary: #000000;
--color-accent: #ff6b6b;
--color-secondary: #4ecdc4;
--color-light: #f7f7f7;
```

**Earthy Artist:**
```css
--color-primary: #2c2416;
--color-accent: #d4a574;
--color-secondary: #8b7355;
--color-light: #f5f1e8;
```

**Cool & Professional:**
```css
--color-primary: #1a1a2e;
--color-accent: #0f3460;
--color-secondary: #16213e;
--color-light: #eaeaea;
```

---

### 11. GOOGLE FONTS

**Current fonts:**
- Display (headings): Cormorant Garamond
- Body (text): Work Sans

**To change fonts:**

1. Go to https://fonts.google.com
2. Select 2 fonts (1 for headings, 1 for body)
3. Replace the `<link>` tag in `<head>` (around line 8)
4. Update CSS variables (around line 15):

```css
--font-display: 'YourHeadingFont', serif;
--font-body: 'YourBodyFont', sans-serif;
```

**Good Font Combinations:**

**Elegant:**
- Display: Playfair Display
- Body: Source Sans Pro

**Modern:**
- Display: Montserrat
- Body: Open Sans

**Creative:**
- Display: Abril Fatface
- Body: Poppins

**Professional:**
- Display: Lora
- Body: Raleway

---

### 12. SEO META TAGS

**Add in `<head>` section (around line 6):**

```html
<!-- Basic SEO -->
<meta name="author" content="Your Name">
<meta name="keywords" content="visual content creator, digital artist, social media content, Melbourne artist, watercolor paintings">

<!-- Open Graph (Facebook, LinkedIn) -->
<meta property="og:title" content="Your Name - Visual Content Creator & Artist">
<meta property="og:description" content="Melbourne visual content creator specializing in social media, video, and original paintings">
<meta property="og:image" content="https://yoursite.com/images/og-image.jpg">
<meta property="og:url" content="https://yoursite.com">
<meta property="og:type" content="website">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Your Name - Portfolio">
<meta name="twitter:description" content="Visual content creator & digital artist based in Melbourne">
<meta name="twitter:image" content="https://yoursite.com/images/og-image.jpg">
```

---

### 13. GOOGLE ANALYTICS

**Add before `</head>` tag:**

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

Replace `G-XXXXXXXXXX` with your actual tracking ID from Google Analytics.

---

### 14. ADD TESTIMONIAL SECTION

**Insert after the portfolio section:**

```html
<section id="testimonials" style="background: var(--color-white);">
    <div class="section-header">
        <div class="section-tag">Testimonials</div>
        <h2 class="section-title">What Clients Say</h2>
    </div>
    
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 3rem;">
        
        <blockquote style="background: var(--color-light); padding: 2rem; border-left: 4px solid var(--color-accent);">
            <p style="font-size: 1.1rem; font-style: italic; margin-bottom: 1rem; line-height: 1.8;">
                "Quote from client about your work and results achieved."
            </p>
            <cite style="font-weight: 600; color: var(--color-secondary);">
                — Client Name<br>
                <span style="font-size: 0.9rem; font-weight: 400; color: var(--color-gray);">Position, Company</span>
            </cite>
        </blockquote>
        
        <!-- Add more testimonials by copying the blockquote above -->
        
    </div>
</section>
```

---

### 15. MOBILE MENU (If needed)

**If you want a hamburger menu on mobile, add this:**

```html
<!-- Add after nav tag (around line 163) -->
<button id="mobile-menu-toggle" style="display: none; background: none; border: none; font-size: 1.5rem; cursor: pointer; position: fixed; top: 1.5rem; right: 2rem; z-index: 1001;">
    ☰
</button>

<!-- Add before closing </script> tag -->
const menuToggle = document.getElementById('mobile-menu-toggle');
const navUl = document.querySelector('nav ul');

menuToggle.addEventListener('click', () => {
    navUl.style.display = navUl.style.display === 'flex' ? 'none' : 'flex';
});

// Show menu toggle on mobile
if (window.innerWidth <= 640) {
    menuToggle.style.display = 'block';
}
```

---

## 🎯 Quick Tips

1. **Always save a backup** before making major changes
2. **Test after each edit** to make sure nothing broke
3. **Use Ctrl+F (Cmd+F)** to find text quickly
4. **Keep line breaks** and indentation as they are
5. **Don't delete closing tags** (`</div>`, `</section>`, etc.)

---

## 🔍 Find & Replace Shortcuts

**Find these strings and replace with your info:**

| Find | Replace With |
|------|--------------|
| `Your Name` | Your actual name |
| `your.email@example.com` | Your email |
| `yourprofile` | Your LinkedIn username |
| `yourhandle` | Your Instagram handle |
| `Melbourne, Australia` | Your location |
| `[Project Image X]` | `<img src="images/...">` |

---

## 🚨 Common Mistakes to Avoid

❌ **Don't** delete closing tags
❌ **Don't** remove quotes from attributes
❌ **Don't** break the CSS `:root` section
❌ **Don't** forget to upload images folder

✅ **Do** keep all HTML structure intact
✅ **Do** test on mobile after changes
✅ **Do** compress images before uploading
✅ **Do** save backups regularly

---

## 📱 Quick Mobile Test

After editing, test these on your phone:
1. Text is readable without zooming
2. All buttons are easily tappable
3. Images load properly
4. Navigation works
5. No horizontal scrolling

---

**Save this file for quick reference when editing your site!**
