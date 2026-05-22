# Tuffen Website - Deployment Steps

## Files You Have

✅ `index.html` - Complete website (ready to go)
✅ `README.md` - Full documentation
✅ `.gitignore` - Git configuration

## Files You Need to Add

### Fonts Folder (`fonts/`)
Download and place these in a new `fonts/` folder:
1. `ClimateCrisis-Regular-VariableFont_YEAR.ttf` - You already have this
2. `Unbounded-VariableFont_wght.ttf` - You already have this

### Images Folder (`images/`)
Create a new `images/` folder and place:
1. `logo-tuffen-full.png` - Your full logo (from Asset_6_2x.png)
2. `badger-head.png` - Badger head icon (from Asset_4_2x.png)

## Folder Structure (Before Pushing)

```
tuffen-website-mockup/
├── index.html
├── README.md
├── .gitignore
├── fonts/
│   ├── ClimateCrisis-Regular-VariableFont_YEAR.ttf
│   └── Unbounded-VariableFont_wght.ttf
└── images/
    ├── logo-tuffen-full.png
    └── badger-head.png
```

## GitHub Deployment (Step by Step)

### Step 1: Create the Repository
1. Go to github.com and sign in
2. Click **+** → **New repository**
3. Name it: `tuffen-website-mockup`
4. Set to **Public**
5. Click **Create repository**

### Step 2: Install Git (If Not Already)
- **Mac**: brew install git
- **Windows**: Download from git-scm.com
- **Linux**: sudo apt install git

### Step 3: Setup Your Project Locally

Open Terminal/Command Prompt:

```bash
# Navigate to your project folder
cd /path/to/tuffen-website-mockup

# Initialize git
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial commit: Tuffen website mock-up"

# Rename branch to main (if needed)
git branch -M main

# Add remote repository (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/tuffen-website-mockup.git

# Push to GitHub
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to github.com/YOUR_USERNAME/tuffen-website-mockup
2. Click **Settings** (gear icon)
3. Click **Pages** in the left sidebar
4. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **Save**

### Step 5: Wait for Deployment

- GitHub will deploy your site in 1-2 minutes
- Your site will be live at: **https://YOUR_USERNAME.github.io/tuffen-website-mockup/**
- You'll see a green checkmark when it's done

## Testing

### Local Testing
Before pushing, open `index.html` in your browser to verify fonts and images load correctly.

### After Deployment
- Visit your GitHub Pages URL
- Check all images and fonts load correctly
- Test responsive design (use browser Dev Tools)
- Test navigation links

## Updating Your Site

After initial deployment, to make changes:

```bash
# Make your edits to files
# Then commit and push:

git add .
git commit -m "Describe your changes"
git push
```

Your site updates automatically (usually within 30 seconds).

## Custom Domain (Optional)

To use a custom domain instead of github.io:

1. Settings → Pages
2. Under "Custom domain", enter your domain (e.g., tuffen.com)
3. Update your domain's DNS records to point to GitHub Pages
4. GitHub will auto-enable HTTPS

## Support & Troubleshooting

**Fonts not loading:**
- Verify files are in `fonts/` folder
- Check file paths in `index.html` are correct
- Clear browser cache (Ctrl+Shift+Delete)

**Images not showing:**
- Verify files are in `images/` folder
- Check file names match exactly (case-sensitive)
- Verify image formats (PNG recommended)

**Site not deploying:**
- Check Settings → Pages is configured correctly
- Verify `index.html` is in the root folder
- Wait 2-3 minutes for deployment to complete

---

**Your site will be live in minutes!**
