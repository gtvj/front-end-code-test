# Technical skills test

This front end development test is intended to cover a broad range of skills required to deliver high quality government digital services. This includes:

1. Accessibility
2. HTML
3. CSS
4. jQuery and JavaScript
5. Other best practices

Candidates will pair with an existing Senior Front End Developer that will be able to help candates or clarify anything that is not clear.

## Accessibility

1. Describe how you would implement the ***'I am looking for...'*** tab panel that appears on [justice.gov.uk](https://www.justice.gov.uk) with a specific focus on not disadvantaging users of: 
    * Assistive technology
    * Older/less featured browsers

Your answer should describe both ***how*** you would do this and describe ***what*** specific features of HTML, ARIA, CSS and JavaScript you would use to achieve this.

2. How would you implement a version of [GOV.UK browse](https://www.gov.uk/browse/) for an MOJ Digital service. Your answer should:

* identify, so far as possible, what GOV.UK have done to ensure accessibility and progressive enhancement
* assume you're approaching this from scratch

## JavaScript and jQuery

1. A DOM manipulation exercise using jQuery is provided in test-jquery.html. Please make the necessary changes to the code and submit your changes as a pull request to this repository. 

2. You have been asked to perform client-side validation of an input allows users to proceed only if the value entered is in either of the following two formats (in the example '0' could be any digit and the dashes are required):
    * 00-00-0000
    * 0-000-0000
3. How would you make this work? 

```javascript
add(2, 5); // 7
add(2)(5); // 7
```


## CSS

* Given the HTML below, write a CSS3 rule that will give prepend the text ‘Tel:’ to the third list item. You are not able to amend the HTML to achieve this. 
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
production environment? 
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

## Testing 

1. ***What*** are the key things you need to test for on the front-end of digital services and ***how*** do you approach testing?


## Best practices

1. Is this good quality code? Provide a brief justification of your
   answer. 

```css
   <button
     type="button"
     onclick="document.getElementById('xyz').style.color='red';">
       Click Me
   </button>
```

2. Describe three ways to decrease page load time (answers may include perceived or actual load times) 

3. Why is it generally a good idea to position CSS ```<link>```s between ```<head></head>``` and JS ```<script>```s just before ```</body>```? Do you know any exceptions?
