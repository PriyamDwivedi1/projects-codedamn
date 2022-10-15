In this step your goal is to set up the navbar, background image and link the `style.css` file with the `index.html` file.

Before jumping into the code of the project, make sure that you understand the basic structure of the HTML5 document and what the boilerplate code does:

-   `<!DOCTYPE html>` tag: Tells the browser that we are using HTML5 and not any previous versions of HTML.
-   `<html>` tag: Tells the browser that the content inside the `<html>` tag is, well, HTML!
-   `<head>` tag: Tells the browser that the content inside the `<head>` tag is metadata about the HTML document.
-   `<body>` tag: Tells the browser that the content inside the `<body>` tag is the content to be displayed on the browser page.
-   `<link>` tag: Tells the browser that we want to link an external file with the HTML document, and process it.

It is advised that you go though the [HTML & CSS Fundamentals course](https://codedamn.com/learn/html-css) for a comprehensive and detailed understanding of these tags.

## What will you do?

In this step you are tasked to create a new `style.css` file and link it with the existing `index.html` document.

1. Change the class name of <nav> tag from `navbar` to `home_navbar`. Give the `<nav>` tag an id called `nav-container`.

2. Create a file named style.css in same directory as index.html and link the `style.css` file with the `index.html` file. Add the following line of code inside the `<head>` tag of the `index.html` file, using the `<link>` tag.

    ```html
    <link rel="stylesheet" href="style.css" />
    ```

    Here the `rel` attribute specifies the relationship between the HTML document and the linked file. The `href` attribute specifies the path to the linked file.

3. Reset the CSS properties by setting `margin` and `padding` to `0`, and `box-sizing` to `border-box`, for all the elements of the HTML Document.

    ```css
    * {
    	margin: 0;
    	padding: 0;
    	box-sizing: border-box;
    }
    ```

    `margin`, `padding` and `box-sizing` are the CSS properties that are used to set the spacing between the elements of the HTML document.

    By settings these values globally to all the elements, it removes the different pre-defined margins and paddings of the elements (which are set by browsers), making it easier to style.

4. Set the `background-color` of the `body` element to `#000`.

    ```css
    body {
    	background-color: #000;
    }
    ```

5. Now, let's setup the background image of the website by adding a `background` tag in `style.css`
   the image is in assest folder.

   ```css
   background: url(/assests/`img-name.png`);
   ```

   It should cover the whole page as you saw in the image.

Now that we setup the navbar, background image and linked the `style.css` file with the `index.html` file, let's move on to the next step and create the website.
