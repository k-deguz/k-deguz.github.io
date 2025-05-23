---
layout: essay
type: essay
title: "The Pattern Playbook"
# All dates must be YYYY-MM-DD format!
date: 2024-04-24
published: true
labels:
  - Design Patterns
  - Software Development
---

<!-- Padding for space between sections-->
<div>
    <p class="pt-1"></p>
</div>

#### An Architectural Blueprint

<div style="float: right; margin-left: 15px;">
  <img width="250px" class="rounded" src="/essays/img/pattern-playbook/architecture_blueprint.png"> 
</div>

Design patterns are not just a set of guidelines for structuring code. They are a useful tool for solving recurring problems in software development. They provide a template: a set of guidelines for structuring code for many purposes. Much like a blueprint guides architects by outlining the framework, materials, and specifications for different buildings, design patterns encourage developers to be efficient by promoting code reusability and flexibility for many issues. For example, they come in handy when creating new components for a web application. Creating different UI elements may yield a repetitive process prone to multiple errors. Finding patterns helps streamline and simplify this process so that we have more efficient and error-free code. 

The Factory pattern is a versatile tool within a developer's arsenal. It's like a coach's game plan, with various plays to use in different in-game situations. Similarly, the Factory pattern equips developers with a proven process for creating a variety of UI elements. Each time a new component is needed, developers can consult the playbook to determine the most suitable method, ensuring their code is adaptable and flexible. This approach encourages efficiency, adaptability, and flexibility so that developers feel more secure in their code's ability to handle different situations. 

<!-- Padding for space between sections-->
<div>
    <p class="pt-1"></p>
</div>

<div style="float: left; margin-right: 30px;">
  <img width="180px" class="rounded" src="/essays/img/pattern-playbook/design_patterns.png"> 
</div>

#### Seasoned with Code!

<div style="float: right; margin-left: 15px; padding-top: 50px">
  <img width="240px" class="rounded" src="/essays/img/pattern-playbook/code_cooking.png"> 
</div>

While working on the final project for ICS 314, I frequently used the Factory pattern as many of the components for displaying pages were repetitive. Code for adding/listing a recipe or ingredient all followed an identical process, given that they all possessed similar features. Like the design pattern suggests, I used this specific playbook since I knew that it worked for one aspect of the application. As other pages had the same type of attribute, I figured that I could kill four birds (pages) with one stone (design pattern). 

Prior to learning about design patterns, I hadn't realized or recognized that I had been implementing ideas from this concept multiple times in the past. Recently, I have been working on a web application with classmates for our final ICS 314 project. It will be a platform for busy college students to navigating simple, tasty meal options tailored to their time and budget. In order to maximize efficiency while working on it, I learned to find and use patterns that would cut down the amount of time needed to think in order to produce different pages that used similar elements.
