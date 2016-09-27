# Full width elements
Within our Shopify themes all content is contained to a maximum width defined by the framework of the theme.
In order to add full width content like images or video within that content that breaks out of this boundaery a few small code changes would need to be applied within the page that you are editing.

Open the page that you are editing and on the top right of the editor window click on the View HTMl button.
Where you want to break out into full width use the following.

```html
</div><!-- close the row container -->
</div><!-- close the desktop / tablet / mobile container -->

Add your full width content here.

<div class="row"><!-- re-initialize the row container -->
<div class="desktop-12 tablet-6 mobile-3"><!-- re-initialize the desktop / tablet / mobile container -->
```

click save when done.
This will expand the content inbetween the above to full width leaving the rest of the content of that page contained.
It is vital to ensure that the row and desktop-12 tablet....   are re-initiated to stop content below from breaking.
