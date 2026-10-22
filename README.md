# স্বপ্নসন্ধানী সমাজকল্যাণ ফাউন্ডেশন — Website

A responsive Bengali-language informational website built with plain HTML, CSS, and JavaScript. Suitable for GitHub Pages or any static hosting.

## Features
- Responsive mobile/desktop layout
- Bengali content and all 14 supplied objectives, in expandable panels
- Logo, cover, and executive committee image with remote fallback URLs
- WhatsApp, email, and Facebook contact links
- SEO title, description, keywords, Open Graph metadata, and Schema.org NGO structured data
- Accessible navigation, semantic sections, reduced-motion support

## Run locally
Open `index.html` in a browser. No build step or package installation is required.

## Publish with GitHub Pages
1. Create a repository on GitHub.
2. Upload the files and folders in this project to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. The public URL will appear in the Pages settings.

## Images
The site expects these local files:
- `assets/logo.png`
- `assets/cover.png`
- `assets/committee.png`

If an image could not be downloaded when this project was prepared, its original GitHub attachment URL is configured as a fallback in the HTML. If a fallback does not load, download the image from the original attachment link and place it in `assets/` with the expected filename.

## Before publishing
- Confirm the executive committee image is current and readable.
- Add the organization's location/address if you want local SEO and a map.
- Replace the cover image if you later have a higher-resolution, optimized version.
- For a custom domain, configure it in GitHub Pages and add the required DNS records.
