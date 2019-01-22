---
layout: post
title: "Hank Quinlan, Horrible Cop, Launches Site"
date: 2017-10-31
---


What's a Binary Search Tree? It's a fairly basic data structure probably taught early in a lot of DS courses--essentially, it takes a 
dictionary that has keys and values and represents it as a "tree" that allows you to search through the dictionary more efficiently. 
Besides the basic idea, it's got a number of properties which I won't go over right now.

In CS 60, my Principles of Computer Science class, our Professor first revealed these gems to us as a picture: a fairly tree-like 
structure, with circles containing numbers that cascaded down in various directions until they reached various ends, the leaves. 
After playing around with the visuals, we finally hit the Racket implementations. 

During today's execises, the professor noted that the main point of this part of the class was to learn about this data structure--writing 
code to formalize and manipulate this abstract entity was meant to help us better understand it. 

In "I Am A Strange Loop," Douglas Hofstadter writes of how humans tend to understand things. When I imagine what makes me eat something, 
I think of a combination my stomach responding to a scarcity of food, giving my brain and me a signal, that eventually results in me 
deciding on something to eat and consuming it. There are a lot of chemical and physical processes that underlie these seemingly simple
occurrences, but they just don't enter my (or likely, your) mind. The point is that we don't think of things on a microscopic level all 
the time, or even at all--rather, we abstract them to higher-level explanations and ideas that reflect the world as we see it, not the 
small, molecular happenings that escape the ability of the naked human eye, or mind, to perceive or imagine. 

Now what about Binary Search Trees? Today, we started off with an abstract entity. It makes sense that I would want to start learning 
about a Binary Search Tree by looking at a picture--while it might be "made up" of numerous lines of code, looking at those isn't going 
to do much for me in terms of understanding what the hell we're actually trying to do, what the structure looks like, and why it's 
called a tree (okay, maybe you could understand this from looking at code but you have to admit that a visual likely helps a lot). 
So we started with an abstract, high-level representation of a concept--that probably would make sense to most people. 

But, eventually, we have to get around to coding it. Just as we went from looking at pictures of Linked Lists to writing them as 
objects in Java, the same lower-level grounding will have to come about with linked lists. But why? Didn't Hofstadter say (and I agree) 
that humans tend to understand things at a high level? What's a bunch of esoteric syntax going to do for me? 

While code does operate at a "lower level" than pictures, there's a bit of a separation here. When I look at a computer program that 
implements a Binary Search Tree, the picture is the highest level of abstraction I'll deal with--no words, just pictures. I then 
might go down into pseudocode, and then into actual code. But that being said, there's a distinction between looking at the code 
implementing a Binary Search Tree and considering the most basic neurochemical processes that underlie how I make decisions. Think 
of it as a hierarchy of levels of abstraction--code is only the third from the top, but those basic processes lie at the very bottom. 
Who knows how much lies in between? 

In computing, what are these "basic processes" that underlie everything--how far do I have to go to reach the point where it's as if 
I'm looking at the interactions of particles on such a basic level that I'm not understanding anything that's going to have any 
reasonable chance of improving my understanding? Probably a lot farther than a few lines of Racket code (which you can probably 
understand, unless you don't know Racket in which case what's just a language barrier). In fact, one of the first things you'll 
learn in Computer Science is that below the lines of code we write, there's a compiler that understands what's going on. Eventually, 
if we go deep enough, the computer contains something called a "stack," that understands and moves between instructions that the 
computer executes. You can work with these low-level things deeply with Assembly (and interestingly enough, understand them)--you 
might implement a function that gives you a certain Fibonacci number, or solves the Towers of Hanoi problem. But does that help 
you actually understand the problems themselves better? Probably not--if you ever wrote these programs, you were probably thinking 
about questions like, "What line do I need to jump to?" or "Where should the stack pointer go now?" Furthermore, you probably 
weren't even coding in Assembly directly, but translating a program from another language (say, Python) to Assembly. 

So maybe we'll make Assembly the cutoff here. If I go even beyond that, looking at the very basic inner workings of my processor, 
what happens on things inside my computer when I run a program involving a Binary Search Tree probably doesn't tell my anything 
about the actual Binary Search Tree. Perhaps Hofstadter isn't discouraging us from attempting to work beyond the surface to deepen 
our understanding of things, but warning us against diving too deep. You don't need to go all the way to molecules to understand 
how you make the decision to eat food, but you can jump a few levels deeper than I did. Maybe it'll help you with your diet, or 
something.
