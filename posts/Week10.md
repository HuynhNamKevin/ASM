---
title: Week 10 
published_at: 2025-05-13
snippet: 10th post.
disable_html_sanitization: true
allow_math: true
---

# 10a: Mycelial Creativity 
For my AT3 project, inspired by Lauren McCarthy's The Changing Room, I'm designing a TouchDesigner patch with my friend that allows people to influence a live generative artwork remotely. To extend this idea further, i've brainstormed how I might incorporate the WebSockets API into this system - enabling real - time participation from users anywhere. 

WebSockets offer a way to maintain a persistent, real-time, bidirectional connection between a web client and a servere. I could use this to: 

> Host a simple webpage with sliders, buttons, or text inputs.

> Allow remote users to control parameters in my TouchDesigner patch.

> Reflect those inputs instantly in the visual output -- changing the mood or structure of the generative piece

For technical aspects, I'd need to understand: 

> How to setup a WebSocket server

> How to build a simple HTML+JS front--end for users to interact with 

> How to use TouchDesigner's WebSocket DAT to receive and map data in real time

> How to keep it secure, stable, and low-latency 

For anything else I need to do or learn:

> Learn how to host a server online

> Handle multiple users and possibly limit/control how each person influences the patch 

> Add visual feedback to help users feel connected 

> Design thoughful interaction logic
# 10b: Scripting Languages 