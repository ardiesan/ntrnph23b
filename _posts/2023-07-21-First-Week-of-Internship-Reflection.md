---
layout: post
title: "First Week of Internship: A Reflection"
author: mtrinidad
categories: 
- internship
image: assets/images/firstweek.jpeg
---
I understand the significance of having a good internship for shaping my future career. It is essential to have a meaningful internship to gain practical skills and insights in the IT industry. I am grateful for this opportunity and eager to make the most of it.

---
## Day 1: Article Reading

The first day was a rollercoaster of emotions, it was my first time going to the office and meeting the manager in person. During my first day, I was tasked to read "The Cathedral and the Bazaar" by Eric S. Raymond and the "How to Report Bugs Effectively" by Simon Tatham. I was then asked to write my learnings and reflection from the articles I read.

The Cathedral and the Bazaar taught me that If I want to be a great developer then I must learn how to be resourceful, good programmers know how to write code but great ones know what code to reuse or rewrite. If one wants to create software, it is good to look for similar existing software. I think this will make the development much faster, you just have to make it your base, maybe make it better, or add some features that are specific to your needs. 

How to Report Bugs Effectively, an article where the author shows us the ways and the 
proper procedures for reporting bugs in a software. This article implies that not a single programmer is perfect, everyone makes mistakes, even the great ones. When you report bugs, you can either show the developer the bug in person or show it to the developer through the Internet. Developers will not be able to address the problem if you provide little to no information about the bug, therefore, provide relevant information as much as possible, the more the better. You can tell the programmer exactly what you did like the exact buttons that you pressed, the exact inputs that you entered, etc. This way, it will be easier for the developer to diagnose the problem right away. The developers know their software more than you do like how doctors know our body more than we do, so be very honest about the information you provide because these are the primary basis for the problem diagnosis. 


---

## Day 2: Protecting Github commits, Docker

We talked about the articles I read the previous day and my insights on it. Then I was tasked to read an article written by my mentor himself, "Protect your Github Commits". Followed the instructions in the article and unfortunately, I missed a single step, my mentor pointed the specific step out to me. It was a good test for me because I'm an aspiring developer, so I should be attentive, especially to small details.
What do we mean by protecting GitHub commits? It verifies git commits by just signing it. So why should we sign our commits? Someone could know your email and they could make a commit in your project under your name and email with malicious intents, which might result in bad quality of your code. 
<br>
After the GitHub exercise, my mentor introduced me to Docker. I'm not new to the term, I've read things about it but honestly, at that point, I didn't know what is the purpose of Docker and why it is so important in the development stages. It took some time for me to process the things that my mentor discussed about Docker, I was overwhelmed. I did have time to learn more about it though. At first, I was confused as to what is the difference between docker images and docker containers. Docker images serves as a template or a snapshot of your working environment, it defines the container. On the other hand, docker containers are just runnable instances of images. You can also run several containers using only a single image. 

---
## Day 3: Markdown, Setting up Docker, Learning Docker through CLI

This day, I was tasked to learn Markdown, set up Docker on my machine, and learn it through the command line. I was new to Markdown, I learned that it is just a markup language for creating formatted text or creating documents like the one you are currently reading. After learning Markdown, I went ahead and set up Docker and Docker app. However, during the installation of the Docker app using Brew, I encountered a strange error. Luckily, I found a simple solution online, which helped me successfully install it in the end. 

I learned a few commands like:
- docker image ls -> returns list of all images
- docker container ls -> returns list of all containers
- docker ps -> returns list of all running containers
- docker start/stop/restart 
- docker rename
- docker rm
<br>

##### Why should we use Docker for our local projects? 
We can isolate our projects from each other when we containerize them. Then it will be very easy for us to manage those projects. Let's say project1 one and project2 utilizes MySQL but in different versions. By putting them in a container, we can avoid version conflicts and confusions.


---
## Day 4: Establishing connection from MySQL workbench to MySQL container

This day, I was tasked to establish a connection from the MySQL workbench to the MySQL container. I pulled a Docker image for MySQL and then started the MySQL container. Then I installed MySQL workbench. I didn't establish the connection right away, I keep getting the 'Unable to Connect' error. It took me some time to notice that I mistakenly configured the port number as I'm trying to establish the connection between the two. A very small detail that caused the error. Attention to detail is an essential factor in software development, without it, we will never be able to produce accurate work free of errors.  

---
## Day 5: Learning the basics of PHP, Setting up Ruby, Writing my first weekly reflection

My day started by learning basic PHP programming, which was exciting. Later, I set up Ruby in my machine. After setting up Ruby, I clone the Engineer's Log repository and ran it locally. Then I took some time reading the previous interns' entries and I observed how they structurized their reflections. Then I did my own reflection. While doing so, I got feedback from my mentor, who helped me improve my reflection by emphasizing the importance of providing clear statements and precision of words. 

A valuable lesson I learned today is to provide clear and precise statements. As a software developer, part of our job is to create and communicate clear statements. We need to be very precise with our words when working on a software development project. This is important because even a small mistake or uncertainty in our code or instructions can lead to errors in the software. So, we always aim to be as clear and accurate as possible in our work to ensure the software functions properly and meets the desired requirements.