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
3. Moved the individualized class names for each article into the id attribute
4. Added "content-article" class to all articles in the content section
5. Moved the repetitive styling for individual article classes into the content-article class selector
6. Moved css selectors for images and headers in the articles into a single content-article class selector (img and h2)
7. Gave each image in the content section an alt attribute

### Benefits Changes
1. Changed div with class "benefits" to a semantic section tag
2. Changed child divs of benefits section to semantic article tag
3. Added "benefit-article" class to all articles in the benefits section
5. Moved the repetitive styling for individual article classes into the benefit-article class selector
6. Moved css selectors for images and headers in the articles into a single benefit-article class selector (img and h3)