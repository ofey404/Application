一个野生程序员的世界
================

“在科学的殿堂中有许多深宅大院，有各种人住在其中，而他们住在这儿的动机也是形形色色、五花八门。”爱因斯坦说的是 1918 年的物理学界。今天的计算机编程作为一门显学，同样也慷慨地给了身怀各种理由的人一席之地。上一代人留给我们的，是一个充满了公共财富的计算机世界：信息技术的生活化赋予了充足的市场空间，网络上公开的资料便利了入门的时空条件，而自由/开源软件运动的成果使获得基础工具的经济门槛进一步降低。我就是受益于这些公共财富而成长起来的，兴趣使然的野生程序员，我从 linux 开始对编程感兴趣，用开源软件连接国际互联网、对抗防火长城的信息污染，这是我编程生涯中的珍贵回忆。

自由的软件，友好的用户社区，这些公共财富是为人所创造，也需要人去维护的。我希望成为维护者，不仅是因为我受过恩惠，更因为它们构成了我的生活的一部分。我还记得去年听说 OpenSSL 只有一个全职维护者时的震惊——基础软件就像世界树，几乎每个人都受益于此，但是只有一个园丁，而这个园丁很可能是过劳的。计算机短暂的历史几乎就是一部当代史，今日的用户隐私、可控计算、自由软件之争，不过是几十年来论题的自然延伸。技术的未来是由当下的人所塑造，正如今天计算机世界的自由精神是过去的人奋斗的产物，如果没有人在乎，有的东西就会淬灭。

我们今天的这个计算机世界，这个还残留着公共物品、残留着自由精神和对用户的尊重的计算机世界，并不是凭空得来，而是经过了无数人的不懈努力与合作，这些努力大到提出思想、写下文章、开发和维护自由/开源软件，小到停下来读一遍用户协议，使用一款自由/开源软件。

// FIXME: 感觉没到，上面这三段还写不出有深度的东西……不够具体可感很尴尬。先放一会儿再写

-----

我是一个野生程序员。野生意味着在我成长过程中受过许多人有形无形的帮助，从良好编制的文档和手册，网络上详细的问答、博文，还有使用的软件本身。

工程学科永恒的话题就是如何合作，如何互相帮助，因为工程就是『多者异也』。不同于理论科学，要造出哪怕一件有意义的工程造物需要的知识超乎一个人的头脑和生命可以容纳。Linux 有几百万行代码，据说一个人单单读 Microsoft Windows 的文件名，就需要几十年才能读完。电子计算机及其软件是人类历史上最复杂的工程造物，它们就像一座座看不见的城市，但是你并不需要知道城市中的每一个房间、每一个摆设才能找到你要去哪儿——要紧的是能够打开地图，阅读路标，心里对这座庞大的城市保存着基本的抽象概念。另外，参与工程的人数变多之后，人群本身也变成了一个极度复杂的系统。工程人员必须做的事，就是为这个天量的数据结构编制一个人脑可进入的索引，从技术文档、抽象屏障、合作规范到代码本身，都是在做这种安装路标一般的事情。（我的入门：适应看路标）

// 使看不见的城市成为城市，而不是米诺陶的迷宫。

而我是从这个索引的一角猛然跳入这个结构的。我第一次的编程经历，是 18 岁时看着一页文档自己安装 ubuntu 17.04 ，我发现自己非常适应概括问题-搜索-理解-实验的循环，就像一个个地辨认出路标，最终点亮的那一刻，我完全为之着迷了。那之后我逐渐开始尝试，去了硬件、然后是计算物理的实验室，开始上计算机系的课，找到了一份开源公司的工作，然后又回到软件的实验室。

// FIXME：上面这段其实把三件事情混在了一起——阐述我对工程的理解，合作的重要性，还有 My experience and background。应该把重心放在某一个，然后拆成某一段。现在有一个思路的断裂，文气没法顺下去了。

// 把这三个顺序倒一下？

- 作为野生程序员为学习计算机突破的障碍，作出的努力；
- 受到了分享，见证了合作，作出自己的事情
- 对合作的理解：工程

// FIXME：上面这段应该最后顺到我的价值观念和选择。试试把 PS0 的『专业精神』放进来？

------

野生也意味着我有一个家园，一个熟悉的街区、成长的角落。因此我想做底层软件，像操作系统、数据库，想为自由/开源的底层软件工作。就像《禅与摩托车维修艺术》中说，“科技的产物并非真正丑陋……真正的丑陋在于发明科技的人和他们制造的产品之间的关系。”当使用者也是创作者的时候，创作者会怀着爱去创造，这将会构建出良好的关系。我每天都使用操作系统、命令行软件、各种各样的包管理器，使用它们让我感到快乐，回忆过去和它们的相遇也让我感到快乐，因此我愿意为它们做一些什么。去年我很喜欢一个命令行速查的开源小工具，在使用的过程中发现它缺少一个功能，就花了一个晚上[把它加上了](https://github.com/knqyf263/pet/pull/161)，当你可以 hack 源代码，就会带来双倍的快乐。我想为自由/开源软件工作，并不是说我觉得只有无偿劳动才是唯一可取的，那是乌托邦的想法。我工作过，拿过工资，知道经济行为塑造了绝大部分的现实世界。自由软件强调[『社会的凝聚力，具体来说就是分享和协作的精神』](https://www.gnu.org/philosophy/open-source-misses-the-point.zh-cn.html)，而开源则找到了一种和经济行为共存共荣的生息之道，而这两群人至少共通的一点，就是 hacking 是快乐的，他们都爱着计算机编程这件事，他们都在创造公共物品。现在的计算机行业就像文艺复兴时的绘画，或者二十世纪上半叶的物理学，它的胸怀是如此宽广，足以容纳各种各样的人。这些人创造的公共物品被我所享受，我也愿意花我的时间去创造公共物品。如果这能成为一份工作，有人付我钱，那就再好不过了，如果没有，我也可以在计算机领域中找到一份『日间工作』，它让我有时间和空间去为这些公共物品做一些贡献。应用程序改变的往往是现实世界，不会让整个计算机世界变得更尊重用户或者更蔑视用户，而底层工具影响计算机世界本身（细化）。

// 短期和长期规划：在 2-4 年内为自由/开源软件工作，成为 linux contributer 或者相等程度的贡献者，在 7-8 年内能够胜任社区运营和开发的工作，就像 tison 一样。

// TODO: 基于这个规划，我有什么可以做的？现在？念硕士的过程中？

- 买书！看书！学习！
- 写代码！
- 参与开源项目！参与我能参与的任何事！

为什么我要去读 Master？和其他选项比，有什么理由？

和工作相比，我可能接不到我想做的工作。

什么是我想做的工作？

现在能够找到的工作不够核心。

什么是核心？

