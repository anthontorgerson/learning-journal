# Design Webpages with CSS

Cascading Style Sheets (CSS) is a programming language used to add or modify how elements in a webpage should appear. For example, you could specify that you want a blue background and for all paragraphs to appear in red with New Times Roman font. CSS works by associating rules with HTML elements & contains a *selector* and a *declaration*.

p {
    font family: New Times Roman;}
}

- *Selectors* indicate which element the rule applies to; the same rule can apply to various elements by separating the element names with commas. Shown above, the selector would be p or `<p></p>`.

- *Declarations* indicate how the element specified in the selector should be styled. Declarations are split into by 2 parts: a *property* & a *value*.

- *Properties* indicates the aspects of the elements you want to change and ends with a colon. Shown above, the property would be the font family, but you can also change color width, height, border & more.

- *Values* specify the settings you want to use and ends with a semi-colon. Shown above we specify to use New Times Roman font. If you wanted to change the color to yellow, in "Color: Yellow", yellow would be the value.


CSS can be used in 3 different places: (1)externally, (2)internally and (3)embedded.
1) *Externally*: the programmer has a separate file named "styles.css" & links to it in the html file with a `<link href="styles.css" rel="stylesheet">` tag, located in the `<head></head>` tags. The "styles.css" file will contain the CSS code. External CSS is better for a website with several pages.
2) *Internally*: the programmer uses `<style></style>` tags in the `<head></head>` tags of each individual HTML file.
3) *Embedded*: the programmer can add style rules directly to the HTML tags using the `style=""` attribute & will only apply to a single paragraph element.


### CSS Selectors

There are a wide variety CSS selectors you can use to target specific elements in a HTML document. Some examples include universal, type and class selectors. Selectors are case sensitive & must match element names & values exactly. Click [HERE](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors) to see a list of CSS selectors.

### How CSS Rules Cascade

"Cascading" refers to the order in which similar style rules are applied. If two selectors are identical, the latter of the two will take precedence. So in the coding below, "blue" will be the color applied. This can be referred to as the *last rule*.

i {
    color: green;
}
i {
    color: blue;
}

If one selector is more specific than the others, that one will take precedence over more general ones. This can be referred to as the *specificity* rule.

* You can add `!important` after any value to indicate that it should be considered more important and take precedence over other similar rules.

### Chapter 11: Color

There are multiple ways you can add and specify color using CSS:
    Way         Example
- Color name:   Black
- Hexadecimal:  #123456
- RGB values:   rgb(255, 0, 0)
- RGBA values:  rgba(0, 0, 0, 0.5)
- HSL values:   hsl(0, 100%, 50%)
- HSLA values:  hsla(0,100%,100%,0.5)
- CMYK values:  cmyk(0, 1, 0.5, 0)

You can use colors to change text, background and borders. Using a color picker can help you find the color you are looking for. There are 100 predefined color names. Using RGB or Hexadecimal values can broaden your color range (16 million color combinations.) By using HSL value you can control the hue, saturation and lightness of the colors. When choosing colors for you webpage it is important to understand the flow of your color scheme. Your webpage should be readable. Using light background with dark text is a good practice. A good color scheme for your webpage should make it easy to read and be accessable for everyone that visits.



- [Return To Home - 102](/README.md)