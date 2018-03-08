# C-R-A as PWA deficiencies

I ran a newly initialized `create-react-app` build through [DevTools Audit/Lighthouse](https://github.com/GoogleChrome/lighthouse) and found a few deficiencies to meet PWA standards.

## Service worker does not successfully serve the manifest's start_url

I'm not sure why I'm seeing this, but I seem to be having this problem in production as well.

## Need for more icon sizes

- 512px
- 192px
- 144px

## Issues

**Note**: Ignore the HTTP -> HTTPS error when running locally.

![PWA checklist](/public/pwa-checklist-failures.jpg)

![144px icon needed](/public/another-icon-size-error.jpg)

## non-PWA optimizations

- CSS, text optimization
- index `<head> meta` tags

![PWA checklist](/public/performance-optimization-opportunities.jpg)

![PWA checklist](/public/seo-meta-tag.jpg)
