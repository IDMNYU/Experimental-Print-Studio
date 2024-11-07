# Plotter

[Overview](#Overview)

[SVG preparation](#SVG-preparation)





### Overview

(picture) 
 
IDM has two AxiDraw V3 machines

The AxiDraw V3 is a simple, modern, precise, and versatile pen plotter, capable of writing or drawing on almost any flat surface. 

---
### SVG preparation

You can control Axidraw through the Axidraw plugin in Inkscape. Inkscape can open and work with SVG files.

SVG, or Scalable Vector Graphics, is an XML-based format for creating two-dimensional vector graphics. You can create it in various ways, such as using coding frameworks like p5.js or design software like Adobe Illustrator.

For p5js:

Add this script to your index html page

```<script src="https://unpkg.com/p5.js-svg@1.5.1"></script>```


In addition, change your P5 cloud version to 1.6.0 instead of the default 1.10.0 or other versions as shown above. Otherwise you may encounter errors in exporting SVG with this script

Here’s an [example](https://zenozeng.github.io/p5.js-svg/examples/#exporting ) of the code you need to add to your js file in order to export.

### Pen and paper size

The machine supports a variety of pen types, including fountain pens, permanent markers.
Check out this github page from [awesome-plotters](https://github.com/beardicus/awesome-plotters?tab=readme-ov-file#pens)for more suggestions on pens.





---
