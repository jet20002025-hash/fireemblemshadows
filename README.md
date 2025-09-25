# Fire Emblem Shadows Website

A comprehensive website dedicated to Fire Emblem Shadows mobile game, featuring game reviews, strategy guides, latest news, and community discussions.

## Features

- **Responsive Design**: Optimized for both PC and mobile devices using Tailwind CSS
- **SEO Optimized**: Complete SEO implementation with proper meta tags, sitemap, and robots.txt
- **Apple Design System**: Clean, modern interface using Apple's typical color scheme
- **Fast Loading**: Optimized for speed with efficient CSS and minimal dependencies
- **Google AdSense Ready**: Includes ads.txt file and AdSense integration

## Website Structure

```
/
├── index.html                          # Homepage
├── reviews/
│   └── fire-emblem-shadows-complete-review.html
├── guides/
│   └── character-building-guide.html
├── news/
│   └── index.html
├── robots.txt                          # SEO robots file
├── sitemap.xml                         # XML sitemap
└── ads.txt                            # Google AdSense verification
```

## SEO Features

- **Meta Tags**: Complete Open Graph and Twitter Card meta tags
- **Canonical URLs**: Proper canonical URL implementation
- **Structured Data**: Semantic HTML with proper heading hierarchy (H1, H2)
- **Sitemap**: XML sitemap for search engine indexing
- **Robots.txt**: Proper crawling instructions for search engines

## Google AdSense Integration

The website includes:
- `ads.txt` file with your AdSense publisher ID: `pub-7208260866318884`
- AdSense script integration in all pages
- Placeholder for Google Analytics tracking

## Deployment Instructions

### GitHub Setup
1. Create a new repository at https://github.com/jet20002025-hash/fireemblemshadows
2. Clone the repository locally
3. Copy all files to the repository directory
4. Commit and push to GitHub

### Cloudflare Pages Deployment
1. Connect your GitHub repository to Cloudflare Pages
2. Set the build command to: `echo "Static site - no build required"`
3. Set the output directory to: `/`
4. Deploy the site

### Domain Configuration
1. Point your domain `fireemblemshadows.org` to Cloudflare
2. Configure DNS settings in Cloudflare
3. Enable SSL/TLS encryption

## Content Guidelines

- All content is written in native English
- Game information is based on real Fire Emblem Shadows content
- Articles are original and non-repetitive
- Regular updates ensure content freshness and SEO performance

## Technical Specifications

- **HTML5**: Semantic markup with proper structure
- **Tailwind CSS**: Utility-first CSS framework for responsive design
- **JavaScript**: Minimal JavaScript for enhanced user experience
- **Performance**: Optimized for Core Web Vitals
- **Accessibility**: WCAG compliant design

## Google AdSense Setup

To complete AdSense integration:

1. **Add Verification Code**: Add the Google Site Verification meta tag to all pages:
   ```html
   <meta name="google-site-verification" content="YOUR_VERIFICATION_CODE">
   ```

2. **Analytics Setup**: Replace `GA_MEASUREMENT_ID` with your actual Google Analytics ID

3. **Ad Placement**: Configure ad units in your AdSense dashboard and add the ad codes to appropriate locations

## Maintenance

- Update content regularly to maintain SEO rankings
- Monitor Core Web Vitals performance
- Keep dependencies updated
- Regular backup of content and configuration

## License

This website is created for educational and community purposes. Fire Emblem is a trademark of Nintendo and Intelligent Systems. This site is not officially affiliated with Nintendo or Intelligent Systems.

## Contact

For questions about this website, please contact the development team through the contact page.
