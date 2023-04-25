# CAMEL (Communicative Agents for “Mind” Exploration of Large Scale Language Model Society)

随着对话和基于聊天的语言模型的快速发展，复杂任务解决方面取得了显著进展。然而，它们的成功在很大程度上依赖于人类输入来引导对话，这可能具有挑战性并且耗时。本文探讨了构建可扩展技术以促进交流代理之间的自主合作以及提供对其“认知”过程的洞察的潜力。为了解决实现自主合作的挑战，我们提出了一种名为角色扮演的新型交流代理框架。我们的方法包括使用内部提示来引导聊天代理完成任务，同时保持与人类意图的一致性。我们展示了如何使用角色扮演来生成用于研究聊天代理行为和能力的对话数据，为研究对话语言模型提供了宝贵的资源。我们的贡献包括引入一种新型的交流代理框架，为研究多代理系统的合作行为和能力提供一种可扩展的方法，并开放我们的库以支持交流代理和其他方面的研究。该项目的GitHub仓库已公开发布在：[https://github.com/lightaime/camel](https://github.com/lightaime/camel)。

定义下图的4个角色，
* Human User: 设定想法
* Task Specifier（AI）： 把人类的想法制定为具体的任务
* AI Assistant：执行者
* AI User：指导者

由Human User制定想法，Task Specifier 先翻译为具体任务， 下达给AI User， 通过AI User和AI Assistant 反复沟通交流完成任务

![CAMEL](chatGPT/pics/CAMEL.pngpics/)

具体prompt设计如下：
![AI Society Inception Prompt](chatGPT/pics/AI_society_inception_prompt.png)


参考文献：
* [CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society](https://arxiv.org/pdf/2303.17760)