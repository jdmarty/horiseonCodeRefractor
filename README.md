# Horiseon Code Refractor
## UCI Bootcamp HW 1

### Project Goals
1. Semantic HTML elements are found in the source code
2. Elements follow a logical structure independent of styling and position
3. Image elements have accessible alt attributes
4. Heading attributes fall in sequential order
5. The title is concise and descriptive

### Head Changes
1. Added a descriptive title in html head
2. Added a "type" attribute to the stylesheet link in html head

### Header and Jumbotron Changes
1. Changed a div with class "header" to the semantic header tag
2. Updated CSS to match new element tag for header
3. Replaced a parent "div" in the header containing navigation elements to the semantic nav tag
4. Updated CSS to match new element tag for nav
5. Changed div with class "hero" to an image tag with relative filepath src and alt attribute
6. Updated CSS for hero class to remove background image and set object fit to cover

### Content Changes
1. Changed div with class "content" to a semantic section tag
2. Changed child divs of content section to semantic article tag
3. Removed redundant id tags from online reputation management and social media marketing articles