---
layout: essay
type: essay
title: The WODs will NOT get easier
date: 2020-09-03
labels:
  - Javascript
  - Learning
  - WOD
---

<img class="ui large left spaced image" src="../images/noscript.jpg">

*NoScript is an addon that blocks Javascript for privacy reasons.*

## A very privacy conscious person learning Javascript.

Sometimes I can browse over a hundred different websites a day, so I’m fully aware of the importance of Javascript in making the web interactive and dynamic versus those static HTML web pages we often used to see in the past. But as someone who's very privacy-minded I’m also aware of the controversy surrounding it due to its ability to track users and insert malicious code. Not to mention the most obnoxious ads are often loaded using Javascript. However, Javascript itself is good and is only bad when it's abused for wrongdoing. With this class I’ll be able to learn how to code in Javascript and use it in a proper manner. I already gained a lot of knowledge with regards to programming, specifically Java, thanks to ICS 111 and ICS 211. Although Java and Javascript aren’t related to one another, despite similar names, many concepts in Javascript were already familiar with me. This was a good thing since Javascript is a new language for me. Still, there were a couple of differences that I discovered within just the first two weeks that I found quite interesting.

## Javascript training wheels.

The site used to complete E06, freecodecamp.org, was incredibly helpful. The best thing about it was how it helped me refresh my coding skills because I confess that I didn't do much coding over the summer. I was able to go through much of the problems in the “Basic Javascript” with ease, although the conditional ternary operators which consisted the last few problems in that section were new to me. The ability to rewrite an if-else statement into a one line: 

```
condition ? statement-if-true : statement-if-false;
```

was something I don’t believe we covered in ICS 211. Even so, I’ll have to make the effort to use the ternary operator otherwise I’ll keep writing it as a traditional if-else statement. The ES6 problems were also very helpful. I was initially misled into thinking most variables in Javascript were “var” because of the initial problems in the previous section, but actually “var” should be avoided in favor of “let” or “const”. The ES6 problems also taught me about using arrow functions to write anonymous functions since many functions often don’t need to be named. I like how it condenses the code into a single line. There’s also template literals which I think will come in handy for solving fill in the blank problems since it simplifies complex strings. The last few problems involved using the Promise() function which was new to me. Nonetheless, while freeCodeCamp was a helpful introduction to Javascript I’ll have to go through it a couple times to let the content sink in, especially those in ES6. 

With arrow functions the following:
```
const myFunc = function() {
  const myVar = "value";
  return myVar;
}
```
becomes
```
const myFunc = () => "value";
```
*It's just so much more compact.*

## Slow and steady will not work. Gotta go fast.

I’m a slow coder and the WODs have made it clear that I need to improve myself in that aspect. I can eventually solve most problems given enough time, but when there’s a time limit to do it, then I’m working under pressure. I think the difficulty I have with solving coding problems is a combination trying to determine what algorithm I need to utilize and remembering how to write that in Javascript. Using the WOD E07: Project Euler Problem as an example, at first I attempted to make an empty array and with a for-loop I would count the numbers from 1 to 1000 and if they were divisible by 3 or 5, then I’d add them to the array. Afterwards, I would try to add the numbers in the array. The problem was that I didn’t know how to do that and I was stuck in the problem for a few minutes. Eventually, I looked at the video since I was stuck and that’s when I realized I was overcomplicating myself, there was no need for an array, I could just count just add it to a 

```
total += i; 
```

When I'm under pressure I find myself having a hard time finding the right approach. Despite that, with enough practice I believe I can solve the WODs quicker and with less pressure as I familiarize myself with Javascript. Before the first official WOD I participated in a bWOD and it really helped me for the real thing. In the bWOD we practiced going through a string with various symbols, “-”, “/”, “\\” which have different values and adding them to get the total distance and elevation. I was able to solve it and when the actual WOD came and asked  to make a Blackjack counter I managed to find a solution using a similar method, but this time with switches instead of an if-else. I am looking forward to learning more about Javascript so the WODs can become less stressful with time. 

```
case string[i] = 'K':
  value += 10;
  break
```
*King gives 10 points.*

The problems in the WODs will not get easier, but I know I will have an easier time solving them if I keep practicing my Javascript.
