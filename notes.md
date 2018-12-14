### page 11

> To override inline declarations in your stylesheet, you’ll need to add an `!important` to the declaration, shifting it into a higher-priority origin. If the inline styles are marked important, then nothing can override them. It’s preferable to do this from within the stylesheet.
> So `important` is actually creates a different origin

### page 17

> A helpful mnemonic to remember this order is LoVe/HAte—link, visited, hover, active.

> The browser follows these three steps—origin, specificity, and source order to resolve every property for every element on the page.

### page 23

> Declaring display: initial is equivalent to display: inline. It won’t evaluate to display: block regardless of what type of element you apply it to. That’s because initial resets to the initial value for the property, not the element; inline is the default value for the display property.

`initial` resets to the initial value for the `property`, not the `element`;
