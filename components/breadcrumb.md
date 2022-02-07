# Breadcrumbs
Breadcrumbs are a particular type of navigation that helps a visitor understand their current location in the website's hierarchy.


## When to use
Breadcrumbs are most useful when a site has an extensive navigational structure.

## When not to use
If you site is only one or two levels deep, it is not really valuable to add a breadcrumb navigation.

## Accessibility & Usability

- use an ordered list versus an unordered list - this indicates hierarchy versus just being a list of items
- use a nav element with the role attribute equal to "navigation"
- use a aria-label element to indicate the type of navigation element, set to "breadcrumb"
- if the current page is represented in the breadcrumb, use aria-current attribute set to "location"
- list items are enough of an indication of the location level, separators are just for visual presentation and should be added either with CSS or hidden from assistive tech with an aria-hidden attribute


## HTML and CSS
