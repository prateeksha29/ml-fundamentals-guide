# ML Interview Prep - Technical Blogs

A collection of in-depth technical articles for Applied Scientist interview preparation.

## 📚 Articles

1. **Mastering Optimization Algorithms** - Deep dive into GD, SGD, Momentum, RMSProp, Adam, AdamW
2. **Loss Landscapes & Generalization** - Understanding sharp vs. flat minima and why it matters

## 🚀 Setup GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it something like `ml-interview-prep` (or any name you prefer)
3. Make it **Public** (required for free GitHub Pages)
4. Don't initialize with README (we have our own files)

### Step 2: Upload Files

You have two options:

#### Option A: Using Git (Command Line)

```bash
# Navigate to the folder containing these files
cd /path/to/your/files

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: ML interview prep blogs"

# Add remote repository (replace USERNAME and REPO-NAME)
git remote add origin https://github.com/USERNAME/REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### Option B: Using GitHub Web Interface

1. Open your repository on GitHub
2. Click "Add file" → "Upload files"
3. Drag and drop these files:
   - `index.html`
   - `optimization_blog.html`
   - `loss_landscape_blog.html`
4. Click "Commit changes"

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source":
   - Select branch: `main`
   - Select folder: `/ (root)`
5. Click "Save"

### Step 4: Access Your Site

After 1-2 minutes, your site will be live at:
```
https://USERNAME.github.io/REPO-NAME/
```

For example, if your username is `pratiksha` and repo is `ml-interview-prep`:
```
https://pratiksha.github.io/ml-interview-prep/
```

## 📁 File Structure

```
.
├── index.html                    # Landing page with links to all blogs
├── optimization_blog.html        # Optimization algorithms guide
├── loss_landscape_blog.html      # Loss landscapes explained
└── README.md                     # This file
```

## 🎯 For Interview Prep

### Recommended Study Order

1. **Week 1-2:** Optimization Algorithms
   - Read the blog 2-3 times
   - Implement each optimizer from scratch in NumPy
   - Implement in PyTorch for comparison
   - Practice explaining to yourself out loud

2. **Week 2-3:** Loss Landscapes
   - Read while keeping optimization blog open for reference
   - Visualize landscapes using matplotlib
   - Connect concepts: why does SGD find flatter minima?

3. **Week 3-4:** Integration & Practice
   - Answer all interview questions without looking
   - Explain concepts at different levels (intuition → math → implementation)
   - Practice debugging scenarios

### Key Concepts to Master

- [ ] Implement Adam from scratch
- [ ] Explain bias correction in Adam
- [ ] Know when to use SGD vs. Adam
- [ ] Understand sharp vs. flat minima
- [ ] Measure sharpness (Hessian eigenvalues)
- [ ] Debug convergence issues systematically
- [ ] Explain batch size effects on generalization
- [ ] SAM and other flatness-seeking methods

## 🛠️ Customization

### Update Content

Simply edit the HTML files and push changes:

```bash
git add .
git commit -m "Update blog content"
git push
```

Changes will appear on your site within 1-2 minutes.

### Add More Blogs

1. Create a new HTML file (e.g., `new_blog.html`)
2. Add a card to `index.html`:

```html
<div class="blog-card">
    <div class="blog-icon">🎯</div>
    <h2>Your New Blog Title</h2>
    <div class="blog-meta">
        <span>📚 Category</span>
        <span>⏱️ X min</span>
    </div>
    <p>Description of your new blog...</p>
    <a href="new_blog.html" class="btn">Read Article →</a>
</div>
```

### Custom Domain (Optional)

If you have a custom domain:

1. Add a file named `CNAME` with your domain:
   ```
   blog.yourdomain.com
   ```

2. Configure DNS with your domain provider:
   - Add CNAME record pointing to `USERNAME.github.io`

## 📝 Notes

- All fonts are loaded from Google Fonts CDN (no local files needed)
- Sites are static HTML/CSS/JS (no build process required)
- GitHub Pages is free for public repositories
- Updates take 1-2 minutes to deploy

## 🔗 Sharing Your Site

Once live, you can share your site URL:
- Add to LinkedIn profile
- Include in resume/portfolio
- Share with study groups
- Reference in cover letters

Example:
> "I've written technical deep-dives on ML fundamentals: [your-site-url]"

## 🐛 Troubleshooting

**Site not loading?**
- Check that GitHub Pages is enabled in Settings
- Verify branch is set to `main` and folder is `/ (root)`
- Wait 2-3 minutes after pushing changes

**Styles not showing?**
- Fonts load from CDN - check internet connection
- Clear browser cache
- Verify HTML files uploaded correctly

**Want to test locally?**
```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000
```

## 📧 Contributing

Feel free to fork and customize these blogs for your own prep!

---

**Good luck with your interviews!** 🚀
