# Setup Instructions

## Adding Your Profile Photo

Your profile photo needs to be saved as `profile.jpg` in the root directory.

### Option 1: From your existing files
If you have the photo file saved locally:
```bash
cd "C:\Users\nikla\Projects\BellerNiklas.github.io"
# Copy your photo here and rename it to profile.jpg
cp "/path/to/your/photo.jpg" profile.jpg
```

### Option 2: Quick search for the photo
The photo you showed me might be in your files. Let me search common locations:
```bash
# Search in Desktop folders
find "C:\Users\nikla\OneDrive - Universität Mannheim\Desktop" -name "*.jpg" -o -name "*.png" 2>/dev/null | grep -i "niklas\|beller\|photo\|profile" | head -10
```

Recommended image specifications:
- Format: JPG or PNG
- Size: 400x400 pixels or larger (will be displayed as 180x180 circular)
- File name: `profile.jpg`
- Location: Root directory of the repository

## Current Status

✅ Website structure created
✅ All personal information added from CV
✅ CV PDF file copied to repository
✅ Professional styling applied
⏳ Profile photo needs to be added

## Quick Start

Once the photo is added:
```bash
cd "C:\Users\nikla\Projects\BellerNiklas.github.io"
git add .
git commit -m "Add profile photo and finalize website"
git push
```

Your site will be live at: https://bellerniklas.github.io
