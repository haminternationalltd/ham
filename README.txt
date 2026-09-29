HAM International Ltd. SEO Website Package
==============================================

Contents:
- index.html: SEO-optimized website
- assets/: locally optimized WebP images extracted from the original HTML

Image optimization:
- Embedded base64 local images were extracted to separate WebP files.
- Duplicate logo usage was deduplicated where the same source image was reused.
- width/height attributes were added to local images to reduce layout shift.
- lazy loading and async decoding are applied to non-critical images.
- the primary hero image is marked eager/high priority.

Note:
Four existing Unsplash images remain remote because this package was prepared without external network access:
https://images.unsplash.com/...

Before publishing:
- Replace remote Unsplash images with your own licensed/brand images if desired.
- Add a canonical URL, sitemap.xml, and robots.txt using the final production domain.
