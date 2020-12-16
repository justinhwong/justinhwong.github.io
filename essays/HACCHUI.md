---
layout: essay
type: essay
title: Hacc Hui 
# All dates must be YYYY-MM-DD format!
date: 2020-12-15
labels:
  - HaccHui Project
  - Learning
  - Javascript
---



## What is HACC-Hui?
  Hacc-Hui is a project we created to assist people in the HACC by helping individuals find teams and vice versa. Our Hacc-Hui website is connected 
  through an application called Slack, using a slackbot to communicate between the workspace and application. Users can sign up to the website through 
  the slackbot as well as receiving messages regarding team management whether it’s an invitation or a request to join. When they first login to the 
  website they are required to read through and accept a consent form. For participants of the HACC that are under 18 they are required to provide their 
  parent’s email address in which the parents can sign for their child. There are two groups, users and admins. Users can fill out a profile and create or 
  look for a team. There are also functionalities for teams such as dming team members, leaving a team, suggestions for tools and skills, and even filter 
  through participants. As an admin you had the ability to view all the teams, view all the participants, edit information about the teams, as well as edit 
  topics such as tools or challenges.


## My Milestone Functionality
<p align="center"><img class="ui medium right floated rounded image" src="../images/stressing.jpg"></p>
  The project was originally split up into 4 milestones. For the first milestone I was tasked to configure HACC. A page was to be created for admin use 
  in which a list of challenges, skills, and tools are shown. The lists can be edited, a new option added, or delete and option. This issue was worked on 
  by me and my team member Angeli. To configure the challenges, tools and skills you had to route to the database that held these respective tools and fetch 
  them respectively, creating an administrator component which would be pulled through by the administrator page.

  Here on this page you can view, add, edit, or delete challenges, skill or tools.
  Github Page Link: https://github.com/HACC-Hui/HACC-Hui/blob/master/app/imports/ui/components/administrator/ManageHaccWidget.jsx 
	For the second milestone I was tasked to work on creating a team finder page which showcases all the created teams, as well as the functionality to 
  sort through the list of teams by challenges, skills or tools. The best fit team page pulls from the a component widget that lists all the teams. The 
  functionality of sorting through these teams was however pulled from another group. The general functionality of the sorting was done through retrieving 
  all the developers from each team, finding all the teams through a team ID, and having an intersection through the teams topic ID (challenges, tools and 
  skills) respective to the list of topics. 

  This page lists all the teams and you can sort them by topic. (Alphabetical and best fit was added later on)
	The final milestone was a combination of milestones 3 and 4. The issues I worked on included working on a view team/team compliance page for an 
  administrative account with a team member, and frontend ui in which I improved the look and feel across all the pages. We created a function that would 
  look through all participants and check whether or not they fulfill the “isComplaint” requirement from the participant collection. Then we created 
  functions that acted upon that information, and showcases either “Team is compliant” or “Team is not compliant”. Compliance is shown when you first 
  create an account, and if a member has not accepted it, or a participant who is under 18 and have not had their parents accept it on their behalf, every 
  team they are on is in non compliance. For the overall page to showcase the teams, we mapped through the teams, their challenges, members, info, and an 
  edit button to edit info about the team. As for the look of the website, I changed the help page to be more compact, made pages fit an overall theme of 
  the website by making all pages the same color, the same style of div, padding, navbar, and backgrounds.

  Here you can view all the teams that have been created and whether or not the team is compliant.

  Help page became more like other pages and fit two questions per row instead of one.
