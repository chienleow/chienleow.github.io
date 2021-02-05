---
layout: post
title:      "JS Project Most Important Tips"
date:       2021-02-05 12:23:04 -0500
permalink:  js_project_most_important_tips
---

![](https://media.makeameme.org/created/programming-is-10.jpg)

If you watched Ayana's JS project build series, you are probably familiar with the JavaScript Mantra. 
> "When some event happens, I want to make what kind of fetch and then manipulate the DOM in what way?"

I would like to share how I pseudocode my entire project based on this JS Mantra. What is "pseudocoding" you might ask? As Wikipedia puts it: 
> In computer science, pseudocode is a plain language description of the steps in an algorithm or another system. Pseudocode often uses structural conventions of a normal programming language, but is intended for human reading rather than machine reading.

I structured all my to do list sorely based on these 3 keywords, "Event", "Fetch" and "DOM".

**Feature 1:**
**- Event:** When user (enter their username and questions in a form)
**- Fetch:** I want to (post the data to the backend API) 
**- DOM:** and then manipulate the DOM by (showing user their username has been saved)

**Feature 2:**
**- Event:** When user (enter their 1st question in a form)
**- Fetch:** I want to (post the data to the backend API)
**- DOM:** and then manipulate the DOM by (showing user their question has been saved) and (append another form)

**Feature 3:**
**- Event:** When user (click on the "open a question" button)
**- Fetch:** I want to (get questions from the backend API - select random question) 
**- DOM**: and then manipulate the DOM by (appending the questions from backend API to the frontend HTML), so users can see the questions ONE at a time

**Feature 4:**
**- Event:** When (there is a question already on screen)
**- Fetch:** (No fetching)
**- DOM:** I want to manipulate the DOM by erasing the question on screen before the next question pops up

*As I am going through the program, I came to a realization that programming isn't JUST about writing code, it is about problem solving, it is about understanding the tools that you were given, rephrasing your problem, writing them out in pseudo code first, then eventually translating them from English to whatever programming language that you are working on. 
**Remember, always pseudo code first before diving right into writing code!***
