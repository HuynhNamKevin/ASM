---
title: Week 4
published_at: 2025-03-08
snippet: 4th post.
disable_html_sanitization: true
allow_math: true
---

# Week 4a: Canvas API, Recursion, & Effective Complexity

**Lecture**

**Anatomy of a Website**

*Document Object Model*

> hierarchical approach to document organisation 

> elements are nodes 

> each node has a parent 

> can also have children

> creates a tree-like structure

> by itself, does not specify exactly how the document should be formatted / rendered to the screen, etc

*CSS(Cascading Style Sheets)*

> provides the relevant information about how each node, or category of node, in the DOM, should be rendered to the screen

> style information can be given per a node's type, class, or ID 

> can be very fiddly and annoying 

> we don't need to use CSS at all

> we can provide this information using javascript!

*Doing CSS things in Javascript*

 . document.body.style.margin = 0 

 . document.body.style.overflow = 'hidden'

 *Why use JavaScript for everthing?*

 > Because we can!

 > To keep thing simple!

 > So we don't need to learn CSS!

 > We can use Javascript for EVERYTHING (nearly)

 *Most Minimal Working HTML File:*

 . <!DOCTYPE html>

 . <body>

    <script src=script.js></script>

   </body>

 *Minimal File Structure*

   . public (folder)

    . index.html

    . script.js

 *Serving HTML*

 > the html file is served (either locaaly, or by an  internet server)

 > the html file points the browser to the javascript file 

 > your javascript does the rest 

 **Javascript without p5**

 *Application Programming Interface (API)*

 > specifies how to plug one piece of software into another piece of software

 > DOM is an API

 > ways of extending functionality 

 > ways of dealing with specific situations / use cases 

 *Canvas API*

 > this is the API that p5 interfaces with 

 > different paradigm

 > not as friendly as p5 

 > clunkier and more verbose 

 > less data overhead (no library necessary)

 > faster (no intermediating functions, etc)

 *Web Audio API*

 > how the browser 

    . processes  sound 

    . connects to the operating system;s audio output device

 > requires a user gesture to become active 

    . no blasting unsuspecting visitors with loud noise 

 > audio graph paradigm

    . nodes are created and wired together

    . nodes are controlled via AudioParam attributes (objects)

 > we will look at working with: 
    
    . samples 

    . synths 

*Web Audio API: Samples*

 > loading a soundfire into an audio buffer

 > loading the audio buffer into an buffer source node 

 > connecting the buffer source node to the output device 

 > playing the buffer source node on a click event 

 > using the mouse position to change the playback rate of the sample 

 *Web Audio API: Synths*

 > instantiating an audio graph
    
    . nodes

    . connections

 > types of node: 

    . oscillators 

    . amplifiers

    . panning 

 > input: 

    . mouse / keyboard 

    . generative algorithm




