---
title: "Assignment 3: Convergent Design"
layout: doc
---


# Assignment 3: Convergent Design


## 1.  Pitch. 

<!-- Write a succinct (100 to 300 word) product pitch for your app, that gives it a name, describes its intended audience, the value that it brings, and some of its key functionality. Feel free to build on what you wrote in the previous assignment, and to draw on the insights you gleaned from your interviews and introspection. Describe the functionality in terms of the central concepts. We recommend drafting this pitch and then returning to adjust and revise it after you have completed your conceptual design. -->

Wandr: A Journey Beyond Echo Chambers

**Wandr** reimagines social media as a journey, where each user is an explorer navigating their consumption habits and discovering beyond their media echo chambers.

Upon signup, users can follow other "Wandrrs" and share a variety of media, including text, photos, short videos, and audio clips, as well as comment on posts.

In the main feed, each post can be *flipped* to reveal alternative viewpoints, encouraging users to broaden their understanding and access new content easily.

Users can customize the "flipped" content behind each *flip* by using the Compass, a tool that allows for personalized exploration.

With the *Compass*, users can adjust their *Step*, determining how far each flip will take them—whether opting for small, thoughtful steps in a similar direction or bold leaps into new, potentially contrasting territories. The *Compass* also features a direction tool that helps users choose the thematic direction they wish to explore further, guiding their journey based on their interests and curiosity.

Additionally, a *summary* feature tracks users' content consumption, providing insights into their behaviors and helping them reflect on their media habits. This encourages mindful engagement and inspires users to seek out fresh ideas.




## 2. Functional design: Concepts
<!-- Design a collection of concepts that will embody the functionality of your app; you’ll probably want 5-7 concepts for an app that is sufficiently rich to be interesting but not so complex that it can’t be implemented in the time you have (4 weeks). In some cases, a feature will correspond directly to a concept; in others, you may need to coalesce or split features. Concepts should be semantic, serve a distinct purpose, and be mutually independent. Each concept should be described with the standard parts: name, purpose, operational principle, state, and actions. You can write the principle informally, so long as it’s clear which actions are being referred to. The state should be defined using sets and relations. The actions can be written informally, or using the set/relation syntax illustrated in class. Define the app-level actions as synchronizations of concept actions, and instantiate generic concepts with appropriate types. Draw a dependency diagram showing the possible subsets. -->

<!-- Remember that the goal of this personal project is not just to learn the basics of building a full-stack web app but also to practice innovative design. So your design should have some novel elements to it, such as new concepts (which are not familiar from existing apps), new enhancements of existing concepts (adding actions or state that makes the concept more powerful or flexible or perhaps easier to use), new uses of existing concepts, or new synchronizations between existing concepts. -->

### Concept 1: Spotlite Selection

**Purpose**: The purpose is to ensure a diverse and dynamic content ecosystem by randomly selecting a set of users each week to be featured prominently, allowing them to share fresh and new content for the entire community to engage with.
DW
**Principle**: Every week, select a random set of users from the entire user base to be part of the 'Spotlite', granting them the ability to post content and engage with the community for the week.

**State**:

- Spotliters: Set of users randomly selected for the weekly spotlight.
- Content Pool: Set of users who have opted to participate in the pool from which 'Spotliters' are chosen.

**Actions**:
- Opt-in or Opt-out: Users can opt to participate in the pool from which 'Spotliters' are chosen or choose to be viewers.
- Random Selection: Randomly select a subset of users from the 'Users' set to be featured as 'Spotliters' for the upcoming week.









## 3. Dependency Diagram. 


## 4. Wireframes. 
<!-- Construct a set of wireframes that shows the user interface elements and their layout, and includes some of the main flows. You can omit error handling and completely standard interactions (such as user registration), but your wireframes should otherwise be enough to cover all your concepts. -->

## 5. Design tradeoffs. 
<!-- Using the notes that you took during your design, pick at least 3 design decisions that you made in which you had to choose between multiple options. For each one, provide (a) a pithy title naming the issue; (b) an outline of what the various options were; (c) a rationale for why you chose one option over the others. Try to keep your analysis below 300 words in total (for all the tradeoffs). -->

### Tradeoff 1: 
- **Options**:

- **Rationale**:    

### Tradeoff 2: 
- **Options**:

- **Rationale**:

### Tradeoff 3: 
- **Options**:

- **Rationale**:    

