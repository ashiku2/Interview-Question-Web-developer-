# What are CSS preprocessors, and why are they used?
CSS preprocessors such as Sass and Less are scripting languages that extend CSS by adding features like variables, nesting, mixins, and functions. They help improve the maintainability and organization of CSS code, reduce repetition, and enable the use of advanced CSS features that are not yet supported natively by browser.

# What is the `z-index` property in CSS?
The `z-index` property specifies the stacking order of elements along the z-axis. Elements with a higher `z-index` value will appear on top of elements with a lower `z-index` value, assuming they have a position other than `static`.


# How do you center an element horizontally and vertically in CSS?
To center an element horizontally, you can use `margin: 0 auto;` along with a specified width. To center an element vertically, you can flexbox (`display: flex; align-items: center; justify-content: center;`) or CSS grid (`display: grid; place-items: center;`) for more complex layouts.

# What is the difference between `display:block`, `display:inline` and `display:inline-block`?

`display:block` makes an element a block-level element, causing it to start on a new line and take up the full width available.

`display: inline` makes an element an inline-level element, allowing it to flow within the text content. 

`display: inline-block` makes an element an inline-level block container, allowing it to behave like an inline element while still respecting width and height properties.


# What are CSS selectors?
CSS selectors are patterns used to select and style HTML elements. Common CSS selectors include element selectors (e.g `p`, `div`), class selectors (e.g.,`.classname`), ID selector(e.g., `#idname`), attribute selectors(e.g., `[attribute=value]`), and pseudo-selectors(e.g., `:hover`, `:nth-child()`).


# What is the importance of specificity in CSS?
Specificity is the means by which browsers decide which CSS rule to apply when multiple rules match a given element. It determines which styles are applied based on the specificity of selectors. Specificity is calculated based on the type of selector used and their order of precedence.


# What is the CSS `position` property used for?
The `position` property specifies the positioning method used for an element. Common values include `static`, `relative`, `absolute`, `fixed` and `sticky`.