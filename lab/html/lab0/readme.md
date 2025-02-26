# Lab 0: Your first HTML Page

Let's start by creating a simple HTML page. An HTML page has the following basic layout:

```html
<!DOCTYPE html>
<html>
    <head>
        <!-- head definitions go here -->
    </head>
    <body>
        <!-- the content goes here -->
    </body>
</html>
```
Let's start by creating a simple page that contains the phrase "Hello, World!" in the body. The page will also have a title - that thing that shows up in the title of the tab in your browser. The `<title>` element defines the title of the HTML page.

The `<!DOCTYPE html>` tag defines the document type that the browser is going to render. This is used for legacy reasons. If you want to get to the latest version of HTML (HTML5) then it's recommended to use this tag.

The `<p>` element defines a "paragraph", a block of text that has a small amount of spacing in between its top and bottom.

Notice how the tags have a start tag and an end tag denoted with a slash (`</p>`). Everything in between is the content of the tag. The content of a tag can usually have additional HTML tags within them.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Example</title>
    </head>
    <body>
        <p>This is an example of a simple HTML page with one paragraph.</p>
    </body>
</html>
```

You may also copy and paste this code into a new file in your text editor or IDE, and save the file as `index.html`. The `index.html` file is the default file that a web server will look for when accessing a website. After saving the file, you can double click it to open it with your browser.

Now that we know the basic structure of an HTML page, let's try it out.

## Exercise
1. Add an HTML `<title>` tag with the text "Hello, World!"
2. Add a paragraph (`<p>` tag) to the body with the text "Hello, World!"

You must place your file in the [submission](./submission) folder. Within the [submission](./submission) folder, create a folder called your `id github`. Name the file as `L0_Githubid.html`.
> Example: 
> /submission/cwenghowe/L0_cwenghowe.html

