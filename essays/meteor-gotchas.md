---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---
<img class="ui medium right floated rounded image" src="../images/meteor.png">

<h1>Meteor Gotchas</h1>
<p>Over the passed a couple of weeks I have been using Meteor, an interesting way of forming JavaScript Apps. Although I was a skeptical about this I was also excited because I've heared many things about meteor in the past. As a newbie to Meteor I was not sure of what to expect, I dove right in and started on my first assignemnt. I saw a couple of screencasts/videos and read up on a couple of articles and it seemed like it was going to be a good time. Through out the first Assignment using Meteor, I realized that the building up and indexing through Intellij took a tremendous amount of time. I knew for this class this was going to be an issue. I had to come up with a way to over come this issue. I later discovered that I could make changes to the file while it was going through all of these things, which helped a lot beause I could start working ASAP.</p>

<p>Another problem I ran into while using Meteor was the Mongo database. Although I find it very cool that the database is in Meteor already, which is awesome because it isn't that hard to link the database since its already there, sometimes the record would not be added to the collection. I would set everything right or so I thought I did, and it still would not appear. I would check through the browsers console and through the terminal window and it would appear in a different collection. Once I saw this error I realized I was misplacing the target to a different place. I also realized I forgot to turn on ESLint where it would tell me that a function or a name was not being used in the page. As soon as I turned on ESLint and changed the target to the correct place the app was working properly.</p>

<p>Also, through out this discovery I did realize I would be inserting files into directories however, I would forget to import the files into the index.html which would obviously cause an issue when the app was trying to find the file. Once I imported the file I would try to physically click on a link on the app but the file would return a "Page not Found". This made me realize I forgot to route the actual page. Among other issues when it came to linking pages together I realized I needed to create a checklist in my head to remember to import the files that I created, route them to the correct location, created the right scheme for the intended page etc. Creating this checklist made it easier to narrow down the problem. Working on heavy directory projects, it was hard to pin point where the error was coming from when the page could not be found but now I now know where the problem could be coming from. </p>
