# Content Update Guide

This guide will help you update the placeholder content in the website with your actual information.

## Quick Start

1. Open `index.html` in a text editor
2. Update any sections that need to be changed
3. Replace placeholder text with your actual content
4. Save the file and commit your changes

## Sections to Update

### 1. Bio/Background Section

**Location:** Lines ~30-35 in `index.html`

**What to update:**
- Replace the generic bio paragraphs with your actual background story
- Keep it short and focused (2-3 paragraphs max)
- Emphasize your teaching background
- Mention your passion for wellness and kindness

**Example structure:**
```
Paragraph 1: Brief introduction and what you do
Paragraph 2: Your background (teaching experience, wellness journey)
Paragraph 3: Your mission and why you do this work
```

### 2. Credentials Section

**Location:** Line ~40 in `index.html`

**What to update:**
- Add your specific certifications
- Mention your teaching credentials
- List relevant wellness training or qualifications

**Example:**
```
Experience & Credentials: Former Educator (20 years), Certified Wellness Advocate, 
dōTERRA Wellness Advocate, [Add any other certifications]
```

### 3. Organizations Section

**Location:** Line ~68 in `index.html`

**What to update:**
- List specific organizations you support
- Mention the causes you're passionate about
- You can list them or describe them in a paragraph

**Example:**
```
I actively support [Organization 1], [Organization 2], and [Organization 3]. 
Through these partnerships, I contribute to causes focused on education, 
community wellness, and mental health support.
```

### 4. Email Address

**Location:** Line ~77 in `index.html`

**Current email:** `hello@anointforwellness.com`

**What to update (if needed):**
- Replace with a different email if desired
- Update it in TWO places:
  1. The `href="mailto:..."` attribute
  2. The visible text between the `<a>` tags

**Example:**
```html
<p><a href="mailto:youremail@example.com">youremail@example.com</a></p>
```

### 5. Social Media Links

**Location:** Lines ~82, ~87, ~92 in `index.html`

**What to update:**
- Update Instagram URL with your actual Instagram profile
- Update Facebook URL with your actual Facebook profile
- Update LinkedIn URL with your actual LinkedIn profile

**Find your URLs:**
- Instagram: Go to your profile, click Share Profile → Copy Link
- Facebook: Go to your page, copy the URL from the address bar
- LinkedIn: Go to your profile, copy the URL from the address bar

**Example:**
```html
<a href="https://instagram.com/yourhandle" target="_blank" ...>
<a href="https://facebook.com/yourpage" target="_blank" ...>
<a href="https://linkedin.com/in/yourprofile" target="_blank" ...>
```

## Optional Updates

### Offerings Descriptions

**Location:** Lines ~48-65 in `index.html`

You can customize the descriptions of:
- Your Kindness Project
- dōTERRA Products
- Wellness Cards

Keep them concise but descriptive.

### Colors

**Location:** `styles.css` lines ~8-15

To change the color scheme, update the CSS variables:
```css
--primary-color: #6b9080;     /* Main green color */
--secondary-color: #a4c3b2;   /* Lighter green */
--accent-color: #cce3de;      /* Very light green */
```

Use a color picker tool to find hex codes for your preferred colors.

## Testing Your Changes

1. Save your changes to `index.html`
2. Open the file in your web browser
3. Review the changes
4. Make sure all links work correctly

## Publishing to GitHub Pages

Once you're happy with your changes:

1. Commit your changes:
   ```bash
   git add index.html
   git commit -m "Update website content with actual information"
   git push
   ```

2. Enable GitHub Pages (if not already enabled):
   - Go to your repository on GitHub
   - Click Settings → Pages
   - Under "Source", select the branch you want to deploy
   - Click Save

3. Your site will be available at:
   `https://nickryanweber.github.io/Anoint-for-Wellness/`

## Need Help?

If you need help updating the content, feel free to:
- Ask Nick for assistance
- Refer to the README.md file
- Look at the HTML comments in the code for guidance
