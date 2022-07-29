# 02-Challenge

Refactor Web Page

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes

?WHEN I view the heading attributes
THEN they fall in sequential order?

WHEN I view the title element
THEN I find a concise, descriptive title
```


# My changes to HTML

```
Changing non-samantic element "div" to samantic element "header"
getting rid of "span" element and using "h1" as the selector on css page
getting rid of "div" and keeping "ul" and adjusting indentation for "<ul></ul>"
changing "div" to "main"
changing "div" under "main" to "section" sematic elements
changing "div" to "aside"
changing "div" under "aside" to "section" sematic elements
changing "div" to "footer"
adding "alt" attributes to every image/icon
moving "class" attributes towards the front of every "img" attribute

```

# My Changes to CSS

```
removing ".seo" for "header h1"
changing div to ul since ul replaced divs container for ".header ul"
changing div to nav for ".header nav ul"
removing div to match with semantic html for ".header ul li"
```
