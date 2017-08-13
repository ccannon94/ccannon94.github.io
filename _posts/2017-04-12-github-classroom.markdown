---
layout: post
title:  "GitHub Classroom Part 1"
date:   2017-04-12 15:27:58 -0400
categories: jekyll tech ccannon github classroom git education
---
[GitHub Classroom](https://classroom.github.com) is a powerful, open source tool for education that I have been working for several months to implement at my university, the North Carolina Agricultural and Technical State University. This is the first of an ongoing series about how we are implementing GitHub Classroom at NC A&T, the challenges we face along the way, and the rewards that our students' reap from our efforts. I hope that this series can inspire students and faculty alike to make changes that will improve their educational experience, and share some data with those already in the process!

## The Idea

This past summer and fall, I completed my first internship as a computer engineering student. Honestly, I was amazed when I finally got to work on the code base and was introduced to this crazy command line application called "git". Suddenly, thanks to git and a solid online repository hosting service, almost every annoyance I with storing and organizing code was eliminated! I was absolutely appalled that this was something I had _never_ been taught as a student software developer.

Upon my return to school, I was offered a position as an undergraduate teaching assistant for the 2nd level Computer Science class, which included leading labs and grading "major programming assignments". This class is primarily focused on Java application development, which includes about 10 labs and 3 major programming assignments. The labs are completed under the supervision of a TA, on school workstations during a set time. Major programming assignments are large programs containing multiple classes, completed by students individually, and on their own time and machines. I saw these two forums as a great opportunity to implement GitFlow and introduce students to git best practices, as well as make it easier for me as a TA to provide them feedback on their code.

## The Plan

I evaluated a couple of repository hosting services, as the company I worked for did not use GitHub to manage our repos. However, I quickly came across GitHub Classroom and the decision was made. GitHub Classroom provides a simple interface through [organizations](https://github.com/blog/674-introducing-organizations) to create, manage, and few related repositories. It allows full management of the repositories by the owners of the parent organization, and allows private repositories to be created based on the organization's account (so only the organization must be approved by GitHub as educational). I now had a simple, private, and _free_ solution to implement git as a topic in class, and I approached my professor to lay out my plan.

I'm lucky to belong to a Computer Science department is eager to implement any changes that will benefit the students' education. My professor was interested to hear what my internship experience had taught me about software development, and how to bring our course up to par with current industry standards and best practices. He submitted an application for GitHub assistance that day, and we were approved within the week.

## The Presentation

Once I had approval, it was up to me to familiarize my class with git and GitHub before the first major programming assignment. I decided to introduce the students to source control through our weekly lab, beginning with [this slideshow](https://github.com/ccannon94/ccannon94.github.io/blob/ccannon94-addpost-github-classroom/_bin/GEEN%20165%20Git%20Presentation.pdf). I kept things brief, explaining to students exactly how I saw GitHub benefiting them both in the workplace and in class. For each feature that was explained, I tried to give two examples, one from the workplace and one about how they would use it in class. For example, while explaining the branching model, I first explained how the `master` branch of a project can be though of as the released code, or some similar level of completeness, that was readily running on devices. I explained `development` branches and `feature` branches as reasons developers may really benefit from branches at work. _Then_, I tried to make branches applicable to them **now** by explaining that for their major programs, `master` would be treated as their graded code, basically anything that is already 100. In the meantime, they would have `level` branches where they work towards implementing different features based on the assignment requirements. For example, `level-1` may be creating all data types needed for the project, without any real business logic yet, and so on. After my 15 minute lecture, we began using GitHub Classroom for our first assignment.

## The Projects

We had 3 labs before major programs began, and students used GitHub Desktop with GitHub classroom every lab. TA's answered any questions they had and reminded them regularly how these concepts would translate to their major programs. Students were provided a link to create their major program repository and begin coding! Conversations took place through pull requests and issues where student's were able to ask questions and receive feedback with context, which is a powerful tool for communication.

I will continue this series as I learn more about using GitHub Classroom and git as a teaching tool.

Have a question about GitHub in the classroom? Any other constructive feedback? Find me on Twitter [@ccannon94](twitter.com/ccannon94)!
