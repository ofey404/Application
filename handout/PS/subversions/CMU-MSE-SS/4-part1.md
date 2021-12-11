Part 1: Experience and Background
=================================

## Main

"More is different." that's the very thing I understand after I switch from natural science to engineering. Developing Software is not a noun, instead, it's the process of creating a thing with people coming together. And craftsmanship is a meme, it would sink in when I was collaborating, observing and learning.

metrics-checker was a test infra I made in PingCAP QA team, I deliver it supervised by my mentor. Written in Golang, it became an effective part in the testing pipeline by its flexibility.

The idea came from my observation of our daily workflow, and I persuaded the whole QA team by extensive research. With positive feedback of my mentor Shaowen, I studied optional solution: prometheus's AlertManager. Though it was not quite suitable, by reading its implementations, I thought building a stand alone metrics checker is viable. Then I made a presentation, sold the idea to my colleagues, and own the task to deliver it. It turned out to be a handy tool, still maintained and upgraded even after I left.

From the success of metrics-checker, I learnt good design can do more with less. By offloading logic to yaml config file, checker itself acts as an executor, which made it data-driven and could be deployed in a breeze. The seperation of mechanism and strategy was reached by intensive requirement collection, study open-source code and redesign, while my mentor observed and judged my decision by constant code review.

At DASLab, I engaged in research of multi-tanent KV, based on an 2014 CMU paper MICA. The codebase was C++ and DPDK, and I took responsibility of the low level programming part, while my partner did the machine learning.

I applied an effective way to communicate: organizing our work with *GitHub*. We synced the progress, recorded technical decision and shared knowledge with wiki page. It turned out to be a bonus when another graduated student joined, because there are always so many lucrative pages I can refer to - issues, pull requests, code review, and so on.

However, I faced probably the most challanging issue in my whole journey of development: How to collaborate with the absent original developer. The codebase came with few documentation and tests, even worse, several outdated package needed to be upgraded. I utilized formal ways like test framework to push the progress forward, and constantly exchange ideas of source code with my partner. When I develop new functionalities, I spent too much time to do it clean and maintainable. However, in tight time constraint, we should make shift with what was on hand. Finally, the project was still delayed to some extent.

If I could say one thing to my past self, I would told him tech debt is not a prohibition but a tool. Sooner or later, we would encounter imperfect project, but real life software engineering is an art of tradeoff between speed and maintainance. Research project is strong result-oriented, so I will getting ahead more agressively.

One more special project to mention: I introduced version control to computational physics lab I worked two years ago. To my surprise, it become a productivity tool even in non-CS descipline.

In the development of two-dimensional calculation pipeline with graduate student Bo and supervisor Mr. Zhang, I set up a *Gitlab* instance. First is for my own use, then I tried to introduce it to my colleagues. After I gave several lectures and wrote documentation, some started to manage code, some stored slides, notes, or even paper drafts. It is actively used even after I left, and last month I gave a lecture about git to their newcomers at the invitation of supervisor Mr. Zhang.

Version control is a real treasure chest for all kinds of creators, that's why I came up with the idea of building an open-source version control system for artists.

## EndMain