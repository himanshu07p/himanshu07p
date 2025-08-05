# Snake Color Variants
# You can use these in your GitHub workflow for different color schemes

## 🌈 Available Color Palettes

### 1. **GitHub Dark Theme (Current)**
```yaml
github-contribution-grid-snake-dark.svg?palette=github-dark&color_snake=#58a6ff&color_dots=#0d1117,#161b22,#21262d,#30363d,#656c76
```

### 2. **GitHub Light Theme (Current)**
```yaml
github-contribution-grid-snake-light.svg?palette=github-light&color_snake=#1a7f37&color_dots=#ebedf0,#9be9a8,#40c463,#30a14e,#216e39
```

### 3. **Ocean Blue Theme**
```yaml
github-contribution-grid-snake-ocean.svg?palette=github-dark&color_snake=#00d4ff&color_dots=#0a0e27,#1e2761,#3c56a6,#5b7ec8,#7aa6eb
```

### 4. **Sunset Theme**
```yaml
github-contribution-grid-snake-sunset.svg?palette=github-dark&color_snake=#ff6b35&color_dots=#2d1b0e,#5d2f1a,#8b4513,#cd853f,#ffa500
```

### 5. **Purple Galaxy Theme**
```yaml
github-contribution-grid-snake-galaxy.svg?palette=github-dark&color_snake=#da70d6&color_dots=#1a0d26,#2e1a4a,#4b0082,#663399,#8a2be2
```

### 6. **Matrix Green Theme**
```yaml
github-contribution-grid-snake-matrix.svg?palette=github-dark&color_snake=#00ff41&color_dots=#0d0d0d,#1a331a,#267326,#33b333,#40ff40
```

### 7. **Fire Theme**
```yaml
github-contribution-grid-snake-fire.svg?palette=github-dark&color_snake=#ff4500&color_dots=#2d0d00,#5d1a00,#8b2500,#cd3700,#ff4500
```

## 🎨 How to Add More Variants

1. Edit `.github/workflows/main.yml`
2. Add new lines to the `outputs:` section
3. Customize the `color_snake` and `color_dots` parameters
4. Update your README.md to include the new variants

## 🌟 Advanced Customization

You can also customize:
- **Snake speed**: Add `&speed=1` (1-5)
- **Snake size**: Add `&size=20` (10-30)
- **Grid size**: Add `&grid_size=20` (10-50)

### Example with all parameters:
```yaml
github-contribution-grid-snake-custom.svg?palette=github-dark&color_snake=#58a6ff&color_dots=#0d1117,#161b22,#21262d,#30363d,#656c76&speed=2&size=15&grid_size=25
```
