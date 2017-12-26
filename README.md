# My Web Dev Journey 2017

After working at Lowe's Home Improvement from 2009 to 2017, I made the decision to quit and pursue a career in web development.  I had the opportunity financially to make a full-time job for up to a year.  

I technically started in March 2017 and, although it's not quite a year yet, I decided to create this repo to review the progress I've made and to discuss the things I want to work on in 2018.

For the most part, I have been following the web developer roadmap guide from this [github repo](https://github.com/kamranahmedse/developer-roadmap), focusing mainly on the front-end

---

## Overview

The following is an overview of the skills I learned in 2017.  I discuss each skill more in depth and my plans for 2018 after this list.

**Front-End Skill List**
* Front-end:
    *  HTML and CSS
        *  Preprocessors (SCSS)
        *  Front-end Frameworks
            *  Bootstrap
            *  Materialize CSS
    *  JavaScript
        *  ES6
        *  Frameworks
            *  Angular
            *  React
    *  Git/Github
    *  Responsive Web Design
    *  CSS Methodologies
        *  BEM


**Back-End Skill List**
*  APIs
    *  Promises
    *  Observables
*  Firebase
    *  Firestore database
*  PHP
    *  Basic PHP

---

**Table of Contents**       
[Required For Any Path](#required-for-any-path)     
[Front-End](#front-end)     
[Back-End](#back-end)     

## Required For Any Path

These are skills listed as essential for any web dev path, be it front-end or back-end:

[Git](#git)     
[Basic Terminal Usage](#basic-terminal-usage)      
[Learn To Research](#learn-to-research)      
[Data Structures And Algorithms](#data-structures-and-algorithms)      

### Git

I didn't learn Git until a month or so into all of this but I soon discovered it's essential to managing code and especially for using things like GitHub.

**What I Learned**

* Basic git commands
    * Initializing git with *git commit*
    * Adding changed files *git add -A*
    * *git commit -m "my message"* for committing changes
    * *git push* for pushing to a repository
    * *git pull* for pulling in changes
    * *git clone* for cloning a repo
* Branching
    * Creating a branch from the master branch
    * Committing a branch then merging it to the master branch

**What I need to work on in 2018**

Because I'm not working on a team, it's difficult for me to get a full understanding of git workflow.  I haven't had a chance to handle conflicts although I have experimented with them in my own projects.  Hopefully I'll have the opportunity to learn more about git workflow when I get my first web dev job.

### Basic Terminal Usage

Before starting to learn about web development, I was fairly familiar with using the command line and terminal.  I've experimented with the terminal in Mac OSX and also in Linux operating systems.  I knew how to do things like navigate folders, create, delete, and edit files.  Still, there were some things that I learned over the past 9 months:

**What I learned**

* NPM Scripts to install various 3rd party packages
* Using the command line to utilize task runners
    * Compiling typescript to javascript
    * Compiling sass/scss files to css

### Learn to Research

I believe this is something I've improved upon the most.  I learned that much of web development and programming is about tenacity and perseverance when encountering errors.  I feel like I learn the most from Googling things then, when finding a solution, understanding it.

Over time I've learned to Google better, meaning how to use proper search terms to narrow down search results towards the solution I need for my project.

### Data Structures And Algorithms

This is something I am admittedly weak on, but during the summer I did study them for at least 2 hours a day.  Lately I've been slacking on them and it's definitely something I want to get back into for 2018.

I think my biggest issue with studying them is that I am not directly using them in my projects at the moment.  I know they are a major part of software development interview jobs and although I may not encounter them in a front-end development position, they are important to know and understand.

I started a [Google Drive Document](https://docs.google.com/document/d/1psnkSyM1ZyzjBiK-JpHaxb-jpd4K9eQEkC-i_toGYDY/edit?usp=sharing) earlier this year to track my progress on Data Structures.  In 2018, I will review them and continue learning them.

---

## Front-End

This was the path that I stuck with for the most part.  Some projects required me to learn some back-end technologies, but I am much more proficient in front-end technologies at the moment.

[The Basics](#the-basics)     
[Getting Deeper CSS](#getting-deeper)     
[Responsive Web](#responsive-web)     
[Front-end Frameworks](#front-end-frameworks)       
[Getting Deeper JavaScript](#getting-deeper-javascript)     
[JavaScript Frameworks](#javascript-frameworks)      

### The Basics

My first major resources when learning the basics were at [Codecademy](https://www.codecademy.com/) and [freeCodeCamp](https://www.freecodecamp.org/).  I eventually moved to using freeCodeCamp exclusively when I because I felt it offered a better structure and roadmap to follow.

My profile can be found here: https://www.freecodecamp.org/xmtrinidad

I haven't used freeCodeCamp since April, but the first few months spent with it gave me a decent foundation to build upon.

On December 1st, 2017, I started to learn React.  Many of the projects on freeCodeCamp (after the basic content) require React to make them.  In 2018, I would like to return to freeCodeCamp to try some of their projects as I continue to get a better understanding of the React library.

**What I learned**
* Basic HTML structure
* How to use CSS with HTML
* Basic JavaScript with jQuery

---

### Getting Deeper CSS

Part of the reason I moved on from freeCodeCamp was because I discovered that there was much more to CSS than what I was learning on freeCodeCamp.  I started getting into CSS preprocessors like SCSS and learned about other front-end frameworks beyond bootstrap (although I use Boostrap for the most part to this day).

As my projects started to grow, I noticed code was becoming difficult to maintain especially with how I was using naming conventions in CSS.  I learned about CSS methodologies like BEM to better organize my code.

As the months progressed, I learned about the latest CSS3 features such as Flexbox, CSS Grids, and transitions.  In 2018, I hope to get more experience using animations (especially with frameworks like Angular).

In 2018, I would like to learn other preprocessors like LESS.  Although it isn't as popular, it's probably something good to know incase I have to use it in the future.  There are also some front-end frameworks like Bulma that I want to experiment with.

**What I learned**      
* Basic SCSS
* CSS3 features
* Front-end frameworks like Bootstrap and Materialize CSS
* CSS Methodologies (BEM)

**TODO 2018**
* Get a better understanding of SCSS mixins
* Learn LESS
* Try some projects using Bulma
* Read up on more CSS Methodologies
* Practice more animations and transitions

---

### Responsive Web

Taking a mobile first approach to projects was something I learned early and I continue to follow to this day.  Before I start to think about how something will look on a desktop, I design assuming that my project will be viewed on a mobile device first.

**What I learned**
* Using media queries to adjust/hide/show content depending on viewport size
* Better understanding of web accessibility
* Designing mobile first before desktop

---

### Getting Deeper JavaScript

I liked the way freeCodeCamp started teaching JavaScript.  As someone who had very little programming experience, it was important to understand the basics of general programming.  However, as I moved past freeCodeCamp I learned that the JavaScript I learned wasn't completely up to date.

When I learned about ES6, I adopted that syntax over what I learned from freeCodeCamp.  There weren't many differences that I noticed at first (switching *var* for *let* or *const*), but as I did more research I learned about several improvements ES6 had to offer, which essentially eliminated my need for jQuery.

About two months ago I started reviewing JavaScript interview questions.  The three most common questions I've seen involve the following topics:
* Closures      
* Prototypes
* The keyword *this*

I am still trying to get a better grasp of these concepts and several other core JavaScript fundamentals.  In 2018, I hope to improve my understanding of them and will make it a goal to learn something new about JavaScript as often as possible.

There are still several aspects of ES6 that I'd like to get a better understanding of in 2018.  Although I use ES6 in many of my projects, there are some things I could use more practice with (classes, maps).  I think doing a project that explicitly uses an ES6 concept would help me get a better understanding of how they work.

I also want to get into ES7 features, especially async/await which I hear is better than Promises.

**What I learned**
* New syntax (const, let)
* ES6 arrow syntax
* ES6 methods (filter(), reduce(), map() etc)
* Various ES6 features (rest/spread parameters, string interpolation, promises, classes)

**TODO 2018**
*  Make a list of ES6 and ES7 features that I'm not 100% sure I understand completely
*  Do more projects that use these features 
*  Get a better understanding of core JavaScript and prepare better for interviews

---

### JavaScript Frameworks       

After doing several projects without frameworks, I decided to finally get into one around July.  I was reluctant at first because I didn't understand them but the only way to find out why frameworks are popular is to do a project with one.  Since I started learning Angular, I haven't done a project without a framework.

Angular is the JavaScript framework I'm most familiar with, but I am still learning it.  I've done several projects and each time I start a new one I learn a brand new set of new things.

I didn't get into React until recently, but after spending a few months using Angular, the concepts behind React aren't completely new to me.  In 2018 I want to continue with the tutorial series I am following and do several more projects until I am proficient with it.

I also want to get into Vue.js as it is the another popular JavaScript framework.  I know there are several others, but from all the research I've done the top 3 are Angular, React and Vue.js.

As a result of working with these frameworks I was able to learn about things like NPM and Webpack.  Although I am not proficient in these technologies yet, I know that these frameworks are built using them.  As I continue to learn more about frameworks in general, I'll continue learning about how they are made.

**What I learned**
* Angular Fundamentals
    * Using components to layout a website
    * Making API requests with Angular
    * Angular Routing
    * Animations
    * TypeScript fundamentals to manipulate data
* React
    * components
    * Using state to manipulate data

**TODO 2018**
*  Review Angular Tutorial series and take notes similar to React project
*  Keep learning about TypeScript
*  Continue React tutorial series and do more React projects
*  Learn Vue.js basics

---

## Back-End

At the moment, I have limited knowledge of back-end technologies.  Whatever I know now was what I picked up from working with front-end tech and learning from tutorials.  In 2018, I want to learn PHP and whatever necessary frameworks (Laravel comes to mind first).

On December 15th, 2017, I started learning more about WordPress and consequently PHP, so technically I'm starting to learn PHP in 2017 but will continue to learn it throughout 2018.

Below is a list of back-end technologies I've learned in 2017 and additional skills I'd like to gain in 2018:

### APIs

I've done several projects using APIs on the front-end.  I first started learning it when doing freeCodeCamp projects.  At that time I was using jQuery to get data from an API request, but as I learned about ES6 and other JavaScript frameworks I learned about Promises and Observables to resolve the data from an API request.

I don't think I've done enough projects using Angular to fully understand how the HttpClient module works (the module that aids in making API requests) so in 2018 I want to do more practice projects that involve using APIs.

I haven't learned how to work with APIs in React yet, but that is coming up in the tutorial series I am taking.

When I learn Vue.js, working with APIs is something I will need to learn as well.

There's also an async/await function in ES7 that involves APIs that I want to learn more about.

**What I learned**
* Working with APIs using jQuery, pure JavaScript, and with Angular
* Getting nested data from APIs

**TODO 2018**
* More projects with APIs to better understand Promises and Observables
* Learn how to use APIs with React
* Learn about Async/Await and how it works with APIs

---

### Firebase

This isn't listed in the web dev roadmap but for many of the tutorials I viewed while learning various web dev technologies, firebase was used for a backend to save data.  I experimented with it several times and, most recently, I've experimented with the latest [Firebase Firestore](https://firebase.google.com/docs/firestore/) in an Angular project.

I'm not sure how viable knowing Firebase is for employment, but it has been useful for a quick back-end to save data for front-end projects.  In 2018, I plan on using it more for projects that require a quick back-end set up.

**What I learned**
* Setting up Firebase Firestore with Angular
* Saving data to the database
* Retrieving and deleting data from the database

---

### PHP

Earlier this month (December 2017) I wanted to learn more about WordPress.  I don't plan on becoming a WordPress developer but I know that much of the web uses WordPress and the technology it's built with, PHP.  I wasn't planning on getting into PHP, but the more I continued learning about WordPress, the more I realized from a job perspective how important PHP is.

I'm really looking forward to learning PHP in 2018 and how it works with back-end databases.

Other than basic syntax and mixing front-end PHP with HTML, I don't know much about it.  I'm learning more everyday and will continue to do so until I feel like I am capable making projects using it.

---

## Summary

I'm sure there are many more skills I could include in this and this is by no means a comprehensive list of my web development skills.  I think I highlighted the main aspects of what I've been focusing on.  

I feel like I've learned a lot of things over the past 9 months.  I believe I ready for a junior position where I can learn even more.  Even so, the learning never stops.  There are many things to learn still.  I'm looking forward to all the things I will learn in 2018.


