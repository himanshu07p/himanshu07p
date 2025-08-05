# 🎯 Quick Snake Setup Guide

This repository uses an enhanced snake animation that adapts to your GitHub theme!

## 🌟 Current Features

✅ **Responsive Design**: Automatically switches between dark/light themes  
✅ **Custom Colors**: Beautiful blue snake for dark mode, green for light mode  
✅ **Smooth Animation**: Optimized contribution grid snake  
✅ **Auto-Updates**: Refreshes every 12 hours automatically  

## 🚀 Quick Customization

### Want different colors? Edit `.github/workflows/main.yml`:

```yaml
# Ocean Blue Theme
color_snake=#00d4ff&color_dots=#0a0e27,#1e2761,#3c56a6,#5b7ec8,#7aa6eb

# Purple Galaxy Theme  
color_snake=#da70d6&color_dots=#1a0d26,#2e1a4a,#4b0082,#663399,#8a2be2

# Matrix Green Theme
color_snake=#00ff41&color_dots=#0d0d0d,#1a331a,#267326,#33b333,#40ff40

# Fire Theme
color_snake=#ff4500&color_dots=#2d0d00,#5d1a00,#8b2500,#cd3700,#ff4500
```

### Want to manually trigger the snake? 
Go to **Actions** → **Generate Snake** → **Run workflow**

## 📁 Files Explained

- `main.yml` - The workflow that generates your snake
- `README.md` - Your profile page (includes the responsive snake)
- `SNAKE_CUSTOMIZATION.md` - Detailed customization options
- `github-contribution-grid-snake*.svg` - The generated snake files

## 🎨 Advanced Options

Add these parameters to customize further:
- `&speed=2` (1-5) - Snake movement speed
- `&size=15` (10-30) - Snake thickness  
- `&grid_size=25` (10-50) - Grid cell size

## 🐛 Troubleshooting

**Snake not updating?**
1. Check if the workflow ran successfully in Actions tab
2. Clear your browser cache
3. Wait a few minutes for GitHub to serve the new image

**Workflow failing?**
1. The latest version includes error handling
2. It will automatically resolve most git conflicts
3. Check the Actions tab for detailed logs

---

*Happy coding! 🚀*
