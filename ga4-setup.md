# Google Analytics 4 Tracking Script

## Measurement ID: G-XXXXXXXXXX

Add this code to the `<head>` section of your website (before the closing `</head>` tag):

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

## Alternative: Add to index.html

If you want me to add this directly to your index.html, run:
```bash
# This would add the gtag script to your index.html
```

## Where to get your Measurement ID

1. Go to [Google Analytics](https://analytics.google.com)
2. Create an account or sign in
3. Create a property (GA4)
4. Go to Admin > Data Streams > Web Stream
5. Copy the Measurement ID (format: G-XXXXXXXXXX)

## Note

Replace `G-XXXXXXXXXX` with your actual Measurement ID from Google Analytics.