# My_Web
html,css,

------------------------------------------------------------Day 1--------------------------------------------------------------------

# My_Web_Learning
just created to be familiar with git hub and upload my code which i am learning now


## learning css ##
 
    1).div tag : a container unit help to style a specific part.
    
    2).float tag :as far as i understand it is for positioning the div or any others..
    
          put in side styling portion
          
    3).position tag
            relative
            absolute
            fixed
     
    4). z-index === for giving priority to overlapping div
    5). opacity
            range b/w {1,0} can take any values b/w 1 and 2
            1 --> invisible
            0 --> fully visible
    6). margin tag (affect all the way around the div unlike position tag)
            relative
            absolute
            fixed
    7).padding tag (inside the div space "work inside")
            ** to get rid of default padding and margin by browser add inside style tag **
               
                    body {
                            margin='0';
                            padding='0';
                         }
    8). border tag
        syntax::  border thickness  color  type 
        eg        border 1px red solid;
        
        * border-  (  top  / right / bottom / left )
        * border-style  (  top  / right / bottom / left )
        * border-width  (  top  / right / bottom / left )
        * border-radius (to make edges curved)
    9). font
       font-family:
       font-weight:
       font-style:italic
       text-decoration:underline
       text-decoration:none
    10). link
    
    
 
    ----------------------------------------------------------------
                               Day 2
    --------------------------------------------------------------

CSS tags
---------
      1) ::before (psudo element) 
                 creates a pseudo-element that is the first child of the selected element. It is often used to add cosmetic content to an element with the content property

                 eg: <style>
                        p::before {
                        content: "Read this -";
                        }                       
                     </style>
                        
### ---> Meet the Units
                (a) em : The “em” is a scalable unit that is used in web document media. An em is equal to the current font-size, for instance, if the font-size of the document is 12pt, 1em is equal to 12pt.

                (b) Pixels (px):
                (C) Points (pt):
                (d) Percent (%):
