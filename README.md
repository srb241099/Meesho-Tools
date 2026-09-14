# SRB Meesho Profit Calculator

A single-file offline Meesho profit planning calculator.

## Run offline
Just open `index.html` in Chrome, Safari, Edge or Firefox.

## Host on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then Save.
6. GitHub will provide your public Pages URL.

No server, API, database or npm install is required.

## Calculation
Profit per order =
Selling price
- commission
- shipping
- 18% GST on commission + shipping
- expected return impact
- product cost
- packaging
- ads
+ estimated ITC when GST toggle is enabled.

Actual marketplace settlements may differ, so enter your real deductions from settlement reports for best results.

## Label Cropper tab
- Select or drag one or more Meesho label PDFs.
- Choose 45–65% top crop height.
- Output: Crop only, A4 2 labels/sheet, or A4 4 labels/sheet.
- PDFs are processed in the browser and are not uploaded.
- The PDF engine is loaded from a CDN, so the cropper needs internet when the page is first opened. The Profit Calculator itself remains offline.

## Price Calculator tab
Backward pricing tool: start from product costs and your target profit, then estimate the listing price needed after shipping, commission, GST, returns/RTO, reverse freight and unsellable stock.

## PWA / Mobile
- Mobile-first layout with bottom navigation.
- Installable from supported browsers.
- Standalone portrait app mode.
- Profit and Price calculators work offline after installation.
- Core app shell is cached by service worker.
