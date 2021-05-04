# p5.js-Commenter

## Welcome!

This Readme serves as a project documentation for _p5.js Commenter_, a proposed add-on for the _p5.js web editor_.  This project was developed to fulfull a course requirement for my PhD program in Learning Sciences.  Informed by research in STEAM education and transdisciplinary learning, this add-on affords p5.js creators a means to critique personal and peers' works. 
<br>

![Inline Commenting Screenshot](https://github.com/dmawer13/p5.js-Commenter/blob/main/Inline.png?raw=true)
<br>
<h2>Introduction</h2>
As a burgeoning curriculum model, STEAM (Science, Technology, Engineering, Arts, and Mathematics) education has been gaining momentum over the past decade as educators attempt to integrate arts and design into STEM (Science, Technology, Engineering, and Mathematics) curriculum.  As with many nascent developments in education, the introduction of STEAM content in classrooms has faced difficulties partially due to ambiguous conceptualizations of the model (Mejias et al., 2021).  Recent research has positioned STEAM as transdisciplinary in nature (Costantino, 2018), offering learners unique conditions to conduct inquiries that “go beyond, or transcend, the boundaries of particular disciplines” (Kreber, 2009, p. 25). This research highlights transdisciplinarity’s potential in preparing students to meet “the demands of the modern knowledge society” (Kreber, 2009, p. 25) as well as solving “wicked problems” whose solutions require multiple epistemological perspectives (Brown, Harris, & Russell, 2010).   
<br>
Emerging research has identified overlapping epistemic practices of STEM and the arts disciplines, one of which is critique (Bevan et al., 2019, Costantino, 2018).  Although critique practices in STEM and the arts share certain features related to their intended purpose, they ultimately maintain distinct properties that reflect their original disciplines.  Moreover, some have conjectured that in a transdisciplinary STEAM environment, critique might assume new forms as the practice transcends its disciplinary boundaries in a hybridized “third space” (Costantino, 2018).  Ultimately, there is an exciting opportunity in creating conditions for learners to critique within STEAM contexts.
<br>
I offer a software add-on for the open-source creative coding platform p5.js web editor that affords users a means to critique work in STEAM contexts. With the p5.js Commenter add-on, users can comment on their own or others’ work via inline code commenting or overall commenting. This system’s functionality was iteratively informed through feedback, collaboration, and design critique offered by academics in the learning sciences, media studies, and visual arts education fields. 
<br>
<strong>The ability to conduct critique in STEAM contexts offers students rich transdisciplinary learning opportunities and will potentially illuminate further understanding of STEM and arts hybrid epistemic practices.</strong><br>

![Overall Commenting Screenshot](https://github.com/dmawer13/p5.js-Commenter/blob/main/Overall.png?raw=true)
<br>

<h2>Design Overview</h2>

Alone, p5.js is an open-source Javascript library for creative coding.  A user can write code that produces multimedia content in an internet browser.  The p5.js web editor provides a browser-based creative coding environment for any user with internet access and a browser (p5js.org).  Developed in 2017 by Cassie Tarakajian, the goals of the web editor are “making a beginner friendly environment, creating a tool for teaching, and making web accessibility a priority” (Tarakajian, n.d.).  This interface is shown in Figure 1 with an example program, or “sketch”:  The user develops code in a simple text editor at the left, and the code is output to the canvas at the right.  
<br>
For this project, the p5.js Commenter is proposed as an add-on to the p5.js web editor.  This add-on serves to afford users a means to critique p5.js “sketches” and provide an instrument for understanding STEAM critique processes to inform future research.  P5.js Commenter contains two main features: inline commenting and overall commenting.  With inline commenting, users can highlight a line of code and provide textual comments, as shown in Figure 2.  This functionality is similar to commenting in text editor software such as Microsoft Word or Google Docs.  With this functionality, users can comment on their own or others’ code.
<br>
The overall commenting feature, by contrast, affords users a means to critique an entire p5.js sketch without specifically targeting a line of code.  Rather, a peer user provides critique in a larger-scale text entry area, as shown in Figure 3.  When the original creator of the p5.js sketch visits his or her work, he or she can see all overall comments given by peers.  This functionality is similar to that found in Padlet, an educational software used for commenting on user-uploaded multimedia (Padlet, n.d.). 
<br>

<h2>Findings<h2>
This section describes the design process that led to the design functionality as described.  P5.js Commenter was iteratively designed over the course of a single semester of a PhD program at a public research university in the northeastern United States.  Academic faculty from media, learning sciences, and visual arts education provided feedback that served to inform this software design.  This feedback was largely generated from formal interviews with academic faculty, a formal in-class design critique, and a pilot user experience study.  
<br>
The p5.js Commenter prototype used during these feedback sessions was bound in an example STEAM project case.  The project featured a mandala whose visual characteristics were informed by real-time weather data of a given user-inputted city, and this data was programmatically scraped from an online weather database.  The mandala’s formal elements would change according to regularly-updating weather data, as seen in Figure 4: If a user selected a city that was cold and windy, for example, the mandala would exhibit a cool color palette with shades of blue and purple, and shapes radiating from the mandala’s center would become longer to represent high wind speeds.
The choice to offer two options for commenting (overall vs. inline) was perhaps the largest design decision that informed this software add-on.

![Mandala Screenshot](https://github.com/dmawer13/p5.js-Commenter/blob/main/Mandala.png?raw=true)



