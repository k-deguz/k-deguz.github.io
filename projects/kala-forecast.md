---
layout: project
type: project
image: projects/img/kala-forecast/kala-forecast-landing.PNG
title: "Kālā Forecast"
date: 2025
published: true
labels:
  - Agile Project Management
  - Full-Stack Development
  - Fiscal Sustainability Model
  - JavaScript
summary:  Our team and I created a web application for Spire Hawaii LLP to replace their Excel-based financial sustainability model with a user-friendly integrated platform. It stores historical financial data and uses relevant variables to create a future financial forecast and trending analysis. 
---
<hr>

<!-- Padding for space between sections-->
<div>
    <p class="pt-1"></p>
</div>

<figure style="float: left; margin-right: 20px; text-align: center; padding-top: 10px">
  <a href="/projects/img/kala-forecast/fsm_worksheets.PNG" rel="noopener">
    <img
      width="240"
      class="rounded"
      src="/projects/img/kala-forecast/fsm_worksheets.PNG"
      style="display: block; margin: 0 auto 0.5em;"
      alt="FSM worksheets">
  </a>
  <figcaption style="font-size: 0.9em; color: #555; margin-top: 0.6em;">
    FSM worksheets
  </figcaption>
</figure>

#### Project Overview
Kālā Forecast is a web application developed by myself and five peers in our ICS 414 course at the University of Hawai‘i at Mānoa. It replaces Spire Hawaii LLP’s complex, Excel-based Financial Sustainability Model with a more intuitive, integrated solution. We replaced different types of interlinked worksheets that form the core of the FSM which cover sustainability inputs, stress-test scenarios, audited income statements and balance sheets with out-year forecasts and model scenario work papers. 

While working on this project, I contributed to developing the pages for landing, sign-in, sign-up and the work papers. To implement the modeled scenarios for work papers where individual financial scenarios are developed, I created a JavaScript module that contains each scenario's default inputs and calculation logic. In a React Work Papers component, I linked that module to a dynamic interface that brings everything together. 

<figure style="float: right; margin-left: 10px; text-align: center;">
  <a href="/projects/img/kala-forecast/work_papers.PNG" rel="noopener">
    <img
      width="280"
      class="rounded"
      src="/projects/img/kala-forecast/work_papers.PNG"
      style="display: block; margin: 0 auto 0.5em;"
      alt="The work papers page">
  </a>
  <figcaption style="font-size: 0.9em; color: #555; margin-top: 0.6em;">
    The work papers page
  </figcaption>
</figure>

I built the Workpapers page as an interactive hub where users can explore different financial _what-if_ scenarios. At the top, a dropdown lets you switch between predefined scenarios which cover a variety of emergency expense shocks to loan amortization analyses. This is so stakeholders don’t have to hunt through dozens of Excel tabs to compare cases. Once a scenario is selected, a form that adapts the chosen fields to whatever inputs are relevant: interest rates, contribution amounts, forecast years, or specific expense entries for a given month. This makes it easy for users to tweak assumptions, with every change being wired to update the underlying data model immediately.

Below the form, I added several tables that present both the immediate _stress effects_ and the longer-term _residual effects_ of each test. I structured each scenario’s calculation logic in modular JavaScript objects so that adding new tests or adjusting formulas is straightforward. Those updates flow into the Work Papers page without rewiring the user interface. Altogether, these features provide a platform for the previous spreadsheet model into an intuitive web interface so that decision-makers have access to fast, hands-on control over their financial forecasts.

<div style="float: left; margin-right: 20px; padding-top: 5px">
  <img width="170px" class="rounded" src="/projects/img/kala-forecast/swe_perspective.png">
</div>

<!-- Padding for space between sections-->
<div>
    <p class="pt-1"></p>
</div>

#### Further Experience
As a result, I was able to improve my JavaScript, CSS, React and Bootstrap capabilities even more much like a previous project from an ICS 314 course. I was able to learn how to collaborate in Git-based workflows, using code-review etiquette and branch-management so that there were no lingering conflicts with project functionality. Though there were some hitches in team and project management, these experiences as a whole helped me gain an in-depth insight into the world of business software development, with a focus on bridging financial data logic and the user experience.
