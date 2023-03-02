# CSS COLORS

## Colored Markers

**Learning Apply colors using the:**

- additive RGB (red, green, blue) model:
  where max value 255, min value 0 for example RGB (255, 127, 0)

- Hex colors #00FF00 :
  where each pair represent 0%(00) or 100%(FF) for example 00 -> 0% red, FF -> 100% green, 00 -> 0% blue and is the same as rgb(0, 255, 0)

- HSL color model (hue, saturation, lightness) :
  accepts 3 values: a number from 0 to 360 for hue,
  a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness.
  for example hsl(240, 100%, 50%)

  **Example Applying color in CSS:**

  .red { background-color: rgb(255, 0, 0); }
  .green { background-color: #007F00; }
  .blue { background-color: hsl(240, 100%, 50%) }

- linear-gradient() :
  This function allows us to generate an image with a color gradient with a specified direction and colors.
  linear-gradient(gradientDirection, color1, color2, ...);

  _nota: If no gradientDirection argument is provided to the linear-gradient function, it arranges colors from top to bottom, or along a 180 degree line, by default._

  for example:
  **linear-gradient using rgb**

  .red {
  background: linear-gradient(90deg, rgb(255, 0, 0), rgb(0, 255, 0),rgb(0,0, 255));
  }

  **linear-gradient using hsl**

  .blue {

            background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%),hsl(240, 56%, 42%));

        }

- RGBA(RED,GREEN,BLUE,ALFA) : The rgba function works just like the rgb function, but takes one more number from 0 to 1.0 for the alpha channeL.
  For example: background-color:rgba(255,255,255, 0.5); set white color with 50% opacity
