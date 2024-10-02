+++
title = '[Java, JS, SQL] Retro Mobile Gaming Database'
date = 2024-04-26
tags = ['java', 'javascript', 'vuejs', 'postgres', 'sql']
description = 'RMGD'
draft = false
+++

# Retro Mobile Gaming Database
In Spring 2024, I worked as a software research assistant (RA) in the Networked Mobilities Lab (NML).
The NML was operated by Dr. Adriana De Souza e Silva in the College of Humanities and Social Sciences, at North Carolina State University.
While I was in the NML, I was one out of three software RAs.

The **Retro Mobile Gaming Database (RMGD)** was an NML project that sought to catalog mobile games from 1975 to 2008.
Users could search for games using multiple search criteria, filtering by title, year developed, type of game, and so on.
This could support researchers to find games and find correlations among historical types of mobile games.

Live site: [database.mglab.chass.ncsu.edu](https://database.mglab.chass.ncsu.edu/home)

The RMGD originated as a senior design project in the computer science department in Fall 2020.

## Technical stack and software engineering tools
The front end of the project was primarily written in VueJS.
The back end of the project was written in Java, using the Spring Boot framework.
It connected to a relational database, which was a PostgreSQL database.

The following tools were used to support development:
- Trello for issue management and feature requests
- GitHub Enterprise (NCSU) for version control
- npm for package management within the front end
- VS Code for writing and reviewing code

## Contributions
The majority of my contributions were on the front end, either bug fixes or UI enhancements.
This includes:
- Adding a "back" button from the Game card, so that the user can easily navigate back to their previous search
- Fixing the site search bar, so that it only returned results that were relevant to the NML
- Enhancing the "Forgot Password" form by using Vue SweetAlert2, so that the style matches that of the rest of the website
- Incorporating UI/UX fixes as provided by a team member in a Usability and Accessibility Report

Working in the lab was an interesting learning experience, since I had not worked in the Humanities and Social Sciences realm in a while.
The majority of the team had exposure to software development, and therefore were very realistic about what features could be implemented.
However, there was a sense that there was a "customer" and a "engineering team," which was different atmosphere from my previous course projects.
The work was also very self-driven; there was a large backlog of issues and feature requests, and so the team had to decide what to do on an autonomous basis.
