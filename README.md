# Technical skills test

This front end development test is intended to cover a broad range of skills required to deliver high quality government digital services. This includes:

1. Accessibility
2. HTML
3. CSS
4. jQuery and JavaScript
5. Other best practices

Candidates will pair with an existing Senior Front End Developer that will be able to help candates or clarify anything that is not clear.

## Accessibility

![alt text](https://github.com/gtvj/front-end-code-test/images/tab-panel.png "Tab panel")

1. Describe how you would implement this design, with a specific focus on not disadvantaging users of: 
    * Assistive technology
    * Older/less featured browsers

Your answer should describe both ***how and what*** specific features of HTML, CSS, ARIA and JavaScript.

[Maxiumum 5 marks]

## Best practices

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

* A DOM manipulation exercise using jQuery is provided in test-jquery.html. Please make the necessary changes to the code and submit your changes as a pull request to this repository. [Maxiumum 5 marks]

## CSS

* Given the HTML below, write a CSS3 rule that will give prepend the text ‘Tel:’ to the third list item. You are not able to amend the HTML to achieve this. [Maxiumum 3 marks]
```html
<body> 
  <ul>
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
## HTML

A test using HTML5 is provided in test-html.html within this repository.
Please amend the code and submit your changes as a pull request.
