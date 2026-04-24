[README.md](https://github.com/user-attachments/files/27035905/README.md)
# Special Olympics Website Deployment Guide

## Files Included
- `index.html` - Chinese version (中文版)
- `index_en.html` - English version (英文版)

## GitHub Pages Deployment Steps

### Method 1: Upload via GitHub Web Interface

1. **Log in to GitHub** (github.com) with your account (adamwu27)

2. **Create or navigate to your repository**
   - If you don't have a repository yet, create a new one named `specialolympics` or similar
   - Or use an existing repository

3. **Upload the files**
   - Click "Add file" > "Upload files"
   - Drag and drop both `index.html` and `index_en.html`
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

5. **Access your website**
   - Wait 1-2 minutes for deployment
   - Your Chinese version will be at: `https://adamwu27.github.io/[repository-name]/`
   - Your English version will be at: `https://adamwu27.github.io/[repository-name]/index_en.html`

### Method 2: Update via Git Command Line

If you have Git installed locally:

```bash
# Clone your repository (first time only)
git clone https://github.com/adamwu27/[repository-name].git
cd [repository-name]

# Copy the HTML files to the repository folder
# Then commit and push
git add .
git commit -m "Update Special Olympics website"
git push origin main
```

## Future Updates

When you need to update the website:

1. Get the latest HTML files from your assistant
2. Upload/replace the files in your GitHub repository
3. GitHub Pages will automatically redeploy (usually takes 1-2 minutes)

## Tips

- **WeChat Compatibility**: GitHub Pages links can be opened directly in WeChat
- **Custom Domain**: You can configure a custom domain in GitHub Pages settings
- **Multiple Languages**: You can add a language switcher or create separate pages for different languages

## Support

If you encounter any issues, please contact your assistant for help.
