### Installation Guide
Once you install the app in your store, we'll send you the activation script that you need to add to your Shopify theme codebase.

> Goto Online Store -> Themes -> Edit Code -> Layout/theme.liquid -> head via your store admin

Add two script tags-

First one: (will provide this script)
```html
<script>!function(){function initialize()....</script>
```

Second one:
```html
<script>
  const concierge = new Concierge()
  concierge.init("<your-shop-domain>")
</script>
```
