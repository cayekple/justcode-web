# HTML 5 Tags Definition and Usage
All HTML documents must start with a ``<!DOCTYPE>`` declaration.

In HTML 5, the declaration is simplified.
```
<!DOCTYPE html>
```

## html

The ``<html>`` tag is the root of an HTML document.
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document Title</title>
  </head>
  <body>

    <h1>Heading One</h1>
    <p>This is a paragraph.</p>

  </body>
</html>
```

## head

The ``<head>`` element is a container for metadata about the website.

## title

The ``<title>`` tag defines the title of the HTML document. The title must be text-only, and it is shown in the web browser's title.

The ``<title>`` tag is required in HTML documents.

## body

The ``<body>`` tag defines the document's body.

## header

The ``<header>`` element represents a container for introductory content or a set of navigational links.

A ``<header>`` element typically contains:

- one or more heading elements (``<h1> - <h6>``)
- logo or icon
- authorship information

```
<article>
  <header>
    <h1>Article Title</h1>
    <p>Posted by Jane Doe</p>
    <p>Other information</p>
  </header>
  <p>Lorem Ipsum dolor set amet....</p>
</article>
```
## main

The ``<main>`` tag specifies the main content of a document.

The content inside the ``<main>`` element should be unique to the document. It should not contain any content that is repeated across documents such as sidebars, navigation links, copyright information, site logos, and search forms.

```
<main>
  <h1>Most Popular Browsers</h1>
  <p>Chrome, Firefox, and Edge are the most used browsers today.</p>

  <article>
    <h2>Google Chrome</h2>
    <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
  </article>

  <article>
    <h2>Mozilla Firefox</h2>
    <p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
  </article>

  <article>
    <h2>Microsoft Edge</h2>
    <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
  </article>
</main>
```

## footer

The ``<footer>`` tag defines a footer for a document or section.

A ``<footer>`` element typically contains:

- authorship information
- copyright information
- contact information
- sitemap
- back to top links
- related documents

You can have several ``<footer>`` elements in one document.
```
<footer>
  <p>Author: Example References</p>
  <p><a href="mailto:example@example.com">example@example.com</a></p>
</footer>
```
### html cheatsheet
![cheatsheet](res/html-cheatsheet.jpg)