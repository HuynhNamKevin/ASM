---
title: Week 6 
published_at: 2025-03-08
snippet: 1st post.
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


# Week 6b: Shaders, Moire, & the Demoscene