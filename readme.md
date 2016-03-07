## Homework Review
- we will be using github repo for each project
    + repository will be URL
    + surge in notes
- ask questions more than other classes would
- **Reminders**
    + must use overflow hidden when floating child
    + border-radius for non-circular elements are better using fixed widths

## Topics for this week
- grid systems
- sass
- typography

## File structure
- project_name
    + index.html
    + css folder
    + images folder
    + js folder
- to remove .html tag
    + create folder with correct name
    + create index.html in that folder
    + browser will default to index.html

## How to structure Sass files
Putting all of your CSS in a single file gets confusing. Multiple pages to style, partials, multiple files (variables, Sass, CSS).
- Always have files
    + variables
    + smallest media query - organizing by breakpoints can work
    + universal - styles for fonts, etc.
    + reset
        * normalize - takes away/replaces styles in order to be cross-browser compatible
        * reset - takes away **ALL styles**
- Import the breakpoint sheets (or page sheets) into the main.css
- Import universals and variables into each breakpoint(or page) sheets
- think about structure from the beginning

**Important!** use underscores for partials _small.css

## CSS specificity
- Learning about DRY (Don't Repeat Yourself) code.
- Second class in double class element will win (cascading)
- Be specific when naming classes - reference elements (i.e. header-wrapper, inner_wrapper)
- Target things efficiently
    + parent/direct child (>)
    + sibling (+)

## CSS Pseudo Selectors
- a:active - on-click
- a:hover - mouse over
- a:focus - selected field
- a:visited - previously clicked
Can test in devtools
- a:before - add this after
- a:after - add this after
Must use "content" - content: 'your_icon';  
useful for icons, etc.

## CSS Positioning
Four types: static, relative, absolute, fixed
- Static
    + default
    + tries to go top left as far as possible
- Relative
    + placeholder space for where element would have been prior to top, left, etc. properties
    + doesn't move other elements like margin would
    + **Relative to parent/self**
- Absolute
    + No 'ghost space' like in Relative
    + relative to the first non-statically positioned element
    + **Relative to first non-static parent - browser by default, not relative to self**
- Fixed
    + maintains position regardless of scroll
    + think headers/navs
    + **Relative to browser, doesn't regard parent**
Z-index decides what is in the foreground
- when using it, use it on both back and front
- numerically, just keeps going up, higher number wins

## Web Standards
### Why does we have web standards?
- We want the user to have the same experience on every browser
- We want the user to have the same experience on every device
- Functionality must be maintained


### Who sets the standard?
- W3C (avoid w3schools - it's not a good explanation)
    + tells browsers what they should be able to do
    + if it's accepted by w3c, it should be functional in your browser
- New versions/features of HTML, CSS, Java
    + it happens fast
    + browser have to figure out what they support or don't

### How to use new features fast
- Adding webkit extensions
    + will work on some browsers, but have fall back on others
        * -webkit- (Chrome)
        * -moz- (Mozilla)
        * -o- (old versions of Opera)
        * -ms- (IE)
    + example: mask-image
    + MDN has good ones
- Still cool features that aren't standards, use [caniuse](http://caniuse.com)
- Support browsers your customers are using

### Check your code for compatibility
- use a markup validator
- w3c validator [validator.w3.org](http://validator.w3.org)

## BEM (Block, Element, Design)
Quicker CSS markup
- uses default/universal
- then uses (__) or (--) to modify
- More on CSS tricks [BEM 101](http://css-tricks.com/bem-101)
- Explore BEM and figure out your own syntax.
- This is helpful for teams.
- Naming conventions are important

## Homework Tonight
- use CSS positioning for codepens
- some reading
- UI design masterlist
    + invite us all to be editors of repo
    + checklist of things you should do when beginning a project
    + everyone contributes and at the end we have reference
    + fork repo and do pull request
        * move to your organization
        * cd url
        * git clone
        * add changes like normal
        * pull request
What do you want to learn from this course? **Ask Abby**.
- UX
    + I'm in this because I like building things and then making them work better
    + I like architecting an experience
- how to make custom sites using CMS
    + online publication interests me
    + but I don't want to just have ability with WP
- how to do my own basic designs with AI (logos, icons, etc.)
- workflow with backend people and how to connect to databases.
- how to lead design teams and full builds (project manage)
    + interested in building my own digital products
    + want to know how to lead teams that I'll work with remotely
- how to go from junior to senior designer - what skills do I need to be refining?
- how to perform research before creating prototypes
    + steps for each iteration
    + the non-coding side of the design
# css-positioning
# css-positioning
