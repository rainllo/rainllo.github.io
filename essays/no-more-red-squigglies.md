---
layout: essay
type: essay
title: No more red squigglies
date: 2020-09-24
labels:
  - Software Engineering
  - Javascript
  - Coding Standards
---

## Must use Windows

<img class="ui large left spaced image" src="../images/githubdesktop.jpg">

*Available for macOS and Windows but NOT Linux.*

Before I can talk about my experience with IntelliJ IDEA I need to discuss my problem in setting up the program. As stated in a [previous essay](https://rainllo.github.io/essays/excited-for-open-source.html) I've wanted to become more familiar with the UNIX environment which led to me switching to using Linux most of the time. For the most part it was no problem at all as most of the Javascript programming in class was done through JSFiddle, a browser based IDE. After our last WOD that was done on JSFiddle, I actually welcomed the news that we would be switching to IntelliJ. I thought it would be great to use a fully featured IDE, and best of all, it was *free* for students! Thankfully, IntelliJ was available on Linux. But just after I finished setting it up according to the configuration guide, I realized it would be no good as Github Desktop was not available on Linux. Since we'd have to use Github Desktop concurrent with IntelliJ to do Javascript programming from here on out, I had no choice but to switch to my Windows partition. Fortunately, it's not too much of a nuisance to switch between the two operating systems, still it would've been great if [Github Desktop was available on Linux](https://github.com/desktop/desktop/issues/1525). But enough of my mini-rant, now I can discuss my impressions with IntelliJ. 

## It loads pretty fast

Setting up IntelliJ itself was not much of a problem for myself. There was a fully detailed guide and a video to follow. The program itself loads very fast, less than ten seconds, and even before I disabled all the unnecessary plugins it was still plenty fast although I have my SSD to thank for that. I was also a bit concerned that since we'd have to do a bit more setting-up before programming on IntelliJ compared to JSFiddle, that it would take away time from solving the actual Javascript problems. In the end this became a non-concern because we could change the defaults for creating new projects and we could copy-paste the .eslint, sample.json, and .gitignore files between projects. As for my encounter with ESLint errors, I'm very glad that they're informative in explaining what's wrong, especially compared to JSFiddle. You can easily click the red exclamation in the upper right hand corner and it will list at the bottom all the errors ESLint is seeing with the code. Overall, the errors are described in mostly plain English and if there's any unfamiliar terminology, then it's just a [search away](https://eslint.org/). One thing that I really liked about ESLint was how it told me when to use 'const' rather than 'let'. Previously, I found myself in the bad habit of using 'let' to declare variables even if 'const' would've been better because I usually didn't encounter problems with the final outputs when using 'let'. My only other previous experience with coding standard tools on an IDE was Checkstyle for Eclipse, however, ESLint just seems to be way more in depth. 

<img class="ui large left spaced image" src="../images/eslinterrors.jpg">

*Begone, errors!*

## Keep getting familiar with Underscore

While I've found the transition from JSFiddle to IntelliJ a breeze, I sometimes still have difficulty with using Underscore. The beauty with using Underscore is that it allows you to create functions in a more compact way. Yet, I find myself having trouble in figuring out how to use the different functions in a way that it doesn't give me an error, undefined, or empty arrays when doing a console.log(). The practice and actual WODs often have hint's that recommend which Underscore functions to use which is great but a couple times I've had a bit of trouble passing the functions around to get my desired result. I'll have to keep reviewing algorithms to get better at doing this. For this experience I've found adhering to coding standards easy as they were mostly automated by ESLint, but I still need to practice using Underscore. 
