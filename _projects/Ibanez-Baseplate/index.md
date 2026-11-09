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
{% include image-gallery.html images="Etsy-Ibanez-(1).jpg" %}
{% include image-gallery.html images="Etsy-Review.jpg" %}
This project was inspired by an Etsy listing of an existing Ibanez TS9 backplate. I considered the sellers design but it showed flaws that made it incredibly weak to pulling forces. My mission was to improve the feature strength so it could be taken on and off the pedalboard repeatedly without plastically deforming and failing. My biggest challenge was designing 

## Feature 1 - Screw Tabs
After creating the flat base geometry from the chassis measurements, I began by improving the screw contact tabs first. My goal was to improve tab strength without compromising the thread engagement. My first attempt simply increased the thickness of the feature. However, in testing, the tabs still plastically deformed around the screw head after removing the pedal from the board. My best next move was to determine how much, so I tested  My second attempt, I was able to add  as much as the threads would allow. 
Ibanez-2.5.jpg
Now, I realized that the floating tab would act like a cantilever under load and I needed to support the I needed to I added wall supports that connected the tab to the 
## Feature 2 - Latching Hook
I created 3 different sketches that made the hook to behave as parameters I can tune to find the optimal fit. The *Hook Base* defined the clearance from the initial chassis lip I intended to latch onto, the *Hook Spacer* defined the 
## Feature 3 - Alignment Features
To ensure the backplate also resists forces in the lateral direction, I added a symmetrical alignment feature toward the bottom where the screws cannot resist.

## Embedding images 
### External images
{% include image-gallery.html images="https://live.staticflickr.com/65535/52821641477_d397e56bc4_k.jpg, https://live.staticflickr.com/65535/52822650673_f074b20d90_k.jpg" height="400"%}
<span style="font-size: 10px">"Starship Test Flight Mission" from https://www.flickr.com/photos/spacex/52821641477/</span>  
You can put in multiple entries. All images will be at a fixed height in the same row. With smaller window, they will switch to columns.  

### Embeed images


## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. <br>
*Example* : https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="MhVw-MHGv4s" autoplay= "false"%}
{% include youtube-video.html id="XGC31lmdS6s" autoplay = "true" %}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 pixels x 315 pixels.  

The width of the video below. Regardless of initial width, all the videos is responsive and will fit within the smaller screen.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "900px" %}  

<br>

## Adding a hozontal line
---

## Starting a new line
leave two spaces "  " at the end or enter <br>

## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header


