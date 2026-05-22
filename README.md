# Tuffen Website Mock-up

A gritty, retro endurance brand website for Tuffen. Built with a vintage athletic poster aesthetic, featuring bold typography, textured design, and a no-nonsense approach to endurance product support.

## Project Structure

```
tuffen-website-mockup/
├── index.html
├── fonts/
│   ├── ClimateCrisis-Regular-VariableFont_YEAR.ttf
│   ├── Unbounded-VariableFont_wght.ttf
│   └── Heatched.otf (optional, currently unused)
├── images/
│   ├── logo-tuffen-full.png (Asset_6_2x.png)
│   └── badger-head.png (Asset_4_2x.png)
└── README.md
```

## Quick Start

### 1. Clone or Download This Repository

```bash
git clone https://github.com/yourusername/tuffen-website-mockup.git
cd tuffen-website-mockup
```

### 2. Add Your Font Files

Place these files in the `fonts/` folder:
- `ClimateCrisis-Regular-VariableFont_YEAR.ttf` (headings)
- `Unbounded-VariableFont_wght.ttf` (body text)
- `Heatched.otf` (optional - for future highlight text)

### 3. Add Your Brand Images

Place these files in the `images/` folder:
- `logo-tuffen-full.png` (your full "TUFFEN" logo with badger - Asset_6_2x.png)
- `badger-head.png` (badger head icon - Asset_4_2x.png or Asset_3_2x.png)

### 4. Verify Local Setup

Open `index.html` in your browser to test locally before deploying.

## Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon in the top right → **New repository**
3. Repository name: `tuffen-website-mockup`
4. Description: "Gritty retro website mock-up for Tuffen endurance brand"
5. Select **Public**
6. Click **Create repository**

### Step 2: Initialize Git Locally

```bash
cd tuffen-website-mockup
git init
git add .
git commit -m "Initial commit: Tuffen website mock-up"
```

### Step 3: Push to GitHub

Copy the commands from your new GitHub repo (they'll look like this):

```bash
git branch -M main
git remote add origin https://github.com/yourusername/tuffen-website-mockup.git
git push -u origin main
```

Replace `yourusername` with your actual GitHub username.

### Step 4: Enable GitHub Pages

1. On GitHub, go to your repo → **Settings**
2. Scroll to **Pages** section
3. Under "Build and deployment", select:
   - **Source:** Deploy from a branch
   - **Branch:** main
   - **Folder:** / (root)
4. Click **Save**

Your site will be live at: `https://yourusername.github.io/tuffen-website-mockup/`

It may take a few minutes to deploy.

## Design Features

- **Gritty textures**: Noise overlays, scan lines, halftone patterns
- **Retro aesthetic**: Vintage boxing gym / athletic poster style
- **Bold typography**: Climate Crisis (headings) + Unbounded (body)
- **Responsive design**: Works on mobile, tablet, and desktop
- **Optimised for performance**: Minimal external dependencies

## Customization

### Change Colors
Edit the CSS variables in `index.html`:
```css
:root {
  --black: #1a1a1a;
  --white: #ffffff;
  --cream: #f5f1e8;
  --red: #c41e1a;
}
```

### Update Product Information
Edit the product cards in the HTML under the `<!-- Products Section -->`:
```html
<div class="product-card">
  <div class="product-number">01</div>
  <h3>YOUR PRODUCT NAME</h3>
  <div class="product-tagline">Your tagline here.</div>
  <p>Your product description here.</p>
  <a href="#" class="product-link">SHOP →</a>
</div>
```

### Modify Text Content
All text is editable directly in `index.html`. Update:
- Hero section copy
- Product descriptions
- Values section content
- Footer information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- Font files are loaded locally from the `fonts/` folder
- Image files must be placed in the `images/` folder
- The site uses CSS Grid for responsive layout
- All textures are CSS-generated (no extra image files needed)

## License

This is a brand mock-up for Tuffen. Contact for usage permissions.

---

**Site live at:** https://yourusername.github.io/tuffen-website-mockup/
