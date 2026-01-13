# GRID//SPLIT - Instagram Grid Splitter

A free, client-side Instagram grid splitter tool that splits images into perfect grids for Instagram carousel posts with zero quality loss.

## Features

- **Zero Quality Loss**: Split images with perfect PNG quality preservation
- **100% Free**: No watermarks, no sign-up required
- **Privacy First**: All processing happens in your browser
- **Flexible Grid Options**: Create 2x1, 2x2, 3x3, 4x4 and more grid combinations
- **All Image Formats**: Support for JPG, PNG, WebP, and all common formats
- **Instant Download**: Download all split images as a ZIP file

## SEO Optimization

This application is fully optimized for search engines with:

- **Comprehensive Meta Tags**: Title, description, keywords optimized for Instagram grid splitting
- **Open Graph Tags**: Perfect social media sharing on Facebook, Twitter, LinkedIn
- **Structured Data**: JSON-LD schema for rich search results
- **SEO Content**: Keyword-rich content section for better ranking
- **Sitemap**: XML sitemap for search engine crawlers
- **Robots.txt**: Proper crawler instructions
- **PWA Manifest**: Progressive Web App support for mobile devices
- **Semantic HTML**: Proper heading hierarchy and alt text

### Target Keywords

- Instagram grid splitter
- Instagram image splitter
- Split image for Instagram
- Instagram carousel splitter
- Grid image splitter
- Instagram grid post
- Instagram grid maker
- Free image splitter
- Instagram puzzle grid

## Deployment to Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Login to Vercel:
   ```bash
   vercel login
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts to link your project

### Option 2: Deploy via Vercel Dashboard

1. Push this code to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Deploy!

### Domain Configuration

Once deployed, configure your domain:

1. Go to your project settings in Vercel
2. Navigate to "Domains"
3. Add `igsplitter.vercel.app` (or your custom domain)

## Post-Deployment SEO Tasks

After deploying to Vercel, complete these SEO tasks:

### 1. Google Search Console

- Go to [Google Search Console](https://search.google.com/search-console)
- Add property: `https://igsplitter.vercel.app`
- Verify ownership
- Submit sitemap: `https://igsplitter.vercel.app/sitemap.xml`

### 2. Bing Webmaster Tools

- Go to [Bing Webmaster Tools](https://www.bing.com/webmasters)
- Add your site
- Submit sitemap

### 3. Create Social Media Images

Generate the following images and place them in the public directory:

- `og-image.png` (1200x630px) - For social media sharing
- `favicon-32x32.png` (32x32px) - Browser favicon
- `favicon-16x16.png` (16x16px) - Browser favicon
- `apple-touch-icon.png` (180x180px) - iOS home screen icon
- `icon-192.png` (192x192px) - PWA icon
- `icon-512.png` (512x512px) - PWA icon
- `screenshot.png` (1280x720px) - App screenshot

### 4. Update Sitemap

After deployment, update `sitemap.xml` with the current date in the `<lastmod>` tag.

### 5. Build Backlinks

- Submit to free web directories
- Share on social media (Twitter, LinkedIn, Reddit r/webdev, r/InstagramMarketing)
- Write a blog post about the tool
- Create tutorials on YouTube
- Post on Product Hunt

### 6. Monitor Performance

- Set up Google Analytics (optional)
- Monitor Google Search Console for:
  - Indexing status
  - Search queries
  - Click-through rates
  - Mobile usability issues

## Technical Stack

- Pure HTML/CSS/JavaScript
- Client-side only (no backend)
- JSZip for creating ZIP files
- Canvas API for image processing
- Azeret Mono font from Google Fonts

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- All modern browsers with Canvas API support

## License

Free to use and modify.

## Support

For issues or feature requests, please create an issue on GitHub.
