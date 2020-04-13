# Welcome to my Page
<br>
<br>

## Meeting Charleston

### 4-09-2020

Content pending.

## Chapter 9

### 4-07-2020

Content pending.

## Chapter 6

### 3-24-2020

Content pending.

## Chapter 5

### 3-12-2020

Content pending.

## Release early and often

### 3-05-2020

Content pending.

## Stupid or Solid?

### 2-20-2020

In this blog, I'm going to reflect on the differences between STUPID (Singleton, Tight Coupling, Untestability, Premature Optimization, Indescriptive Naming, Duplication) code and SOLID (Single Responsibility Principle, Open/Closed Principle, Liskov Subsitution Principle, Interface Segregation Principle, Dependency Inversion Principle). STUPID code focuses on ideas and actions that make code that is messy, undocumented and unscaleable, and SOLID code seeks to correct that using certain principles. There are a lot of things that are really good to know here, and great to keep in mind for anyone who is seeking a career field in software development. Avoiding premature optimization is one thing that I myself know that I need to keep in mind more in a lot of things, including coding. It's good to avoid wasting unnecessary time optimizing things that are bound to change, and this applies outside of coding in certain ways. For example, if I see a box of books in my room that's a messy, cluttered mess and I spend two hours making it all neat and organized, it will be wasted time, because I know my bookshelf is coming in tomorrow and I will have to take them all out and re-organize them based on the size and space allotted in the bookshelf anyways. Being able to test things is obviously something that goes beyond coding as well in any sort of product being sold. As I read through these principles laid out in the SOLID code, I realize quickly that a lot of it makes sense and can be applied outside of the realm of coding. As someone who isn't necessarily planning on coding for a living, this is what interests me the most. Regardless, in any coding I do in the future, I will certainly be keeping these principles and ideas in mind to ensure that I am writing "Solid" code.

Admittedly I fell behind this semester on these blogs, so I will be dropping the idea of updating with every blog entry what is going on with the group project. If you would like to see our team's deliverables and progress updates, you may visit our wiki here: https://github.com/CSCI-462-02-2020/Seawolves-Again-Redux/wiki

## What's Happening?

### 2-13-2020

The magazine I picked up to look at is from Communications of the ACM, edition 07/2014 Volume 57 No. 7 with the subtitle "Your Phone as Quake Detector". The article I'm choosing to discuss is titled "Automated QA Testing at Electronic Arts", and doesn't seem to be written by any particular person (with credit going to acmqueue at queue.acm.org). The article discusses the effectiveness of automated QA testing for the company Electronic Arts, as well as the challenges that are faced with such testing. Automated QA Testing is essentially writing scripts to run through your program to test and make sure that you receive the expected outcome. Scripts that do not receive the expected outcome are investigated and any bugs that led to that change in outcome are fixed. In this situation, this is applying to video games where bugs and exploits are famously present. This is why specific video games tend to have an entire team focused on game testing to spot these flaws and point them out to the development team. Games such as Fortnite are constantly evolving with weekly patches that fix and break new things on a constant basis, and since that game holds online tournaments with real prizes, the pressure to prevent and fix exploits is ever present and high. That's why developers like Electronic Arts have looked into automatic this process, as both a cost-saving measure and an efficient one.

In this article, Terry Coatta (a member of the ACM Queue board), Michael Donat (advocate for automation at EA), and Jafar Husain (lead software developer for Netflix) discuss automated QA testing in detail. Michael Donat specifically states that it is good to develop automation for QA testing so that the testers can actually focus on the fun experience of the game, rather than focusing primarily on what he calls "stability testing" which automation could handle more easily. After reading this article, I tried to do research on whether or not this became a common practice in game development (since the article is 6 years old and it seems that it was on the rise at the time) but I wasn't able to find much relevant information posted within the past four years, with the latest article I could find dating back to 2016. I would assume that this is still being used, but I was unable to find any hard statistics on it, and is something I'll need to dig deeper into (perhaps if I enter the gaming industry after I graduate, which is quite possible).

As an update on the project, we are in direct contact with a Mozilla employee now to see about getting assigned a project that fits our size and capabilities. And, as a personal note, this article starts on page 50. You're welcome, me.

## This bugs me

### 2-06-2020

