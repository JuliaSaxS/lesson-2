# Instruction for working in Markdown.

## Text selection.

## Lists.

To add unnumbered lists, you need to put a symbol (*) or (+) before each item in the list. For example, like this:
* Element 1
* Element 2
+ Element 3
+ Element 4
  
To add numbered lists, you need to number each item in the list. For example, like this:
1. Element 1
2. Element 2
3. Element 3

## Working with images.

To insert an image into the text, you need to write:
![It's a wolf.](wolf.jpg)

## Links.

### Hyperlink with immediate indication of the address (in-text).
The link text is enclosed in square brackets. To create an in-text hyperlink, you must use parentheses immediately after the closing square one. You need to put a URL inside them. In them it is also possible to place the name enclosed in quotation marks, which will be displayed when hovering.

[example](http://gb.ru/ "GeekBrains")

When referring to a local directory, it is possible to use a relative path (from the current page, site, etc.)

### A hyperlink similar to a footnote.
When creating a passable hyperlink, instead of the target address, a second pair of square brackets is used, inside which a label, a link identifier (id) placed anywhere in the document is placed:

[Example][id]

[id]: http://gb.ru/ "GeekBrains"

Link identifiers can consist of letters, numbers, spaces, and punctuation marks.

When using the abbreviated identifier, the label is not given, instead the hyperlink text is also used as its name, and the second pair of square brackets remains empty. For example, to make the word "Example" a hyperlink leading to the site http://gb.ru/, it is enough to write:

[Example][]

[Example]: http://http://gb.ru/

## Working with tables.

## Quotes.

## Conclusion.