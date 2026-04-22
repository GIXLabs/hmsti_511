# Overview
CNC milling is used to make parts directly (Apple's aluminum-bodied laptops) or indirectly (injection molds). The limitations of CNC milling show up in so many designs. Unlike 3D printers, when you use a CNC mill you will have to tell it how to move the cutting head around, which are called toolpaths. This activity will walk you through how to make a basic set of toolpaths that could be used on the CNC router at GIX.

# Learning Objectives
By the end of this activity you will be able to:
- Create your own toolpaths for the CNC router.
- Describe the limitations of CNC milling.

# Quiz Format
1. Open a new Hybrid design project in Fusion.
[Image showing Fusion loading screen with file choice](assets/toolpaths/hybrid.svg)
1. Model the desk organizer using a single sketch with multiple extrudes. Use the external dimensions in this engineering drawing to model the outer border. Add at least 3 pockets for things like pens, erasers, SD cards, etc.
- [Engineering drawing showing exterior dimensions of the desk organizer](assets/toolpaths/engineering_drawing.svg)
Here is an example of what your desk organizer might look like, but make yours fit your needs.
- [Example of a suitable desk organizer model](assets/toolpaths/organizer_example.svg)
1. Open the Manufacturing tab of Fusion
[Image showing where to find the Manufacturing tab on the Fusion ribbon](assets/toolpaths/manu_tab.svg)
1. Create your stock
The stock is the piece of material you're going to carve the desk organizer out of. Think of it as the piece of wood you buy from the store.
[Image showing where dimensions are put into the stock]()
1. Determine your axes.

1. Put your origin in the right place

1. Create 2D pocket toolpaths
1. Create 2D contour toolpaths
1. Simulate
    1. How long does it say it's going to take?
    1. Once the simulation has run, do the pockets have right angled corners? Why or why not?