---
layout: post
title: "Design Sprint: Stitch Tracker"
date: 2019-01-05
categories: design-sprint
---

 Whenever I start a new knitting or crochet pattern, the first thing I do is print it out so that I can cross off rows as I complete them. I recently had the frustrating experience of deciding to make a second hat right after completing the first, only to realize that my pattern was all scratched out and difficult to read, let alone scratch out again for the second hat. Why not have an app for this?

 <img src="/jaschiroo/images/sprints/stitch/splash.png"
      alt="Splash screen"
      style="max-width:50%;height:auto;border:1px solid black;" />

 As a recurring crafter, I am familiar with patterns that come as PDF files, websites and word documents, so the input method doesn't need to be complicated to grab the pattern.

 <img src="/jaschiroo/images/sprints/stitch/addpattern.png"
      alt="Add a pattern"
      style="max-width:50%;height:auto;border:1px solid black;" />

During import, ideally some text scraping will be used to get the pattern into the right shape. Rows are consistently labeled or numbered, and that provides the basic structure; repeat sections will usually contain the word "repeat" as a trigger.

An important consideration here is to allow some editing of the pattern within the app. Sections of knitting will have headers and there may be repeat sections missed by the import. To have a useful pattern, the user must be able to fix any errors easily.

<img src="/jaschiroo/images/sprints/stitch/pattern.png"
     alt="Knitting pattern"
     style="max-width:50%;height:auto;border:1px solid black;" />

Once the pattern is edited, the user can begin working. The basic actions available are checking off a row and counting a repeat.

<img src="/jaschiroo/images/sprints/stitch/completed.png"
     alt="Pattern with progress"
     style="max-width:50%;height:auto;border:1px solid black;" />

As rows are completed and the user checks them off, they are still available for view through a "see completed" menu, in case the user wants to double-check their work or go back.

Upon completion of the pattern, an option is available in the menu to reset the completed rows, in case the user is making duplicates of the pattern, such as socks, sleeves or a second hat for a friend.

<img src="/jaschiroo/images/sprints/stitch/menu.png"
     alt="App menu screen"
     style="max-width:50%;height:auto;border:1px solid black;" />
