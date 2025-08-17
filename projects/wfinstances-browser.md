---
layout: project
type: project
image: projects/img/wfinstances-browser/wfinstances-browser-main.PNG
title: "WfInstances Browser"
date: 2025
published: true
labels:
  - Agile Project Management
  - Full-Stack Development
  - Docker
  - Python
  - TypeScript
  - IPInfo Geolocation
summary: During my final semester as an undergraduate at UH Mānoa, I worked with a partner on implementing a usage report modal to the WfInstances Browser. It displays a comprehensive view of the web application's most used features by fetching collected user data.
---
<hr>

<!-- Padding for space between sections-->
<div>
    <p class="pt-1"></p>
</div>

<figure style="float: left; margin-right: 20px; text-align: center;">
  <a href="/projects/img/wfinstances-browser/spring_2025_ics_project_day_poster.jpg" target="_blank" rel="noopener">
    <img
      width="200"
      class="rounded"
      src="/projects/img/wfinstances-browser/spring_2025_ics_project_day_poster.jpg"
      style="display: block; margin: 0 auto 0.5em;"
      alt="Spring 2025 - ICS Project Day Poster">
  </a>
  <figcaption style="font-size: 0.9em; color: #555; margin-top: 0.6em;">
    Spring 2025 - ICS Project Day Poster
  </figcaption>
</figure>

#### A Capstone Project
To acquire my BS degree in Computer Science, I was required to complete ICS 496. This project-based course provides the opportunity for undergraduates to work in teams and apply the technical know-how they have gained throughout their educational journey within the ICS department. Students need to plan, execute, deliver and present a software development project. This ultimately provides preparation for real-world experiences along with the demands and expectations of the industry.

The team-based projects are sponsored by many different organizations, including faculty from the ICS department and other departments within the university, state departments, federal agencies, non-profit organizations, or industry partners. Students work closely with their project sponsors throughout the project lifecycle to make sure that the project meets the sponsor's expectations and requirements. Upon the completion of the course, each team presents a poster about their work for ICS Project Day towards the semester's end.

<!-- Padding for space between sections-->
<div>
    <p class="pt-1"></p>
</div>

<figure style="float: right; margin-left: 20px; text-align: center; padding-top: 20px">
  <a href="/projects/img/wfinstances-browser/usage_report_modal.PNG" target="_blank" rel="noopener">
    <img
      width="340"
      class="rounded"
      src="/projects/img/wfinstances-browser/usage_report_modal.PNG"
      alt="Usage report modal">
  </a>
  <figcaption style="font-size: 0.9em; color: #555;">
    Usage report modal
  </figcaption>
</figure>

#### Project Overview
In scientific domains, workflows are the blueprints for complex computational processes for data processing and analysis. The WfCommons project hosts are repository of production workflow instances, WfInstances. These instances support a wide range of research, development, and education activities. The WfInstances Browser is an accompanying web application that lets users easily browse, select, sort, download, simulate, visualize workflow instances in WfCommons repositories.

At the end of the course, our team and I were able to implement new features in the WfInstances Browser that primarily focused on increasing usability. One major addition we worked on was the implementation of the usage report modal, which shows a comprehensive timeline and displays the aggregate usage reports for downloads, simulations and visualizations. It also allows for date ranges to be customized so that users can filter usage data. A sidebar within the modal shows the top usage countries and displays a list of the ten most active nations in order. It uses IPInfo for geolocation tracking and is based on the combined count of users in a country that made up the bulk of those who used simulations, visualizations, and downloads.

<!-- Clear previous floats to keep the gallery together -->
<div style="clear: both;"></div>

<!-- Centered side-by-side gallery for the two images -->
<style>
  .wfib-image-pair {
    display: flex;
    flex-wrap: wrap;
    gap: 24px;
    justify-content: center;
    align-items: flex-start;
    margin: 10px 0 20px;
  }
  .wfib-image-pair figure {
    margin: 0;
    text-align: center;
  }
  .wfib-image-pair img {
    display: block;
    margin: 0 auto;
  }
  .wfib-image-pair figcaption {
    font-size: 0.9em;
    color: #555;
    margin-top: 0.6em;
  }
</style>

<div class="wfib-image-pair">
  <figure>
    <a href="/projects/img/wfinstances-browser/user-questionnaire.PNG" target="_blank" rel="noopener">
      <img
        width="170"
        class="rounded"
        src="/projects/img/wfinstances-browser/user-questionnaire.PNG"
        alt="An occasional pop-up for user questionnaire">
    </a>
    <figcaption>An occasional pop-up for user questionnaire</figcaption>
  </figure>

  <figure>
    <a href="/projects/img/wfinstances-browser/wfinstances-readme.png" target="_blank" rel="noopener">
      <img
        width="170"
        class="rounded"
        src="/projects/img/wfinstances-browser/wfinstances-readme.png"
        alt="WfInstances README">
    </a>
    <figcaption>WfInstances README</figcaption>
  </figure>
</div>

Based on how frequently the user interacts with the application's features, they may occasionally be prompted with questionnaires about the usability and usefulness of the site. Moreover, the .json files for workflow instances are now acquired using the git Python package instead of the GitHub REST API for higher performance. Lastly, we developed a GitHub action to the WfInstances repository so that it displays WfInstances Browser usage data within the README file.

<figure style="float: left; margin-right: 30px; text-align: center; padding-top: 10px">
  <a href="/projects/img/wfinstances-browser/wfinstances-browser-final-poster.jpg" target="_blank" rel="noopener">
    <img
      width="270"
      class="rounded"
      src="/projects/img/wfinstances-browser/wfinstances-browser-final-poster.jpg"
      alt="WfInstances README">
  </a>
  <figcaption style="font-size: 0.9em; color: #555;">
    Our ICS Project Day Poster
  </figcaption>
</figure>

Here is the [live deployment](https://wfinstances.ics.hawaii.edu/) of the WfInstances Browser. For more information regarding our team's progress and an extensive guide into the WfInstances Browser, visit the [wfinstances.github.io](https://wfinstances.github.io/) page.

<!-- Padding for space between sections-->
<div>
    <p class="pt-1"></p>
</div>

#### Real-World Preparation
The overall experience and insights I acquired from this course throughout the semester allowed me to prepare for the expectations within the software development industry. Using Python scripts for handling the backend for usage metrics and TypeScript for frontend development of the usage report modal gave me a real-world application of full-stack development. It also improved my knowledge about problem-solving from a software engineering perspective and taught me how to leverage different technologies to complete a project.

Additionally, I gained hands-on experience with Docker deployments and backend development by making sure that the data flow between the frontend and backend were both efficient and correct. By working directly with our REST API, I learned how to route backend data all the way to the modal component in the frontend and integrated IPInfo geolocation tracking to elevate our usage reports with precise location-based analytics. 
