---
title: "Objectional programming"
category: Work
tags: development musings
---

It was at uni during my masters programme, when one of my classmates (who happened to be a middle-aged uni professor) stormed into the classroom early morning and blasted at another - rather young - student "have you gone berserk!? I pulled the changes since last night and nothing is working anymore", to which he replied "I thought it was better this way".

## Background
I had seen this situation before both at work, and in teams working on coding projects during my bachelors'. In another instance, another developer had swapped out the annotation-based configuration of Hibernate (an ORM for Java) with XML-based configuration. The entities were in different packages and it was hard to spot what classes really represented the database. I called it ODD for _Objection-driven Development_[^1], but over the years have come to favour the name _Objectional Programming_ because it often isn't _driven_ by anything and rather how individuals like to work (until told off, hopefully).

We can define **Objectional Programming** as follows:
> A style of programming practised by those who disagree with the work of (all) other developers by introducing coding practices vastly divergent - if not orthogonal - to the project's status quo, whilst claiming they know 'better'.

Examples include:
- Introducing a C++ component into a predominantly Javascript company
- Writing a new server-to-server api using gRPC when everything else uses REST over HTTP
- Adding a second ORM to the codebase for interacting with a subset of the application's tables

Behaviours observed in such individuals may be:
- Refactoring code to be "better" the night before they leave on holiday for two weeks
- Creating custom frameworks and bullying others into using their monstrous creation
- Writing new code using a (different) library without having discussed this re-architecting with the team

If engineers who practice objectional programming have a good rapport with their leadership, they are seen as _10x developers_, _rockstar developers_ (not the [language](https://codewithrockstar.com/), although that would be rather objectional!) or simply as _someone who 'just gets things done'_.

Whilst I'm being a bit satirical, such members can be seriously toxic to a team, bring down team morale, and create a future headache when they are a single-point of ~~knowledge~~ failure. Not to mention the techncial debt they introduce.

## What to do about it
Software is all about people - and often creative people - and we shouldn't discourage continuous change and improvement to a codebase that evolves mostly through stories from a backlog otherwise. So my advice is to always  have a conversation with the individual first, replay their behaviour and explain the (negative) impact they're having. Perhaps recommend that they channel their enthusiasm into work the team will benefit and learn from. That way it will still lead to praise for them as champions (they're often keen to be seen as great, so give them that opportunity) but under the conditions of a greater good.

If you're a tech lead or engineering manager, keep your ears open and watch out for these behaviours. They may help you hit a short-term milestone, but your experience should tell you that this is unsustainable and unacceptable when you pursue healthy, happy teams.

#### Footnotes
[^1]: My old colleague James Birnie created an [entire alphabet of *-driven-development](https://www.jamesbirnie.com/2018/05/driven-development.html) that is worth a read.