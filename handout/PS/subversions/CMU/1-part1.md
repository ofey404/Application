Part 1: Experience and Background
=================================

Team oriented development experiences.

- Nature of project
- Technologies involved
- Engineer in team
- Role and responsibilities

The most challenging issue in any project you have been involved with.

Optional:

- What activities did you initiate, and how?
- ... did you support and how?
- Where did the project succeed?
- Where did it fail, what did you learn, what would you do differently and how?

## Main

metrics-checker was a test infra I made in PingCAP QA team. Written in Golang, initially used to monitor test coverage by collecting metrics in TiDB, then became an effective part in the testing pipeline by its flexibility.

I initiate the idea and persuaded the QA team that it's feasible and beneficial. Noticing some uncollected metrics in TiDB can reveal test coverage, I dicussed with my mentor Shaowen about utilizing it. With positive feedback, I studied and found prometheus's AlertManager did not fit our need well. But after I read AlartManger's implementation, building a metrics checker become more viable to me. Thanks to extensive study, I made a presentation to sold the idea to my colleagues, and own the task of delivering it.

I collected requirements, designed it and push it forward, while my mentor observed and judged my decision by constant code review. The best part of the metrics-checker is its data-driven design: the logic of checking are expressions stored in yaml file, based on PromQL, and the checker itself acts as an executor. By seperating the mechanism and strategy, it can do more with less, and is easy to maintain and deploy. After all, it's good to hear it still  acts as a handy tool, well beyond my expetation.



The most challanging issue I faced


## EndMain

The metrics-checker goes far beyond my expectation, it was maintained and widely used even after I left. I think I did a right thing: use data-driven programming. The metrics-checker was written in Golang, and accepting yaml config files. It execute expressions defined in yaml file, which leads to flexibility, since the program itself would be built into a container image file, it's important to seperate mechanism and strategy. 

### Metrics checker project

- The first project I engage in the whole life cycle and deployed in production. I raise the idea, take the study, design, implementation and integration task. Formal method.
- It goes far beyond my expectation, for my flexible design.

- Requirement: In evaluation of GC test coverage, some metrics could reveal test coverage and system status, if collected.

- Nature: A test infra, an internal tool deployed in k8s cluster
- Technology:
  - Use Golang, offload logic to yaml.
    - do more with less
    - The checker is to evaluate expression defined in yaml.
  - Deployed on k8s, use API of prometheus to get metrics
    - Studied prometheus's own Alartmanager, also the source code.
    - We need a simple tunable little thing then.
    - Integrated to existed pipeline
- Engineer:
  - I do the programming, my mentor and another infra developer review the code.
- Role and responsibilities:
  - I raise the idea and push it forward.

- Where did the project succeed?
  - Design it in a flexible way.
    - Expression evaluater.
    - Eric Raymond: Data driven programming 
  - I have a reliable mentor to observe and judge my desicion and progress.
- What activities did you initiate, and how?
  - Requirement collection, study, design... Mentioned above.
- What did you learn, what would you do differently and how?
  - Learnt how to be a mentor.
  - Leadership is about asking the right question. Not about getting the opportunities, but noticing that opportunities are there.

### ML on mica project

- My first software research project.
- Technical debt is a tool, I should know more about how to use it wisely.

- Nature of project: Experimental database
- Technology:
  - C++, DPDK
- Engineer:
  - A doctral student and me.
- Role and responsibilities
  - My colleague did the ML part and overall design, but I also discuss with her.
  - I did the low level job I prefer. To make it running. Low level job is exciting, and I was watching Andy Pavlo's advanced database systems.

- Where did the project delayed? What do you learn?
  - I don't try hard to own the project.
    - If you want to feel you own a process, help to implement it.
    - Or I tried to own but don't push it completely.
  - I tried to introduce standard process to the project, but don't find an ecnomic way to integrate it well with existing workflow.
    - Software research project is very different from company code.
    - As a research project, there is little time for me to do refactoring. We had to go with the technical debt.
  - Low level programming like DPDK is a brave new world for me, and I don't choose the best way to learn it. I should make use of DPDK's sample applications, read more of them and do experiment on them.
- What did you supported and how?
  - Contribute my ideas from my working experience:
    - Understand fast timestamp with rdtsc instruction.
    - Applied sampling method inspired by Gprof.

- Technical debt is a tool. it had consequences, but it can be powerful if used wisely and consciously.
- prioritize client value and/or project constraints such as delivery deadlines, over more technical implementation, and design considerations

### Challange

When the project is already not a best practice, how to:

- Get work done in time and spec?
- Fix it? Make it something further usable.
- When to 

The hands-on experience and technical mentorship in CMU-MSE-SS can answer my demand.