I will be doing the following exercises from the <a href='https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/ch-Debugging_the_Code.html'>Teaching Open Source website</a>: 6.4, 6.5, 6.6, and 6.7.

6.4) The oldest bug I could find using Bugzilla is <a href='https://bugzilla.mozilla.org/show_bug.cgi?id=224571'>this</a> bug titled 'ldap_simple_bind_s() returns LDAP_PARAM_ERROR instead of LDAP_TIMEOUT', which hasn't been updated since 2006. This is a simple problem where an error reporting function returns the wrong value. However, it isn't clear when this would happen, and given how old this issue is, I'm unsure if any of these variables are still there, let alone where they would be in the code. Someone else asked for more information, and the reporter provided some more information but said he himself did not remember where it was. I may follow up later and see if I can trace what the issue could be or if it's still an issue.

6.5) I have already created an account as detailed in my previous reports.

6.6) I'll just reflect on the Bookmark bug I'm working on now. I was able to reproduce the bug quite simply by following the gif that was posted in the <a href='https://bugzilla.mozilla.org/show_bug.cgi?id=1398753'>thread</a> but the main issue here is whether or not this 'bug' is by design or not. One may hope that by removing a page bookmark, it removes that page from bookmarks entirely, even if it is bookmarked more than once, but another may have that same page in different folders that they use to check different things, and would want to keep one in the event that another is erased. In that sense, the way it works is probably better, but we have been able to narrow down what would need to change in order to get it working this way. Even if a fix is not approved, I will be looking into providing a plug-in which changes the behavior in such a way the reporter described it should work, in case anybody would prefer it that way.

6.7) As of writing this I'm not currently in a position to test bugs so it would be difficult to find anything to contribute to triaging bugs that isn't mostly useless, but it is something I plan to do extensively throughout the semester when searching for bugs, and something I have already done for the one described above, as well as the VM issue our team is tackling through contacting developers in the #developers IRC. I won't have time before this blog is due (my bad, poor time management) to be in such a position to do this exercise so I'll be forfeiting this one for now. Maybe I'll make it up in a later blog entry.

Our team has taken up the project of getting the Mozilla VM up and running again and we are still looking into how we can do that. Given it is feasible to perform within the semester it would be our big project with three main goals; to get it running again, to correct information on the wikipedia page for it, and to drum up support for it so that it does not become abandoned again once the semester is over. We have made some progress on getting it working again, but we need to do some more research on who was initially in charge of the previous (now broken) VM and how best to approach this given Mozilla's guidelines.

## Reflections on Open Source in Today's World

### 1-30-2020

Today, I will be discussing articles from opensource.com and responding to them. Afterwards, I'll follow up on my progress with the team project. Here are the article names and their links: <a href='https://opensource.com/article/19/9/found-linux-video-gaming'>How I ditched my old OS and jumped into Linux</a> & <a href='https://opensource.com/business/16/3/top-linux-shells'>Top 5 open source command shells for Linux</a>

Both articles are related to Linux, which seems appropriate to focus on as one of the most successful open source projects out there. Don Watkins' article, "How I ditched my old OS and jumped into Linux", actually focuses in on the experience of Jason Evangelho, who is a Forbes tech writer who discusses his experience switching from Windows to Linux. I found this article particularly interesting due to its partial focus on gaming on Linux, discussing the compatability software Proton and how its open source development has led to rapid optimization of gaming on Linux. I myself have frequently considered making the switch from Windows to Linux, and bar the convenience that Windows brings to me for running various school applications, I would have already made the switch on my laptop. I had run a dual boot setup on my desktop at home once before, but due to various small frustrations I decided to nuke it for the time being, but I plan on re-adding it again soon looking into the various distros available. I am particularly interested in the distros that were recommended in this article, so I will be checking those out soon. This article has definitely increased my interest in switching to Linux; perhaps after I graduate, I can ditch Windows entirely, maybe running it in VM for the various applications that won't work on Linux. It also inspires me to look into contributing to Linux open source development myself, given I develop the skills necessary and feel confident and inspired in the future.

The second article, "Top 5 open source command shells for Linux", had me interested because I hadn't heard of any of these open source command shells, and didn't even think about the benefits to choosing one over the other until reading this article. I had only heard of bash before out of the five discussed, and reading into the other two has me interested in trying them out sometime. Also, hearing that they are often packages with many distros helps me with the ease of access, allowing me to just jump right into it next time I decide to try Linux. I'll keep this article in mind.

