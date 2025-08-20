# Overview
You will be repurposing the PCB (printed circuit board) from the mouse you analyzed last week in Assignment 1.1. To do this, you will use sheet materials to create a new enclosure for the PCB, allowing for one of the existing PCB buttons to be pressed. This button can be reprogrammed to trigger one of many shortcuts on your computer. You should have a use case in mind for your repurposed mouse and it shouldn't just be to act like a normal mouse in a new enclosure. For example, it could be meant to be a mute button pedal for Zoom meetings, a shuffle button for a playlist, or any other combination of input and application. Ideally, your design will enhance the use case you have in mind, rather than just being a button.

# Examples

Here is some work completed during a previous class. The project was slightly different, but the process is the same: 

Stacked construction with sewing thread to join layers, repurposed button using flexure:
thread.png

Rewired buttons, repurposed the scroll wheel, nice use of contrasting materials:
rewired_buttons.png

Excellent use of low-fidelity prototyping to get general shape and size using a discarded pen case and some folded paper:
low_fidelity.png

Creative method of creating 3D shapes using flat materials by folding, but remember to not just replicate a mouse's functionality.
folded.png

In this example laser cutter file, you can see the number of 2D layers required to make a precise, stacked, 3D form, in this case a wheel from a toy:
Example cut file

# Learning Objectives
- Create a functional electronics enclosure that is constrained by existing parts (PCB)
- Develop your modeling and prototyping skills using fast, low-cost materials and methods (e.g. hand-cut cardboard)
- Develop your sketching skills and refine your prototype design in 2D design tools

# Constraints
- Your design must fully enclose the PCB.
- Your design must use a stacked construction, no box joints.
- Your design may only use glue to fix the PCB, not to join the layers together.
- Your design must allow for the activation of at least one button.
- No 3D printing, only sheet materials allowed (wood, MDF, acrylic, cardboard).
- Your final prototype should include a decorative element like a label, pattern, drawing, or something else.
- Process PDF should be <10 mb.

# Deliverables
- Process PDF (Submit on Canvas)
    - Brief description of your concept (250 words max)
        - Will be used during critique.
    - Sketches - minimum 10, included in sketchbook and scanned into PDF
    - 3+ low fidelity prototypes (at least 1 by hand)
        - One must be made by hand to answer the question of what size and shape should your design take (can be cardboard, foam, tape, clay, or anything else you can shape easily and quickly without a computer).
        - One must quickly evaluate whether you have gotten the dimensions of the PCB correct. Please use the lasers for this.
        - One to evaluate press fit joint you'll use to connect the layers together. Please use the lasers for this.
    - 1+ medium fidelity lasercut prototype (final prototype)
    - Notes on what you learned in each prototype
    - Submitted on Canvas, must be under 10 mb in size
- Single SVG containing the files you cut on the lasers for your final prototype.
    - See References section for details on ways to do this using Fusion.
- In-Class Presentation - Graded in Participation as a separate grade.
    - Bring sketchbook
    - Bring all prototypes (low-fi and medium-fi)
    - Demonstrate during critiques

# References
First download and install the Shaper Origin Plugin for Fusion making sure to choose the appropriate operating system. Link here.Links to an external site.

Windows will tell you it is a sketchy piece of software, but it is safe to run. This plugin frequently breaks whenever Fusion is updated, but the developers update it quickly. You may need to reinstall a few times this quarter.

Once installed, open Fusion. Navigate to the Utilities tab (1), then select the Export to Origin icon (2), then check the Advanced box (3).

fusion_export.png

You will then have the option to export from many formats. You will likely end up using the Entire Sketch option for this, but play around with the options and see how they look. You may need to create new sketches and project (keyboard shortcut 'p') to get only the geometry you care about.

Once you have all of the parts exported into individual SVGs, you can join them all together using Inkscape by opening one and using File->Import to pull each of the other svgs in. Click and drag to arrange them.

# Optional Implementation
## Mac
Jeremy has created this guideLinks to an external site. for making your repurposed mouse button work on a Mac computer. It's really easy and should take you about 10 minutes. There are also some recommended functions that you might find useful as inspiration for your enclosure, even if you don't intend to follow these steps. We would welcome help from any expert students who can put together a similar guide but for a PC.

Even if you don't want to follow the steps for repurposing the mouse, you can reassemble all the original parts and use it as... a mouse! (very handy for CAD work). We want to discourage waste in this course, so if you don't need your mouse, you can return it to us or donate it.

## Windows
Windows doesn't distinguish between different mouses, so this is a little tougher to do. X-MouseLinks to an external site. has the ability to remap a mouse input to a key combination, and can be application specific, but not mouse specific. Just don't do what Kevin did, who foolishly unbound the left click, then had a terrible time trying to disable X-Mouse without having the ability to click.

# Frequently Asked Questions
- Can I count the sketches from the sketch assignment for the sketches required here?
    - Yes.
- Do my sketches have to match the final outcome?
    - No, but they should be related. Part of prototyping is learning from each iteration, so we expect your design to evolve as you progress through iterations. If you decide you don't like any of your ideas after some iterations, you should sketch out new ideas that you would like to try, then fabricate them. These would also be good things to put in your notes of each iteration in your process pdf.
- Does my device have to work during critiques?
    - No, getting the device to function is optional, but it should be theoretically possible. A button that just gives you free cash isn't feasible, but one that types in your password for you is.

# Rubric
| Points | Requirement |
| --- | --- |
| 1 | Description of concept |
| 3 | 10+ Hand sketches |
| 1 | Size and shape prototype (hand crafted) |
| 1 | PCB dimensions prototype (lasercut) |
| 1 | Press fit joint prototype (laser cut) |
| 2 | Medium fidelity finished prototype (laser cut) |
| 1.5 | Execution Quality |