# joplin-style-dark-colors
Alternating rows on lists with muted colors, larger, bolder editing styles.

Add both css files to your `JoplinProfile` directory, and restart Joplin.


## Colored Rendered Markdown Stylesheet
`userstyle.css`

Adds horizontal rules to all headers, up to h5.

Increases font size and weight of all text for readability, and colorizes bold and italicized content.

Italicizes blockquotes, and adds color to inline code.


## Indented custom global stylesheet
`userchrome.css`

Fixed last editor line display cutoff by adding margin and padding to containers.

Alternating background colors for list items.

To preserve default highlighting of active list item, only affect the anchor inside the list item, leaving the left as an indented indicator; best compromise to full alternating row colors, as defined global styles override native dynamic css used to enable highlighting.

Also (optionally) removes `click to add tags` element, as it blocks the last line of editing and review windows, requiring either scrolling or extra whitespace at the end of long notes for last line visiblity.

Direct child specificity used to avoid cascading to nested divs, like styling bar.

Wider scrollbars for lists and editor.

Colorized bold and italic styles, italicized blockqoute (text preceded by `>` on a new line).
