# Technical skills test

This test contains a number of questions covering:

1. Web best practices
2. HTML
3. CSS
4. jQuery and JavaScript

Some of the questions will require candidates to download HTML files
containing demo code and to debug/improve this code. Having done so,
candidates are asked to submit their changes as a pull request to this
repository.

Candidates are asked to complete as many questions as possible in the
allocated time.

## Best practices

* How would you incorporate features of HTML5, CSS3 and JavaScript into
   a project in a way that does not disadvantage users of older/less
featured browsers [Maxiumum 5 marks]

* Is this good quality code? Provide a brief justification of your
   answer. [Maximum 3 marks]

```css
   <button
     type="button"
     onclick="document.getElementById('xyz').style.color='red';">
       Click Me
   </button>
```

* Describe three ways to decrease page load time (answers may include perceived or actual load times) [Maximum 3 marks]

## JavaScript and jQuery

* A DOM manipulation exercise using jQuery is provided in jquery.html. Please make the necessary changes to the code and submit your changes as a pull request to this repository. [Maxiumum 5 marks]

## CSS

* Given the HTML below, write a CSS3 rule that will give prepend the text ‘Tel:’ to the third list item. You are not able to amend the HTML to achieve this. [Maxiumum 3 marks]
```html
<body> <ul>
       <li>The National Archives</li>
       <li>Kew, Richmond, Surrey, TW9 4DU</li>
       <li>+44 (0) 20 8876 3444</li>
      <li><a href=”#”>nationalarchives.gov.uk</a></li>
     </ul>
</body>
```
* What changes would you suggest to make these CSS rules ready for a
production environment? [Maximum 3 marks]
```html
<!DOCTYPE html>
<html>
     <head>
     <meta charset=utf‐8 />
     <title>Test</title>
       <style type="text/css">
         #one { background‐color: #000; }
         .three { color: rgba(255,255,255,1); }
         div > span { border: 3px solid green; }
       </style>
     </head>
     <body>
       <div id="one">
         <div class="three">
           Hello <span>World!</span>
         </div>
       </div>
     </body>
</html>
```
HTML
