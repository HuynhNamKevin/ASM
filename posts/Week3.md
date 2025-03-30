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

# Week 3b: Redundancy, Style & Refactorisation

**Lectuere**

**Homework**