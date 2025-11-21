## requiredHtml
only the required html we need.

<!-- 
- This repo is not only for learning Html but also for exploring git and Github.
- I want to learn how multiple people can work on a single project, in this case a html web page .
- Also instead of conventional start , we will use cloning of this repo .
-->

## 101

- #### "DOCTYPE" Declaration
    ```html
    <!DOCTYPE html>
    ```
    - This declaration tells the web browser that the page is written in HTML5. It is a standard practice and ensures the browser renders the page correctly.  
    - This single line is the starting point for every modern web page.

- #### **root** Element
    - In this step, you will add the `<html>` element. This element is the root container for all other HTML elements on the page (except for the <!DOCTYPE> declaration).
    - It's also a best practice to include the lang attribute inside the opening `<html>` tag. This attribute specifies the language of the document's content, which helps search engines and screen readers. For English, we use lang="en".
    - In your index.html file, add the `<html>` and `</html>` tags right after the `<!DOCTYPE html>` declaration.

    ```html
    <!DOCTYPE html>
    <html lang="en"> </html>
    ```
    - All other elements of your webpage will go between these two tags.
- #### head

- #### body    
    -  In this step, you will add the `<body>` element. This is where all the visible content of your web page goes, such as headings, paragraphs, images, links, and more. The `<body>` element should be placed after the `<head>` element, but still inside the`<html>`element.

    - Let's add a main heading to our page to make it visible in the browser. We'll use the `<h1>` tag, which stands for "Heading 1".

    - In your index.html file, add a `<body>` section. Inside the `<body>`, add an `<h1>` element with the text "Hello, World!".

```html
    <!-- declaration -->
    <!DOCTYPE html>
    <!-- root -->
    <html>
        <!-- head -->
         <head></head>
        <!-- body -->
         <body></body>
    </html>
```