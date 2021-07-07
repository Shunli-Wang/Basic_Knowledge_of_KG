
# 一、知识图谱的基本定义

**1、什么是知识？**  
&emsp;&emsp;知识是人类通过观察、学习和思考有关客观世界的各种现象而获取并总结出的所有事实（Fact）、概念（Concept）、规则（Rule）或原则（Principle）的集合。具有获取、表示和处理知识的能力是人类心智区别于其他物体中心智的重要特征。

**2、什么是知识图谱？**  
&emsp;&emsp;知识图谱是一种用图模型来描述知识和建模世界万物之间的关联关系的技术方法。

**3、KG技术的目的是什么？**  
&emsp;&emsp;知识图谱旨在从数据中识别、发现和推断实物与概念之间的复杂关系，是事物关系的可计算模型。

**4、KG在AI中的定位？**  
- 符号派（Symbolism）侧重于模拟人的心智，研究怎么用计算机符号表示人脑中的知识并模拟心智的推理过程。符号派关注的核心正是知识的表示和推理；  
- 连接派（Connectionism）侧重于模拟人脑的生理结构，即人工神经网络；  
&emsp;在KG的加持下，能够从具备感知、识别、判断能力的“聪明的AI”增强为具备思考、语言、推理能力的“有学识的AI”。

**5、KG与专家系统的不同？**  
&emsp;&emsp;专家系统的基本思想是：专家是基于大脑中的知识来进行决策的，因此AI的核心是用计算机符号表示这些知识，并通过推理机模仿人脑对知识进行性处理。一般专家系统由知识库和推理机两部分构成。
与传统专家系统时代主要依靠专家手工获取知识不同，现代KG的显著特点是规模巨大，无法单一依靠人工和专家构建。

**6、KG能用在哪些领域？**  
&emsp;&emsp;最早应用于提升搜索引擎的能力，现广泛应用于辅助搜索、辅助问答、辅助大数据分析、辅助语言理解、辅助设备互联。

**7、关于KG的几个事实**  
- 现有大规模KG都大量地以开放领域的数据抽取和开放社区协作的方式构建。
- 不能指望NLP和ML能自动构建KG。KG的确需要大量使用NLP/ML各种技术手段，帮助冷启动、后期补全和质量提升。NLP是获取KG手段之一，文本知识KG数据的一种来源。
- 构建KG的成本非常高，单一机构无法构建覆盖全面的KG，即便是金融这样的垂直领域也是如此。
- 所有KG的共同问题：知识缺失严重。

**8、KG的发展历史**  
![知识图谱发展历史](https://github.com/Shunli-Wang/-/blob/main/imgs/history.png)
- **1960-语义网络**：作为知识表示的一种方法被提出，主要用于自然语言理解领域；
- **1980s-本体论**：知识表示中需要对概念进行本体约束，从哲学引入AI用于刻画知识；
- **1989-Web**：Tim Berners-Lee发明万维网；
- **1998-语义Web**：更高级的万维网，从超文本链接到语义链接；
- **2006-链接数据**：强调语义网本质是建立开放数据之间的链接；
- **2012-知识图谱**：谷歌发布基于知识图谱的搜索引擎产品。

**9、KG的本质**  
- **Web视角**：像简历文本之间的超链接一样，简历数据之间的语义链接，并支持语义搜索
- **NLP视角**：怎样从文本中抽取语义和结构化数据
- **KR视角**：怎样利用计算机符号来表示和处理知识
- **AI视角**：怎样利用知识库来辅助理解人的语言
- **DB视角**：用图的方式去存储知识
- 总结：做好KG要兼容并蓄，综合利用好KR、NLP、Web、ML、DB等多方面的方法和技术。  
<img src="https://github.com/Shunli-Wang/-/blob/main/imgs/AI.png" width = "500" alt="KG和AI的关系" align=center >