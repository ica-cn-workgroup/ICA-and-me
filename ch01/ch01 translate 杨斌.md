# 1. 引言
仪表，控制，自动化（ICA）是一项隐藏的技术。即使是在运行中，它也不会被察觉到。不过，在大部分水处理系统中，它无处不在。20世纪70年代早期，ICA就已经被世界水协（IWA），和它的前身们，包括国际水污染研究和控制协会（IAWPRC）和国际水质协会（IWAQ），认定是一项可以改善供水和污水处理系统运行，并能够同时满足出水质量和运行效率的重要技术。工业电脑和在线仪表的发展，这两个关键科技驱动力使得ICA成为可能。今天，ICA变得更加成熟，几乎所有供水和污水处理厂中都配备了计算机控制系统。

ICA包括在系统中生成和使用的所有信息。有了今天的计算机技术和仪表，我们理所当然地认为它能够获取大量的数据。然而，数据的丰富不同于信息的丰富。数据必须被加以解释：必须分析信息模式，并将各种信号组合起来，与预期行为进行比较。而这可以形成一些行动的基础。ICA不是在无人控制室里的一个大黑匣子。理想的ICA系统包括：
*	对系统所有权拥有深刻见解，并致力于持续改进的高素质人才团队；
*	一个收集足够的过程变量信息的仪表系统；
*	一个收集、处理和显示数据的监测系统，检测并隔离测量故障或处理异常情况，协助诊断和建议，并能模拟操作调整的后果。正确的数据采集和报告至关重要；
*	一个能够满足操作目标的控制系统。不管在每个单元过程本地运行中，还是在工厂内各个单元过程之间的协调运作中，这个控制系统都能实现。

对ICA的需求可以通过许多不同的方式来激发。“出水水质看起来很好，满足了监管机构的要求”。但是它有多好？它是否符合明天的规定和审查？我们可以削减运营成本吗？工厂能够处理不可避免的负荷增加吗？在需要更多容积之前它能够承受多大的负荷？出水标准会变得更严格。一些国家已经要求抽查时必须达到最低标准，而不再只对月均水平进行要求。不遵守规定将花费高昂。经常性预算会变得越来越紧张。

饮用水（供水）和污水系统都需要控制，这不止是为了保证出水水质。随着能源价格的上涨，效率和能源成本也变得越来越重要。水和能源的相互依存性越来越被认可。在配水系统中由于漏损而流失的水是一种能量损失。所有这些因素促进了更多的在线监测和控制的使用。

一氧化二氮（N2O）对全球温室效应的贡献约6%。与二氧化碳相比，N2O的吸热效率大约是其300倍。大气中只含有少量的N2O，但它能在大气中停留150年左右。由于N2O可以在硝化和反硝化过程中产生，所以控制活性污泥操作中的温室气体排放是非常有意义的。最近的研究表明，动态条件会导致N2O的增加排放（Kampschreur等人，2008）。

所有的过程都可以被控制以更好地运行。现在，工艺过程知识、传感器技术和工厂的设计及建造方式可能会限制可以实现的那些目标。我们也知道，与其他过程工业相比，污水处理工艺具有一些独特的特征：进水流量、随机扰动、低浓度、生物质、分离以及所有“原材料”都必须被接受并处理的事实。关键问题在于态度和激励。当然，态度往往取决于激励机制。今天，我们有投资ICA的激励政策，同时我们可以借鉴很多其他引进ICA的过程工业的成果。

所有控制的动机是随机干扰的存在。污水处理厂的负荷很少是恒定不变的。污水的流量、浓度和组成一直在变化。在许多情况下，一天的最低和最高负荷之间存在一个数量级的差异。作为这一运行过程的结果，厂区内部产生许多了干扰。例如回流污泥流量、硝酸盐再循环、消化池上清液或反冲洗过滤流量，除非仔细控制，否则这几个循环流量可能会导致严重的运行问题。由于所有这些干扰，我们不可能通过保持泵、压缩机、阀门和其他设备的恒定设置来运行任何一个工厂。

供水系统也常受到干扰。供水系统由用户需求所驱动，所以水的生产必须跟踪消费者的行为。通常，工厂只能满足日常的消费模式。在配水系统中，压力必须被严格控制。通过可变压力控制可以节省能量，也可以减少漏损的发生。对由漏损或水质扰动引起的干扰进行必要的检测和定位，并对其采取措施。
我们通常从三个重要水平（或标准）来描述控制和自动化：
*	保证工厂运转
*	满足出水要求
*	使效率最大化

