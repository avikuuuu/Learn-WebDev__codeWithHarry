```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS display  property</title>
    <style>
        .box{
            margin: 30px 30px;
            padding: 30px 30px;
            border: 2px solid red;
            display: inline-flex;
        }
        .box2{
            /* display: none; */
            visibility: hidden;
        }

    </style>
</head>
<body>
    <div class="box">
        i am
    </div>
    <div class=" box box2">
        box
    </div>


    <span>
        hey
    </span>
    <span>avi</span>
    
</body>
</html>
```
The `display` property in CSS is used to define the layout behavior of an element, specifying how it should be rendered in the document. In your provided code, you've used the `display` property with the values `inline-flex` and `none`. Let's break down how each is applied:

### CSS Display Property:

1. **Box with Class `.box`:**

   ```css
   .box {
       margin: 30px 30px;
       padding: 30px 30px;
       border: 2px solid red;
       display: inline-flex;
   }
   ```

   - **Explanation:**
     - The element with class `.box` is styled to have a margin of 30 pixels, padding of 30 pixels, and a red border of 2 pixels.
     - The `display: inline-flex;` property is applied, indicating that the element should be displayed as an inline-level flex container. This allows the box to participate in a flex container's layout while behaving like an inline-level element in the flow.

2. **Box with Classes `.box box2`:**

   ```css
   .box2 {
       /* display: none; */
       visibility: hidden;
   }
   ```

   - **Explanation:**
     - The element with classes `.box` and `.box2` has styles for both, but the display property is commented out (`/* display: none; */`) in favor of using `visibility: hidden;`.
     - When `visibility: hidden;` is applied, the element is not displayed, but the space it would occupy is still reserved. It is hidden but not removed from the layout.

3. **Spans:**

   ```html
   <span>
       hey
   </span>
   <span>avi</span>
   ```

   - **Explanation:**
     - Two `<span>` elements with text content "hey" and "avi" are included in the body.

### Usage Example:

- The first `.box` element will be displayed as an inline-flex container, meaning it will align horizontally with other inline elements and have a flex layout.
- The second `.box2` element, even though styled, will not be visible due to `visibility: hidden;`.
- The `<span>` elements will be displayed as inline elements, aligning horizontally in the default flow.

This example demonstrates the use of the `display` property to control the layout behavior of elements, specifically employing `inline-flex` for flex container behavior and `visibility: hidden;` to hide an element while keeping its space in the layout.