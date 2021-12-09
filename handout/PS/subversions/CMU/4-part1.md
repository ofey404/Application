Part 1: Experience and Background
=================================

## Main

"More is different." that's the very thing I understand after I switch from natural science to engineering. Developing Software is not a noun, instead, it's the process of creating a thing with people coming together. And craftsmanship is a meme, it would sink in when I was collaborating, observing and learning.

metrics-checker was a test infra I made in PingCAP QA team. Written in Golang, it became an effective part in the testing pipeline by its flexibility.

The idea came from my observation of our daily workflow, and I persuaded the whole QA team by extensibe research. With positive feedback of my mentor Shaowen, I studied optional solution: prometheus's AlertManager. Though it was not quite suitable, by reading its implementations, I thought building a stand alone metrics checker is viable. The I made a presentation, sold the idea to my colleagues, and own the task to deliver it. It turned out to be a handy tool, still maintained and upgraded even after I left.

From the success of metrics-checker, I learnt good design can do more with less. The checker is totally data driven: offload logic to yaml config file, while checker itself acts as an executor. The seperation of mechanism and strategy was reached by intensive requirement collection, study open-source code and redesign, while my mentor observed and judged my decision by constant code review.


...

Those are all valuable experience that can contribute to my goal of building an open-source version control system for artists.

## EndMain