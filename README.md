# Academic Profile Website

Personal academic website hosted on GitHub Pages.

## About

This is a simple, clean academic profile website designed for PhD students and researchers. The site features:

- **About Section**: Profile photo, bio, and research interests
- **CV Section**: Downloadable CV and inline education/experience details
- **Contact Section**: Email, social media links, and office location

## Live Site

Visit the live website at: [https://BellerNiklas.github.io](https://BellerNiklas.github.io)

## How to Update Your Information

### 1. Personal Information

Edit `index.html` and replace all placeholders marked with `[...]`:

- `[Your Name]` - Your full name
- `[PhD Student in Economics / Your Field]` - Your current title/position
- `[Your University / Institution]` - Your institution
- `[Your bio and research interests]` - Your personal information

### 2. Add Your Profile Photo

1. Add your photo to the repository as `profile.jpg` (or `profile.png`)
2. Update the image source in `index.html` if using a different filename
3. Recommended size: 400x400 pixels or larger (will be displayed as 180x180)

### 3. Add Your CV

Upload your CV as `cv.pdf` to the repository root, or update the link in `index.html` to point to your CV location.

### 4. Customize Colors (Optional)

Edit `style.css` at the top where CSS variables are defined:

```css
:root {
    --primary-color: #2c3e50;    /* Dark blue-gray for headers */
    --secondary-color: #34495e;  /* Medium gray for text */
    --accent-color: #3498db;     /* Professional blue for links */
    --light-bg: #f8f9fa;         /* Light gray backgrounds */
}
```

## Local Development

To preview the website locally:

1. Open `index.html` in your web browser
2. Or use a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Publishing Updates

After making changes:

```bash
git add .
git commit -m "Update profile information"
git push
```

Changes will appear on your live site within a few minutes.

## Technologies

- Pure HTML5 and CSS3 (no frameworks required)
- Responsive design (mobile-friendly)
- Semantic HTML for accessibility
- Clean, academic styling

## License

Feel free to use this template for your own academic website.

---

**Last Updated**: January 2026
