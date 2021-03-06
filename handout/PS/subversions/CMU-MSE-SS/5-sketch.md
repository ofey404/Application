Statement of Purpose
====================

Engineering 有两方面：和机器打交道，和人打交道

- case 1, 3 如何和人合作

过渡段，我不仅有如何 collaborate 的体会，在做技术决策方面也有体会。

- case 2, 如何做技术决策。软件工程的价值。

part 2：short term 和 long term goal 的关系。这个开一段。可以把第一段的抽出来。

. Technology should help people develop themselves and connect together.

最后两段应该讲一讲长期目标。

## Part 1: Experience and Background

"More is different." that's the very thing I understand after I switch from natural science to engineering. Developing software is not a noun; instead, it's the process of creating a thing with people coming together. And craftsmanship is a meme, it would sink in when I was collaborating, observing and learning.

metrics-checker was a test infra I made in PingCAP QA team, I delivered it supervised by my mentor. Written in Golang, it became an effective part of the testing pipeline by its flexibility. The idea came from observing our daily workflow, and I persuaded the whole QA team by extensive research. With positive feedback from my mentor Shaowen, I also studied an optional solution: prometheus's AlertManager. Though it was not quite suitable, I thought building a stand-alone metrics checker was viable by reading its implementations. Then after a presentation, I sold the idea to my colleagues, and owned the task to deliver it. It turned out to be a handy tool, still maintained and upgraded even after I left.

From the success of metrics-checker, I learnt good design could do more with less. By offloading logic to yaml config file, the checker itself acts as an executor, making it data-driven and easy to deploy. The separation of mechanism and strategy was reached by intensive requirement collection, study of open-source code and redesign, while my mentor observed and judged my decision by constant code review.

At DASLab, I engaged in research of multi-tenant KV, based on an 2014 CMU paper MICA. The codebase was C++ and DPDK, and I took the responsibility of the low-level programming part while my partner did the machine learning.

I applied an effective way to communicate: organizing our work with *GitHub*. We synced the progress, recorded technical decisions, and shared knowledge with wiki pages. It turned out to be a bonus when another graduated student joined, because there are always so many lucrative pages I can refer to - issues, pull requests, code review, and so on.

However, the most challenging issue I have ever encountered lay in this project: How to get things done on an existed imperfect project. With few documentation and tests, and tight time constraint, I faced a dilemma: an overhaul of test for reliable code was time-consuming, but if I made a quick and dirty prototype but failed, I couldn't afford the time loss. I tilted at windmills with all formal methods I know, made a painful decision of refactoring. But the refactor never really finished, because it was almost equal to totally changing the codebase's nature. Finally, I had to admit the delay in a strong result-oriented research project.

If I could say one thing to my past self, I would say, tech debt is not a prohibition but a tool, if used wisely. Also, if I knew more about software engineering then, I might come up with the "tracer bullets code" method. Write simple structure code to keep, rather than a disposable prototype, since immediate feedback is crucial When facing an unknown target. Real-life engineering is an art, and I'm longing to learn more in your program.

One more special experience to mention: By introducing version control to the computational physics lab, I found a real treasure chest even for non-CS creators. At first, I set a *Gitlab* instance for myself, but after I gave several lectures and wrote documentation, my colleague started to utilize it in various ways: managing code, sharing slides, or even writing a paper together. The *Gitlab* instance is actively used even after I left, and last month I gave a lecture about git to their newcomers at the supervisor's invitation. This experience made me feel it's possible to unleash the power for the artist community through an open-source version control system for illustrations, which will be discussed detailed in the coming part.

## Part 2: Purpose, Goals, and Achievements

My short-term goal is to build an open-source version control system for digital illustrations. In the long run, my goal is to be an open-source leader, focusing on disseminating knowledge. Technology should help people develop themselves and connect together. I hold this belief since my first exposure to programming - installing Linux with the help of friendly strangers on the web. In the age of remote work, it's time to apply free/open-source software insights to other non-CS areas. 

Digital illustration creation has adopted CS as a core methodology, but mass social collaboration is yet to come. Compared with all possible solutions of visual artists' remote collaboration, like shared storage workspace, open-source VCS would lead to a free and unified ecosystem. Artist communities could enjoy the merit of asynchronous and fine-grained cooperation, which are well tested. Besides, a company-neutral open-source project can be compatible with all competing file formats. It's for the good of all creators, not just for specific drawing software producers.

As Walter Benjamin said, tech could capture a place of its own among the artistic processes. With an accessible VCS, enthusiasts could study exactly how professionals work. Remote artists can work together, just like Michelangelo and his apprentices working on the same mural. What's more, VCS would go further beyond yet another productivity tool, even beyond an art academy without walls. "Given enough eyeballs, all innovations will come out," by unleashing the power of social collaboration, a healthy community could make unprecedented large-scale projects. This idea first hit me when I was shocked by the early death of Miura Kentaro, author of the famous manga *Berserk*. If there were a VCS, more posthumous or unfinished works would have a second life.

All those sound like yet another crazy idea, but I am used to taking up challenges and pushing myself to sink-or-swim. I bootstrap myself in programming, by taking two honours program courses, Data Structure and Operating System, while dealing with hardcore physics courses like Electrodynamics. To win my PingCAP intern, I took up their assignment with Golang, which I was unfamiliar with then, kept hacking in the convenience store under the dormitory for a week, and submitted the assignment ahead of time. What's more, I do not program for prestige and stability, because nobody chooses physics for those either. I program with love, and I want to do great at the risk of failing noisily.

CMU's "hands-on" teaching approach can build up the skill I need to lead a project: maturity in engineering and a deep understanding of technical, economic, and social issues. And CMU also won my respect by the mass public goods it created: I enjoyed Andy Pavlo's Advanced Database Systems during the pandemic; the quality and accessibility impressed me. Also, the OSSTA report (Open Source Software Toolkits for the Arts) by the Frank-Ratchye STUDIO was one of the most valuable pieces of documentation I read about art and technology.

And I bring my roadmap, if I have the honor to be accepted. Your software practicum is the perfect place to transform my idea into real-life product. Before that, I would engage in anti-disciplinary collaboration in Frank-Ratchye Studio early. Also, with a solid skillset to deliver in 17-\* courses, I would find my team member by working hand-in-hand with my fellows.  I would select [] as my elective course, to [].

I am an indie hacker, but I'm not Athena who was born full-grown - I started programming at the age of 18. The only thing I'm sure of is that I would be somebody, early or late, in the software industry. And I applied for your renowned MSE project to grow faster. I believe I will be a valuable asset to the project.