+++
date = 2026-04-06
title = "AI, LLMs and a step change in SW engineering"

[taxonomies]
tags = ["AI", "engineering"]
+++

A lot has been written about AI and LLMs for the last year and a half (probably much longer).  I mostly ignored AI and LLMs outside of chat clients on the web and found even with something like Cursor, that it wasn't quite up to what I needed to be that much more productive.  Around the beginning of 2026, I ended up trying Claude Code at work and was sort of blown away.  It has led to me using Claude on a lot of my own projects and getting through a huge backlog of annoying bugs or tasks that I had put off for a long time.

## How Agent Coding has Changed my Dev Process

The velocity change in my hobby development has been crazy.  I typically have 30 minutes to an hour a night to play around due to other responsibilities like parenting two amazing young boys, so I can kick off a task and come back and review and tweak things while making dinner - it's basically unlocked a bunch of time that I couldn't use before.

At the same time, a lot of bugs or tasks that I previously just wouldn't bother looking at, e.g. fixing stack trace printing on Windows for [testz](https://github.com/srjilarious/testz), I was able to get done.  Now, is the code perfect and how I would have written it?  No.  I wouldn't have written the code at all because I would always have had a lower hanging fruit to work on.

Is AI perfect?  Absolutely not.  It still can get into weird loops where it's not considering edge cases the way any human would.  It's not great with software architecture choices all the time.  But for tools, examples, handling boring boiler plate type work - it is really a game changer.

## Implications to the Wider Industry

I've been a professional software engineer for over twenty years at this point and AI coding agents, like Claude Code, are the single most dramatic step change I've witnessed.  I've seen many hype cycles over my career: virtualization, the cloud, containers, mobile development, front end java frameworks like React, etc.  

You'd see [r/programming](https://www.reddit.com/r/programming/) and [Hacker News](https://news.ycombinator.com/) filled with stories about the hype for some time, usually about a year and a half, and then it would start to die down.  The difference there was each of those applied to specific groups of developers: backend web, frontend web, mobile apps.  This change is more like going from assembly to having compilers and is affecting a much broader set of developers.

A big differences with that comparison though: going from everything in assembler to compilers ruling took years.  The massive use of coding agents has been over the last few months, from what I've seen.

Many folks are worried that now *real* software engineering will get lost to agent coding slop and that there will be huge loss of software jobs as individuals can be more productive.

It's hard to say with any certainty, but I think like with moving from assemblers to compilers, we'll see the amount of software created massively expand.  

The number of smaller companies that simply did without various automation tools is huge - they can now work to improve their business in a way that was not economically feasible before.  The engineering job of translating rough ideas into requirements that can actually be created will exist in any case.

There will be much more sloppily written code, but as I've heard other people mention - many problems that we solve with software don't need super elegant code and other areas definitely need human review.  

For example, [a tool for generating a documentation site for a zig project](https://github.com/srjilarious/zkdocs) - the software architecture is not so important, just that the output is what I want.  On the other hand, handling concurrency in an OS kernel - probably want a human to have verified all of the logic thoroughly.

I do believe in the short term we will see a massive downward pressure on software engineering salaries as companies see improved productivity.  I also think we will see a huge number of 10-20 person companies that will have the same output as older 100-200 person companies.  The lower communication overhead of a smaller team will allow product-first engineers to make progress far faster than larger organizations are able to.

## Conclusion

At the end of the day, it doesn't really matter what software engineers want our job to look like.  As I've said for a long time, in a professional context, our job is to provide business value and software is our tool.  If it is possible to create that value more quickly, that is going to become the way it is done - with all the warts and problems that brings with it.

I'm excited about this change, mostly.  It's sad to see a skill I've spent thirty years working on become far more commoditized over the course of a few short months - but this industry has always been one for people who can embrace change and learn new things.
