# Nina-Wiik-js-frameworks-ma-1-level-2
 
READ ME FILE

1. HTML
We are going to make a div with an id slider for the main container, and a container that 
holds all the pictures. We also need a div that contains the arrows and a pager. 

I have used bootstrap for this, and it can be added in the head. 

``` <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">```
You also have to link to your stylesheet in the head. 
In the footer, you need to include the JQuery Library. You add the code before the closing of the body tag. 
You have to add the JQuery, before you add your own script file. 

```<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>```

Please download the index file and assets, to follow this instuction. Its described inside the
files. 

STYLESHEET
We need to add some styles for the slider. Add the width and height so it is the same as the
pictures you are added. Mine pictures is 333x500px. Set the position to relative because 
we need to set slides to absolute. Then we will have them underneath each other, and have
a good fade transition. Add colors and fonts as you wish. All images are set to 100% 
so they will fit their container. 

JQUERY
First we declare all the variables. We then hides all the slides except the first one, and
we are adding an active css class, so it keeps track on which slide we are on. We then create
a function that will fade next and back. Then we create another function that starts the auto 
slideshow. We have to remember to reset the pause/timer between the slides. The last thing 
is to transition the slides when user clicks on next or back arrow, and call it the AutoPlay
function, so the slider autoplay starts is true. We wrap the whole slider into an function 
called MA1Slider, with an element, auto = false, and pause at 400. 