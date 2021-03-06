# 9. 基准化控制系统

大部分报道的控制器和控制结构都是基于仿真模拟或中试规模装置的，（而不是基于工程实践）。在一座大型污水处理厂中，对两个不同的控制器进行比较，可能是一件非常困难的事情。污水处理厂的运行条件通常变化很大，（导致）可能在冬季使用一个控制器，而在夏季使用另一个。在这样（交替使用控制器）的测试期间，运行人员的经验会得到提高。这些因素都促使我们开发一个基准仿真平台，作为检测（和比较）各种控制器和控制策略的基准。受美国控制系统协会（CSC）在飞行控制系统基准工作的启发，瑞典的Bengt Carlsson在1993年ICA会议上提出了基准化的思想。随后，这个想法被IWA的呼吸测量专家组采纳，并顺次在1997年ICA会议上正式提出\(Spanjers et al., 1998b\)。Vanrolleghem 等人\(1996b\)发表的文章讨论了（基准模型）排放标准，Spaniers等人\(1998a\) 发表的文章解释了基准测试的思想。

在1997，基准系统评估控制策略的工作成为欧洲COST 624/682研究计划的一部分，从而得到了进一步发展（Copp, 2002）。瑞典隆德大学Ulf Jeppsson领导的IWA专家组继续了上述研究。这个专家组在过去十年里一直持续研究，开发了模拟平台来对控制器做各种测试 \([http://www.benchmarkwwtp.org](http://www.benchmarkwwtp.org)\)。BSM1和BSM2模型以活性污泥模型\(Henze et al ., 2000\) 和厌氧消化1号模型\(Batstone et al ., 2002\)为基础，其实用性已被超过300篇使用基准平台的论文证实。BSM2模型\(Jeppsson et al., 2007; Nopens et al., 2010\) 是一个全厂控制模型，包含了污水处理的活性污泥模型和浓缩-厌氧消化的污泥处理过程\(Rosen et al ., 2006a\)。

基准模拟平台不仅能用于测试控制系统，还能用于比较监测方法。与控制方法的测试相似，监测方案是否有效也缺少客观的比较标准。很多监测方法在这个污水处理厂的某些具体指标上可行，但在其他污水处理厂却不再有效。通常原因是数据序列的时间太短（水质指标的观测时间太有限）。这方面的工作在2003年启动，Rosen\(2004a\)等人提出一个方法对BSM1模型进行扩展。时间维度必须进行扩展，并且模拟真实的运行条件，包括进水的外部扰动和传感器、执行器故障的内部扰动 \(Gernaey et al., 2006; Rosen et al., 2008\)。（因此，）“长期基准仿真1号模型”\(BSM1\_LT\)作为BSM1的扩展被开发出来。模型时间跨度从1周增加到1年，为评估比较监测和控制策略提供了更真实的框架。关于监测方案评估的最新结果可以在Corominas et al .\(2010\)文章中找到。

仿真模型可以免费在多个仿真平台上使用，既可用于污水处理工艺商业模拟软件\(GPD-XTM, SIMBA, WEST\)，也可用于通用模拟平台\(MATLAB/SIMULINK\)或者独立编译FORTRAN程序。其他模拟平台，如STOAT、BioWin、AQUASIM、JASS、SciLab和EFOR等，可以使用不完全版本的基准模型。Gernaey et al. \(2011\)的文章介绍了IWA专家组的成果。目前的BSM系统还不能完全满足评估控制与监测系统的所有需要。Jeppsson等人\(2011\)为模拟平台提供了大量的扩展功能，包括长期评估的可能性，以及在BSM2模型中增加污水管网和收纳水体的模型、更多污水处理厂内部的单元过程等。新的脱氮工艺模型已经被加入了，比如SHARON-厌氧氨氧化工艺\(Dapena-Mora et al., 2004），还有膜生物反应器\(Maere et al .,2011\)、生物除磷工艺\(Gernaey Jørgensen,2004\)，以及扩展的温室气体排放基准模型\(Flores-Alsina et al., 2011\)等。N2O是潜在的温室气体（GHG），因此活性污泥系统产生的N2O受到了很多关注（Porro et al., 2011）。文献中的模型以及被整合到全厂范围BSM2模型中，以便测算硝化过程和反硝化过程的N2O排放。

通过上述模型方法，已经测试和验证了许多的控制方法：

* 反馈控制器（P、PI、PID）\(Ma et al., 2006a\)和模糊控制器\(Ma et al., 2006b\)；
* 反馈/前馈控制结构\(Stare et al., 2007\)；
* 模型预测控制器\(Zarrad et al., 2004; Holenda et al., 2008\)。

在具体实施大型污水处理厂的先进过程控制系统方面，基准模型的贡献还非常之少\(Ayesa et al., 2006\)。为了实施大型污水处理工艺的控制，控制算法的设计必须与检测仪器和执行器想配合，还包括与实时软件的配合，比如监测数据库、数据筛选和过滤、参数估计，以及大量基于实际情况的考虑。

