---
layout: archive
title: "Research Projects"
permalink: /research/
author_profile: true
redirect_from:
  - /research-project/
  - /research-prokects
---

## Active Projects
------

### *StudyBuddy*: A Chatbot Designing for College Freshman Study Habits
*Collaborators: Ishrat Ahmed, Arun Balajiee, Zak Risha, Jacob Biehl*<br/>
*University of Pittsburgh, School of Computing and Information*

<img align="right" width="450" height="650" src="/images/chatbot.png">

This is a course project for CS 3570 Advanced User Interface Seminar. 
In the transition to a new stage of learning, college freshmen are in specific need of developing their study habits and skills to achieve independent work in higher education. We designed a chatbot *StudyBuddy* to support freshman’s behavoiral change. We administered interviews with peer tutors and surveys freshmen at Pitt’s CS department, which we found students have difficulties managing their project and time. We built prototypes in both high fedality over Slack and low fedality as storyboards. To evaluate a chatbot's role in support learning, we conducted cognitive walkthrough studies with both senior and first-year CS students. We offer design guideline of the chatbot supporting learning behavioral change. 

### Rapport Management in Multi-session Interactions with a Social, Teachable Robot
*Collaborators: Nichola Lubold, Leah Friedman, Erin Walker*<br/>
*University of Pittsburgh, Facet lab*

<img align="right" width="450" height="650" src="/images/teachable-robot.jpg">

This is an independent research project advised by Dr. [Erin Walker](http://erinwalker.owlstown.com/). I studied middle school students’ rapport (a sense of harmony) with a robot who speaks socially called *Emma*. This is an exploratory study investigating 1) whether different individuals' reaction patterns are different from each other, 2) whether the same person behaves predictablly over multiple sessions, and 3) whether human rapport framwork could translated into human-robot interactions. Our rapport work is based on human rapport theories (e.g. Tickle-degnen and Rosentual's), but is operationalized using conversational strategies and linguistic cues from our data, i.e. the human-robot dialogue. 

### *Allo Alphabet*: Mobile Literacy System Improving French Literacy for Children's in West Africa
*Collaborators: Michael Madaio, Amy Ogan* <br/>
*Carnegie Mellon University, Human Computer Interaction Institute*

<img align="right" width="450" height="650" src="/images/AlloAlphabet.jpg">

This is my research intern work at Carnegie Mellon collaborated with [Michael Madaio](michaelmadaio.com/) and Dr. [Amy Ogan](https://www.amyogan.com/). Literacy has been linked to pervasive poverty, unemployment and illness, educational technologies can help mitigate low levels of childhood literacy. As part of a large project *Allo Alphabet* currently deployed their phase 2 study in rural Côte d’Ivoire, my responsibility includes monitoring the user's (children and their parents) system usage and analyzing children’s learning progress through the curriculum. More recently, I started look at learning curve analysis of childhood literacy in low resource contexts. 

## Past Projects 
------

### Social Media Attention Effectiveness for Fundraising among Nonprofit Organizations
*Collaborators: Rosta Farzan* <br/>
*University of Pittsburgh, Sustainable Social Computing lab*

<img align="right" width="450" height="650" src="/images/nonprofit.png">

This project is an independent study supervised by Dr. [Rosta Farzan](rosta-farzan.net/) during Spring 2019. I explored how nonprofit organizations’ use of social media for publicity and for gaining donations. I analyzed 414,312 Twitter posts of local non-profit organizations in Chile and their donations records. I found that a nonprofit being “heard” does not solely depend on how “loud” it speaks (i.e. the number of tweets), instead, these accounts also rely on “whom” they speak to and “where” they speak (i.e. Mentions “@” and Hashtags “#”). Using the findings from this research, nonprofit organizations can allocate their restricted capacity more effectively. 


{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
