# Quick Deployment Guide

## Fastest Way to Deploy (GitHub Pages)

### Step-by-Step Instructions:

1. **Go to your GitHub repository:**
   - Visit: https://github.com/anolloby/aljen

2. **Enable GitHub Pages:**
   - Click **Settings** (top menu)
   - Click **Pages** (left sidebar)
   - Under "Source", select: **Deploy from a branch**
   - Choose branch: **main** (or **master**)
   - Choose folder: **/ (root)**
   - Click **Save**

3. **Wait a few minutes** (usually 1-3 minutes)

4. **Your website will be live at:**
   ```
   https://anolloby.github.io/aljen/
   ```

5. **Done!** 🎉

### What Happens Next?

- Every time you push changes to the main branch, GitHub will automatically update your website
- The GitHub Actions workflow (`.github/workflows/deploy.yml`) handles the deployment
- You can check the deployment status in the **Actions** tab

### Alternative: Use GitHub Actions

The repository already includes a GitHub Actions workflow that will:
- Automatically deploy whenever you push to the main branch
- Can be manually triggered from the Actions tab
- Provides deployment status and logs

To manually trigger a deployment:
1. Go to **Actions** tab
2. Click **Deploy to GitHub Pages**
3. Click **Run workflow**
4. Click the green **Run workflow** button

### Troubleshooting

**If the website doesn't load:**
1. Check the **Actions** tab for any errors
2. Make sure GitHub Pages is enabled in Settings → Pages
3. Verify the branch and folder are set correctly
4. Wait a few more minutes (sometimes it takes up to 10 minutes)

**If you see a 404 error:**
1. Make sure `index.html` is in the root directory
2. Check that all files (audio, images) are committed and pushed
3. Try accessing: `https://anolloby.github.io/aljen/index.html`

**Need help?**
- Check the full README.md for more deployment options
- GitHub Pages documentation: https://docs.github.com/pages
