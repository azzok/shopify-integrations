# Show Different Shopify Banner Image on Desktop and Mobile
-----
Step - 1 Create following files in section folder
1. custom-banner-desktop.liquid
2. custom-banner-mobile.liquid 

for showing different banner images for Shopify Store
more details please view <a href="https://www.mojoin.com/show-shopify-banner-image?utm_source=github&utm_medium=inreadme">here </a>.
-----
Step- 2 Add following style in theme.css or theme.css.liquid
```
@media only screen and (max-width: 749px) {
    .yx-mobile-hidden{
       display:none;
     }
    .yx-desktop-hidden{
       display:block;
     }
 }
 @media only screen and (min-width: 750px) {
    .yx-mobile-hidden{
       display:block;
    }
    .yx-desktop-hidden{
       display:none;
     }
 }

```
------
For you reference
<a href="https://www.mojoin.com/show-shopify-banner-image/">Click here </a>

