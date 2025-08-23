# Product Images Setup

This folder contains placeholder images for all products. To add actual product images:

## Image Requirements

- **Format**: PNG or JPG (PNG recommended for transparency)
- **Size**: 400x400 pixels minimum (square format recommended)
- **Quality**: High resolution for best display quality
- **File size**: Keep under 500KB for optimal loading

## Product Image Files

Replace the following placeholder files with actual product photos:

1. `jeera_cookies.png` - Jeera cookies (sweet & salty)
2. `eliachi_cookies.png` - Eliachi cookies
3. `coconut_cookies.png` - Coconut cookies
4. `chocochip_cookies.png` - Chocochip cookies
5. `ragi_chocochip_cookies.png` - Ragi Chocochip cookies
6. `jaggery_oats_cookies.png` - Jaggery Oats cookies
7. `honey_oats_cookies.png` - Honey Oats cookies
8. `placeholder.png` - Default fallback image (keep as generic placeholder)

## Image Naming Convention

- Use lowercase letters
- Use underscores instead of spaces
- Keep the same filename as listed above
- Maintain the .png extension

## Adding New Products

When adding new products:

1. Add the image file to this folder
2. Update the product data in `mock_product_datasource.dart`
3. Use the path format: `assets/images/products/your_image_name.png`

## Image Optimization Tips

- Compress images to reduce file size
- Use tools like TinyPNG for optimization
- Ensure consistent aspect ratios across all product images
- Consider using WebP format for better compression (supported in Flutter)

## Testing

After adding images:

1. Run `flutter pub get` to refresh assets
2. Hot restart the app (not hot reload) to load new assets
3. Verify all images display correctly on different screen sizes
