# Aman singla

Google Summer of Code 2019

Organisation: [CircuitVerse](https://github.com/CircuitVerse)

Project: [Interactive-book](https://github.com/CircuitVerse/Interactive-Book)

[Interactive-Book-link](https://learn.circuitverse.org/)

Project developed during google summer of code with the objective of creating an online interactive guide for digital logic design.

## Outcome of Gsoc19 project
The primary goal which was to develop an open source book with quality content which teaches digital logic design is achieved. It enable's students to learn digital design by interacting with circuits,truth table and other interactive elements as they proceed through the book.The professors and students all over the world can read and contribute to the same.

<img width="400" src="https://user-images.githubusercontent.com/20012612/63544327-856c5d00-c514-11e9-9844-bb7012cf9737.png">


## Code Contribution
- [Code Repository of Interactive-book](https://github.com/CircuitVerse/Interactive-Book).
### A total of 130+ commits were made by me
- [Commits](https://github.com/CircuitVerse/Interactive-Book/commits?author=Amansingla97).

## Overview of Interactive book
The Interactive book have two components in it. 
1. Content
2. Interactions

![ib](https://user-images.githubusercontent.com/20012612/63456348-3a801600-c43e-11e9-8f5a-db19c98afcb1.png)


### Content
It include's quality content which would be gathered from various books (primarily from ‘​Digital Design​’ by ​Morris Mano as its copyright has expired and is in public domain) and online material. Basic notes have already been prepared to reference the aforementioned book and are attached in the table below.

### Interactions
There would be two types of Interactions.

1. **Circuit Interactions-** This include designing optimal circuits which would help to clearly understand the logic. The student would be able to clearly detect the variation of output with the change in input via these circuits. With each Interaction module, there would be a set of instructions that would guide the user to see the desired changes.

I have designed more than 20 *Circuit Interactions* which could be seen in the book.

2. **Module Specific Interactions-** This include interaction which are designed for individual module like kmap simulator , truth table generatoretc.

# Here are the module Specific Interactions I designed.

## *Binary*

It teaches how a binary number is converted to decimal and vice versa.
![ezgif com-video-to-gif](https://user-images.githubusercontent.com/20012612/63545325-a170fe00-c516-11e9-9d94-462d571e8421.gif)

---

## *Bitwise Operators*

It teaches how the Bitwise operator works.
![ezgif com-video-to-gif](https://user-images.githubusercontent.com/20012612/63545465-00367780-c517-11e9-8417-2a30150443d1.gif)

---

## *Interactive Logic Gates*

Designed two interactive usage of logic gates with a interactive design for user interaction.
![adsfafa](https://user-images.githubusercontent.com/20012612/63545561-3d9b0500-c517-11e9-8458-520b0d1aa2d8.gif)

---
I designed two basic application of digital logic design mentioned below.

## *Binary Flags*

It shows how the binary flags could bbe used in a practical way.
![adfadfa](https://user-images.githubusercontent.com/20012612/63545751-aa160400-c517-11e9-8ee1-5544c0f8dac8.gif)

---

## *Representing a Character*

It clearly shows how a digital screen could be generated and transmitted in binary no.
![adfadsfadf](https://user-images.githubusercontent.com/20012612/63545831-d893df00-c517-11e9-83be-6d09bcc303b2.gif)

---

## *Boolean Algebra*


![adrter](https://user-images.githubusercontent.com/20012612/63545904-ffeaac00-c517-11e9-847a-e3dd6b79b319.gif)

---

## *Truth Table Genrator Interaction*

It shows the application of boolean function.
![asdhgf](https://user-images.githubusercontent.com/20012612/63546007-3d4f3980-c518-11e9-90b9-b6d613b12ce5.gif)

---

## *Kmap interaction*

This is the most interesting Interaction of all and took me the longest time. With 2k+ js lines, It clearly shows how the k-maps are used in the digital logic. K-maps for variables upto 8 could be drawn from this interaction.
![kmap](https://user-images.githubusercontent.com/20012612/63546118-899a7980-c518-11e9-9471-1e4bdc9d48fc.gif)

---

## *Flip flop Interaction*

It shows how flip-flop could be used to generate a state table.
![flipflop](https://user-images.githubusercontent.com/20012612/63546298-03326780-c519-11e9-9cd4-6cc3901a0759.gif)

---

## *FSM Interaction*

A coin vending machine with it various corresponding states have been designed in this interaction.
![fsm](https://user-images.githubusercontent.com/20012612/63546307-09284880-c519-11e9-99e3-489d4c9f19c8.gif)

---
# Contribution(before getting selected)

<img width="400" src="https://user-images.githubusercontent.com/20012612/63544326-84d3c680-c514-11e9-81bf-298f16c19a2b.png">

## PRsinCircuitVerse
[#319](https://github.com/CircuitVerse/CircuitVerse/pull/319) Pgsearch(search on projects)
Previously we were using google custom search which doesn't do a very good job. This search would search over project names and descriptions.

[#297](https://github.com/CircuitVerse/CircuitVerse/pull/297) Sidekiq
I have dockerized sidekiq.
Also added the Sinatra gem which is needed for the Sidekiq web UI (the dashboard is shown below)

[#290](https://github.com/CircuitVerse/CircuitVerse/pull/290) Fix_Scroll
Added a scroll to combinational analysis (Tools->combinational analysis) when the number of inputs is high as earlier, the truth table was no longer viewable

[#265](https://github.com/CircuitVerse/CircuitVerse/pull/265) Empty_Project
Saving an empty project produced an error. When the circuit is empty, then data_url is data:,, it otherwise is data:image/jpeg;base64,<actual_data>

[#232](https://github.com/CircuitVerse/CircuitVerse/pull/232) Implement Subscriptions
Added the functionality of subscriptions to comments. This was done through gem Commontator. More to add I even changed the inbuilt functioning of the gem​.

[#247](https://github.com/CircuitVerse/CircuitVerse/pull/247) Implement Voting and Mentions
Have implemented voting (likes and dislikes) on comments along with mentions in the comment.

[#239](https://github.com/CircuitVerse/CircuitVerse/pull/239) Drop Mysql support
Supporting two databases causes unnecessary hurdles in development. We decided to drop Mysql support and just use PostgreSQL in all environments

[#187](https://github.com/CircuitVerse/CircuitVerse/pull/187) Adding watermark to iframes
A watermark "Made with CircuitVerse" is displayed on iframes on clicking to which directs to a new page in the simulator.

[#298](https://github.com/CircuitVerse/CircuitVerse/pull/298) Watermark_clickable_fix
The clickable area was hidden under the simulation area. Setting the z-index solved the problem

[#303](https://github.com/CircuitVerse/CircuitVerse/pull/303) Watermark and tooltip overlap issue
Changed the position of tooltip from the bottom right to bottom left.

[#178](https://github.com/CircuitVerse/CircuitVerse/pull/178) Fixing Dropdown Position
Added a bootstrap class that fixes the positioning

[#164](https://github.com/CircuitVerse/CircuitVerse/pull/164) Css correction of alert in case of invalid login Css issues related to positioning were corrected.

[#351](https://github.com/CircuitVerse/CircuitVerse/pull/351) Issue raised to Implement Elastic Search
Provided a step by step guide + Resources to implement elastic search.
 
[#356](https://github.com/CircuitVerse/CircuitVerse/pull/356) Enable edit and delete for all the comments.
A quick fix in commontator.rb enabling the user to delete and edit their previous comments.

## PRsinCircuitVerseDocs
[#113](https://github.com/CircuitVerse/CircuitVerseDocs/pull/113) Added documentation for saving projects
Added documentation for saving the project both offline and online.
It also includes the importance and usage of tags in online saving.

[#114](https://github.com/CircuitVerse/CircuitVerseDocs/pull/114)Added documentation for forking projects
Added documentation for forking the project.
Tried to explain what is a fork and when do we use it w.r.t CircuitVerse.

[#115](https://github.com/CircuitVerse/CircuitVerseDocs/pull/115)Added documentation Collaborations
Explained what do we mean by collaborations in CircuitVerse Also, Explained how we can implement collaborations.

[#116](https://github.com/CircuitVerse/CircuitVerseDocs/pull/116)Typo+Grammar+Spaces in the entire repo
Went through the entire repo and found a ton of mistakes. Was able to detect 35+ mistakes.


### Additional links
[Mentor's post](https://www.linkedin.com/feed/update/urn:li:activity:6569084161158676480/)