在工厂运行的初级阶段，我们认为控制是理所应当的。液位、流量、压力和温度主要通过泵、压缩机和阀门来自动控制。这些控制将保证工厂的运行。在这个层面上，任何过程工业中都有标准化的控制回路。自动化供应商通常有足够的知识来安装并成功地运行这些控制回路来保证工厂的运行。

在下一阶段中，有了许多针对浓度的控制回路。在活性污泥工艺设施中，溶解氧（DO）、污泥龄、回流污泥和其他浓度的自动控制已经是被认可的方法。在大多数工厂中，这种控制水平是完全可以的。这有助于保证出水水质；可以实现夜间和周末的无人运行，同时节省能源和其他运营成本。但是，在这第二级水平中，已经出现了很多失败的控制系统。失败的原因并不是控制很困难，或者传感器不够强大。原因很简单，许多实施者没有足够的过程动力学（工艺动态）知识，也没有将他们所掌握的知识有效地跟同事交流。失败可能是由于传感器位置错误、数据分析不够充分、采样频率往往不够现实（通常是太快），又或者是控制器设置不够充分。

在线营养传感器正在变得普遍且经济实惠。这使得根据氨的去除情况，通过可变设定值来控制溶解氧成为可能。化学药品的使用剂量可以基于在线磷酸盐的测量，而预脱氮设施中富含硝酸盐的水的再循环则可以基于缺氧反应池中硝酸盐的测量来进行。大多数情况下，更加昂贵的仪器的回报时间是令人惊奇地短暂。可以节省能源，同时化学药品的用量也可以降到最低。其他传感器，如pH值和气体流量传感器，在保证运行安全的前提下，能够以更高的处理能力运行厌氧消化器。

最大限度地提高效率，也意味着我们不能再孤立地操作每个单元过程。相反，我们需要一个在整个工厂或全系统范围的方法。活性污泥系统中污泥的产生量与厌氧消化过程中所需的污泥水平相关，用以生产沼气。污水管网的运行则必定与污水处理系统的能力相关。处理厂的电能消耗必须最小化，而这需要从全厂范围角度来思考。通过使用沼气和污水的热量，污水处理厂也可以成为净能源生产者。显然，污水处理厂的运作是非常复杂的。而使其日益复杂的则是，曾提到过的全天候高效运作的要求。工厂必须始终能够处理各种干扰情况，最大限度地利用可用容量，并始终满足出水水质的要求。为了控制目标而给出一致且明确的命令，这是一个真正的多标准的决策问题，同时也被认为是ICA的总挑战。

同样地，对于供水厂来说，控制也必须基于全厂范围以获得高效率。所有出水都必须符合质量标准。单元过程之间的紧密耦合迫使控制过程也要考虑到耦合。

我不得不承认，我是怀着复杂的心情接受了邀请来写“ICA与我”这篇文章。一方面，能讲述自己在理解和控制城市供水和污水系统的历程和经验，我非常开心。另一方面，我又很害怕，因为在标题中加入“我”是很自负的。这么多天才研究者和其他专业人士对ICA的发展产生了巨大的影响。我要怎样才能增添任何有意义的东西，并公平地对待所有这些重要的贡献呢？就在IWA安排的十个ICA会议中，已经发表了大约800篇论文。这篇文章是对我从1972年开始并至今仍在继续的有关ICA的个人旅程的记录。这并不是一篇关于ICA的传统的最前沿的论文。它反映了我个人的发现、失望、振奋人心的发展以及个人的期望。许多ICA的应用还没有被令人满意地描述出来，而是由于主观原因被忽略。在教科书Olsson和Newell（1999）以及Olsson等人的最新报告中，对ICA领域有更详细的描述（2005）。
我将从我的个人经验出发来讲述ICA的早期发展。其中大部分来自污水处理领域，同时也涉及配水问题，特别是漏损检测和定位。在第2、3章中，国际水协（IWA）及其前身组织的ICA会议很好地反映出这些年来ICA的发展历程。第4章是对传感器和致动器的概述，第5章是控制建模，第6章则是数据分析和监测。第7章中描述了配水系统中，漏损检测是监测的另一种应用体现。第8章综述了污水处理中各种单元过程控制方面的内容，而第9章中介绍了通过基准测试来检验监测和控制系统的方法。第10章中简要介绍了对饮用水（供水）系统的控制过程，同时，第11章概述了全系统或全厂范围控制的概念。这么多年来，我明白了驱动力和激励机制的重要性（第12章）。第13章也许是最重要的，其中描述了我所遇到过的一些成为榜样且真正敬业之人。那么，未来是怎么样的呢？我会在第14章中对此加以推测。
