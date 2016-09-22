css
- css has a list of rules
- each rule has a selector along with one or more property and value pairs
- selectors specify which elements a rule appiles to

with css the most specific rule is always used
- use more specific selectors to override properties from parents you want to change

use css classes to style a group or set of elements
ex. p.greentea { color: green; } with <p class="greentea"></p>
or for all elements in a group just use .greentea { color: green; }

and you can tag elements with multiple classes
ex. <p class="greentea raspberry blueberry"></p>

Rules of CSS selecting
1. Do any selectors select (match ) your element
2. Do any selectors match via inheritance?
3. Use default
4. If a tie in specificity go with last one (ie. bottom of file)

use text-decoration to underline text

Box Model:
- background-color extends from content area into padding but *not* margin
- you can get crazy and do things like:
   - border-top-color: black;
   - border-bottom-style: dashed;
   - border-left-width: thick;

background-image places an image in the background of an element. Two other properties also affect the background image: background-position and background-repeat.
   - by default background images repeat. you need to disable if you don't want that

The width property only applies to content area portion of box model. The total width is calculated by adding left margin, left border, left padding, content area width, right padding, right border and right margin!

If you don't set a width on an element it defaults to "auto" which fills the entire space it was placed in.

The text-align property affects all in-line elements in a block, including images.

Todo:
- Wrap all <li> elements in <ul>
- use validator for html and css
- Create the About me section above price list; use padding around text to make the new gray area stand out and then use margin to put space between it and the price list
- Add spans for the list/price bullets
- Center image blocks in div
- Underline H1 in header
- Maybe add font-weight to H1 or text-decoration

Restructure:
About Us page
Products page
Home page
Contact us
