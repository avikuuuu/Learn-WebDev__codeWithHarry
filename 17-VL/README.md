### CSS Selectors and Styling Rules:



### 1. Element Selector:

```css
Element Selector  
 div{
     background-color: red; 
} 
```

- **Explanation:** This is a commented-out block of code that would apply styles to all `<div>` elements if uncommented. Currently, it has no styles applied.

### 2. Class Selector:

```css
Class Selector  */
 .red{
    background-color: red;
}
```

- **Explanation:** Similar to the element selector, this block is commented out. If uncommented, it would apply a red background to all elements with the class "red."

### 3. ID Selector:

```css
/* Id Selector */
#green{
    background-color: green;
}
```

- **Explanation:** Targets the element with the ID "green" and applies a green background to it.

### 4. Child Selectors:

```css
/* Child Selectors  */
div > p {
    color: blue;
    background-color: brown;
}
```

- **Explanation:** Selects `<p>` elements that are direct children of `<div>`. Applies blue text and a brown background to those paragraphs.

### 5. Descendant Selector:

```css
/* Descendant Selector  */
div p {
    color: blue;
    background-color: brown;
}
```

- **Explanation:** Selects all `<p>` elements that are descendants of `<div>`. Applies blue text and a brown background to those paragraphs.

### 6. Universal Selector:

```css
/* Universal Selector */
* {
    margin:0;
    padding: 0;
}
```

- **Explanation:** Applies zero margin and padding to all elements on the page.

### 7. Pseudo Selectors:

```css
/* Pseudo Selector  */
a:visited{
    color: yellow
}

a:link {
    color: green;
}

a:active{
    background-color: red;
}

a:hover{
    background-color: yellow;
}
```

- **Explanation:**
  - `a:visited`: Applies yellow color to visited links.
  - `a:link`: Applies green color to unvisited links.
  - `a:active`: Applies a red background to active links.
  - `a:hover`: Applies a yellow background to links on hover.

### 8. First-child Pseudo-class:

```css
p:first-child{
    background-color: aqua;
}
```

- **Explanation:** Selects the first `<p>` element among its siblings and applies an aqua background to it.
----