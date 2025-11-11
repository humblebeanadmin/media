# Product Images Directory

This directory contains product images organized by category.

## Directory Structure
```
src/assets/products/
├── whole-bean/           # Whole Bean Collection products
├── lab-editions/         # Lab Editions (Experimental Lots) products
├── instant-brews/        # Instant Brews products
├── ground-coffee/        # Ground Coffee Selection products
├── drip-bags/           # Drip Bags products
└── coldbrew-bags/       # Coldbrew Bags products
```

## Image Naming Convention
Use kebab-case (lowercase with hyphens) based on the product name:
- `premium-espresso-blend.jpg`
- `coorg-bold-robusta-anaerobic-fermentation.jpg`
- `freeze-dried.jpg`

## Image Specifications
- **Format**: JPG or PNG
- **Size**: Recommended 800x600px or similar aspect ratio
- **Quality**: High resolution for web display
- **File Size**: Optimized for web (under 500KB when possible)

## Adding New Images
1. Place the image in the appropriate category folder
2. Name it according to the product name (kebab-case)
3. Update the `imageUrl` field in the JSON file
4. The frontend will automatically use the new image

## Fallback Behavior
If a product doesn't have a specific image, the system will fall back to the category default image.
