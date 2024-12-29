# CSS Specificity Gotcha: Unexpected Color Inheritance

This repository demonstrates a subtle but important aspect of CSS specificity that can lead to unexpected inheritance behavior.  The example highlights a situation where a seemingly more specific selector does not override a less specific one as expected. The solution clarifies the specificity rules and shows how to correctly override styles based on the principle of cascading. 

## Bug Description:

The bug involves unexpected inheritance in CSS. A paragraph tag (`<p>`) nested within a `div` element does not adopt the style declared specifically for `div p`, unexpectedly inheriting from the parent `div` element's styling instead. 

## Bug Solution:

The solution addresses the issue by applying a more specific selector or using the `!important` flag (though generally discouraged due to its potential to create maintainability problems).  Understanding how CSS specificity works and how inheritance interacts with the cascade is key to resolving similar issues.