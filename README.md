# Software Engineer

#### Technical Skills: C#, Python, JavaScript, HTML, SQL, C++, Java, C, .NET, Bootstrap, NodeJS, Razor Pages, AJAX, Agile & SCRUM, REST API, Jira, Azure, WSL, AWS, Bash, Data Analysis & Visualization, Cloud Computing, Docker, BDD, TDD, CICD 

## Education
- B.S., Computer Science | Western Oregon University (Sep 2019 - June 2023)
- AAOT | Chemeketa Community College ( January 2016 - June 2017)

## Projects
### Project Team++
[Repository](https://github.com/SWoinowsky/ProjectTeamPlus/tree/dev)

To keep it short and sweet, this project was intended to give gamers a nice website to be competitive with friends on Steam through achievement competitions, races, and the ability to receive concise update logs that would, and are, otherwise quite cumbersome to read through at times.

Developed as part of the Senior Sequence at Western Oregon University over the course of six 2-week sprints, in teams of four. The other three members of the team can be seen on the front page of the repo for the project linked above. The project was coded in C# using .NET, JavaScript, and AJAX. ChatGPT was used for several parts of the project, such as summarizing game update logs that can be difficult to read and understand at best. We applied concepts such as Agile and Scrum, as well as the REST API, and used Git and Jira to manage our code and development processes. The finished project was hosted on Azure and was presented during our university’s Academic Excellence Showcase in June 2023.

The project made extensive use of the Steam API, as well as some parts of the IGDB API. We struggled with getting the Steam API to cooperate, since the documentation is quite old and seems to seldomly get updated since its conception; if it ever has been updated that is. The use of IGDB was to fill a gap in the unmentioned usage limitations and issues we had with Steam, where we were continuously hitting their call limits and getting our API token muted for hours at a time. These limits are not well documented so we were never sure _exactly_ what the limits were. IGDB was very clear and enabled a large set of features to be possible that we originally thought were impossible early on.

![Project Picture 1](/assets/img/Project Team++ - 1.png)
![Project Picture 2](/assets/img/Project Team++ - 2.png)
![Project Picture 4](/assets/img/Project Team++ - 4.PNG)
![Project Picture 3](/assets/img/Project Team++ - 3.PNG)


### Random Name Selector
[Repository](https://github.com/JustinDavis7/my-code-playground/tree/main/Demos/Raffle%20C%23%20Desktop%20Application/Raffler)

This project was developed for a business where my father works as the General Manager. They had used various online name pickers over the years to facilitate things such as raffles, random screening, and numerical ordering of workers, but no single program provided all of the features they desired. They were also concerned about what kind of data was being harvested by these programs, but had no way to really know what was being taken each time they had to find a new one. Another problem was the reliability of these online solutions. They either started as free programs available online and then turned into paid programs, or were sporadically updated, breaking the whole system. Another issue with most of the programs that were used was the fact that they simply weren’t random. If the program was run four times on the same list of 50 people, you would see the same five names being picked every time.

The issue was brought up in a random chat I was having with my father one day, to which I scoffed at the randomness of said programs. I had wanted a reason/topic to develop a GUI style program since my schooling had never taught this, or provided classes on doing it, so I took it as a chance to learn a new skill - Windows Form Applications.

There was also a desire/requirement to have an easily printable result page, and I decided to tackle this with a dynamic HTML document that would be created and opened every time that the picker was run. It would overwrite the same HTML document in the files every time, so there was no worry of filling up a drive with countless documents.

![Raffler Picture 1](/assets/img/Raffler 1.png)
![Raffler Picture 2](/assets/img/Raffler 2.png)
