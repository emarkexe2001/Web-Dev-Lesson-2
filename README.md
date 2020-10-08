# Web-Dev-Lesson-2
Bootstrap + Html Elements

# Homework Review

Review of last week's homework - create a simple web page using html, css and javascript.

# Bootstrap 

What is Bootstrap?

Bootstrap is a CSS framework used to create responsive and mobile-first websites.

Latest version of Bootstrap is Bootstrap 4.

Requires a containing element to wrap site contents.

Two container classes we can use to do that

.container 

```html
        <div class="container">
            <h2>Testing One Two</h2>
        </div>
```

.container-fluid
```html
     <div class="container-fluid">
            <h2>Testing One Two</h2>
        </div>
```

# Setting up Bootstrap 

Bootstrap tutorial on getting started with Bootstrap 4: https://www.w3schools.com/bootstrap4/bootstrap_get_started.asp

We need a few things to set up our HTML code to use Bootstrap 

# Div and div classes

What is a div tag?

div is a tag that we use to define a section / division in HTML

Acts as a container for html elements to be styled in CSS and manupulated in JavaScript

Styled using class or id tags.

class tag is used to point to css elements.

Example of a class tag 

```html
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
</style>
</head>
<body>

<div class="city">
  <h2>London</h2>
  <p>London is the capital of England.</p>
</div>

<div class="city">
  <h2>Paris</h2>
  <p>Paris is the capital of France.</p>
</div>

<div class="city">
  <h2>Tokyo</h2>
  <p>Tokyo is the capital of Japan.</p>
</div>

</body>
</html>
```
    
# Line breaks in html 

A line break is a seperation of text through the creation of a new line, we can use this to format text such as address lines to create a single text with a text on each new line.

We can accomplish this through the use of two different HTML tags

Break tag - Seperates the line where the tag is used - has no ending tags.

Pre tag - Keeps the formatting for the text exactly the same including line breaks and spaces.

# Break Tag (br) Example

```html
<html>
    <title>Welcome to Web Development Lesson 2</title>
    <body>
        <p>This<br>is<br>a<br>Line<br>Break<br>
    </body>
</html>
```

# Pre Tag (pre) Example

```html
<html>
    <title>Welcome to Web Development Lesson 2</title>
    <body>
        <pre>This is the pre tag              ,
             any information displayed in this tage
             preserves spaces and line breaks.
        </pre>
    </body>
</html>
```

# Example of Bootstrap code

```html
<!DOCTYPE html>
<html lang=en>
    <head>
        <title>Bootstrap 4 Lesson</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    </head>
    
    <body>
        <div class="container">
            <h1>Welcome to Bootstrap</h1>
            <p>This is some Bootstrap code</p>
        </div>
    </body>
</html>
```


