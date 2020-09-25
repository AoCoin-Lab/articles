#  - Web3 热潮下 AOCOIN 做了什么？

### 2020 注定是不平凡的一年，数字资产行业同样，要说行业内有什么比今年夏日阳光更火热，一定是 DeFi、PolkaDot生态了 —— 以 Uniswap、Curve 为代表的 DeFi 产品将  liquidity mining 带入公众视野，红薯、土豆、玉米、寿司等食物也被赋予了新含义，成了圈内最潮流的谈资，此外高速发展的web3时代，也迎来了异构多链的区块链生态网络--Polkadot，搅动一江春水，让这个夏天有故事。

##### 面对行业快如此快节奏的发展，AOCOIN 围绕 DeFi、Polkadot 在产品有条不紊的跟进，DeFi产品上，AOCOIN 已上线TRON、ETH 流动性挖矿专区，在这里，你可以快速参与 SushiSwap、Uniswap等热门项目，对于波卡生态，我们快速支持了Polkadot,Kusama,Kulupu,ChainX 钱包以及Staking、Vote 等生态支持，同时，波卡也是我们本次重要聊的话题。

### 什么是波卡?
当前，已经启动了许多区块链项目，包括Bitcoin区块链和以太坊区块链，但是仍然存在许多挑战，例如可伸缩性，治理，互操作性，可开发性和实用性。在这种情况下，区块链行业主要参与者创立的Web3基金会开始开发“ Polkadot”项目，该项目将不同的区块链连接起来，以解决现有区块链的问题。

Web3 Foundation 的愿景是将Internet的现有集中式Web结构转变为完全分散的Web结构，而Polkadot将成为Web3 Foundation的第一个产品。

然后，我将介绍Polkadot是什么样的项目以及它是如何工作的。

### Polkadot如何开放连接？

在Polkadot如何连接不同的区块链之前，我们可以思考一个问题：Polkadot通过连接链以及它所面向的世界想要做什么？

Polkadot试图连接各个区块链系统以创建一个新的去中心化世界视图(Web3)

与“ Web3”相反，当前的Web称为“ Web2”，并具有集中式Web结构。在Web2中，互联网由Google，Amazom，Facebook和Apple等巨型技术公司所控制，这些公司拥有大量用户数据。他们分析大量用户数据进行业务开展并获得利润。但是，在极少数情况下，就会发生与数据处理有关的各种问题，例如，在没有用户意图的情况下使用收集的数据，或者由于安全漏洞而导致数据泄漏。

与这种高度集中化的Web2相反，“ Web3”试图构建一个分散的Web。在Web3中，数据记录在分布式分类帐和分布式存储中，并且用户可以通过分布式分类帐（例如区块链）来管理各种特权。用户可以在其中管理数据，控制自己处理数据的权限以及保护个人隐私。

为了实现Web3，也需要大量可稳定work的基础设施或组件，如已经可以使用的IPFS（分布式存储）、以太坊（分布式账本）这样的分散式Web，Polkadot则是通过无缝地连接每条公链和组件，在广义上体现Web3。

![](https://cdn.lianhaoping.com/docs/other/t1.jpeg)

回到主题，Polkadot如何连接不同的区块链？Polkadot中有三个元素来连接不同的区块链：“Reley(中继)”，“Parachains(平行)” 和 “Bridges(桥接)”。

“Parachain” 是相互连接和兼容的独特链，例如Bitcoin和Ethereum。如果我们想使这些平行链兼容，由于协议不同且块生成速度不同，因此规格也不同。这样不可能连接每个链。因此，“Bridges”介于两者之间。Bridge吸收了这种协议形成之类的差异，Bridge不直接连接，而是将每个Parachain通过Bridge连接到大型链“Reley”。从每个链写入的数据都记录在此中继链中，并且可以从其他链中引用它。通过这种方式，它们之间的Ralay链实现了链间通信，从而允许不同的区块链相互通信。

通过这种方式，就可以成功地组合 “Reley链”、“Parachains” 和 “Bridges”来连接不同的区块链来创建去中心化的Web3世界。

![](https://cdn.lianhaoping.com/docs/other/t2.png)



### Polkadot网络参与者的作用？
接下来，我解释下Polkadot的参与者及其角色，如果将参与者与比特币进行比较，将其视为生成和批准区块的节点这样更容易理解，但是在Polkadot中，参与者的方式和角色有点复杂。Polkadot有四种类型的参与者：“验证者”，“提名者”，“集合者”和 “渔夫”。
![](https://cdn.lianhaoping.com/docs/other/t3.png)

Collator负责将Parachain交易收集为区块并将其以隐藏形式发送给Relay链。它还支持Parachain的完整节点。要成为整理者，需要直接抵押Polkadot中使用的DOT令牌。

Validator负责批准从Collat​​or发送的Parachain区块并将其写入Relaychain，使其成为Polkadot网络中最重要的参与者。与Collat​​or一样，需要抵押DOT才能成为Validator。波卡鼓励Validator共同治理网络，例如，如果Validator做错了事(如恶意攻击)，则没收抵押的DOT，做为惩罚。

Nominator负责选择验证者，通过直接在验证者上抵押DOT来选择验证者。提名人不会直接生成区块，而是会在其选择的验证者所生成的区块获得批准时从验证者那里获得一些奖励。

最后，Fisherman与其他参与者不同，它负责监视验证的欺诈行为。如果验证人的行为不正常，则可以从验证人中没收DOT令牌。

通过这种方式，Collat​​or发送了一个Parachain交易区块，Nominator选择的验证者批准了该区块，将该区块写入RelayChain，Fisherman监控程序阻止了Validator作弊，四方通过扮演各自的角色来支持Polkadot的网络。


### 未来
Web3.0 将以什么形态展示在我们面前还很难说，毋庸置疑的是，解决 Web2.0 时代的一些弊端，以及更以用户为核心，提供一个更安全、透明、公平的分布式网络是大势所趋。异构多链通信平台、去中心化的用户身份管理等都有可能成为 Web3.0 快速发展的基础之一，AOCOIN也会坚持投身Polkadot生态支持、基础设施建设，为生态贡献尽可能的力量。

AOCOIN 是一款去中心化数字资产移动端钱包。它支持包括 ETH、TRON、Polkadot 等多链、多币种的管理以及各公链的DApp Broswer入口，拥有来自全球的近 500 万用户。


