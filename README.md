# pattern_quant
A simple algorithm to find pattern in images

(this is the beginning of a project; bear with me)

Pattern can be simply defined as a collection of three or more similar items, actions, or ideas. From a previous project, I have been trying to imagine a simple way to summarize patterns in images. I hope to do so here.

I will attempt this project in several pieces.

from input:
• find the most represented colors in the image using Lab colorspace
  - determine relative variability of color in the input
  ___ color is only one aspect of detail; even black and white images can be layered and complex

to output:
• re-map the image as resampled colors (image relative local minima)
  - images with lots of detail (distinctive elements) are given fewer colors relative to total number represented
  ___ minimizes fuzziness in high detail inputs, highlights fuzz in low detail inputs
  ___ think a of a mosaic using colors of higher contrast than alike

determine texture:
• quantify input texture (noise)
  - determine color to texture relationships
  ____ determine possible patterns (three or more similar elements)
