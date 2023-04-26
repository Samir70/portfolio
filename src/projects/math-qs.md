---
title: "Math Qs"
summary: "I made this to help create specific types of questions for use in maths classes"
image: /images/Math-qs-example.png
imageAlt: "Screenshot of math-qs app"
tech:
  - "Vue.js"
  - "NodeJS"
  - "Firebase"
siteUrl: "https://math-qs.netlify.app/#/"
repoUrl: "https://github.com/Samir70/math-qs"
---

### Problem Solved

At Bucks college group, we liked to use revision questions from MathsBox in our starters. And we also used Bingo games to help break up the lessons from a string of worksheets.

But these came in predefined types of questions. I made this so that we could choose for ourselves which topics came up for the revision session. I then extended this to enable us to have bingo games on a list of topics we could choose.

I also added a feature whereby students who are stuck on a topic can click on a 'building blocks' icon to practise topics that are required for the tougher question.

### Technologies Used

The user interface is made in VueJS. I wrote the question generator in nodeJS -- it is a seperate module, so it can be used with other javaScript projects.

Authentication and saving of data is acheived with Firebase.

### Challenges Faced

Maintaining code and processing large amounts of data -- although this wasn't part of the initial brief, I have tried to adapt the project to assess student ability.

### Lessons Learned

Rather than trying to get one app to do everything, it would have been better to use the modular nature of it -- question generation and question display have their own npm packages -- to split out different functions to different apps.