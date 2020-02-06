![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

# PROJECT 4

![final countdown](https://media0.giphy.com/media/RnX4q6yYDoYCI/200.gif)

One. More. Project.

## Overview

For your final project, you will build a full-stack, full-CRUD app, utilizing a RESTful JSON API on the back-end and React on the front end.

This project, like the others, will be a portfolio piece... Your ultimate portfolio piece. Build something you can be proud of– something that demonstrates an understanding of- and an ability- to use- the tools and techniques introduced over the last 3 months; it must be **functional with sufficient complexity**.

_No tricks and hidden challenges this time- you're real devs now._

#### Two Quick Notes. <!-- omit in toc -->

While we've been somewhat lenient on certain requirements (commits) in your prior projects, _the requirements for your final project are non-negotiable_. If you do not meet these requirements by the deadline, we may need to consult Student Services about conditioning your certificate of completion (and Outcomes support eligibility) on the future completion of your project.

If you have an idea that displays the requisite level of complexity with a strong reason for utilizing a different tech stack, we're willing to hear you out. If you take this approach, you need a back up proposal that meets the React on Rails specs, in the event that we do not approve your alternate stack.

#### So, this is what 3 months of grueling work has come to... <!-- omit in toc -->

<br>

## The MVP Requirements

### Planning

- Have a **thoroughly** developed `README.md` file. (Refer below to _"Pitch Your Project Idea"_ for more.)

### Server (Back End)

- Have a **RESTful JSON API**.
  - Build a **Ruby on Rails** server, exposing RESTful JSON endpoints.
  - Build a database with at least 3 tables:
    - 1 user table
    - 2 other tables, of your choosing
    - There must be at least 2 pairs of associated tables. (1:m _or_ m:m)
  - Utilize **Rails** to define models for interacting with the database.
  - Implement Authentication using **JWT**.
  - Implement working generic controller actions for full-CRUD (`index`, `show`, `create`, `update`, `delete`) between the 2 non-user tables AND partial-CRUD (`create`, at least) for the user table.

### Client (Front End)

- Have a working, interactice **React** app, built using `create react app`.
  - Have at least 8 separate, rendered components in an organized and understandable React file structure.
  - Utilize functional and class React components appropriately.
  - Utilize state and props in your components efficiently.
  - Use _only_ React for DOM Manipulation.
- Consume data from your **Ruby on Rails API**, and render that data in your components.
- Utilize **React Router**, for client-side routing.
- Utilize Authentication, permitting the user to:
  - Register, login, and send authenticated requests.
  - Perform `index` or `show` actions, **whether or not they are logged in**.^
  - Perform `create`, `update`, and `delete` actions **when logged in**.

_^ Unless it makes sense for that information to be restricted to particular users._

### Styling

- Be styled with CSS (or SCSS, if you'd prefer).
- Use flexbox for your indices (`display: flex`).
- Implement responsive design on 3 screen sizes (including desktop) using 2 media queries (tablet and mobile).

### Linting

- Indent properly.
- Utilize high-quality, semantic variable names.
- Follow `camelCase`, `snake_case`, and `kebab-case` convention.
- Remove unnecessary boilerplate React files and code.
- Remove all `console.log()`s and commented out code (functional notes and comments are okay).

### Deployment

- Deploy the fully functional front-end via Surge.
- Deploy the back-end via Heroku.

### Procedural

- Initialize a **git repo on Github**, with a link to your hosted project.
- Have **frequent commits**, making a _robust_ commit history at least every day. (75 commits minimum)
- Use effective and safe **branching and merging** processes.

<br>

# Getting Started

## Step 1. Make A New Repo

You will start by creating your project repository on your **personal** GitHub.

## Step 2. Pitch Your Idea

Before you start coding away, you will meet with instructors to get your idea approved. You will have 5 minute pitches in which you will present your ideas. **You must have your idea prepared and written up in the repository's ReadMe file, including all of the following items, to get approved. Do not slack off on this step.** 

<!-- (Frankly, we'll just be mad if you walk into the pitch without a thorough, organized `README.md`. You have a template available. Clone the template, don't leave any of the template boilerplate in your own README, and use that to pitch us.) -->

1. **Title:** A working title for your app.
2. **Overview:** A brief explanation, in non-technical speak, summarizing the app.
   - **Features:** A full feature list for your MVP app.
   - **Goals:** The overarching goals for your project.
   - **Challenges:** An explanation of the challenges you expect to face with this project.
3. **MVP:** An overview of your MVP, including the minimum, need-to-have features of the app.
   - **Client:** Mid-fi wireframes, component heirarchy, component breakdown, and timeframe estimates.^^
   - **Server:** Data architecture, ERD model, and API endpoint documentation.^^
   - **Dependencies:** A full list of all libraries, frameworks, etc.
4. **Post-MVP:** Your goals for post-MVP, including features that you would like to implement once your MVP is complete.

^^ **No more hand-drawn wireframes or ERD models.** There are heaps of free services that can create great wireframes and ERD models. Refer to the Resources section below for templates, services, and other README resources.

## STEP 3. Get Hacking

### Getting Support

When you experience issues with your code, once again, you will need to use the GitHub Issues tab. The Issue Ticket templates help you observe, research, and attempt to resolve your issue. If there's still no resolution, submit and slack the issue ticket your squad leader to reserve time to troubleshoot together.

<br>

# Resources

## Templates

- [Full Stack Project README Template](https://github.com/mishakessler/course-template/blob/master/projects/template_fullstack-README.md)
- [Project Issue Ticket Template](https://github.com/mishakessler/course-template/blob/master/projects/template_issue-tickets.md)

## Wireframing

- ["How detailed should wireframes be?"](https://justuxdesign.com/blog/wireframe-fidelity)
- [Wireframe.cc](https://wireframe.cc/)

## ERD Modeling

- [lucidchart](https://www.lucidchart.com/) This is a great tool for building ERDs.
- [draw.io](https://www.draw.io/) Another great tool for ERDs.
- [ERDPlus](https://erdplus.com/) Yet another great tool for ERDS.

# Plagiarism

Remember. We have a **zero tolerance policy** towards plagiarism. More on our plagiarism policy can be found in our course wiki's [plagiarism page](https://github.com/mishakessler/course-template/blob/master/policy_plagiarism.md).
