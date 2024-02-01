```HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fonts</title> 
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&family=Poppins:wght@300&display=swap');
        h1 {
            font-family: 'Poppins', 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
        }

        p {
            /* font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; */
            font-family: 'Baloo Bhai 2', sans-serif;
            font-size: 20px; 
            /* font-style:italic;
            font-weight: 500;  */
            
        }
        h2{
            text-align: center;
            text-transform: uppercase;
            text-decoration: underline;
            text-decoration-color: blue;
            /* text-decoration-style: dotted; */
            text-decoration-thickness: 7px ;
            /* text-indent: 45px; */
        }
        .lorem{
            border: 2px solid red;
            width: 145px;
            word-break: break-all;
            /* text-overflow: ellipsis;
            overflow: hidden; */

        }
    </style>
</head>

<body>
    <div>
        <!-- https://codepen.io/web-dot-dev/pen/yLojraG -->
        <h1>Fonts</h1>
        <h2>about Fonts</h2>
        <p>This is a video on fonts</p>
        <p class="lorem">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos sequi accusamus quas itaque molestias dolorem quisquam quod, adipisci maxime dolore, mollitia illo officia deserunt voluptatem iure qui. Fugit aliquam possimus aperiam commodi eum amet veniam at vel. Necessitatibus asperiores eos amet laborum dolor, ipsum porro!</p>
    </div>
</body>

</html>
```
### Importing Fonts:

```css
<style>
    @import url('https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&family=Poppins:wght@300&display=swap');
</style>
```

- **Explanation:** This style imports two Google Fonts: 'Baloo Bhai 2' and 'Poppins' with a weight of 300. These fonts can be used in the subsequent CSS styles.

### Styling `<h1>`, `<h2>`, and `<p>`:

```css
<style>
    h1 {
        font-family: 'Poppins', 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }

    p {
        font-family: 'Baloo Bhai 2', sans-serif;
        font-size: 20px; 
    }

    h2 {
        text-align: center;
        text-transform: uppercase;
        text-decoration: underline;
        text-decoration-color: blue;
        text-decoration-thickness: 7px;
    }

    .lorem {
        border: 2px solid red;
        width: 145px;
        word-break: break-all;
    }
</style>
```

- **Explanation:**
  - `<h1>`: Uses the 'Poppins' font and falls back to a series of sans-serif fonts. No specific styles are applied other than the font family.
  - `<p>`: Uses the 'Baloo Bhai 2' font and sets the font size to 20 pixels.
  - `<h2>`: Styled with center alignment, uppercase transformation, and an underlined decoration with a blue color and 7-pixel thickness.
  - `.lorem`: Applies styles to a paragraph with the class "lorem," including a red border, a width of 145 pixels, and the `word-break: break-all;` property.
