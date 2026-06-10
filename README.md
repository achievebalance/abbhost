# abbhost - Image Hosting

A simple GitHub Pages-based image hosting solution.

## How to Use

1. **Upload Images**: Add your image files to the `/images` directory
2. **Access Images**: Images are served at:
   ```
   https://achievebalance.github.io/abbhost/images/your-image.jpg
   ```

## Directory Structure

```
images/
  └── your-images-here
```

## Serving Images

Once GitHub Pages is enabled, you can reference images in your website:

```html
<img src="https://achievebalance.github.io/abbhost/images/example.jpg" alt="Example">
```

## GitHub Pages Setup

GitHub Pages has been configured to serve from the `main` branch. Your images are now publicly accessible!

### Supported Formats
- JPG/JPEG
- PNG
- GIF
- WebP
- SVG

## Tips

- Optimize image sizes before uploading for better performance
- Use descriptive filenames
- Consider organizing images in subdirectories (e.g., `/images/hero/`, `/images/gallery/`)
