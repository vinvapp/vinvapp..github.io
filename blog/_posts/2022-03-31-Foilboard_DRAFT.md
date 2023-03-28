---
layout: post
title:  "Building a Foil board"
date:   2022-03-17 12:00:00 +0100
categories: Blog
description: Share my progress on how I build my own foil board. # Add post description 
tags: [Builds, Germany, Foil]
img: 2022-foilboard/cover.jpg
#author_img: 2021-italy/cover_square.JPG # Add other picture to author box
author_img: 2022-foil_1/author.jpg # Foil picture
author: Vincent von Appen # Add name author (optional)
---

{% assign id_counter = 0 %}

## Disclosure: 
I'm not an expert on glassing, shaping, hydro-dynamics, woodworking and so forth. I'm just a engineering student with some intuition with enough motivation to build a foil board myself. 

Sadly the above workshop is not mine, but I have great friends with amazing basements!

---

This post is divided into different sections: 

1. [Planing](#Planing) 
2. [Wood](#Wood)
3. [Shaping](#Shaping) 
4. [Trackbox](#Track-box) 
5. [Glassing](#Glassing) 
6. [Finishing](#Finishing) 

---


## Planing 

Let's get into it!

Things I optimised for initially:
- Ease of building, e.g. 
  - save cuts by getting the foam in the height of the trackbox
  - make the board as big as one sheet of foam to save waste and cuts
- Costs 
  - Comparing prices and options, there is a variety of manufactures out there.
  - Evaluate time and costs, e.g. the leash plug was such a thing where it simply doesn't make sense to build it DIY. I could easily 3D print it, but it's not tested and might not provide the same stability. 
- Save waste
  - Only get the needed material and be thoughtful about the materials used

During the process I had to adapt to different circumstances, which made the process more complicated, involved more waste and made it more expensive. Since this is my first time planing a board and I'm still learning. I'm just sharing my thoughts so somebody else might perfect this process.


I started by thinking of a shape that maximises the surface area of a single sheet of foam and the wood plate I got ([Picture]({{site.baseurl}}/assets/img/2022-foilboard/raw-materials-1.jpg)). At my local hardware store there is always a section of left overs that are half the price, so I got a all plates for about 15€. 

{% assign id_counter = id_counter | plus:1 %}
{% include image-gallery-full.html folder="assets/img/2022-foilboard/deck" num=2 id=id_counter %}

Other than that, a local surf shop owner advised me to copy the profile of the board from a existing board [^1]. Long flat surfaces underneath the board lead to an increased suction to the water surface. I looked at different shaped and stringers online and went for the following shape. The cut out in the back houses the foil track box. The tail has a round shape, like many 2022 boards. 

[![Stringer](/assets/img/2022-foilboard/stringer.png){:style="display:block; margin-left:auto; margin-right:auto; width:60%"}](/assets/img/2022-foilboard/stringer.png)

In the beginning I also thought about adding some sheer [^2] to the deck of the board. At some point decided that the effort is not worth the potential outcome. Here is the technical drawing for the stringer: [link]({{site.baseurl}}/assets/pdf/2022-Foilboard/Stringer-7cm-Drawing_v2.pdf).


TODO
- Stenciles 
- Feedback from other people

## Wood

I added a solid wooden structure to deflect the forces of the foil through the board. Thus the board is very ridged, but a bit heavier. For my first board I wanted to make sure it would not break. I used papule wood, which is lighter compared to other types. 

{% assign id_counter = id_counter | plus:1 %}
{% include image-gallery-full.html folder="assets/img/2022-foilboard/wood/" num=3 id=id_counter %}

The following picture shows the complete which later will be in the foam.

[![Wood Structure](/assets/img/2022-foilboard/wood-base-structure.jpg){:style="display:block; margin-left:auto; margin-right:auto; width:60%"}](/assets/img/2022-foilboard/wood-base-structure.jpg)



## Shaping 

*"The best shaper is a sander"* - some guy on Youtube, doesn't really matter. For the shaping I started by glueing the plates together and adding a champer to the sides. After that I tried to create the nose and back curvature. 

{% assign id_counter = id_counter | plus:1 %}
{% include image-gallery-full.html folder="assets/img/2022-foilboard/shapeing-1/" num=3 id=id_counter %}

I improved tools and methods but in the end, some shape emerged. I used another sea-map-stencil for ensuring of the symmetry and adding some more 

{% assign id_counter = id_counter | plus:1 %}
{% include image-gallery-full.html folder="assets/img/2022-foilboard/shapeing-2/" num=5 id=id_counter %}

The foam around the track box was mostly flat, thus I removed some more material and carved the following shape. 

[![Tail shape](/assets/img/2022-foilboard/tail-shape.jpg){:style="display:block; margin-left:auto; margin-right:auto; width:60%"}](/assets/img/2022-foilboard/tail-shape.jpg)


TODO

- Add best practices
- Sanding
- filler 
- 

### Saving weight 

Due to the extremely high weight of the board I had some doubts to continue. But I came up with a solution to the problem, that involved my friends router again. I prepared a another stencil to cut out some of the internal area and only leave a structure. We cut out the stencil in NDF and used a copy-ring to mill out the desired shape. This worked flawlessly.

{% assign id_counter = id_counter | plus:1 %}
{% include image-gallery-full.html folder="assets/img/2022-foilboard/reducing-weight-2/" num=4 id=id_counter %}

Of course, the empty spots need to be filled with foam again, but this was fast and easy.

[![Filled structure](/assets/img/2022-foilboard/glueing-filled-corners.jpg){:style="display:block; margin-left:auto; margin-right:auto; width:60%"}](/assets/img/2022-foilboard/glueing-filled-corners.jpg)

This step was very kind of unnecessary, since it was a problem, that is self made during earlier planning. I would recommend everyone who want's to build their own board, to use a very thin or no deck plate at all. Alternatively, only the relevant spots can be reinforced by wood, but I think it should work without as well.  
However, I think the board looks awesome like this and I really hope to incorporate this in to the final design later!

## Track-box 

The Track box is made out of two 15mm papule wood. I designed and printed a stencil so I could go to a friend with a router and cut out the precise shape. The US finbox tracks I ordered on amazon. [Here]({{site.baseurl}}/assets/img/2022-foilboard/printed.jpg) is another picture of the printed stencil. 

{% assign id_counter = id_counter | plus:1 %}
{% include image-gallery-full.html folder="assets/img/2022-foilboard/trackbox-stencile/" num=2 id=id_counter %}

The outer dimensions ended up a bit weird (195mm x 368 mm x 15mm), but the foil fits perfectly! Next step was to glue them in with epoxy, which is really straight forward. Make sure to do it in multiple turns, to the epoxy really sinks into those creeks. Here is a shot in between: [picture]({{site.baseurl}}/assets/img/2022-foilboard/trackbox-epoxy.jpg).

{% assign id_counter = id_counter | plus:1 %}
{% include image-gallery-full.html folder="assets/img/2022-foilboard/trackbox-stencile-2/" num=2  id=id_counter %}


## Glassing 

tbd...

## Finishing 




[^1]: Just a quick side note: when researching I really fell in love with with the [rubix](https://www.freedomfoilboards.com/rubix/5637725237.p){:target="_blank"} board from freedom foil boards. Amazing shape! 
[^2]: sheer is a measure of longitudinal main deck curvature, in naval architecture