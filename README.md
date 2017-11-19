# pattern_quant
A simple algorithm to find pattern in images

(this is the beginning of a project; bear with me)

Pattern can be simply defined as a collection of three or more similar items, actions, or ideas. From a previous project, I have been trying to imagine a simple way to summarize patterns in images. I hope to do so here.

I will attempt this project in several pieces.

from input:
• find the most represented colors in the image using Lab colorspace
  - determine relative variability of color in the image
  ___ color is only one aspect of detail; even black and white images can be layered and complex

• re-map the image as resampled colors (image relative local minima)
  - images with lots of detail (distinctive elements) are given fewer colors relative to total number
  ___ minimizes fuzziness in high detail images
  ___ think a of a mosaic using colors of higher contrast than alike
  ___ total count of pixels in each color
