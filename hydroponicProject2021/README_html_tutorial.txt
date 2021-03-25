<!DOCTYPE html> // header everything is in lower case but doc type html is not case sensititve
<html> </html> // opening and closing tags


<html>            //define structures and building blocks of your web page
  <head>            //head element to give browser info about page
  <meta charset="UTF-8" // utf is the most used ASCII was the first //metas give us information about a webpage!
  <meta> name="viewport" content="width=device-width, initial-scale=1.0"> // sets the display to the width of the device
  <meta name= "keywords" content="HTML, css"> // keywords when search engines look for your page
  <meta name="description" content = " ...."> //defining a descriptino for this page and will appear on google when it pops up.

     <title> Automated Hydroponic Project </title> //specifies the title info about the pages
     <style>  // css code we will write css rules between the tags
        img{  //image referenced one or more css rules
          width: 100 px; //declaration contains a property(width) and value(100px) use ; to add more then one css rule
          border-radius: 50 px; //half of the width we get a circle
          float: left; // pushes image to the left of our text
          margin-right: 10px; // adding some space after the image

        }
        p.Microcontroller{ //paragraghs referenced with this tag will be styled
          font-weight: bold; // we can remove the p. in front of the Microcontroller


        }
     </style>
  </head>
  <body>  //body elements that will apear on our page

    <img src= "    " alt = "  "> //html5 doesnt require closing tag Previous versions used the <img src= "   " alt = "  "/> a self closing tag

    <p> Automated Hydroponic Project was made possible by the American River College STEM Center Research and Innovation Mini Grant and is supported by Society of Hispanic Professional Engineers - American River College, and American River College Engineering Club. Here our basic setup will be accessed remotely, displaying all desired information such as temperature, humidity and and pump operation.
    </p>

    <p class = "Microcontroller" Microcontroller One - Tomato
    </p>




  </body>             //Body element end tag
 </html>    // Go over the url of the page. the IP address of the before : represents the local computer you are on. Then numbers after : are PORT NUMBER http requests sent through this port. forward slash name of file













WE CREATE A FOLDER FOR ALL OF OUR IMAGES, WE USE PATHS TO THIS FOLDER IN THE img src = " ". We type alternative text in the alt= " " for display when someone hovers over or when the image is not displayed
