---
title: Week 3
published_at: 2025-03-22
snippet: 3rd post.
disable_html_sanitization: true
allow_math: true
---

# Week 3a: Images, Sound & Interaction

**Lecture** 

**Functions & Classes**

**Functions**

. are like recipes 

. **defining** a function = writing a recipe 

. **calling** a function = making the cake 

. side effects are when functions change things outside their scope:

    > quick and easy 

    > can get very messy 

. functions have inputs and outputs:
    > **arguments** = inputs

    > **return** = outputs 

**Objects**

 . have both date (**attributes**), and behaviour (**methods**)

 . help us organise our  code in an understandable way

 . can be defined one at a time via **object literal syntax:**

    > const sqr = {x : 150, y : 150, s : 100 }

 . attributes can be addresses from outside, ie: 

    > square (sqr.x, sqr.y, sqr.s)

 . attributes can be mutated from outside, ie:

    > sqr.x += 1

 . can be addressed & mutated from the inside via methods:
    
    > draw () { square (this.x, this.y, this.s)}

 . can be defined *en mass* via **Class definition**

 **Classess**

 . are like cookie cutters (objects are the cookies)

 . attributes are defined in the **constructor()** method

 . methods are defined in a similar style to the constructor

 . the this keyword is used to refer to attributes 

 . an *instance* of the class is created using the keyword new 

    > we call this instantiation 

    > ie. an object is instatiated

 . each instance has itw own set of attributes which can be reffered to with the **this** keyword

**Homework**

1. `[Box by Rafael Rozendaal](https://www.newrafael.com/box/)`

> Visually: 

    In Box, Rozendaal uses bold, blocky shapes and vibrant, saturated colors like bright pink,red,green. While the colors are striking, the simple of the visual design - just a moving looking box - contributes to the cuteness.

> Sonically:

    Box is a silent piece and doesn't include any audio. This maybe invite the viewer to imagegine the sound.

> Interactively: 

    The animation is click the mouse and it will appear random color, minimal but delightfuly responsive


# Week 3b: Redundancy, Style & Refactorisation

**Lectuere**

**Code style**

**Components of Clarity**

    > white space 

    > brevity

    > simplicity

    > comments 

**White Space (vertical)**

    > consistency

    > not too dense 

    > not to sparse 

    > functional chunks 

**White Space (horizontal)**

    > indentation, according to scope (or simila)

    > you can line things up if you want (non-compulsary)

**WET VS DRY**

    > Write Everything Twice vs Don't Repeat Yourself
    
    > How can you use:

        . variables 

        . functions

        . classes

        . arrays

        . etc 

    ... to make your code: 

        . simpler

        . less repetitive

        . ie. "elegant"

**Comments**

    > explain / discuss your code 

    > URLs to relevant sources 

    > introduction/epilogue

    > please respect indentation!!

**Homework**

1.Describe AT1 using the following concepts:

    > Variables: I use many variables to manage the state of the sketch:

        . track the background mood theme

        . Some arrays used to store and control multiple objects 

        . Color palettes for cute mood visuals

    > Functions: are used to separate logic into clean, resuable parts:

        . Draws flowers with petal colors and fading 

        . Choose background music based on mood 

        . Displays effects like rain, star, clouds, or sun based on mood 

        . Fading objects and background 

    > Iteration: "for" loops used to:

        . Create many raindrops, stars and clouds at the statr 

        . Display and fade flowers, trails, and leaves

        . Draw petals of flower and sun rays 

    > Boolean Logic: help to control animation behaviour smoothly and efficiently 

    > Arrays: store and manage collections of elements 

    > Classes: multiple custom classes for Flower, Trail, Raindrop, FallingLeaf, Star and Cloud to summary object behaviour

2.Rough draft of my AT1

    > How well did you achieve cuteness in the visual, sonic, and interactive domains? 

        . The pastel color, with rounded shapes, and animation of objects all contribute to a soft and playful atmosphere

        . Background ambient sound and a short sound when you press the mosue make a gentle soundscape

        . Clicking to plant flower, dragging to draw trail, and press key create simple action witout pressure

    > What communities and learning resources did I use? 

        . Learned from p5,js reference site, The Coding Train on Youtube, and look at some interactive example

    > What did I enjoy the most? What suprised me? 

        . I enjoy the different moods - espeacillay the starry night with the sound of owl 

        . The animation of falling leaf suprised me a lot, because it looks smooth and cute 

    > What did I struggle with or find confusing?

        . The *class* concepts takes me a lot of time to understand and adapt it to my AT1, at the first time I adapt it, it had many errors. 

        . Beside that, mistake at font type also make me struggle when I double chekced on my code