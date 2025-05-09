---
title: Week 6 
published_at: 2025-04-12
snippet: 6th post.
disable_html_sanitization: true
allow_math: true
---

# Week 6a: Signals & three.js(cont.)

**Part 1**

**q5.js:**

*What it's for:* A wrapper for p5.js that makes working with signals and envelopes easier. It's used for animation and responsive interactions in a more declarative way.

*Key feature:* Emphasizes signals and reactive programming - good for complex UI behaviors over time. 

*Different from others:* Built on p5.js, focused on reactive, temporal changes.

**c2.js:**

*What it's for:* A small functional reactive programming (FRP) library for JavaScript.

*Key feature:* Lets you build UI and behavior logic using reactive streams and computations.

*Different from others:* Lightweight and very functional, used more for building UI logic based on signals rather than graphics specifically.

**svg.js:**

*What it's for:* A lightweight JavaScript library for manipulating and animating SVG (Scalable Vector Graphics).

*Key feature:* Lets you create, move, transform, and animate SVG elements easily. 

*Different from others:* It's specialized for SVG graphics, unlike q5.js (which builds on p5) or c2.js(which is more logic-based).

**Part 2**

Some libraries like **svg.js** are avaialble as ES modules. Others like **q5.js** and **c2.js** may not be directly usable without bring bundled or adapted. That's where tools like **esm.sh** come in.

**esm.sh:**

It converts NPM packages to native ES module URLs you can import directly in the browser.

Useful when the library is not published as an ES module or you're working in a Deno environment or strict ES module setup

**Part 3**

let x;

function setup() {

    createCanvas(400,200);

    x = new q5.Signal(0);

    x.ease(300,1000);

}

function draw() {

    background (220);

    ellipse(x.value(), 100, 50, 50);

}

This demo uses **q5.js** to animate a signal from one value to another. It's a way to model 

**Part 4**

**1. Information & Thinking - Michel Serres:**

Talks about how information isn't just data - it changes how we think and interact with the world. He emphasizes the importance of signals and noise in communication and thought.

**2. What is it like to be a fungus? - Merlin Sheldrake**

A deep dive into the world of fungi, exploring how their behavior, communcation, and interactions blur boundaries between organisms, showing intelligence and connectivity in a non-human way.

**3. Xenofeminism: A Politics for Alienation - Laboria Cuboniks**

A feminist techno - political manifesto that argues for using technology and science to build a more inclusive and equal future - by embracing difference and rejecting biological determinism. 


# Week 6b: Shaders, Moire, & the Demoscene

**AT2: What is it like to be a fungus?**

*1. Fungi form networks that grow, split, fuse, and adapt*__ Represented through the dynamically connecting spores and recursive branching. 

*2. They change the world not by force, but through decomposition*__ Embodied in decay mode, where particles fade and shrink slowly.

*3. Their way of thinking is distributed, decentralized*__ Reflected by autonomous, self-moving spores and signals without a single control point. 

**Techniques Used:**

**Signals/ Envelopes:** Time - based pulsing via sine waves in the **draw()** loop simulate fungal communcation and drag interaction with spores mimics adaptive behavior in response to environmental touch.

**Recursion:** adds organic fractal growth reminiscent of fungal branching.

**Project Concept:** 

> connect dynamically through visual pulse (like mycelium)

> grow and fade (via trails and decay)

> emit mist-like particles (cloud)

> adapt to user 