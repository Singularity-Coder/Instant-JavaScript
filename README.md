![alt text](https://github.com/Singularity-Coder/Instant-JavaScript/blob/main/assets/banner_javascript.png)
# Instant JavaScript
List of popular JavaScript topics and their code snippets!

## demo.html
```HTML
<!DOCTYPE html>
<html>
    
    <head>
        <script>
            function myFunction2() {
                document.getElementById("demo").innerHTML = "Paragraph changed.";
            }
        </script>
        <script src="myScript.js"></script>
        <script src="myScript2.js"></script>
    </head>

<body>
<!-- Image View -->
<img id="myImage" src="my_image.png">

<h2>JavaScript</h2>

<!-- Text View -->
<p id="demo"></p>

<!-- Button -->
<button 
    type="button" 
    onclick="document.getElementById('demo').innerHTML = Date()">
        Show Date Time
</button>

<!-- New line -->
<br><br>

<button 
    type="button" 
    onclick="myFunction()">
        Change paragraph Text
</button>
</body>

</html>
```

------------------------------------------------------------------------------------------------------------------------

## Background
* HTML to define the content of web pages
* CSS to specify the layout of web pages
* JavaScript to program the behavior of web pages

## Internal Script
* In HTML, JavaScript is inserted in betweem <script> and </script> tags. It can be between <head> or <body> tags within a HTML doc.
```HTML
<script>
    document.getElementById("demo").innerHTML = "My First JavaScript";
</script>
```

## External Script

**Advantages**
* It separates HTML and code
* It makes HTML and JavaScript easier to read and maintain
* Cached JavaScript files can speed up page loads

**Link External Script**
* Without any path: If the script is in the same directory.
```HTML
<script src="myScript.js"></script>
```
* With a file path (like /js/): If the script is in different directory
```HTML
<script src="/js/myScript.js"></script>
```
* With a full URL (a full web address)
```HTML
<script src="https://www.w3schools.com/js/myScript.js"></script>
```

**Create a file called myScript.js and add the behavior as shown below**
```HTML
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
```
**Add the script as shown below in the HTML doc**
```HTML
<script src="myScript.js"></script>
```

## Output
* Writing into an HTML element, using innerHTML.
```HTML
<script>
    document.getElementById("demo").innerHTML = 5 + 6;
</script>
```
* Writing into the HTML output using document.write(). Use it for testing only.
```HTML
<body>
    <script>
        document.write(5 + 6);
    </script>
    <button 
        type="button" 
        onclick="document.write(5 + 6)">Try it
    </button>
</body>
```
* Writing into an alert box, using window.alert().
```HTML
<script>
    window.alert(5 + 6);
</script>
```
* Writing into the browser console, using console.log(). Press F12 -> Console -> Reload Page
```HTML
<script>
    console.log(5 + 6);
</script>
```
* Printing
```HTML
<body>
    <button 
        onclick="window.print()">
            Print this page
    </button>
</body>
```
## Comments

## Create Variables
```js script
var carName = "Ferrari";
```

## Create Functions
```js script
function myFunction() {
    // Do something  
}
```

## Find HTML element
```js script
document.getElementById("demo");
```

## Set or Change text on click of HTML element 
* Can use both double and single quotes for Strings
```js script
document.getElementById("demo").innerHTML = "Hello JavaScript";
document.getElementById('demo').innerHTML = 'Hello JavaScript';
```

## Change style of HTML elements
```js script
document.getElementById("demo").style.fontSize = "35px";
```

## Hide HTML elements on click of HTML element
```js script
document.getElementById("demo").style.display = "none";
```

## Show HTML elements on click of HTML element
```js script
document.getElementById("demo").style.display = "block";
```

## References
* https://www.w3schools.com/js/js_statements.asp












































