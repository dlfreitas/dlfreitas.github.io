---
layout: post
title: Ibanez TS9 Baseplate
description:  
        Developed a guitar pedal baseplate, optimizing fit and durability through testing and customer feedback, for secure pedalboard mounting. Improved mounting strength and stability by adding supporting material around screw contacts, a tensile latching hook, and alignment features.

skills: 
  - FDM 3D Printing
  - SolidWorks
  - Bambu Slicer

main-image: /images/Ibanez-Cover-IMG.jpg
---

---
{% include image-gallery.html images="" %}

## Background
{% include image-gallery.html images="Etsy-Ibanez-(1).jpg, Etsy-Review.jpg" height="450" %}
This project was inspired by an Etsy listing of an existing Ibanez TS9 backplate. I considered the sellers design but it showed flaws that made it incredibly weak to pulling forces. Reviews highlighted  My mission was to improve the feature strength so it could be taken on and off the pedalboard repeatedly without plastically deforming and failing. This guitar pedal was unique in that it only had 2 backplate screws located on the top corners. My biggest challenge was designing a backplate 

## Feature 1 - Screw Tabs
After measuring the pedal chassis and creating the base geometry, I began by improving the screw contact tabs first. My goal was to improve tab strength without compromising the thread engagement. My first attempt simply increased the thickness of the feature, however, in testing, the tabs plastically deformed around the screw head after pulling the pedal off. My best next move was to determine the thickest tab spacing that maintained a strong thread engagement. To test values, I printed O-ring spacers of heights ranging from 0.8 mm - 2 mm in 0.4 mm increments to match my layer height. I determined 1.6 mm was the thickest spacer that allowed for solid thread engagement. In this iteration, I was able to create a tab that did not deform to the screw head after several removals. 
Ibanez-2.5.jpg
I noticed that the floating tab would behave as a cantilever and was now susceptible to torque. I needed supporting material to wrap around the tab. I added wall supports that connected the tab to the 
## Feature 2 - Latching Hook
My next feature needed to address the lower segment of the baseplate. Without any other tapped holes, I could not reutilize the north end tab feature and the 2 screws alone were not enough to secure the backplate. By removing the 9V battery cover, it gave me access to a cavity with features I could utilize. I noticed a lip on the bottom side and began designing a complementary hook. I created 3 separate sketches to behave as parameters I can change to tune the fit. The *Hook Base* defined the inward clearance from the chassis perimeter, the *Hook Latch* defined the depth the latch would engage at, and the *Hook Spacer* defined the clearance between the hook and the chassis lip. Through a couple iterations, I tuned the fit of hook to pivot and then catch, making it so the plate can only insert or withdraw when at a 45° angle relative to the lip. This added an extra layer of security so the plate could not accidentally come off under normal use.
## Feature 3 - Alignment Features
To ensure the lower section resisted all forces, I had to create a feature that opposed forces in the lateral direction. I added a symmetrical alignment feature that fit to the inner chassis wall which aided in alignment when inserting and prevented twisting. This finalized my first revision of the design.






