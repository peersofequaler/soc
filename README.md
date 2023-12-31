# 自组织社区SOC

自组织社区SOC(Self-Organizing Community)是为了某种共同目标、或理想、或兴趣爱好、或共同利益，以可直接充分沟通的自治单元为基础，自发地自下而上，逐层递进所形成的社区。自组织社区所使用的组织方法称为“递进自组织”。它的基本原则是，对等自治、公开透明、开源开放。

自组织社区由沟通、组织、记录这三个维度构成：

1. 沟通是指直接充分的沟通，将沟通限定在可直接充分的沟通范围内（或称经验范围），以此作为一个基本的自治单元。
2. 组织是指单元内以大于2/3的票权进行管理决策；在同级单元间，自下而上自发选出代理人代表本单元与同级单元进行沟通与合作，一级代理人自由组合成二级的自治单元，二级代理人自由组合成三级的自治单元以此向上递进。不同组织间的合作，也可如此。
3. 记录是指在社区组织内、单元内的决策、与成员的贡献等形成公共公开可验证的记录，以此作为成员间相互了解彼此，记录信用、声望等的基础。

## “递进自组织”基本规则

1. 自组织社区由自下而上逐层递进的自治层级单元组成。
2. 自治单元成员数规模不小于四人，不大于所有成员皆可充分直接沟通的限度。
3. 自治单元内所有成员自由选举，以大于2/3的多数票权选举与决策，也就是，超过三分之一票权即可否决。
4. 每个成员的票权为其所代表的所有下属自治单元的所有成员人数。
5. 单元内的当选者（代理人），代理本单元的所有人与同级单元的代理自由组合成为更上一层级的自治单元。
6. 当选者任期不限，可随时重新选举。
7. 同一社区或组织内，当选者同时只能属于某一个单元，当作为更上一层级单元成员被选为代理时，自动放弃下属单元的代理身份，而对应的下属单元重选新的代理人。
8. 当更上一层级的代理人在重选时落选，自动回到下级单元，经单元决策同意后，作为候选代理人，与当前代理人共享决策票权，参加本单元代理人重新选举时，只代表自己，因此票权为1。
9. 二级以上的单元中，当选的代理人在本单元内的决策票权为成员票权的平均数。

## 为什么需要自组织社区？

1. 信息过载。人所能处理的信息是很有限的，而这个网络时代信息过载极其严重，一个公开群组少的上百人，多的上万人，即使其中只有少数人活跃，经常被信息流淹没，大多数人只能沦为吃瓜群众、旁观者、看客，只会搭便车。人太多了，远超我们的接受能力，所以需要将其拆，将人数减少到能处理的范围内。
2. 由于不公开、不透明带来的黑箱操作、内幕交易、贪腐等等问题。公开透明是解决这些问题的基础，也能极大缓解信息的不对等问题。
3. 信任问题。欺诈层出不穷，陌生人之间建立长久信任关系需要漫长的过程。对自治单元内成员的贡献、历史行为等的记录有助于长期信任合作的建立。
开源项目需要支持，而自组织社区与开源相辅相成。
。。。


## 基本概念

- 组织或社区：为了某个共同目标、或理想、或兴趣爱好、或共同利益而团结在一起，共同构建的自下而上的自治体。
- 自治单元树：组织内所有自治单元层级结构关系树状图。
- 自治单元：自治的基本单位，成员数量以可直接充分沟通为限（经验范围），单元内的成员彼此了解在单元内的贡献或历史行为，谁做了什么，各自做了多少，大家都清楚，没法搭便车。
- 单元代理人：单元内以超2/3票权选举出来的代表，代表本单元与其它同级单元进行沟通。
- 单元成员：普通成员或正式成员，拥有选举与决策权。
- 新人：单元内新加入的人，暂时未获得其它成员了解与信任，处理观察期，没有选举与决策权，直到获得认可成为正式员。
- 单元日志记录：每次选举或决策或贡献或其它事务，都要有一个记录，是公开可查寻的。



### 事件列表


- 创立新组织
- 建立新单元
- 邀请初始成员（至少4人）
- 单元进入自治状态
- 代理人选举或重选
- 投票表决
- 记录日志
- 代理人职位授权
- 新成员加入
- 强制剔除不受欢迎成员
- 生成提案
- 单元联合

# 未来计划

## 基于matrix协议实现自组织社区的构思

为什么选择matrix？它基于http协议，足够简单，足够开放。沟通、组织、记录这三个维度中，沟通是需要一个即时聊天功能的，而matrix的目标与自组织社区比较接近。

目前的想法是，将自组织这套逻辑写清楚，提交到matrix规范中，如果能被接受就太好了。如果他们无法接受，就只能自己慢慢实现了。

## “递进自组织”相关的书籍资料翻译成英文进行传播，国际化

翻译《权民一体论》
