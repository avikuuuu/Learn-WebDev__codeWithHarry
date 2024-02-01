```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Box Model</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        .box {
            background-color: aqua;
        }

        .box1 {
            color: yellow;
            padding: 10px;
            margin: 35px;
            border: 2px solid blue;
            height: 200px;
            box-sizing: border-box;
        }

        .box2 {
            color: red;
            padding: 10px;
            margin: 25px;
            border: 2px solid black;
            height: 200px;
            box-sizing: border-box;
        }
    </style>
</head>

<body>
    <div class="box box1">I am a box</div>
    <div class="box box2">I am another box</div>
</body>

</html>
```


### HTML Structure:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Box Model</title>
```

- **Explanation:** The document starts with the usual document type declaration, the opening `<html>` tag with the language attribute, and the `<head>` section. The head contains metadata like character set, viewport configuration, and the document title.

### Universal Selector (`*`):

```css
<style>
    * {
        margin: 0;
        padding: 0;
    }
</style>
```

- **Explanation:** The universal selector (`*`) targets all elements in the document. Here, it sets the margin and padding for all elements to zero, creating a consistent starting point.

### Box Class Selector (`.box`):

```css
<style>
    .box {
        background-color: aqua;
    }
</style>
```

- **Explanation:** This style targets elements with the class "box" and gives them a background color of aqua.

### Box 1 Styles (`.box1`):

```css
<style>
    .box1 {
        color: yellow;
        padding: 10px;
        margin: 35px;
        border: 2px solid blue;
        height: 200px;
        box-sizing: border-box;
    }
</style>
```

- **Explanation:**
  - `color: yellow;`: Sets the text color to yellow.
  - `padding: 10px;`: Adds 10 pixels of padding inside the box.
  - `margin: 35px;`: Sets a margin of 35 pixels around the box.
  - `border: 2px solid blue;`: Adds a 2-pixel solid blue border to the box.
  - `height: 200px;`: Sets the height of the box to 200 pixels.
  - `box-sizing: border-box;`: Ensures that padding and border are included in the total width and height of the box.

### Box 2 Styles (`.box2`):

```css
<style>
    .box2 {
        color: red;
        padding: 10px;
        margin: 25px;
        border: 2px solid black;
        height: 200px;
        box-sizing: border-box;
    }
</style>
```

- **Explanation:**
  - `color: red;`: Sets the text color to red.
  - `padding: 10px;`: Adds 10 pixels of padding inside the box.
  - `margin: 25px;`: Sets a margin of 25 pixels around the box.
  - `border: 2px solid black;`: Adds a 2-pixel solid black border to the box.
  - `height: 200px;`: Sets the height of the box to 200 pixels.
  - `box-sizing: border-box;`: Ensures that padding and border are included in the total width and height of the box.

### Body:

```html
<body>
    <div class="box box1">I am a box</div>
    <div class="box box2">I am another box</div>
</body>
</html>
```

- **Explanation:** The body contains two `<div>` elements. Each div has the class "box" and an additional class "box1" or "box2" to apply the specific styles defined earlier. The content inside each box is the text "I am a box" or "I am another box."

This example demonstrates the use of CSS to control the box model properties, such as margin, padding, border, and height, creating visually distinct boxes on the webpage. The `box-sizing: border-box;` ensures that the total dimensions of each box are predictable and consistent.