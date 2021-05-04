# p5.js-Commenter 

## Welcome! 👋🏼

<strong>This Readme serves as a project documentation for _p5.js Commenter_, a proposed add-on for the _p5.js web editor_.  This project was developed to fulfull a course requirement for my PhD program in Learning Sciences.  Informed by research in STEAM education and transdisciplinary learning, this add-on affords p5.js creators a means to critique personal and peers' works.</strong>

<br>

<h2>Introduction</h2>
As a burgeoning curriculum model, STEAM (Science, Technology, Engineering, Arts, and Mathematics) education has been gaining momentum over the past decade as educators attempt to integrate arts and design into STEM (Science, Technology, Engineering, and Mathematics) curriculum.  Emerging research has identified overlapping epistemic practices of STEM and the arts disciplines, one of which is critique (Bevan et al., 2019, Costantino, 2018).  Although critique practices in STEM and the arts share certain features related to their intended purpose, they ultimately maintain distinct properties that reflect their original disciplines.  Moreover, some have conjectured that in a transdisciplinary STEAM environment, critique might assume new forms as the practice transcends its disciplinary boundaries in a hybridized “third space” (Costantino, 2018).  Ultimately, there is an exciting opportunity in creating conditions for learners to critique within STEAM contexts.
<br>
I offer a software add-on for the open-source creative coding platform _p5.js web editor_ that affords users a means to critique work in STEAM contexts. With the _p5.js Commenter_ add-on, users can comment on their own or others’ work via _inline_ code commenting or _overall_ commenting. This system’s functionality was iteratively informed through feedback, collaboration, and design critique offered by academics in the learning sciences, media studies, and visual arts education fields.
<br>
<strong>The ability to conduct critique in STEAM contexts offers students rich transdisciplinary learning opportunities and will potentially illuminate further understanding of STEM and arts hybrid epistemic practices.</strong><br>

<br>

<h2>Design Overview</h2>
<br>
![Inline Commenting Screenshot](https://github.com/dmawer13/p5.js-Commenter/blob/main/Inline.png?raw=true)
<caption>Inline Commenting Screenshot</caption>
Alone, p5.js is an open-source Javascript library for creative coding.  A user can write code that produces multimedia content in an internet browser.  The p5.js web editor provides a browser-based creative coding environment for any user with internet access and a browser.
<br>
For this current project, the _p5.js Commenter_ is proposed as an add-on to the p5.js web editor.  This add-on serves to afford users a means to critique p5.js sketches and provide an instrument for understanding STEAM critique processes to inform future research. 
<br>
_P5.js Commenter_ contains two main features: inline commenting and overall commenting.  With inline commenting, users can highlight a line of code and provide textual comments, as shown in the above screenshot.  This functionality is similar to commenting in text editor software such as Microsoft Word or Google Docs.  With this functionality, users can comment on their own or others’ code.
<br>
The overall commenting feature, by contrast, affords users a means to critique an entire p5.js sketch without specifically targeting a line of code.  Rather, a peer user provides critique in a larger-scale text entry area.  When the original creator of the p5.js sketch visits his or her work, he or she can see all overall comments given by peers.  This functionality is similar to that found in Padlet, an educational software used for commenting on user-uploaded multimedia (Padlet, n.d.). 
<br>
![Overall Commenting Screenshot](https://github.com/dmawer13/p5.js-Commenter/blob/main/Overall.png?raw=true)
<br>
<h2>Findings</h2>
  
P5.js Commenter was iteratively designed over the course of a single semester of a PhD program at a public research university in the northeastern United States.  Academic faculty from media, learning sciences, and visual arts education provided feedback that served to inform this software design.  This feedback was largely generated from formal interviews with academic faculty, a formal in-class design critique, and a pilot user experience study.  
<br>
The p5.js Commenter prototype used during these feedback sessions was bound in an example STEAM project case.  The project featured a mandala whose visual characteristics were informed by real-time weather data of a given user-inputted city, and this data was programmatically scraped from an online weather database.  The mandala’s formal elements would change according to regularly-updating weather data, as shown in the screenshot below. If a user selected a city that was cold and windy, for example, the mandala would exhibit a cool color palette with shades of blue and purple, and shapes radiating from the mandala’s center would become longer to represent high wind speeds.
<br>
![Mandala Screenshot](https://github.com/dmawer13/p5.js-Commenter/blob/main/Mandala.png?raw=true)  
<br>
The choice to offer two options for commenting (overall vs. inline) was perhaps the largest design decision that informed this software add-on. Maintaining a distinction between overall and inline commenting functionality was warranted by academic peer and instructor feedback.  During these feedback sessions, it was conjectured that users would offer technical critiques using the inline commenting feature and artistic critiques using the overall commenting feature.  In a pilot user experience test that tasked users with critiquing the weather mandala sketch, users gravitated towards the inline commenting feature for technical comments.  The comments users entered into the inline commenting system contained suggestions for how to improve the highlighted code.  
<br>
By contrast, test users used the overall commenting feature for more versatile purposes.  Overall comments assumed both technical and artistic forms and were largely concerned with generalities.  For example, one user found the overall mandala code to be unorganized, and this feedback was expressed in a short text comment.  Another user felt that the shades of grey did not coordinate well with the rest of the color scheme, and this suggestion was typed out in the overall comments section.
<br>
<h2>Conclusion and Future Work</h2>
P5.js Commenter represents a software affordance intended to engage students in transdisciplinary critique.  The p5.js web editor environment is suited to STEAM learning, serving as an open platform where users can combine technical knowledge with artistic skills to create meaningful STEAM work.
Ultimately, I plan to implement p5.js Commenter into STEAM education contexts to explore its critique affordance.  I plan on using the add-on to study whether the critique products and processes engaged by students are considered STEM critique, arts critique, or a hybrid of the two.  In the future, I may design more critique functionality that is attached to the p5.js “sketch” window, where users can provide spatial and temporal comments that target specific areas of a piece.  





