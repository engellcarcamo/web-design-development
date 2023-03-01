# CSS COLORS

 ## Colored Markers

 **Learning Apply colors using the:**

 * additive RGB (red, green, blue) model:
   where max value 255, min value 0 for example RGB (255, 127, 0)

 * Hex colors #00FF00 :
   where each pair represent 0%(00) or 100%(FF) for example  00 -> 0% red, FF -> 100% green, 00 -> 0% blue and is the same as rgb(0, 255, 0)

 * HSL color model (hue, saturation, lightness) : 
    accepts 3 values: a number from 0 to 360 for hue, 
    a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness.
    for example hsl(240, 100%, 50%)

    **Example Applying color in CSS:**
     
     .red { background-color: rgb(255, 0, 0); }
     .green { background-color: #007F00; }
     .blue { background-color: hsl(240, 100%, 50%) }