Statement of Purpose
====================

## Part 1: Experience and Background

"More is different." that's the very thing I understand after I switch from natural science to engineering. Developing software is not a noun; instead, it's a verb phrase, composed with two factor: technology and people. And today my stories are about various collaboration and technical decisions.

In QA team of PingCAP, I sold the idea of metrics-checker to my colleagues by research and presentation, and delivered it with close collaboration of my mentor Shaowen. It was a test infra written in Golang, based on my observation that some metrics in TiDB can reveal test coverage. To prove it's beneficial and viable, I studied existed optional solution like prometheus's AlertManager, and made a presentation on daily stand-up. I own the task, and deliver it with intensive requirement collection, study open-source code, design and redesign, while my mentor observed and judged my decision by constant code review.

And the metrics-checker went far beyond my expectation by its flexibility, from which I learnt a good design can do more with less. By offloading logic to yaml config file, the checker itself acts as an executor, which made it data-driven and easy to deploy. Also, the separation of mechanism and strategy make it easy to be applied to other task. It turned out to be a handy tool, widely deployed in the test pipeline, and still maintained and upgraded even after I left.

By introducing version control to the computational physics lab, I found version control a real treasure chest even for non-CS creators. At first, I set a *Gitlab* instance for myself, but after I gave several lectures and wrote documentation, my colleague started to utilize it in various ways: managing code, sharing slides, or even writing a paper together. It's actively used even after I left, and last month I gave a lecture about git to their newcomers at the supervisor's invitation. This experience made me feel it's possible to unleash the power for the artist community through an open-source version control system for illustrations, which will be discussed detailed in part 2.

In DASLab, I still enriching my collaboration experience, but also encountered a most challanging technical decision. I develop multi-tenant KV with a doctral student, based on an 2014 CMU paper MICA written in C++ and DPDK.

My habit of organizing work with *GitHub* make communication effective. I took the responsibility of the low-level programming part while my partner did the machine learning. We synced progress, recorded technical decisions, and shared knowledge with wiki pages. It turned out to be a bonus when another graduated student joined, because there are always so many lucrative pages I can refer to - issues, pull requests, code review, and so on.

However, the most challenging issue I have ever encountered lay in this project: How to get things done over an imperfect project. With few documentation and tests, and tight time constraint, I faced a dilemma: an overhaul of test for reliable code was time-consuming, but if I made a quick and dirty prototype but failed, I couldn't afford the time loss. I tilted at windmills with all formal methods I know, made a painful decision of refactoring. But the refactor never really finished, because it was almost equal to totally changing the codebase's nature. Finally, I had to admit the delay in a strong result-oriented research project.

If I could say one thing to my past self, I would say, tech debt is not a prohibition but a tool, if used wisely. Also, if I knew more about software engineering then, I might come up with the "tracer bullets code" method. Write simple structure code to keep, rather than a disposable prototype, since immediate feedback is crucial When facing an unknown target. Real-life engineering is an art, and I'm longing to learn more in your program.
