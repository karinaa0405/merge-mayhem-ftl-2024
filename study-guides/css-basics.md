# CSS Basics

 - Property: A property is the type of style on an HTML element. This includes color, positioning, font, border, etc. Check out MDN Docs for a full list of CSS properties.
  - Value: This is the exact style you want to implement on your website. In the example above, we want to use the color `navy` in the `body` of our website.
  - **Note:** Each property has its own set of valid values. For example, The `color` property can take values by name (`blue`, `green`, etc), Hex format (`#FFFFFF`), or RGB colors (`rgb(255,255,255)`).
- `:`: The colon symbol is used to separate the property and value.
- `;`: The semicolon symbol is used to end a declaration or rule.

There are many great reference materials to read about different CSS properties and values. We highly recommend checking out [CSS Reference's free visual guide to CSS](https://cssreference.io/).

Let’s take a step back and review different CSS selectors and their associated syntax. For this we will focus on the basic selectors, but we highly recommend you check out MDN Docs for a [full list of CSS selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors).


<<<<<<< HEAD
=======
- `{}`: In CSS we use the curly brackets `{}` to define a rule set. All rules or declarations must be included inside the brackets.
- Selector: A selector is used to identify the element the CSS rule will be applied to. In the example above, we use an element selector to apply rules to the entire body element. Basic selectors can select all elements, elements by type, class, and id, or by attribute.
- Declaration: Each property and value pair is considered a declaration or rule.

| Selector | Description | Syntax |
|----------|-------------|--------|
| [Universal Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors) | This selector uses the `*` symbol to apply styling rules to all elements on the website. | `* { property: value; }` |
| [Type Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors) | This selector uses the name of an HTML element to apply styling rules to a specific type of elements | `element { property: value; }` |
| [Class Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors) | This selector uses the `.` symbol followed by the class name (as identified by the attributes of some elements in the HTML document) to apply styling rules to all elements with the same class name. | `.className { property: value; }` |
| [Id Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors) | This selector uses the `#` symbol followed by the id name to apply styling rules to a single element. | `#idName { property: value; }` |


**Line 6**  `<link href="style.css" rel="stylesheet" type="text/css" />`  connects the CSS style sheet to our HTML file.

Let’s break down the syntax used to do this action. Learn more on the [MDN Web Docs about the `link` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link).

- `<link>`: This element specifies relationships between the current document (the HTML file) and an external resource (the CSS file).
- `href`: This attribute specifies the file path, or location, of our external resource. In this particular example, the CSS file is named `style.css` but you can name your stylesheet anything. Take note that the file path is surrounded by double quotes, `""`.
- `rel`: `rel` stands for relationship. This lets the document know how the resource will interact with the current document

, in this case we are linking to a `stylesheet`. Learn more on the MDN Web Docs about link types.
- `type`: Similar to the `rel` attribute, the `type` attribute lets the document know the specific type of file that is being linked.


>>>>>>> main
