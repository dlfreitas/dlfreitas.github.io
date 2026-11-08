---
layout: post
title: Fender Stratocaster CAD Model
description: 
      Modeled the neck, fretboard, headstock, frets, and inlays in a 4-person team to create a full-scale CAD model of a Fender Stratocaster electric guitar using luthier multi-view drawings. Utilized lofting to form the tapered fretboard profile and fillets to create fretboard and neck radii. Produced upper-guitar subassembly, applying constraints to mate to body assembly for the complete model.


skills: 
  - SolidWorks
  

main-image: /images/Full-Fender-Stratocaster-Assembly.jpg
---

---
## Upper Guitar Construction
{% include image-gallery.html images="Assembly-Exploded-View-1.jpg" %}

## Luthier Drawings
{% include image-gallery.html images="Stratocaster-Guitar-Plan(1).jpg" height="800" %}
{% include image-gallery.html images="Stratocaster-Guitar-Plan(2).jpg" height="650" %}
This schematic provided (most) of the necessary dimensions used in this modeling project.

## Neck
{% include image-gallery.html images="Neck-1.jpg" height="550" %}
{% include image-gallery.html images="Neck-7.jpg" %}
I began by creating the profile of the neck and headstock forming the radial and tapering boundaries. The headstock was unique in that it did not have defined radii in the drawings, so the best solution was to construct it by approximating with the use of spline curves traced over an outline. I then cut extruded the back of the neck, roughing out the rear shape and creating the face of headstock. 
{% include image-gallery.html images="Neck-6.jpg, Neck-5.jpg" %}
For this step, I needed to create the rear neck without any callouts shown on the schematic. I created the rear neck curvature by filleting neck contours with a radius that reflects the modern design C-shape profiles.
{% include image-gallery.html images="Neck-2.jpg" height="600" %}
**Completed neck part**

## Fretboard
{% include image-gallery.html images="Fretboard-0.jpg, Fretboard-2.jpg" %}
Here, I needed to capture the curvature of the fretboard as well as the waning of the fret width. A loft was the best solution as it was able to create the 241.30 mm fretboard radius and linear taper in a single feature.
{% include image-gallery.html images="Fretboard-4.jpg" %}
{% include image-gallery.html images="Fretboard-3.jpg" height="600" %}
Next, I etched the slots for the frets, nut, and fret marker inlays using a cut extrude. This provided all the features for fretboard components in the assembly. I dimensioned the fret widths as shown on the luthier drawings.
{% include image-gallery.html images="Fretboard-1.jpg" height="600" %}
**Completed fretboard part**

## Frets & Inlays
{% include image-gallery.html images="Fretboard-Inlay-1.jpg" %}
Fret marker inlays were a very simple cylindrical extrusion. No troubles here.
{% include image-gallery.html images="Fretwire-1.jpg" %}
In guitar fabrication, frets are a subtractive manufacturing process, initially coming in a standard size and are then cut and filed down in place to the width of the fretboard at that point. I needed an efficient way to model the different lengths of each fret wire so they would mate flush to the fretboard for the given fret without modeling from scratch a dozen times. I began by choosing a fret near the center, and ensuring features were fully parametric so they would only require dimension changes to be transposed. This allowed me to easily produce 21 unique frets for the assembly. 

## Multiview Drawings
{% include image-gallery.html images="Stratocaster-Multiview-Drawings-1.jpg, Stratocaster-Multiview-Drawings-2.jpg, Stratocaster-Multiview-Drawings-3.jpg, Stratocaster-Multiview-Drawings-4.jpg" height="450" %}


<div style="display: flex; justify-content: center; margin: 2rem 0;">
  <iframe 
    width="315" 
    height="560" 
    src="https://www.youtube.com/embed/8CDMElWxREs" 
    title="YouTube Short" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen 
    style="border-radius: 12px; max-width: 100%;">
  </iframe>
</div>
