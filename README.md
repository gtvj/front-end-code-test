# Technical skills test

This front end development test is intended to cover a broad range of skills required to deliver high quality government digital services. This includes:

* Accessibility
* HTML
* CSS
* jQuery and JavaScript
* Other best practices

Candidates will pair with an existing Senior Front End Developer that will be able to help candates or clarify anything that is not clear.

## Accessibility

### Describe how you would implement the ***'I am looking for...'*** tab panel that appears on [justice.gov.uk](https://www.justice.gov.uk) with a specific focus on not disadvantaging users of:
 
* Assistive technology
* Older/less featured browsers

Your answer should describe both ***how*** you would do this and describe ***what*** specific features of HTML, ARIA, CSS and JavaScript you would use to achieve this.

### How would you implement a version of [GOV.UK browse](https://www.gov.uk/browse/) for a new digital service. Your answer should:

* identify, so far as possible, what GOV.UK have done to ensure accessibility and progressive enhancement
* assume you're approaching this from scratch

## JavaScript and jQuery

### DOM manipulation 

An exercise using jQuery is provided in test-jquery.html. 

### How would you perform client-side validation of an input that allows users to proceed only if the value entered is in either of the following two formats (in the example '0' could be any digit and the dashes should be retained if entered by the user):
* 0000-0000
* 0-000-0000
    
### How would you make this work? 

```javascript
add(2, 5); // 7
add(2)(5); // 7
```

### The code below relies on closures. Describe closures and their benefits. 

```javascript 
function sandwichMaker(magicIngredient) {
    function make(filling) {
        return magicIngredient + " and " + filling;
    }
    return make;
}
var hamAnd = sandwichMaker("ham");
hamAnd("cheese");        // "ham and cheese"
hamAnd("mustard");       // "ham and mustard"
var turkeyAnd = sandwichMaker("turkey");
turkeyAnd("Swiss");      // "turkey and Swiss"
turkeyAnd("Provolone");  // "turkey and Provolone"
```

### If you saw this in a Pull Request, what would your advice be:

```javascript 
Array.prototype.split = function(i) { // Adds split to all arrays
    return [this.slice(0, i), this.slice(i)];
};
```

### Write a ```log()``` function which acts as a proxy for ```console.log()```. This function should accept any number of arguments and prepend the text 'Logging: ' to any logged message.

```javascript
log('Hello'); // 'Logging: Hello'
log('Hello', 'again'); // 'Logging: Hello' 'Logging: again'

```

## CSS

### What colour would each of the following elements be (Assume each pair of rules are targeting the same element)
```css
h1 {color: red;}
body h1 {color: green;}

h2.grape {color: purple;}
h2 {color: silver;}

html > body table tr[id="totals"] td ul > li {color: maroon;} // li has an id of answer
li#answer {color: navy;}
```


### Given the HTML below, write a CSS3 rule that will give prepend the text ‘Tel:’ to the third list item. You are not able to amend the HTML to achieve this. 
```html
<body> 
  <ul>
    <li>JavaScript</li>
    <li>HTML</li>
    <li>Ruby</li>
    <li>Python</li>
  </ul>
</body>
```
### What changes would you suggest to make these CSS rules ready for a production environment? 
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
### How would you style all links to 'gov.uk' domains differently to other links in an application?
## HTML

A test using HTML5 is provided in test-html.html within this repository.
Please amend the code and submit your changes as a pull request.

## Testing 

### What are **the key things you need to test for** on the front-end of digital services?
### How do you ***how*** approach testing the front end of applications?

## Best practices

### Is this good quality code? Provide a brief justification of your
   answer. 

```css
   <button
     type="button"
     onclick="document.getElementById('xyz').style.color='red';">
       Click Me
   </button>
```

### Describe three ways to decrease page load time (answers may include perceived or actual load times) 

### Why is it generally a good idea to position CSS ```<link>```s between ```<head></head>``` and JS ```<script>```s just before ```</body>```? Do you know any exceptions?
