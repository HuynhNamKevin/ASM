---
title: Week 1 
published_at: 2025-03-08
snippet: 1st post.
disable_html_sanitization: true
allow_math: true
---

# Week 1a: Intro to Creative Coding

**Lectuere**
 For the first class, I can not join at the first day becasue I was clashed with the other class. But when I allocated successfully, I checked on the Canvas so I can got clearly what studied on the first day of this class related to creating blog for write what we learned and homework task. Beside that, I got p5js as the main code language in this semester '[p5js](https://editor.p5js.org/)' and watch the Youtube playlist from "The Coding Train" '[The Coding Train](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)'. In addition, got how p5 work and how to write blog and push on github, which I didn't get clearly how it work.

**Homework**
1. <iframe id="grid homework" src="https://editor.p5js.org/huynhnamkevin123/full/XgmPtoPvV"></iframe>
<script type="module">

    const iframe  = document.getElementById (`grid homework`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16 

</script>

For this homework, I saw it just a horizontally loop, so I created a vertically loop to make a grid, that means we need one loop for columns and one loop for rows.
2. for the work by Rafael Rozendaal, I chose the work "Blocks" '[Blocks by Rafael Rozendaal](https://www.newrafael.com/blocks/)'

Describe: 

_ The screen is filled with colorful rectangular blocks.

_ Each block is a solid color.

_ When refresh the page, it will randomly show another color.

_ Same the layout but different colors.

List of concepts: 

_ **"rect()"** to draw rectangles 

_ **"fill()"** to apply colors for each blocks

_ **"random()"** to set random colors 

_ **"array"** to store the color of each block 

List of references:

_ '[fill](https://p5js.org/reference/p5/fill/)'

_ '[for](https://p5js.org/reference/p5/for/)'

_ '[random](https://p5js.org/reference/p5/random/)'

# Week 1b: What is Creative Coding?

**Lectuere**

_ Learn what is Creative Coding 

**Creative Coding** is the practice of writing code not primarily to build software or apps, but as a form of self- expression, art, or exploration. Tha goal isn't efficiecny or functionally, but rather creativity, experimentation, and often beauty or emotion

**Creative Coding is used in**

Digital art

Interactive installations

Generative visuals

Sound art or music 

Performances 

Experimental design 

_ Some p5js useful concepts 

**Comments**

> are for human readers of your code 

> comments are ignored by the computer 

> single line comments start with: // 

> multi line comments are bookended with: /* and */

> use comments explain what you are doing with each line of your code 

**Print & Log**

> this **print()** function prints information to the console 

> this can help us understand how things are working!

> very useful for troubleshooting bugs 

> **print()** is p5.js specific 

> **console.log** is built into "vanilla" javascript, and does exactly the same thing 

**framceCount & noLoop**

> **frameCount** is a convenience variable provided by p5.js

> the value of **frameCount** is equal to the number of times **draw()** has been called (plus one!)

> ... which is (almost) always equal to the frame number we are up to 

> so long as **draw()** is iterating, **frameCount** will continue to increase

> we can stop **draw()** fro iterating by calling **noLoop()**

> we can resume iterating **draw()** with **loop()**

**Template Literals**

> a **string** is a string of characters, like a word or a sentence 

> in javascript, you can write a string using **'single quotes'**, or **"double quotes"**, or **backticks**.

> using backsticks will let you convert the value of a variable into the middle of a string, using **${ ...}**

>**console.log (`frame: ${ frameCount }!`)** logs:

    frame: 1 on the first frame 

    frame: 2 on the second frame, etc

**Variables**

> variables need to be declared 

> pay attention to the scope you declare your variable in 

> var is the legacy way to declare variables 

> const and let is the modern way to declare variables 

> variables declared with:

    let can be reassigned

    const cannot be reassisgned

> can be used:

    to break complicated processes down into many simple steps 

    to visually organise long or messy code 

    to help troubleshoot bugs 

**Colour**

> **color()**, **fill()**, and **background()**

> default ways of dealing with colour

> HSB: Hue, Saturation, Brightness

> **lerpColor()**: lerps between two colours 

**Iteration**

> iteration is where a process is repeated many times while something changes 

> **frameCount** is an example of iteration 

> **while (...) {...}** loop

> **for (...) {...}** loop 

> you can iterate across an array with **.forEach (...) {...}**

**Arrays**

> are lists of things 

> looke like this: [ `thing_0`, `things_1`, `things_2`]

> can be assigned to a variable 

> we can retrieve elements from an array 

> note that the index of the firt element is 0 

**Random & Noise**

> **random()** returns a random between 0-1

> **random(6)** returns a random value between 0-6

> **random(9,11)** returns a random value between 9-11

> **noise()** is more complicated, but also more useful:

    fills a three dimensional space up with continuous values 

    moving through the noise space gives random, but continuous values 

    circling back to the same position brings you back to your initial value 
