sat
===

_Specify saturated (chroma) colors by hue and luminance (luma)._

Usage
-----

    sat(h = 0, l = 85, precision = 1)
    
|  Argument | Description      |
| --------: | :--------------- |
|         h | hue              |
|         l | luma             |
| precision | chroma increment |

Value
-----

A character array of colors (like "#000000").

Details
-------

Internally, `h` and `l` are `cbind`-ed, so the corrsponding recycling rules apply.

