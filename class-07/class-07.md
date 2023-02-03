# Class 07 Notes

***
### Contains:

* **prompts.html** - Uses HTML and JavaScript to prompt the user for name, age, and location, and it will output different things based on the input.
* **colorpromptdemo.html** - Using HTML and JS, the user can enter a hexadecimal value - the background will be set to that color, and the text on the page to the inverse (negated hexadecimal values).
* **colorpromptdemov2.html** - The same as the above, but with improved code, using regex for string verification, and more demonstration of CSS styling.

***

> An **Event** is something that happens on a computer, whether it be human input or computer-driven.
> 
> An **Event Listener** is code that listens for a specific type of Event to occur, but doesn't react by itself.
> 
> An **Event Handler** is code that is executed when a specific type of Event occurs.

<br>

***

``` `rgb(${r}, ${g}, ${b})` ```
<br>

### Notes about CSS in an HTML header

        <head>
        <style>
        #name {
            <!--for id-->
        }

        .name {
            <!--for class-->
        }
        </style>
        <head>

<br>

### Code suggestion from V:
        function changecolor() {
        var hex = prompt("Enter a hex color code: ");
        console.log(hex.toLowerCase());
        document.getElementById("myMindGoesBlank").style.backgroundColor = `#${hex.toLowerCase()}`;
        
        }
