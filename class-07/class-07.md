# Class 07 Notes



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
