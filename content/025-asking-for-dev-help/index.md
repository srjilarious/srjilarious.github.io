+++
date = 2025-11-26
title = "Asking for engineering help"

[taxonomies]
tags = ["management", "engineering"]
+++

As I've advanced in my career, I spend more and more time helping my team and others in adjacent teams with issues they're hitting.  I realized that many engineers don't know how to properly ask for help from other engineers, leading to frustration and wasting time.

<!--more-->

## The Problem

Engineers will often come to me with a generic problem for some software issue that lacks any context for me to be able to help them quickly.  This tends to happen with more junior software engineers or folks from other engineering disciplines that don't know what information they should be bringing to the table to start with or what steps they should try first for themselves before asking. 

What happens is something is not working, for whatever reason, and they go to another engineer with more experience and say "Thing X isn't working, can you fix it?"  Now the onus is on the one helping, who has probably been pulled out of concentrating on some other project, to try to discover the current state of things and see if they can help resolve the problem for the engineer that needs help.

For the sake of a concrete example, let's say Bob tried running some code from the project repo and goes to Alice, the tech lead of the team.  An expected output file is missing after running one of the tools in the repo, let's call the tool "baz".  Bob simply states: 

> I ran `baz` and the output file isn't there.

## A Checklist

It's a better use of everyone's time if Bob takes some time to give context and the current state of things to Alice.  Even better is to try a couple of basic troubleshooting steps and let Alice know what he's already tried.

Given the statement of "it's not working"  Alice will have to follow up and ask things like:

* [x] What are you trying to accomplish / Why are you running the tool?
* [x] How are you running the tool to get this error?
* [x] Do you have any logs or console output?
* [x] Is the problem reproducible?  Is it consistent or random?
* [x] Are you on a branch?  Can you reproduce it on `main`?
* [x] Is your dev environment up to date and are you using the same versions of tools as the rest of the team?
- [x] Are you sure the tool is running in the correct environement?
- [x] Have you tried any different arguments to see where the problem might stem from?
    - For example, there could be access rights issues with writing to a particular folder

Rather than Alice needing to walk through each of these, Bob should instead provide this information up front:

> Hi Alice, I'm running into an issue where the "baz" tool doesn't output the file I'm expecting.  I'm trying to help out team Y with project X, so I need to transform the `foo` into a `bar` with the `baz` tool.  I can reproduce it every time and I see the issue on `main` as well.  Here's how I'm running the tool: `....` and here's what I see on the console: `....`.  I checked and my dev environment look to be up to date and I see the same issue when I try running on Jim's system.  It looks like it's fine on CI, which I know is Linux, but Jim and I are both running Windows.

There may still be some follow up questions for the particular issue at hand, but this already gives a lot of context to Alice to be able to help more quickly.  

I've begun to use a similar set of questions for junior members I work with to use before asking someone else for help.