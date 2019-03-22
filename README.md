# HackYourFuture Curriculum

>Here you can find an overview of the HackYourFuture program. It gives insight in how our program is structured, organized, what you can expect from the modules that we teach and last but not least where we teach and where you can find support during the week. Our half year course is divided into modules that last 3 weeks with exception of the project module that lasts 6 weeks. Below you can find a short listing of the contents and deliverables/learning goals of the different modules. The headers of the different modules link to the actual repositories that are used by teachers to post assignments/reading materials etc. Be aware that some of the modules make use of more than one repository. 

- Are you a new **teacher**? Take a look [here](https://github.com/HackYourFuture/curriculum/blob/master/i-am-a-new-teacher.md) for some practical tips on how to get started!
- Are you a new **student**? Take a look [here](https://github.com/HackYourFuture/curriculum/blob/master/i-am-a-new-student.md) to see how to prepare for your first class!

### **Are you either a new student or a new teacher? Take a look at what we see as our [core values](https://github.com/HackYourFuture/curriculum/blob/master/hyf-core-values.md) at HackYourFuture before you join our community** :heart:

# When do we teach?

>Class on **Sunday**

>Class is every Sunday from 12.00 to approximately 16/16.30.

# What do we teach?

## [HTML/CSS](https://github.com/HackYourFuture/HTML-CSS)/[CLI](https://github.com/HackYourFuture/CommandLine/)

>HTML is the standard markup language for creating Web pages. CSS is a language that describes the style of an HTML document. This module will introduce the basic concepts of HTML5 and CSS. We spend time getting you familiar with your text editor and handy developer tools. After this we will focus on responsive web development. Making responsive websites is an important part of front-end programming. You will learn how to make your websites responsive by using media queries using a “mobile first” approach. Last but not least we will spend time practicing some soft skills that we think are important for becoming a good developer. These include: give and receive feedback to your fellow students, presenting and explaining your work.

>The command line (cli, shell) is the interface between you (the user) and the operating system which interprets your commands and allows the computer to respond to your command. In this module two half day sessions are spend to get students familiar with the command line.

### **Module goals**
**HTML/CSS**
- Basic understanding of HTML5 and CSS (DOM, semantic elements)
- Know how to work with ARIA (Thinking about people with disabilities / Google (SEO)
- Know how to organize your files
- Know your way around your text editor
- Feel comfortable working with the console
- Properly indent your code
- Properly naming classes, id's
- Responsive mobile first development
- Know "good" and "bad" practices when it comes to HTML
- Get an understanding of what good resources are on the web
- Give receive/feedback from/on fellow students
- Presenting and explaining your work to others

**CLI:**
- To know the terminal/bash/command line for UNIX based systems.
- Navigate the file system without using a UI explorer.
- Copy, rename and move files with terminal commands.
- Learn output redirection, piping on the terminal.
- Write basic shell scripts to ease the programming life.


## [JavaScript1](https://github.com/HackYourFuture/JavaScript/)/[GIT](https://github.com/HackYourFuture/Git)/ [debugging](https://github.com/HackYourFuture/debugging)

> In this module we use Node to run JavaScript. 

> In [this repo](https://github.com/HackYourFutureBelgium/fundamentals) you can find a very nice overview of some of the fundamental javaScript concepts.

### **Module goals**
**JavaScript**

A basic understanding of the following topics:
- Intro JavaScript (What is it, where can you use it for)
- Variables [var, let, const]
- Basic Data types [Strings, Numbers, Arrays, Booleans]
- Operators
- Naming conventions
- Conditions
- Advanced data types [Objects]
- Statements vs Expressions 
- Loops (for/while)
- Functions 

**Git**

After this sessions students should:
- Have an understanding of problems for developers working together on software
- Have an understanding of the need for version control software
- Have an understanding of what GIT is and what problem it solves.
- Understand what a commit is and how it represents a certain unit of work
- Know how to create a new repository using clone and init
- Know how to add / remove files to that new repository
- Know how to commit and push files in that new repository.
- Have an understanding of branches and how they can be used.
- Know what a remote is and know how to retrieve remote information from git:
- git remote [show] [-v] [-vv]
- Know what the difference between the three types of branches are.
- Know how to navigate between branches and what git commands to use for them.
- Have an understanding of what HEAD means.
- Have an understanding of pull requests and forking workflow.


## [JavaScript2](https://github.com/HackYourFuture/JavaScript/)

> JavaScript in the browser with HTML and CSS

### **Module goals for JavaScript2**

- Capturing user input
- Basic DOM manipulations [img src, innerHTML]
- Code debugging using the browser
- Code commenting
- Structuring code files
- Functions + JSON/Arrays
- Array Manipulations 
- JSON
- Map and filter
- Arrow functions
- Closures 
- Scope 
- Events
- Callbacks

## [JavaScript3](https://github.com/HackYourFuture/JavaScript/)

### **Module goals for JavaScript3**

- Object Oriented Programming
- Code flow (order of execution)
- Async VS Sync
- Structure for a basic SPA
- XHTTP Requests 
- API calls
- (re)writing data structures (in JSON)
- Promises

## [Node](https://github.com/HackYourFuture/Node.js)

>Node.js is a server-side platform built on Google Chrome's JavaScript Engine (V8 Engine). For almost any web application, it is essential to have a backend. The backend is a place where we, the developers, can store our data, communicate with users and let the users communicate with us, do smart things like calculations, data processing etc.

There are many languages for this. We might've heard of Java, C, C++, Go, Python, Ruby, PHP and the [list goes on](https://blog.newrelic.com/2016/08/18/popular-programming-languages-2016-go/). 

There are two reasons why we at HYF choose Node.JS over others:
1) You already know JavaScript, so it's easier to get started than other languages
2) Node.js is great for making web APIs because it is asynchronous by nature and thus allows for high input/output. By this we mean that it allows many users to make very light requests at the same time.

### **What will we learn?**
- What is Node.js?
- Using Node Package Manager (NPM)
- Using `require` to include modules
- Using `http` to handle http requests and respond
- Using `fs` to read from and write to files.
- Using `process` to read arguments from the CLI
- Using `express` to make a RESTful API

## [Database](https://github.com/HackYourFuture/databases)

>What is a database? A place to store “things”. Could be as simple as a phone book (physical) or as complex as storing all the inventory for Amazon.com. Why use databases? Easier than having data all over the place. Puts the problem of collecting, storing, sorting and searching data in a single place. There are two primary types of database systems - relational and NoSQL. Relational databases have tables that relate to one another and can be “joined” ACID vs BASE

### **Module goals**
By the end of this module, students should have a familiarity with and basic understanding of the following:

- Entities
- The relational model
- The Structured Query Language (SQL)
- The construction of a database system
- MySQL as an example of a relational database system
- Non-relational data and NoSQL
- MongoDB as an example of a NoSQL database

## [React](https://github.com/HackYourFuture/React)

### **Module goals**

- React Components
- State and Lifecycle
- Forms and Managing State

## [Final Project](https://github.com/HackYourFuture/Project)

>In this module students work together in a team on a predefined project. The goal of this module is to combine all your acquired skills from the last modules into a project, often in collaboration with a real-world organisation and real-world challenge to solve. In this project, scoping, requirement analysis and project management are core themes while building your first full-stack project! 💪

### **Module goals**

- Working on a full-stack skeleton (provided by us), using different technologies you’ve been exposed to during the HackYourFuture program.
- Fill the gaps that you have left in the previous modules. Did you miss an Node assignment? Make sure to pick up an extra issue there.
- Show that you can work and function in a team.
- Get familiar working with Scrum.


**After this module we offer (technical)interview and CV training for those who are interested. The goal of these sessions are to:**
- Get your CV and LinkedIn ready for when you are ready to go to interviews.
- Get an understanding of how (technical) interviews go in the Belgian job market.


Our curriculum is subject to CC BY copyright. This means you can freely use our materials, but just make sure to give us credit for it:)
