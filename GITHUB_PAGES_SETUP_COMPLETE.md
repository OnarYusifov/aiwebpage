# Complete GitHub Pages Setup Guide

## Quick Setup Steps

### Step 1: Enable GitHub Pages (One-Time Setup)

1. **Go to your repository on GitHub:**
   - Visit: https://github.com/OnarYusifov/aiwebpage

2. **Navigate to Settings:**
   - Click the **"Settings"** tab at the top of your repository

3. **Go to Pages:**
   - Scroll down in the left sidebar
   - Click **"Pages"** (under "Code and automation")

4. **Configure Source:**
   - Under **"Source"**, select:
     - **Branch:** `main`
     - **Folder:** `/ (root)`
   - Click **"Save"**

5. **Wait for Deployment:**
   - GitHub will build and deploy your site
   - This usually takes 1-2 minutes
   - You'll see a green checkmark when it's ready
   - A notification will appear at the top with your site URL

### Step 2: Access Your Live Website

Once enabled, your website will be available at:
**https://onaryusifov.github.io/aiwebpage/**

⚠️ **Note:** It may take a few minutes for the site to become available after first enabling Pages.

---

## Automatic Deployment

✅ **Good News:** Your site is now set up for automatic deployment!

- Every time you push changes to the `main` branch, GitHub Pages will automatically update your live site
- Changes typically appear within 1-2 minutes after pushing
- No manual deployment needed!

---

## Files Included for GitHub Pages

- ✅ `.nojekyll` - Tells GitHub Pages not to process the site with Jekyll (for static HTML sites)
- ✅ `index.html` - Your main page (GitHub Pages will serve this as the homepage)
- ✅ All assets, CSS, JS, and images are in the repository

---

## Troubleshooting

### Site Not Loading?
1. **Check the branch:** Make sure Pages is set to deploy from `main` branch
2. **Wait a few minutes:** First deployment can take 2-5 minutes
3. **Check Actions tab:** Go to the "Actions" tab in your repository to see if there are any deployment errors
4. **Verify index.html exists:** Make sure `index.html` is in the root directory (✅ it is)

### Assets Not Loading?
- All paths in your HTML files are relative (e.g., `assets/css/theme.css`)
- These should work correctly with GitHub Pages
- If images/CSS don't load, check that file paths are correct

### Custom Domain?
If you want to use a custom domain:
1. Go to Pages settings
2. Enter your domain in the "Custom domain" field
3. Follow GitHub's instructions to update your DNS settings

---

## Your Live URL

**https://onaryusifov.github.io/aiwebpage/**

Bookmark this URL - it's your live website!

---

## Testing Your Site

After enabling Pages:
1. Wait 2-3 minutes for initial deployment
2. Visit: https://onaryusifov.github.io/aiwebpage/
3. Test all pages:
   - Home: https://onaryusifov.github.io/aiwebpage/index.html
   - About: https://onaryusifov.github.io/aiwebpage/about.html
   - Blogs: https://onaryusifov.github.io/aiwebpage/blogs.html
   - Contact: https://onaryusifov.github.io/aiwebpage/contact.html

---

## Next Steps

1. ✅ Enable GitHub Pages (follow Step 1 above)
2. ✅ Wait for deployment
3. ✅ Visit your live site
4. ✅ Share your URL!

Your site will automatically update whenever you push changes to GitHub!

