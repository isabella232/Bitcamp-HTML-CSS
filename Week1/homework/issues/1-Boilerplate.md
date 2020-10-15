## Boilerplate

The first thing we will do is build ourselves an HTML boilerplate to start off our project. This code will
serve as the starting point in every HTML project you will make.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>

  </body>
</html>
```

With that basic template in place, let’s now examine some of the significant parts of the markup

First, we have the Document Type Declaration, `<!DOCTYPE html>`. This is simply a way to tell the browser — or any other parser — what type of document it’s looking at. In the case of HTML files, it means the specific version and flavor of HTML.

Next up in any HTML document is the `<html>` element. This tag basically indicates everything between the
opening tag `<html>` and closing tag `</html>` will be HTML code. In our example, we’ve included the lang attribute with a value of en, which specifies that the document is in English.

Inside the html tags we have two elements. First, we have the `<head>` that holds information about the webpage
and it tells the browser how it should handle the page. Inside our head we have the `<meta charset="utf-8">` which indicates the character encoding that we use in our documents. In nearly all cases, utf-8 is the value you’ll be using in your documents. And we also have the `<title></title>` between which you can enter the title
of your webpage.

And the second element we have in our HTML is `<body>`. All the content of our webpage will be inside the body
section.

In HTML, spacing doesn't really matter. We've added some tabs to make the code easier to see, but the web browser will ignore the extra spacing. Now that you understand the building blocks of HTML, let's add HTML to the `index.html` file in your project.
