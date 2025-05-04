+++
date = '2025-05-02T20:23:20+03:00'
title = 'Software Construction and System Administration'
+++

Welcome back to another week of Computer Science learning journey. In this post I will be talking about the two courses that I am currently taking, those are:

- MIT 6.031: Software Construction
- UCB Sysadmin DeCal

Which are, indeed, great courses for Software engineering and Linux or System Administration.

## Contents

- [Software Construction](#software-construction)
- [Sysadmin DeCal](#sysadmin-decal)

## Software Construction

This is MIT 6.031: Software Construction, particularly spring 2021, because the newer versions adopt TypeScript instead of Java.

Have you ever written some code then asked yourself: is there a better, more clever way to write this code? you probably have, and actually yes, sometimes there is some *designing* decisions that makes our code better. But what do we mean by **Better code**?

The goal of this course is to learn how to write high quality code, and what is meant by high quality is to meet the following three targets:

- Safe from bugs: Correctness now and defensiveness in the future.
- Easy to understand: The code has to communicate to future programmers, including you.
- Ready for change: Software always changes. Some designs make it easy to make changes; others require throwing away and rewriting a lot of code.

Every principle taught in this course will aim to achieve one of these three criteria, if not all of them, and *reshape* your thinking and coding process to meet high quality standards.

It contains 30 readings, 5 problem sets, and one project.

For this week learning, I covered the first 4 readings:

**Static Checking and Basic Java**

- Covers some basic Java

- One of Java's powerful features being a *statically typed language* which saves us from a ton of bugs.

- Static checking, dynamic checking, no checking, the faster your program fails for a bug, the better it is.

- Mutability and Immutability through *constants* and some other Java constructs like *Strings*

**Testing**

This topic was quite new to me, I have heard about testing before, and saw some unit testing on [codewars](https://www.codewars.com/), but this is the first time understanding testing.

This reading introduce us to *Test-First programming*, which emphasize that you test small units (methods) of you program (unit testing), test often so you don't let things pile up, and that you test before you even write your code **(Black-box Testing)**, just by looking at the *spec* or specification of your method (shall talk about specification in next week's post after finishing the [Specification](https://web.mit.edu/6.031/www/sp21/classes/06-specifications/) reading), and test after you write your code depending on your implementation **(Glass-box Testing)**.

The toughest part was the talk about **Partitioning** the input space into domains, but it was quite natural, to think about different aspects about how to test cases that covers, not all the possible cases because that's quite impossible, but covers main domains of inputs.

From just the first few readings I can see how this course is promising, that it's going to build a good *Software Engineer* mentality.

Follow my progress in this course through my [github repo](https://github.com/HsHs-dev/MIT-Software-Construction-6.031)

## Sysadmin DeCal

I had this old laptop that is working with a fridge processor, but I had no other choice so I worked with it, then it reached a point that it takes about 3 minutes to open *Chrome* so I couldn't take it no more, but I couldn't afford a new one at that time so I thought out of the box, instead of changing the hardware why don't I change the software? So I erased *Windows 10* and set up *Linux Mint*.

After 2 years of using Linux as my main operating system I have to say that a programmer shouldn't use Windows for development unless he is writing native windows applications.

```bash
sudo apt install your-dreams
```

Sysadmin DeCal course aims to get you started with *system administration* concepts like Linux, bash or the shell, packages, processes and services.. etc

The best thing about this course is the labs, it uses a hands-on approach which really teach you the concepts, I have done the first 4 labs and the version control lab and I really found a huge value.

- History of UNIX, and how elegant the unix system philosophy is.

- Core Shell Scripting lab made me write a real Bash-script which taught me a ton about bash, and how much its syntax sucks.

- Packages and the anatomy of packages in Linux.

- Services and `systemd` tools and how automated things can go.

Follow my progress in this course through my [github repo](https://github.com/HsHs-dev/SysadminDeCal)

***

I really appreciate [csdiy](https://csdiy.wiki/en/) for recommending those two courses which hold a tremendous value within.

I can see that my learning path is kinda vague so I will write a post explaining what topics that I am going to cover and the next courses that I will be taking.

I will attempt my best to include much more details about the topics that I study by taking notes and rewrite the concepts in my own words and explain what I understood.

That's for this week, wish me luck.

See you in the next one <3