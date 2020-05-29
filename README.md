# product-slider
Product slider for Shopify using the 'Slick' Javascript library! 

Before getting started, you will need to add a few snippets of code to your theme.liquid file. 
First, add the following code before the closing `<head>` tag:

```html
<!-- Add the slick-theme.css if you want default styling -->
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
<!-- Add the slick-theme.css if you want default styling -->
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>
```

Next, add the following code before the closing `<body>` tag:

```html
  <script type="text/javascript" src="//code.jquery.com/jquery-1.11.0.min.js"></script>
  <script type="text/javascript" src="//code.jquery.com/jquery-migrate-1.2.1.min.js"></script>
  <script type="text/javascript" src="slick/slick.min.js"></script>

  <script type="text/javascript">
    $(document).ready(function(){
      $('.your-class').slick({
        setting-name: setting-value
      });
    });
  </script>
```

Also, make sure to add the slick.js and slick.min.js files as assets.

Once that is done, you're ready to build your slider!

In this particular scenario, my client was using a modified version of the 'Debut' theme and wanted a customizable section that she could manage herself without any hard coding required. See the collection-slider.liquid and slider-styling.css files to see how I created and styled the slider to work as a section within the existing theme.
