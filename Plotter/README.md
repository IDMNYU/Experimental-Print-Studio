# Plotter

[Overview](#Overview)

[SVG preparation](#SVG-preparation)





### Overview

(picture) 
 
IDM has two AxiDraw V3 machines

The AxiDraw V3 is a simple, modern, precise, and versatile pen plotter, capable of writing or drawing on almost any flat surface. 



---

### Software setup

* Download [Inkscape](https://inkscape.org/release/inkscape-1.3.2/)


* Install Inkscape [Extension](https://wiki.evilmadscientist.com/Axidraw_Software_Installation): After installing Inkscape, install the Axidraw extension. It will appear under the "Extensions" menu in Inkscape. You should see the AxiDraw Control option in the drop-down menu

<div align="center">
 <img src="extension.png" alt="extension" width="700" al/>
 </div>

* Select Axidraw Model
  
  in the AxiDraw Control Panel, select options - config - Axidraw Model as AxiDraw V2,V3, or SE/A4

---

### SVG preparation

You can control Axidraw through the Axidraw plugin in Inkscape. Inkscape can open and work with SVG files.

SVG, or Scalable Vector Graphics, is an XML-based format for creating two-dimensional vector graphics. You can create it in various ways, such as using coding frameworks like p5.js or design software like Adobe Illustrator.

**For p5js:**

Add this script to your index html page

```<script src="https://unpkg.com/p5.js-svg@1.5.1"></script>```


In addition, change your P5 cloud version to 1.6.0 instead of the default 1.10.0 or other versions as shown above. Otherwise you may encounter errors in exporting SVG with this script

Here’s an [example](https://zenozeng.github.io/p5.js-svg/examples/#exporting ) of the code you need to add to your js file in order to export.

---

### Pen and paper size

The machine supports a variety of pen types, including fountain pens, permanent markers.
Check out this github page from [awesome-plotters](https://github.com/beardicus/awesome-plotters?tab=readme-ov-file#pens)for more suggestions on pens.

Maximum Drawing Area：The XY travel (printable area) of the AxiDraw is just over US letter (8 1/2 × 11") and A4 (297 × 210 mm / 8.27 × 11.69 inches) paper sizes. To avoid grinding the motors in the machine, ensure you leave a ½ inch of bleed around the edge of your plot. This means your plot should be 7 1/2 x 10 inches in size.



---
