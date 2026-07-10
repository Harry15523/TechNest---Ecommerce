# Lighthouse Evidence Instructions

Actual screenshots must be produced on your own computer because Lighthouse runs inside your Chrome browser and the screenshots must show your tested version.

## Required files
Save these images in this folder:
- Problem1.png
- Fix1.png
- Problem2.png
- Fix2.png

## Step-by-step
1. Open the website in Google Chrome using Live Server.
2. Press F12 or right-click and choose Inspect.
3. Select the Lighthouse tab. If it is hidden, click the double-arrow menu.
4. Select Mobile and tick Accessibility, Best Practices, SEO and Performance.
5. Click Analyse page load.
6. Take a screenshot of the first report and save it as Problem1.png.
7. Choose one reported accessibility issue and fix it in the HTML or CSS.
8. Run Lighthouse again and save the improved report as Fix1.png.
9. Repeat with a second issue and save Problem2.png and Fix2.png.

## Two suitable improvement examples
- Problem: an image has no alt text. Fix: add a short, meaningful alt attribute.
- Problem: a form field has no label. Fix: add a label with a for attribute matching the input id.
- Alternative: improve low colour contrast or add an accessible name to a button.

## Evidence note for presentation
Explain the issue, the exact code change and the score or audit result after the fix. Do not claim a perfect score unless the screenshot proves it.
