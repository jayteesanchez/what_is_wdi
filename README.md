# What is WDI?

A framing and discussion about how to approach the immersive learning environment, and key points about the Web Development Immersive.

### Lesson Objectives

- Define "web application", and name some alternate types of programs.
- Describe the parts of a web application and the path our class will take to learn how to build them.
- Explain what is meant by *owning* your learning experience (active learning as opposed to passive learning).
- List the types of resources that students in this class should either generate or gather, and why:
- Explain the difference between taking notes and receiving notes, and why each is important.
- Explain the purpose of lesson objectives in this classroom.
- Define abstraction, encapsulation, interfaces and modeling, and how these general ideas will apply to our journey.

## Our Course's Journey

The purpose of this course is to learn the **fundamental concepts** and **processes** of *creating programs*, something known as **software development**.

#### Web Application Development

We will learn software development in the context of *networked* (more than one computer) *applications* (another word for program, usually for one that works as a stand-alone product) that communicate using *web* technologies (HTTP, HTML, CSS & JavaScript): ie, **web applications**.

[Other types of development](http://jamesmccaffrey.wordpress.com/2006/04/24/the-7-types-of-software-development/) include systems development, "native" application development (specific to an OS, "ecosystem" or mobile device), and embedded, scientific, or test/automation development. Often the people who do such work append the term "engineer" to the terms above (such as an "automation engineer"). Beyond just software development, however, programmers often work in infrastructure or IT, doing jobs like system administration (ie *[sysadmins](http://en.wikipedia.org/wiki/System_administrator)*), developer operations (ie *[devops](http://en.wikipedia.org/wiki/DevOps)*), or security.

#### Our Primary Goal

The purpose of this course is not to learn the specific technologies on the syllabus, but to ***learn how to use any technology you can work with in software development.***

#### Our Secondary Goals

However, we will judge our growth and build our projects using the technologies outlined in our syllabus, and so we must also (thankfully) ***become competent junior programmers in these technologies***.

We must also ***learn the processes and pitfalls of working in a software development job***: how to manage and share our code, how to distribute workload, how to ask questions and when to ask them, among other skills.

#### Our Class's Learning Path

In order to reach this shared goal, the instructors of this class have used their experience as programmers and as teachers to craft a specific learning path. [**This is our _syllabus_**][syllabus].

No two classes have the same path; all classes share the same goals. We mostly use the same technologies, but not always: *these technologies are largely incidental to the goals of the class*. The plan is that, by the end of WDI, **you can learn any new technology and begin creating software with it**, regardless of what you learned to do in class.

A web application has a certain structure, and we must learn the parts of that structure and how to combine them one-by-one. Here is that structure and the path we will take to understand it as a whole:

![A web application][web-app-diagram]

Weeks 1 and 2:
Week 3:
Winter Break:
Week 4:
Week 5:
Week 6:
Week 7:
...

## "Owning" the Experience

In order to be successful in our journey, we need to understand some major... Be an active learner, not a passive one. Be aware of your strengths and weaknesses, and attempt to find gaps in your knowledge (don't avoid them). Etc.

1. smart learning and taking care of yourself (**from emotional framing**)
- awareness and focus on personal development and understanding the emotional cycle of change (**from emotional framing**)
- **asking questions**,
- **generating and gathering resources**,
- **vocalizing needs**.

self-assessment and lesson objectives: can i do this? if not -- make sure you can!

## Resources

gather and learn how to file...

There are a variety of resources you will need while you learn the fundamentals and processes of programming.

1. example code (receive/find: needs expertise)
- tutorials (receive/find: needs expertise)
- summative material (generate: synthesize)
- cheatsheets (generate: prompts and reminders)
- stories, diagrams and pictures (both: synthesize and develop mental models)

## Core Concepts

When you begin to think about the real work behind our upcoming journey, it can be overwhelming to picture what our path is going to be. Changing how we think, how we approach problem solving, gaining a totally new vocabulary and set of skills, and creating an understanding of the technological systems involved in modern computing, while keeping track of the specific practices of the technologies we are using, is an incredibly **complex process**.

And it is that problem, the problem of ***managing complexity***, that is at the heart of what we need to learn. At all times as a developer we need to be able to take a complex problem or situation and turn it in to something (or some *things*) less complicated, and then solve that.

### Abstraction

The term we use for making a problem less complex is **abstraction**. We all use abstraction every day.

In order to use abstraction to manage complexity we need to know both what our **problem** is (what we need to do) and what our **domain** is (the tools and knowledge we have to reach that goal).

#### Encapsulation

A common way we use abstraction is to focus on the **problem**. We break a problem into multiple, smaller problems, and then solve them one after another. Each solution is simple, and is used in the solution of the next most complex part.

> For example, if we need to drive to Grandma's house, we don't need to build a car first -- the "build a car" part of the problem has been solved. Hopefully we also don't need to "learn how to drive a car," that should also be solved! So now we just apply our existing "driving" knowledge to our existing "car" with the destination "Grandma's House." Huzzah!

![An encapsulated problem][encapsulation-diagram]

When we use encapsulation, we need to think of our problems as systems. We don't remove any aspects of the system, but instead group interconnected parts and connect them together, describing their *inputs* and *outputs* explicitly. This allows us to take these parts out as a subsystem, ie a problem that can be solved by itself, and "encapsulate" it. In this case, we call the inputs and outputs of an encapsulated system an **interface**.

We as programmers will encapsulate systems and describe their interfaces every day.

#### Modeling

Another common way we use abstraction is to focus on the **domain**. We take a very complex system of data and rules and decide to keep only what is necessary to solve the problem at hand. We don't just hide the complexity behind interfaces, we *ignore* it!

> We do this all the time too! For example, when we have to figure out who won a Presidential election, we don't need to know everyone's feeling about every issue, or all the demographic data that pollsters use -- even if this is an aspect to who wins the election. All we need to know is what percentage of the population in every state voted for whom, and how many electoral votes that gives the. Thus we can ignore every data point but percentages, states and electoral votes!

![An modeling problem][modeling-diagram]

Modeling can be a very difficult process, and the outcome of modeling is called a ***model***. We will use models all the time when solving problems, but the process of modeling (hopefully) happens only once in a while.

---

### An example set of notes in markdown (summative):

### [SYLLABUS!!][syllabus]

### **Define "web application", and name some alternate types of programs.**

1. web application: a stand-alone program (application) that is written to communicate between multiple computers using the web
2. [other types of programming](http://jamesmccaffrey.wordpress.com/2006/04/24/the-7-types-of-software-development/) include:
  - systems development,  
  - "native" application development / mobile development
  - embedded development
  - test or automation development
  - system administration (IT)
  - devops (IT)

### Describe the parts of a web application and the path our class will take to learn how to build them.

1. front-end or client-side: the interface for users
2. back-end or server-side: where the data lives
3. network: the structure that combines clients and servers, often the Internet!
4. web-server -- handles incoming requests from a network and routes them to application servers or middleware
5. application-middleware -- some other program that may support the handling of requests within a server
6. application-server -- a program that stores and retrieves information according to some rules or "business logic", often a "web application framework"
7. framework -- a type of program that allows developers to ease the creation of applications by taking care of basic operations and common needs
8. database -- a piece of saftware specifically focused on storing data -- lives with the server)
9. browser -- a program that allows clients to fashion requests to servers and display their responses

Our class will learn how to build programs with Ruby, and then learn about servers and build one using a Ruby framework called Sinatra. Then we will learn about how to write interfaces for web browsers using HTML, CSS and JavaScript. Finally we will connect the two together using sophisticated networking techniques and complex interactions. To make best use of these, we will learn a more complete framework known as Rails, and a powerful SQL database.

### Remember for class:

1. learn to recognize when to go to bed
2. set timers and take breaks (pomodoro, for example)
3. talk to instructors / producers when necessary
4. **ALWAYS ask questions or ask for something when I need it**
5. check for understanding using lesson objectives

### Remember to keep a list of (and have access to):

1. example code (from class and links the instructors give)  
2. tutorials (look these up and ask instructors about it)
3. lesson objectives

### Talk to other students about creating/sharing (maybe use HipChat or DropBox???):

1. notes
2. cheatsheets
3. stories, diagrams and pictures

### Define abstraction, encapsulation, interfaces and modeling, and how these general ideas will apply to our journey.

- abstraction: managing complexity when solving a problem or approaching a complex situation
- encapsulation: breaking a problem into sub-problems, and then hiding each problems' solution behind an interface that we can access
- modeling: removing complexity from a problem, and re-imagining what the actual problem is

<!-- Links -->

[syllabus]:              https://github.com/ga-students/godot#course-outline
[web-app-diagram]:       https://...
[encapsulation-diagram]: https://...
[modeling-diagram]:      https://...
