# Horiseon Code Refractor
## Homework 1 - UCI Bootcamp

Deployed: [https://jdmarty.github.io/horiseonCodeRefractor/](https://jdmarty.github.io/horiseonCodeRefractor/).

Repository: [https://github.com/jdmarty/horiseonCodeRefractor](https://github.com/jdmarty/horiseonCodeRefractor).

![Top half of the Horiseon Website](/assets/images/Screenshot-Top.png)
![Bottom half of the Horiseon Website](/assets/images/Screenshot-Bottom.png)

### Project Goals
1. Semantic HTML elements are found in the source code
2. Elements follow a logical structure independent of styling and position
3. Image elements have accessible alt attributes
4. Heading attributes fall in sequential order
5. The title is concise and descriptive

### General Tweaks
1. Reorganized css to put element selectors at top
2. Reorganized css to group selectors by family (content, benefits, footer, etc)
3. Changed single use classes "seo" and "hero" to ids
4. Tabbed CSS file to visually group selectors by parent element
5. Added comments to HTML to easily traverse minimized elements

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
1. Changed div with class "benefits" to a semantic aside tag
2. Changed child divs of benefits aside to semantic article tag
3. Added "benefit-article" class to all articles in the benefits section
5. Moved the repetitive styling for individual article classes into the benefit-article class selector
6. Moved css selectors for images and headers in the articles into a single benefit-article class selector (img and h3)
7. Moved the individualized class names for each article into the id attribute

### Footer Changes
1. Changed div with class "footer" to a semantic footer tag
2. Updated CSS to match new element tag for footer


------------------------------------------------------------------------------------------------------------------

# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.