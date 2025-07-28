# Static Portfolio Website

Pure HTML + Tailwind CSS portfolio - ready for Cloudflare Pages or GitHub Pages deployment.

## 🚀 Quick Deploy

### Option 1: Cloudflare Pages
1. Push this folder to GitHub
2. Connect repo to Cloudflare Pages
3. Build settings: **No build command needed** (static files)
4. Publish directory: `./`

### Option 2: GitHub Pages
1. Enable GitHub Pages in repo settings
2. Source: Deploy from branch → `main`
3. Folder: `/ (root)`

## 📁 File Structure

```
portfolio-static/
├── index.html          # Main portfolio page
├── assets/             # Images folder
│   ├── avatar.jpg      # Your profile photo (80x80px recommended)
│   ├── redforge-demo.webp    # RedForge project demo GIF
│   ├── securepr-demo.webp    # Secure-PR-Guard demo GIF
│   └── proxene-demo.webp     # Proxene demo GIF
├── favicon/            # Favicon files
└── README.md
```

## 🎯 Customization Checklist

### Required Updates:
- [ ] Replace `assets/avatar.jpg` with your photo
- [ ] Add demo GIFs for each project (convert to WebP for smaller size)
- [ ] Update GitHub links in project cards
- [ ] Update email: `siwen@proxene.dev` → your email
- [ ] Update Calendly links
- [ ] Update social media links (GitHub, LinkedIn)

### Content Updates:
- [ ] Customize the hero tagline if needed
- [ ] Update project descriptions (80 words each)
- [ ] Modify tech stack badges
- [ ] Update testimonial and client results
- [ ] Add your actual GitHub stats

## 🎨 Design Features

- **Clean single-page layout** optimized for 30-second HR scan
- **Mobile-responsive** with Tailwind CSS
- **Hover effects** on project cards (subtle lift animation)
- **Professional color scheme** with Indigo accents
- **Inter font** for modern, readable typography
- **Semantic HTML** for SEO

## 📸 Image Requirements

- **Avatar**: 80x80px, square, professional headshot
- **Project demos**: 320x180px (16:9 aspect ratio), WebP format
- **File size**: Keep under 200KB each for fast loading

## 🔧 Technical Notes

- Uses Tailwind CSS via CDN (no build step required)
- Google Fonts for Inter typography
- Responsive breakpoints: sm (640px), md (768px), lg (1024px)
- Optimized for Core Web Vitals

## 📊 SEO Optimized

- Meta description included
- Semantic HTML structure
- Alt text for all images
- Fast loading times

---

**Goal**: Get job interviews in 30 seconds with this professional, clean portfolio.