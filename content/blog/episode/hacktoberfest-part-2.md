---
title: Hacktoberfest Part 2
date: "2019-10-10"
audio: https://pinecast.com/listen/28b2e37e-8bd2-4844-b1c0-e8d9b70294ea.mp3
slug: "hacktoberfest-part-2"
description: "October means it's time for Hacktoberfest. We're talking with Shannon Crabill about what open source is, how to get involved with Hacktoberfest, and tips & tricks for maintaining open source projects."
episode: "015"
length: "20:34"
draft: false
---

## Sponsors

Shout out to our sponsors for supporting the LadyBug Podcast!

<p><a class="image-link" target="_blank" href="https://do.co/ladybug">
<img src="../../assets/digitalocean.svg" alt="Digital Ocean Website">
</a>
</p>

## Show Notes

- **Who is Shannon?** - 1:17
- **What is open source?** - 4:19
- **How did you get involved in Hacktoberfest?** - 4:55
- **What is it like to maintain an open source project?** - 6:27
- **Tips && tricks for people wanting to work on maintaining an open source project** - 7:35
- **How to contribute to Hacktoberfest projects?** - 8:54
- **Advice for beginners getting started in open source** - 11:51
- **How do you find projects to contribute to?** - 13:09
- **Hard parts of open source** - 14:30
- **Best parts of open source** - 15:38
- **How to gain confidence to contribute** - 16:52
- **Advice to someone beginning their coding journey** - 18:06

## Resources

