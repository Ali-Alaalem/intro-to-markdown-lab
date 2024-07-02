# What is a selector?

A **_CSS_** selector is the first part of a **_CSS_** Rule. It is a pattern of elements and other terms that tell the browser which **_HTML_** elements should be selected to have the **_CSS_** property values inside the rule applied to them. The element or elements which are selected by the selector are referred to as the subject of the selector.

![Css](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/selector.png)

In other articles you may have met some different selectors, and learned that there are selectors that target the document in different ways — for example by selecting an element such as `h1`, or a class such as `.special`.

In **_CSS_**, selectors are defined in the **_CSS_** Selectors specification; like any other part of **_CSS_** they need to have support in browsers for them to work. The majority of selectors that you will come across are defined in [Level 3 Selectors specification](https://www.w3.org/TR/selectors-3/)  and [Level 4 Selectors specification](https://www.w3.org/TR/selectors-4/) , which are both mature specifications, therefore you will find excellent browser support for these selectors.

## Selector lists

If you have more than one thing which uses the same **_CSS_** then the individual selectors can be combined into a selector list so that the rule is applied to all of the individual selectors. For example, if I have the same **_CSS_** for an`h1`and also a class of `.special`, I could write this as two separate rules.

**_CSS_**

```javascript
h1 {
  color: blue;
}

.special {
  color: blue;
}
```

I could also combine these into a selector list, by adding a comma between them.

**_CSS_**

```javascript
h1, .special {
  color: blue;
}
```

White space is valid before or after the comma. You may also find the selectors more readable if each is on a new line.

**_CSS_**

```javascript
h1,
.special {
  color: blue;
}
```

## Summary

In this article we've introduced **_CSS_** selectors, which enable you to target particular **_HTML_** elements. Next, we'll take a closer look at [type, class, and ID selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Type_Class_and_ID_Selectors) .
