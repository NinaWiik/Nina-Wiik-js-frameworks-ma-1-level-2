# Nina-Wiik-js-frameworks-ma-1-level-2
 
READ ME FILE

1. HTML
We are going to make a div with an id slider for the main container, and a container that 
holds all the pictures. We also need a div that contains the arrows and a pager. 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Module Assignment 1 - slider </title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <link href="./assets/css/styles.css" rel="stylesheet" type="text/css">
</head>
<body>
    <h1>Module Assignment 1 - Level 2 - Image slider</h1>
    <div id="slider">
        <div class="container">
            <div class="slide"><img src="./images/image (2).jpg" alt="Slider img 1" ></div>
            <div class="slide"><img src="./images/image (3).jpg" alt="Slider img 2" ></div>
            <div class="slide"><img src="./images/image (1).jpg" alt="Slider img 3" ></div>
        </div>

        <div class="arrows">
            <a class="back" href="#"><</a>
            <a class="next" href="#">></a>
        </div>
    
        <div class="pager">
            1 / 3
        </div>

    </div>
    
</body>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="./assets/js/script.js"></script>
</html>