- [Shannon Crabill's Twitter](https://twitter.com/shannon_crabill)
- [Dev.to Platform](https://dev.to/)
- [Hacktoberfest Website](https://hacktoberfest.digitalocean.com/)
- [Hacktoberfest Twitter](https://twitter.com/hacktoberfest?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor)

## Help us out

- <a target="_blank" href="https://podcasts.apple.com/us/podcast/ladybug-podcast/id1469229625">Leave us a review on Apple Podcasts</a>
- <a target="_blank" href="https://link.chtbl.com/ladybugpodcast">Subscribe to our podcast</a>

## Transcript

Ali 0:00  
Today's episode we'll continue our conversation from Monday about Oktoberfest. will talk to Shannon Crable all about what open sources how to get involved with Oktoberfest and even some tips and tricks for maintaining projects. Let's get started.

Kelly 0:18  
Welcome to the Ladybug podcast. I'm Kelly.

Unknown Speaker 0:20  
I'm Allie. And I'm Emma. And we're debugging the tech industry.

Kelly 0:24  
Before we continue on, we want to give a quick shout out to a couple of our sponsors,

Ali 0:28  
Digital Ocean offers the simplest, most developer friendly cloud platform. It's optimized to make managing and scaling apps easy with an intuitive API, multiple storage options, integrated firewalls, load balancers and more. From predictable pricing to flexible configurations to World Class customer support, you'll get access to all the infrastructure services you need to grow. Plus digital oceans community provides over 2000 tutorials to help you stay up to date on the latest open source software, languages and frameworks get started on Digital Ocean for free with a free 15 dollar credit at do coast Ladybug. That's do dot CEO slash Ladybug, we're going to continue our conversation of October fest today. And we have Shannon on the line. So she introduced the audience to yourself, what are you all about?

Unknown Speaker 1:17  
So by day, I like to say that I am an email developer. So I work with marketers to help execute their email campaigns. So if you ever got an email saying, hey, do this or selling a product or update, you know, some information? Chances are there was an email developer behind that. And then sort of by night, I guess or in my own time, I'm doing a lot of front end stuff like Emerald and flat iron. I'm trying to learn new things with Ruby. And that's I guess that's in a nutshell, sort of what I am or what I'm doing a little bit of everything.

Kelly 1:49  
Cool. And so tell me a little bit more about the the email development. So I you know, I have a little bit of experience with the e commerce side. But how did you get into that? And like, Do you like it? Do you enjoy it?

Unknown Speaker 2:01  
Yeah, it's definitely interesting and challenging. I got into it a little bit by chance. I majored in graphic design in college, and I graduated, and people were like, so you do websites, I'm like, I guess so I learned to code on my own BMW three schools, Code School, that sort of thing. And then somehow, I think I had like a freelance or like a one off job was doing sort of admin work doing a little bit of website stuff. And my boss was like, let's try doing email marketing. I'm like, Sure, okay, let's give it a go. And that sort of turned into like email design, which was my first full time job where I was doing the design, and the slicing, and the coding and the testing. And then now I'm more of the, like, the designs already provided, but it I'm coding it, testing it, maybe adding stuff to make it responsive or accessible. And that's sort of the bulk of what email developments like,

Kelly 2:49  
that's awesome. And I know, we're supposed to be talking about Oktoberfest here, but I'm just email like, email development is really it's, it's interesting to me, because to be coding for emails feels like it's still like in the 90s. Yeah, very much as so do you. Have you seen any kind of like difference? Has it? Has it changed over time for you to you see, like, an upward movement in you know, we're actually like, future? I don't know what the word I'm looking for here. Yeah, like it's getting better for the future. Yeah, yes.

Unknown Speaker 3:17  
And no, it's a really exciting thing right now is like all dark mode. Like, I think outlook has a dark mode, your OS has a dark mode. And I think to some degree, we can target emails to work with that, or at least render well on dark mode, and then not dark mode. So that's really cool. At least we're where I've worked that sort of the issue with email is that like you have, you have the people with, like other iPhones that are checking their email, which supports a lot of the cooler things. And then you have the sort of like, I work in a corporate office, we have, you know, Outlook 2007 for my email, which maybe doesn't render some of the more interesting things like animated gifts, for example, don't render In some versions of Outlook. So it's sort of this like, you have to think of both extremes. So I think we are things are getting better in some ways. But you have to think about like the lowest common denominator to least that's the way I look at it.

Ali 4:06  
Wow, that's wild. I can't even imagine every time I've tried to write email, HTML, like, Oh, my God, this is, this is so wild to me.

Unknown Speaker 4:14  
Think of all the cool things, you know, with code and the web and just throw it all out.

Ali 4:19  
Know, the first time I tried to write HTML for an email, I was like, oh, like, I could just use CSS Grid. Right. Okay, so let's transition back to talking about Oktoberfest, because I'm really excited to hear your takes on that. So first, what is open source is our first question for you.

Unknown Speaker 4:40  
So open source, the way I like to look at it is open source is code that is made freely available to the public that you can contribute to or add to or modify, usually without like having to like buy a license necessarily.

Kelly 4:55  
Cool. And how did you get involved in Oktoberfest?

Unknown Speaker 4:59  
So I first got involved in October Fest, I think, in 2017. And I remember being like mid October, and I think I happen to see an ad for Oktoberfest, and I checked it out. I'm like, Oh, this is pretty cool. Open Source was something I've been wanting to get into. I wanted to do a little bit more with getting GitHub, but didn't really know how to jump in. And then I found out about Oktoberfest, where it's like, contribute to five public repos, you get stickers and a T shirt on like, Okay, this is this is my moment to give it a try. So that's how I got started with Oktoberfest, I did run into struggles as finding projects to sort of contribute to so I ended up making my own opening that up a little bit. And that's how like I first got started to accept packed over fist sort of everything at once. Wow.

Ali 5:40  
Oh, wow. That's awesome. So your first Oktoberfest, you started maintaining a project? That's wild?

Unknown Speaker 5:46  
Yeah, it was, like I said, I just struggled try to find things to contribute to I felt like even though I'm, I wouldn't say to myself, like a code beginner, I found out a lot of things that seemed like they were either very high level, like, Oh, I don't know that code language or that framework, or maybe the easier issues for either taken already down, or maybe it's not clear, but project was being actively like maintained. So realizing there wasn't a lot of stuff out there. And that other people probably felt similar ways. I just took like, as I was experimenting with JavaScript, and like loops, and like math. So I put my project on GitHub, and like, hey, people on Twitter, if you want to contribute, I have this thing. And it kind of blew up a little bit from there.

Ali 6:27  
Very cool. So what's it like to maintain an open source project?

Unknown Speaker 6:31  
So it's definitely really interesting for me at the time, like I didn't really expect anyone to contribute. So getting like more than zero pull request, or commits was like, well, this is not what I was expecting. But it's really cool. I definitely had to learn, I definitely had to learn how to like merge code, as I realized I'd never merge code other than my own into get repo. So it's like, how do I keep everything consistent? How do I resolve conflicts, conflicts? For a fun thing to do? If I broke something? How do I think fix it or roll it back? So for me, it was definitely a learning experience. But definitely pretty fun, too. I feel like I wouldn't have learned any of that stuff. In any other scenario.

Kelly 7:10  
That's Yeah, that's a really great opportunity to learn all that. Are you still maintaining that project?

Unknown Speaker 7:15  
Yeah, sort of, I tend to revive it every or at least for the past two years, I've revived every October 1, I plan to do the same thing this year. And as far as like the rest of the year, I don't really keep up with it, since it's about Oktoberfest and Halloween. But yeah, I would like to, I would like to have more stuff eventually. That's sort of like open throughout the year, at some point.

Kelly 7:35  
That's awesome. So for people who have never maintained a project before myself included, we you know, our podcast website is, is open source, but there's not really much maintaining going on there. Because it's really just the three of us who are working on it. What tips and tricks do you have for people who want to work on maintaining or like maintaining their project,

Unknown Speaker 7:54  
maintaining a project, I would say, have a plan in mind is that might be helpful. For me Sis, maintaining as part of sort of a, you know, after hours, like at home, not like a work thing, I had to sort of carve out the time to do it. And sometimes it does get overwhelming with like, I have, you know, so many commits, and I'm feel like I wasn't keeping up with it. So even having a plan to do like a little bit each day or to know that like, you know, I'm going to set up two hours on Saturday to get through these commits, or to update documentation or whatever the case may be, would be helpful for maintaining forest parks. There's a lot of good resources out there. Luckily, I know GitHub has one, I think it's open source dot guide or something like that. That's probably like the best, you know, set of information you can have about maintaining an open source project. I also think that having things like you're contributing document, your code of conduct is really important. And just setting expectations of what the project is what you're looking for, maybe not what you're looking at what you're not looking forward to, would help people help to guide people with what you're doing.

Ali 8:54  
Those are awesome tips and tricks. From a technical perspective, how do people connect to open source or more specifically Oktoberfest projects?

Unknown Speaker 9:03  
From a technical side? So you mean like pull request or just like sort of the mechanics of getting involved with Oktoberfest?

Unknown Speaker 9:09  
Yeah, totally.

Unknown Speaker 9:10  
Yeah, so hacks over fest think the main thing is you need to commit to a public repo that's on GitHub, so doesn't really matter if it's your project for open source or someone else's. And I think the main thing is, like, you know, has to be adding something not just like deleting white space for the sake of deleting white space. So I've done a few edits that have been titled fixes, or I think one of the first projects I worked on a little bit was like a student project. And they couldn't really open source the whole thing. But they're like, if you want to translate it from like German to English, you're welcome to do so even if you use Google Translate, or something like that. So I did some of that. And I think there was like one or two things where I found like, I happen to find a broken image like that I fixed and that was a way of contributing to open source.

Kelly 9:52  
Awesome. And what else have you contributed to like project wise? I know, it's been, you know, set you started in 2017. Here, so yeah, a lot of experience, I'm sure how,

Unknown Speaker 10:01  
Yeah, a little bit, don't do as much of it as I would like to. But I know there's a few one off things I've contributed to documentation to a cool project I found recently, I think it's called emoji screens calm where to add to it, all you have to do is create like a up to five emoji variation of like a movie or show or play. And you can add that to the repo. And I'm show up on the website, which is really neat. So I think I added a few for like, Sex in the City, and another favorite movie of mine. So that was pretty neat, which is, you know, open source documentation is really great. I might have done a few a few additions to Free Code Camp too. I think I've been eyeing them, but sort of little things here and there, whatever I can find that needs

Unknown Speaker 10:41  
a little bit help.

Kelly 10:42  
I think it's really cool though. Because, you know, when people think of contributing to open source, they always think of the these, like, make some kind of really significant impact. Yeah, project. And there are all these little things that you can do just to kind of like get your toes in the water and, you know, see what it's like. And, and I think like that first project, you mentioned, like the emerging screens, just sent, it sounds so much fun.

Unknown Speaker 11:02  
Yeah, exactly. I think that's, at least for me, like the first like, public commits are the hardest ones. Because I I definitely had moments of I had heard maybe people having bad experiences, or like, what if they're mean to me? What if they rejected my pull request, but it was totally the opposite. But like that fear or just thinking, like feeling like I don't know what to contribute? Or maybe I'm not adding anything meaningful, can be a little paralyzing. So it's, I mean, it's easier said, than done to just jump in. But getting that first one or two done is probably the hardest. Totally see that. So you have experience with Oktoberfest and contributing to open source both as a maintainer and as a contributor. So do you have any advice for beginners getting started in open source on how to contribute or how to participate in a productive way? Sure, oh, participating, I would say try to find things not in your niche necessarily, but like, find ways to contribute using your skillset, like I had a realization that there are lots of open source projects out there. But what about for the people that want to contribute that aren't necessarily coders or programmers. And I think like updating documentation can be a really good way to sort of dive in whether it's the small things like fixing typos, or clarifying language, or adding links, or anything that's broken to like, maybe something's under documented. And you can add to that, I know, Free Code Camp, or at least they used to have like guides, where if you wanted to write like a short article or blurb about let's say, email development, you could do that. And that would become part of their wiki, their curriculum. So think definitely stick with try to look for things that are in your comfort level, that would make it easier, like, I'm not going to necessarily like, oh, here's this very in depth Ruby project that I'm not too familiar with dive in there. But maybe I'll start with like, Oh, this thing is a little bit under document, I can maybe add to it here.

Ali 12:52  
That's awesome. I contributed to the Free Code Camp prepare last year to I would definitely recommend that one for beginners, just because their whole ethos is about new developers. And so their repos definitely follow that mold as well. And they have a lot of great stuff for October. So definitely, highly recommend that one.

Kelly 13:09  
Yeah, that's a really great suggestion. So you said in, when you first got started, you had trouble finding some projects to contribute to, and that's what led you to, you know, starting your own. So do you have any advice for people now who are trying to find projects to contribute to have you found like resources that are, you know, useful for, for listing out projects that, you know, need some contributions?

Unknown Speaker 13:31  
Sure. So I know that Oktoberfest least in past years has had a anything that's tagged with, like, Oktoberfest sort of shows up on the site. You could also search and GitHub using Oktoberfest tags, or, you know, first timers or beginners only that sort of thing. I know Dev to usually or use used to post a list of open source projects that are looking for contributors. And I think even asking around is a good way to go about it. Like I think I've heard of, I think I heard of mo D screen via a tweet on Twitter. And that was a really cool one to add to. So definitely leverage your network on, you know, slack Twitter, Dev to you know, LinkedIn, wherever you are, that asking me do some little has something that they were looking for people to add to their project, or help the team project.

Ali 14:14  
I'm so excited to see what Dev does this year for how they're a sponsor. I just can't wait. We talked to them for the first part of this episode, and definitely got some insight, but I'm really excited to see how it plays out.

Unknown Speaker 14:29  
Yeah, exactly.

Ali 14:30  
Yeah. So it sounds like there are a lot of great parts of open source are contributing and maintaining open source. But what are some of the more difficult parts of maintaining or project?

Unknown Speaker 14:40  
Oh, that's a good one. I think for me, it was definitely time. Having like, for me, like I said, For me maintaining this project was, you know, after work after the dogs had been out after dinner type thing. So I felt like I was very limited on the time that I could contribute, even though I wanted to spend time towards it. So finding a balance of like, you know, maybe I should sleep or maybe I should do a few more pull request. That was a barrier. For me, I think also, to some level, like knowing where to start, I put my project out there sort of like if anyone contributes cool, I wasn't really expecting anything. And then to realize like, this is getting overwhelming and sort of a good way, like a good problem to have people were adding to it. But I did see, I did see, you know, duplicate request, for example, and how can I fix that? Like, what do I do with documentation? If I run into a bug? What do I do? So I think time and just like, the basic book of how do I manage something that has more than one person involved was a barrier for me at least.

Kelly 15:38  
So we just talked about the hard parts, what are the best parts? Let's talk positive here. Now.

Unknown Speaker 15:44  
Yeah, the best part about maintaining an open source project or just open source in general,

Kelly 15:50  
let's go maintaining an open source project. Okay,

Unknown Speaker 15:52  
so maintaining, I would say is seeing the really cool thing least with my product that people decided to add my project, just to put it out there, we should have a countdown timer to Halloween. And if people wanted to add something to it, they were pretty much welcome to do whatever they want it to so got a little bit insane, I loved it. And seeing what people added, like things that I didn't even suggest were really cool. In the first year, someone added these, like bats that were like auto generate and sort of fly across the page, which was really cool, I wouldn't have thought about it. And I thought it was really neat. So seeing what people would add, what people would come up with was fun, in general, with open source and sort of talking about this project is here. And people think like, Oh, I never thought to do that you've inspired me to try something or to put a project out there, or this is what I'm thinking of doing. I think I'll go ahead and do that now. And for me, that's the really rewarding part of open source or just this project or just, you know, talking to people to say like, Hey, you don't have to be like, you know, 10 x developer to have an open source project, you can just be anyone and have an idea and go with it.

Ali 16:52  
Awesome. That's really, really great insight. So one thing that I know a lot of people struggle with, I think myself included, is having the confidence to put your code out there into the world and also to contribute to these projects. I know that open source has a rocky history of inclusion and being kind to people. And so do you have any advice for having just the confidence to start contributing? Because I know a lot of people do struggle with that. Yeah,

Unknown Speaker 17:20  
exactly. I thought the same thing to that, you know, what if someone's mean, what if I did something wrong? What if I miss a crucial bit of information? I would say definitely to help with their confidence is read through their documentation, read through the contributing guide, if they have one. And usually that will answer any questions about what they're looking for, or not looking for how to submit like an issue or pull request. So definitely arm yourself with that information if it exists. And I think might be easier said than done. But try to go into it with a an open mind. Like if if someone's a jerk on the internet, unfortunately, they're just going to be a jerk on the internet. And maybe there's nothing you can do to change that. Luckily, I haven't run into that too much. But you know, try to go from here. So for the information, repeated documentation, and if in doubt, you can ask questions, too.

Kelly 18:06  
I love that. So we have a lot of people who listen to our podcast who may just be getting started on their journey in development, whether they're, you know, first career second career third career 12 career doesn't matter. So what advice this is just kind of a closing question here. What advice would you give to somebody who's just getting started in code, like starting their coding career, whether it's, you know, contributing to open source or just career general advice? What do you have?

Unknown Speaker 18:33  
So like, if I had to do it over again, myself, I would say, to, in a weird way, like just do more things. Just put things out there. Like if it you know, I think with me, the first time I did Tac Toe progress, I didn't really think too much about like, you know, oh, what if I coated wrong? What if this is not the best? What if someone doesn't like it, I just, I'll just put it up there. Whatever happens happens. And being a little bit more comfortable with that might be beneficial. I think we talked about like, I know, I struggle with like completing projects. And like having showing the work that I can do, as opposed to focusing on like what I haven't learned yet or can't do. So I think putting your code out there more. If you refactor it in a year or come back in a year and what to add to it. That's great. like no one's in the perfect developer exists or like the best code exists at all. So you're going to learn you're going to grow, and that's fine. And also googling things is 100%. Okay, I think people think that they should know everything on the back of their hand. But that's definitely definitely not the case. like Google does simple things all the time. Same,

Ali 19:35  
same, for sure. Awesome. Well, thank you so much. This was awesome. We're going to link to your repo and some of the resources you talked about as well in the show notes. So definitely check those out there. Thank you again, so so much, and hope to see everybody contributing to October

Unknown Speaker 19:51  
fest. Yeah. Thank you both. Thank you so much.

Ali 19:54  
I hope this series of episodes has gotten you interested in October faster contributing to open source. If not, that's totally fine as well just wanted to give you some context for

Unknown Speaker 20:05  
what it is and how you can get involved. If you liked this episode, tweet about it will select one Twitter to win Ladybug stickers each week. If you want to hear someone join us on Ladybug podcast thought the nomination form on our website. We post new podcasts every Monday and sometimes those episodes like this on Thursdays to make sure to subscribe to be notified. Also leave a review. We love hearing your

Unknown Speaker 20:28  
thoughts

</div>
