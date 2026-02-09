# Avi Bansal - Accessible Computing Bio

This is an accessible personal bio webpage created for the Accessible Computing course at Texas A&M University.

## 📁 Files Included

- `index.html` - Main HTML page
- `styles.css` - External CSS stylesheet
- `decorative-pattern.svg` - Decorative SVG image
- `0755_SEC_S26.jpg` - Profile photo (you need to upload this)

## 🚀 How to Deploy on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (create an account if you don't have one)
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository (e.g., `accessible-bio` or `your-username.github.io`)
4. Make sure it's set to **Public**
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click "uploading an existing file"
2. Drag and drop all files:
   - `index.html`
   - `styles.css`
   - `decorative-pattern.svg`
   - `0755_SEC_S26.jpg` (your photo)
3. Click "Commit changes"

**Option B: Using Git (Command Line)**

```bash
# Navigate to your project folder
cd path/to/your/project

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit"

# Add remote repository (replace YOUR-USERNAME and REPO-NAME)
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, click on **Settings**
2. Scroll down to the **Pages** section (left sidebar)
3. Under "Source", select **main** branch
4. Select **/ (root)** folder
5. Click **Save**

### Step 4: Access Your Site

Your site will be available at:
- If named `your-username.github.io`: `https://your-username.github.io`
- If named differently: `https://your-username.github.io/repo-name`

It may take a few minutes for the site to go live.

## ✅ Assignment Requirements Met

### HTML Requirements
- ✅ Sections with headings (multiple levels: h1, h2, h3)
- ✅ Hyperlinks (to bio-links.html and email)
- ✅ Images (profile photo with alt text + decorative SVG)
- ✅ Form (mailto form for contact)
- ✅ Lists (multiple ul elements with 2+ items)
- ✅ Semantic emphasis (strong and em tags)
- ✅ External CSS linked
- ✅ No internal or inline CSS
- ✅ No deprecated HTML formatting
- ✅ Semantic markup only

### CSS Requirements
- ✅ External stylesheet
- ✅ Typography updates (font-family, size, weight, color)
- ✅ Layout updates (margins, padding, borders, positioning)
- ✅ Accessible design maintained

### Accessibility Features
- ✅ Semantic HTML structure
- ✅ Descriptive alt text for meaningful images
- ✅ Empty alt attribute for decorative images
- ✅ Form labels properly associated
- ✅ Sufficient color contrast
- ✅ Responsive design
- ✅ Keyboard accessible
- ✅ Clear heading hierarchy

## 🔍 Validation

Before submitting, validate your code:

1. **HTML Validation**: https://validator.w3.org/
   - Upload your `index.html` or enter your GitHub Pages URL
   
2. **CSS Validation**: https://jigsaw.w3.org/css-validator/
   - Upload your `styles.css` or enter your GitHub Pages URL

## 📝 To-Do Before Submission

- [ ] Upload your photo file (`0755_SEC_S26.jpg`) to the repository
- [ ] Update the bio-links.html URL when provided by your professor
- [ ] Validate HTML at W3C Validator
- [ ] Validate CSS at W3C CSS Validator
- [ ] Test the site on GitHub Pages
- [ ] Add your entry to the class Bio Links page (alphabetically by first name)
- [ ] Submit your GitHub Pages URL to Canvas

## 🎨 Customization

Feel free to customize:
- Colors in `styles.css` (currently using Texas A&M maroon #500000)
- Font families
- Spacing and layout
- Add more content about your interests

Just make sure to maintain accessibility and keep passing W3C validation!

## 📧 Contact

For questions about this project, contact Avi Bansal at avi_bansal@tamu.edu

---

**Note**: Make sure your repository is public so your professor can access it!