As for progress on the Team Project, I've built Firefox on my local machine and I am in contact with a user on Bugzilla to get me started on a good first bug. I'll be looking around at other bugs to see if I can get my hands on anything else, but I'll be careful not to overextend so that I don't find myself responsible for more than I can handle within a decent amount of time. I'm also working on getting the Firefox development VM running on my Laptop so that I can do some work on the go without messing around too much with the full installation in my OS, instead focusing on keeping it all within a container in Virtual Box. It also gives me the opportunity to test my fixes on both Windows and Linux to further ensure consistency. I'm still looking for big projects to take on, but even if I don't find one, I'll be content spending the semester exploring the Mozilla ecosystem, getting assistance with bug fixes and perhaps dabbling into some code development and documentation when I want to try something new. If I ever get stuck, the IRC for Mozilla seems like a good place to go for assistance. I'm glad we picked a project with such active support, else we may have ended up stuck for days on issues we otherwise now can receive quick assistance on. Hopefully by the next journal I'll have made a meaningful contribution to the Mozilla community. 

## Reflections on FOSS

### 1-23-2020

I'm not sure if I'm only supposed to talk about The Cathedral and the Bazaar in this post, but I figured I'd blog about my team experience throughout the week as well. Progress with my team has been going very well. I'd worked with two of the members before in previous classes (and in the case of one, work environments) so we're getting along well and tossing ideas along nicely. I'd originally suggested that we go with Osu!, as it looked like a lot of fun and that there was plenty to do. Unfortunately, after trying to get in contact with them on their official Discord Server, nobody had replied after two attempts (following their rules), so I figured with that sort of response we wouldn't be able to get much done in the way of communication, and went with Mozilla instead. We're currently tossing around ideas for add-ons to make, and alternatively we can contribute to their addons-frontend repository.

Now, on the topic of The Cathedral and the Bazaar, I found it very interesting to read about the different types of approaches to open-source development. I'm not very familiar with open-source development (which is why what we'll be working on in this class will be a nice learning experience for me) but of what I know of open-source development, I always thought of it as more of the bazaar-style development process that is described here which is/was used to develop Linux. I always thought that was the only real way to go about open-source development, keeping everything out in the open and opening the development arms outwards towards anyone who wanted to take a crack at it. However, the cathedral-style of development also makes sense, and both seem to be successful in their own ways, but it's clear that the bazaar-style of development is taking the reins in popularity, and for good reason; it's highly effective and efficient. This exerpt is quite outdated by today's standards, being originally written in 1997 with revisions dating up to August 2000 (20 whole years ago), but given that I hadn't even thought of the existence of the cathedral-style development model beforehand gives me the impression that, from what I'm aware of open-source development, the bazaar-style has taken over even further, proving to be the more powerful approach. It makes me wonder if any other styles of open-source development have emerged along with newer technology. With Github getting its start in 2008, it surely seems to have changed a lot about how we handle open-source development, so perhaps it's ready for a new assessment (if one doesn't already exist).


## Introduction

### 1-12-2020

I will be blogging in this format on this page for the entire semester, adding new posts on top of this one in the same format. I believe this is the simplest way to do it while looking professional. I've utilized the Pages function of Github with the Midnight theme created by user 'mattgraham'. I followed these steps to set this site up, and they have been very useful: <a href='https://guides.github.com/features/pages/'>https://guides.github.com/features/pages/</a>

To introduce myself, I am Cory Goodwin. I will be graduating this semester, and I'm hoping to leave this class with an appreciable experience in programming. While I don't see myself pursuing software development as a full-time career, it will be good to dabble in it a bit. I wasn't supposed to take this course as a Computer Information Systems major, but due to issues outside of my control, all I can do is make the best of it. そして日本語を勉強中だから、日本の会社や日本にもいる会社に働けばいいだろうと思っています。 (Also, because I'm studying Japanese, I think I should work for a Japanese company, or a company that is also in Japan.) Those are the most important facts about me and I am both excited and stressed about the coming semester. I will be devoting a lot of energy to this course, and I hope that all of that energy provides opportunities to shine. One of my career goals is to be versatile so that I can work flexibly in my own time, so this class should prepare me for that if some software-engineering-focused needs were to arise in any position I find myself in.
