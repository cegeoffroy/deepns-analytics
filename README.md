# deepns-analytics
Web analytics that tells you which traffic turns into cash. Consent-native, GDPR-compliant, revenue-attributed.

# Deepns Widget — Installation Guide
 
Official installation guide for the Deepns tracking widget. Deepns is a privacy-first web analytics tool that connects your website traffic to revenue — so you know exactly which visitors turn into customers.
 
Full documentation: [deepns.io/docs](https://deepns.io/docs)
Sign up: [deepns.io](https://deepns.io)
 
---
 
## Install
 
Add this script tag to your site's `<head>`, ideally before the closing `</head>` tag:
 
```html
<script
  data-analytics-id="YOUR_ANALYTICS_ID"
  src="https://api.deepns.io/analytics.js"
  defer>
</script>
```
 
Replace `YOUR_ANALYTICS_ID` with the ID shown in your Deepns dashboard under **Settings → Tracking script**.
 
That's it — no config file, no build step.
 
## Framework / CMS notes
 
**WordPress:** use a plugin like *Insert Headers and Footers*, and paste the script into the Header section.
 
**Shopify:** add the script via `theme.liquid`, just before `</head>`.
 
**Static sites / custom HTML:** paste directly into your HTML template's `<head>`.
 
**SPAs (React, Vue, etc.):** add the script tag to your `index.html` `<head>` — it loads once and tracks client-side navigation automatically.
 
## Verifying installation
 
1. Visit your website.
2. Check your Deepns dashboard — a new site status will move from *pending* to *active* once the first event is received.
## Consent & privacy
 
Deepns is cookieless and GDPR-compliant by default. If you want persistent visitor tracking and revenue attribution, you can enable our built-in consent banner in one click from your dashboard — no separate cookie-banner tool required.
 
Details: [deepns.io/docs/consent](https://deepns.io/docs)
 
## Support
 
Questions or issues installing the widget? Reach out at [deepns.io](https://deepns.io) or via the chat widget on any Deepns page.
 
---
