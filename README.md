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

- ### `<h>` tag
```html 
<h1>Continent</h1>
<h2>Country</h2>
<h3>State</h3>
<h4>City</h4>
<h5>Area</h5>
```

- ### `<p>` tag ~ paragraph tag
    - `<p>` tag is used to define a paragraph in HTML. Browsers automatically add some white space (a margin) before and after a paragraph.


 The `<strong>` tag is used to indicate that the text has strong importance, seriousness, or urgency. Browsers typically render the content inside a `<strong>` tag as bold.

 The <em> tag (short for "emphasis") is used for this purpose. It indicates that the enclosed text should be stressed or emphasized.

 The <br> tag inserts a single line break. It is an empty tag, which means it has no closing tag.

 ```
 In this lab, you practiced using:

<h1> to create a main heading.
<p> to structure content into paragraphs.
<strong> to give text strong importance (bold).
<em> to emphasize text (italic).
<br> to insert line breaks.
 ```

 ## lab3

<details>

```
<ul> tag and are used for items where the sequence is not important.

<ul> is just like a div , inside which which we have use multiple <li> tags


ccessfully:

Created an unordered list (<ul>) for items without a specific order.
Created an ordered list (<ol>) for items where sequence matters.
Used the list item tag (<li>) to add items to both types of lists.
Created a nested list to build a hierarchical structure.
Lists are a crucial tool for organizing content and improving the readability of your web pages

```

</details>

## lab3

<details>

```
Hyperlinks are the foundation of the World Wide Web, allowing users to navigate between pages and resources. In HTML, links are created using the <a> (anchor) tag.

he <a> tag, which stands for "anchor", is used to define a hyperlink. The most important attribute of the <a> element is href, which specifies the link's destination URL.

By default, links open in the same tab. To change this behavior, we use the target attribute.

Setting target="_blank" instructs the browser to open the linked document in a new tab or window. This is a common practice for external links, as it keeps the user on your website while allowing them to visit the external resource.

Create internal link with href to id anchor

Use title attribute for link tooltip




Use the <a> tag with the href attribute to create external links.
Use the target="_blank" attribute to open links in a new tab.
Create internal page anchors using href="#id" for navigation within a single page.
Use the id attribute to define the destination for an internal link.
Add informative tooltips to your links with the title attribute for a better user experience.
```

</details>


## lab4
<details>

```
The <img> tag is used to embed an image. It is an empty tag, which means it does not have a closing tag. The most important attribute of the <img> tag is src, which specifies the path to the image you want to display.


The alt attribute provides alternative text for an image. This text is displayed if the image cannot be loaded for some reason. More importantly, it is used by screen readers to describe the image to visually impaired users, making your website more accessible.

By default, a browser displays an image in its original dimensions. Specifying the width and height allows you to resize the image and helps the browser reserve the correct amount of space for it before it loads, preventing the page layout from shifting.

Wrap img in a tag for clickable image link


Embedding an image using the <img> tag.
Specifying the image source with the src attribute.
Providing alternative text for accessibility with the alt attribute.
Controlling image dimensions with the width and height attributes.
Adding a tooltip with the title attribute.
Making an image a clickable link by wrapping it in an <a> tag.


```


</details>


## lab5 

<details><summary>tables</summary>

```
HTML tables are used to display data in a structured, tabular format, consisting of rows and columns. This is essential for presenting information like product comparisons, financial reports, or schedules in a clear and organized way.

-  Every horizontal row in a table is defined by the <tr> tag, which stands for "table row". All content within a row, such as headers or data cells, must be placed inside a <tr> element.

- Header cells are created using the <th> tag, which stands for "table header". These tags are placed inside a <tr> element and typically render as bold, centered text, distinguishing them from regular data cells.


Use the <table> tag to create a table container.
Use the <tr> tag to define table rows.
Use the <th> tag to create header cells for columns.
Use the <td> tag to add data cells.
Add a border attribute to make the table structure visible.
```


</details>


## lab6

<details><summary>Forms</summary>

```
- HTML forms are a fundamental part of the web, allowing users to interact with websites by entering information. This can range from a simple search box to a complex registration page.

- label -->for
  input --> id 
  for and id must match 

- in case the input is quite big and lengthy, normal input tag ineffective
    - therfore use 'TEXTAREA'.
    

```

</details>