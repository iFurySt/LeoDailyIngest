# LeoDailyIngest
我的每天摄入信息的一部分，跟我一起一起大量摄入信息，构建自己的认知体系，增加自己的视野和判断能力

# 2025-10-22

- https://www.oreilly.com/radar/podcast/generative-ai-in-the-real-world-context-engineering-with-drew-breunig/：Drew Breunig大佬谈上下文工程

# 2025-10-21

- https://dotslashwatch.com/：DIY最酷了
- https://50centadjustedforinflation.com/：一眼通货膨胀，笑死
- https://planetscale.com/blog/caching：可视化YYDS，可视化讲解了缓存相关的内容
- https://samwho.dev/big-o/：又是一个YYDS的可视化，这篇介绍了算法的时间复杂度。这个人的个人站里有很多可视化的例子，非常NICE
- https://snarky.ca/why-it-took-4-years-to-get-a-lock-files-specification/：pylock.toml出现。一个规范的制定要持续很久！

# 2025-10-20

- https://blog.bytebytego.com/p/how-salesforce-used-ai-to-reduce：始料未及的是，最后看起来像是在给cursor打call的感觉，整体还是概念性，没太多有趣的细节
- https://www.philschmid.de/agents-2.0-deep-agents：大家开始聊Deep Agent或者说Agent 2.0了，我个人理解就是重视multi-agent的方向去了
- https://nlp.elvissaravia.com/p/deep-agents：同上
- https://github.com/deepseek-ai/DeepSeek-OCR：DeepSeek-OCR 把长文本“拍成图片”，再让模型从图片里读回文字，用这种“看图读文”的方式把上下文压缩成原来十分之一，还能保持差不多的准确率
- https://www.felixstocker.com/blog/talent：努力是必要条件，但天赋决定了努力是否值得。不要因为别人的高产感到自卑，你也许只是把努力花在了不适合你的方向上

# 2025-10-19

- https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills：分了三级的Skills设定，感觉有点类似插件系统了，写各种Prompt和工具使用，还可以使用脚本，甚至感觉有些场景下比MCP更好用

# 2025-10-16

- https://harrisoncramer.me/15-go-sublteties-you-may-not-already-know/：不错的Go知识点
- https://www.pixnapping.com/：同个手机可以获取另一个APP的信息，比如Google Authenticator。原理非常牛逼…也是这个叫**Pixnapping Attack**的原因，通过控制渲染像素点和一些遮罩层隔离及放大像素可以慢慢对比拼凑出渲染像素的文字是什么，这样可以在30s拿到一个2FA的密码
- https://github.com/microsoft/edgeai-for-beginners：又是教程，吃灰Again

# 2025-10-15

- https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents：关于上下文工程实践讲的不错，里面延伸的链接也很棒
- https://www.elonmuskbook.org/：Naval的Newsletter里看到的
- https://www.anthropic.com/engineering/multi-agent-research-system：综述了一下multi-agent在research里的优点

# 2025-10-14

- https://arxiv.org/abs/2510.08338：用LLMs替代真实用户进行调研。好奇这真的奏效么，哈哈。不过确实人类的选择会有偏差，很多时候1-5分，可能有人会偏好4-5分，有人偏好都在中间或更低。
- https://danybittel.ch/macro.html：太酷了，结合拍照和模型和一些相关的技术，最终生成昆虫的3D模型
- https://www.leoniemonigatti.com/blog/ai-agent-from-scratch-in-python.html：展示如何用Python构建一个AI Agent demo，按需推进，适合新人了解

# 2025-10-13

- https://github.com/HandsOnLLM/Hands-On-Large-Language-Models：看着很不错的课程
- https://github.com/karpathy/nanoGPT：Karpathy写的NanoGPT
- https://arxiv.org/pdf/2510.00446：通过数学计算去压缩，而不是通过LLMs进行压缩。很神奇的想法
- https://microsoft.github.io/autogen/stable//user-guide/agentchat-user-guide/graph-flow.html

# 2025-10-12

- https://www.xiaoyuzhoufm.com/episode/68e74f521bef327f3d7ddcd7：老罗和Tim的对话，信息密度挺高的。播客是经历盗窃，很有趣的观点。
- https://docs.google.com/document/d/1rsaK53T3Lg5KoGwvf8ukOUvbELRtH-V0LnOIFDxBryE/edit?pli=1&tab=t.0：看着不错的Agent设计模式

# 2025-10-11

- https://blog.miguelgrinberg.com/post/python-3-14-is-here-how-fast-is-it：不严肃但有趣的py3.14基准测试，图表对比直观且阅读友好
- https://ikeamuseum.com/en/explore/ikea-catalogue：**IKEA catalogue**，很有趣，果然视觉是显学
- https://www.anthropic.com/research/small-samples-poison：在数据里参杂250个（绝对值而不是百分比）就可以污染大模型，让其按照一定行为动作，为AI攻防提供了新思路