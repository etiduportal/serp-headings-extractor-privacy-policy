# serp-headings-extractor-privacy-policy

## 1. Overview
SERP Headings Extractor is a Chrome extension that helps you scrape the first page of organic Google Search results and extract each result page’s **title tag**, **meta description**, and **heading hierarchy (H1–H3)**, then export the data as **CSV/TSV** or **Markdown**.

This extension is designed with privacy in mind. It **does not collect, store, or transmit personal data** to our servers or to third parties.

## 2. Data we access
SERP Headings Extractor temporarily accesses the following information only when you use it:

- The **URL of the active tab** (to verify it is a Google Search results page and to read the SERP content).
- The **organic result links and titles** displayed on the Google results page.
- The **HTML content** of the result pages you select, in order to extract:
  - the page `<title>`
  - the `<meta name="description">` content
  - headings **H1, H2, H3** (text and level)

This information is used only to build the export (CSV/TSV/Markdown) you request.

## 3. How we use this data
- The SERP data and extracted page structure are processed **locally in your browser**.
- The extension may **fetch** the selected result pages so it can parse their HTML and extract the required fields.
- The generated output can be:
  - **copied to your clipboard** (if you click “Copy”), or
  - **downloaded as a file** (if you click “Download”).

We do not send this information to any developer-controlled server.  
We do not store this information anywhere outside your device.

## 4. Permissions explained
SERP Headings Extractor uses the following Chrome permissions:

- **"activeTab"**: allows the extension to access the content of the currently active tab only when you invoke the extension (to read the Google SERP you’re viewing).
- **"scripting"**: allows the extension to run a script on the active Google SERP tab in order to extract organic result URLs and titles.
- **Optional host permissions ("http://*/*", "https://*/*")**: requested only when needed so the extension can fetch the pages from the results you selected and extract title/meta/headings.

These permissions are used exclusively to provide the core SERP extraction and export functionality.

## 5. Data sharing
We do not sell, rent, or share any data with third parties.  
The extension does not include analytics, tracking, advertising, or telemetry.

Note: When the extension fetches selected result pages, your browser will connect to those websites directly. Those websites may have their own logging and privacy practices, governed by their own privacy policies.

## 6. Children’s privacy
SERP Headings Extractor is a general-purpose productivity tool and is not directed at children. We do not knowingly collect any personal information from children.

## 7. Changes to this policy
We may update this privacy policy from time to time. Any changes will be reflected here with an updated “Last updated” date.

## 8. Contact
If you have any questions about this privacy policy or about how SERP Headings Extractor handles data, you can contact us at:

**Email:** etiduportal@gmail.com
