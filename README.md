## Evan Chance (@echance)

I am a Software engineer with extensive experience working on Agile teams using multiple languages and libraries, bringing excellent development and debugging capabilities, creative problem-solving skills, and dedication to continuous learning and self-improvement.

This is my personal GitHub used to create projects in order to enhance my coding abilities, learn new technologies, and have some fun. I have worked as a professional
developer since 2015 and have worked primarily as a backend developer with some front end experience using Java (Hibernate, Spring Framework, JUnit, JSP) 
and JavaScript (JQuery, Ajax, Angular, Node.js, React), working mainly with MySQL and MongoDB databases.

Currently, my main personal projects will have a reference to "eurovision". This is an idea inspired by a recent tradition that 5 of my friends 
and myself came up with to celebrate the annual Eurovision Song Contest (ESC). Before the contest every year, we get together and have a draft to pick the countries
we think will win the contest. The goal of my "eurofriends" projects is to gather historic ESC data from https://eurovision.tv/ 
into a MongoDB database and build a web application that can assist and keep track of our draft picks, organize historic data from previous years with points
and rankings, and add customizable visualized data using ESC results going back until 1956.

### euro-web-scraper

The first step of the process was to gather data from https://eurovision.tv/. The official Eurovision Song Contest site contains data from every ESC event,
including participants, scores, lyrics, youtube links, etc. The scraper was a quick exploration using Python and Selenium to navigate the site and organize
the data into a JSON file that could be imported to MongoDB. Improvements could be made to combine all scraper iterations into one application, but making
a working data gathering tool was the main priority so that I could start building the application.

### eurofriends

This is the backend portion of the application built in Node.js, Express, and Mongoose which serves the data from MongoDB to the front end.

### eurofriends-react (Coming soon)

The frontend is built in React and will have a rest service to retrieve data from the "eurofriends" backend.
