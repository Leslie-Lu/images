# Images Picture Bed

A GitHub repository for hosting and serving images. This repository acts as a picture bed (image CDN) where you can upload images and access them via direct URLs.

## 📁 Directory Structure

```
images/
├── avatars/       # Avatar and profile images
├── screenshots/   # Screenshot images
├── icons/         # Icon images
└── uploads/       # General purpose uploads
```

## 🚀 Usage

### Uploading Images

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Leslie-Lu/images.git
   cd images
   ```

2. **Add your images:**
   - Place your images in the appropriate directory based on their type
   - For general images, use the `images/uploads/` directory
   - Use descriptive filenames (e.g., `logo-2024.png`, `profile-john.jpg`)

3. **Commit and push:**
   ```bash
   git add images/
   git commit -m "Add new images"
   git push origin main
   ```

### Accessing Images

Once uploaded, you can access your images using the following URL format:

```
https://raw.githubusercontent.com/Leslie-Lu/images/main/images/{category}/{filename}
```

**Examples:**
- `https://raw.githubusercontent.com/Leslie-Lu/images/main/images/avatars/profile.jpg`
- `https://raw.githubusercontent.com/Leslie-Lu/images/main/images/screenshots/demo.png`
- `https://raw.githubusercontent.com/Leslie-Lu/images/main/images/icons/logo.svg`

### Using in Markdown

You can embed images in markdown files using:

```markdown
![Alt text](https://raw.githubusercontent.com/Leslie-Lu/images/main/images/uploads/your-image.png)
```

### Using in HTML

```html
<img src="https://raw.githubusercontent.com/Leslie-Lu/images/main/images/uploads/your-image.png" alt="Description">
```

## 📝 Best Practices

- **Naming Convention:** Use descriptive, lowercase filenames with hyphens (e.g., `user-avatar-2024.png`)
- **Organization:** Keep images organized in the appropriate category folders
- **File Size:** Optimize images before uploading to reduce repository size
- **Format:** Use appropriate formats (PNG for transparency, JPG for photos, SVG for icons)
- **Compression:** Consider compressing images to improve loading times

## 🔧 Tips

- Use image optimization tools like TinyPNG or ImageOptim before uploading
- For frequently accessed images, consider using a CDN service for better performance
- Keep track of which images are being used to avoid accumulating unused files
- Regular cleanup of unused images helps keep the repository size manageable

## 📄 License

This repository is for personal image hosting. Please ensure you have the rights to any images you upload.
