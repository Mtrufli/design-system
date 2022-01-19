# Card Component

This is the code for a card component that includes an image, a linked title, and a section of text.  The full card is clickable to activate the link, but the text following the linked title is also still accessible to screen readers.  Many card components make the entire card a linked object but often that results in the screen reader only reading the link and not reading the content of the card.</p>

Our organization wishes to use a card display for just text-based content as well.  It is quite easy to convert the Card with Image by simply removing the "card-image" div.</p>

## When to Use

some text here

## When not to use

some text here

## Accessibility and Usability

- The link is the title of the card. 
  - You should make sure to use the proper heading level according to the cards location in your page content.  
- Image should contain alt text if information is conveyed by the image.  It can be changed to use a blank alt attribute in order to skip the image in screen readers.

## HTML and CSS

### Card Component with Image; Accessible

<iframe height="300" style="width: 100%;" scrolling="no" title="Card Component with Image; Accessible" src="https://codepen.io/team/UMPO_ADDT/embed/abLrdgK?default-tab=html" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/team/UMPO_ADDT/pen/abLrdgK">
  Card Component with Image; Accessible</a> by App Dev & Digital Transformation (<a href="https://codepen.io/team/UMPO_ADDT">@UMPO_ADDT</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

### Card Component, no Image; Accessible

<iframe height="300" style="width: 100%;" scrolling="no" title="Card Componet, No Image; Accessible" src="https://codepen.io/team/UMPO_ADDT/embed/zYEQBGV?default-tab=html" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/team/UMPO_ADDT/pen/zYEQBGV">
  Card Componet, No Image; Accessible</a> by App Dev & Digital Transformation (<a href="https://codepen.io/team/UMPO_ADDT">@UMPO_ADDT</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>
