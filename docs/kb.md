
1. 基于 B端客户更在意产品的价值创造和极低错误率而非各种自动化万能的demo噱头、AI模型内化的能力越来越强导致一些工程和技巧被抹平、因为不同工作的功率不同即为了最大化利用生产资料不会消灭分工    3个基础观点，我对2B AI 赛道的产品做以下几个判断。
一、BPO业务外包 是不错的AI to B合作方式
- 用AI承包企业一部分业务 比 卖给企业一款AI工具更容易让客户打消顾虑。这样的权责也会倒逼AI供应商专注价值创造而不是搞噱头。
- BPO模式下，企业客户会非常愿意配合制订内外衔接规范，像甲方对乙方写招标/SOW那样。因为他的角度从 对工具提要求变成了 对上下游提要求，即 AI 成为工作流程中环节中一个专业节点，而不再是一个辅助人的工具。
- 可以先从质量/风控/审核 、 数据处理和分析、导购/客服等业务外包开始， 再下一步是客户买下这个外包AI产品 替代员工。
- 参考演变：工厂流水线分工 → 共享服务中心→ 第三方供应商/BPO → AI BPO → 数字员工收编
二、agent杀不死编排工具，编排工具的定位将从胶水定位变成管理
- 优秀的员工杀不死组织架构。企业场景中“看得见”的更细粒度的确定性和切片来迎合安全老板的安全感、监管欲、掌控欲、质量管理才是效率。编排工具是组织刚需，不是技术落后。agent搭建门槛更低、更通用，看起来替代了编排工具。但2b场景Agent内部推理链、Multi-Agent间协商过程，必须以可视化的流/图形式显式呈现，并支持在关键节点插入约束、审批、回滚。编排工具不会消失，而是根据信任粒度(参考三)的变化，而改变 被编排的对象。
- n个全才做事，会出现部分环节的生产资料阻塞、空闲，出现瓶颈环节。管理n个长线程是困难的，不如管理m个专才并按照各自环节的功率和依赖关系进行配比，实现综合节拍相同，生产资料100%利用率。
- 参考演变：Dify（编排llm/mcp/function等）→ Manus（全自主黑盒）→ Claude Code（Human-in-the-Loop）→openclaw（灵活自由配置）→ Hermes（自我管理）→ MASFactory（显性图呈现 multi agent编排）→ 企业管理咨询的组织设计 、vsm价值流程图 ?
三、XaaS: X是有价值的被信任的结果
- 一 和 二延申。客户对Ai输出啥粒度是信任的？客户只管给钱，产品直接给你XX，XX到哪个粒度。则X可以升级为啥。例如AI帮企业带来高转化意愿的客户。 消耗量是成本，结果才是利润。定价单位从 消耗的Token → AI完成的任务→ AI带来的价值 / 决策，类似向外包或咨询公司下单。ai把除了实物操作、真人服务 之外的一切数据服务都承包，则人和机器只是执行被下达的任务-- 决策即服务？
- 参考演变：IaaS → PaaS → SaaS → FaaS → AaaS → outcome as-a-Service ；（业务人员不再感知Agent，只感知结果，即主客易位，AI first，员工变机器。）
四、AI in the Supply chain
- 在 数据、AI决策能力、配套工具的加持下企业对客侧的产品、服务、策略、交互方式可以实现对客人的 实时动态、针对性的组合或生成。即AI可以参与实时供应链（信息流/商品流/资金流）。企业为每个客服的服务都是私人定制。
-  AI 不是插件，而是企业实时运行的操作系统。这不是简单的自动化，而是基于数据孪生的实时资源调度。AI 参与到信息流、商品流、资金流的实时耦合中，将企业的供应能力转化为一种“流式服务”。大量的事物需要数据、匹配。数据、建模能力 价值重提。数字孪生等概念可能迎来支持其落地的时代。

  五、综上，爆款和风口不需要预测，只需想办法解决企业的每个痛点。
  - 协作：组织级共享的知识库、上下文、记忆。   出现以目标和任务为中心、 沟通只是下挂的动作之一 、而非以会话/群聊为中心杂糅不同事情的企业协作工具。
  - Agent OS： 身份与权限、协议与互操作、运行时与沙箱、成本与配额、可观测性与审计、质量评测与回归。谁定义了模型和业务逻辑的中间层标准，谁就拿走下一代企业软件的控制权。合纵连横，参考 浏览器大战Netscape公司败落，但他推动的协议成为赢家、参考 Docker定义了容器格式与运行时，K8s赢得了编排层。物理机 → 虚拟机 → 容器 → K8s → Serverless Runtime → Agent Runtime；
  - 业务垂类agent 将从通用agent中脱颖而出：质量/风控/审核 、 数据处理和分析、导购/客服、法务（Harvey）、财务(Rillet/Numeric)、HR、助理、PMO、设计、供应链排产
- 用AI承包企业一部分业务 比 卖给企业一款AI工具更容易让客户打消顾虑。这样的权责也会倒逼AI供应商专注价值创造而不是搞噱头。
- BPO模式下，企业客户会非常愿意配合制订内外衔接规范，像甲方对乙方写招标/SOW那样。因为他的角度从 对工具提要求变成了 对上下游提要求，即 AI 成为工作流程中环节中一个专业节点，而不再是一个辅助人的工具。
- 可以先从质量/风控/审核 、 数据处理和分析、导购/客服等业务外包开始， 再下一步是客户买下这个外包AI产品 替代员工。
- 参考演变：工厂流水线分工 → 共享服务中心→ 第三方供应商/BPO → AI BPO → 数字员工收编
二、agent杀不死编排工具，编排工具的定位将从胶水定位变成管理
- 优秀的员工杀不死组织架构。企业场景中“看得见”的更细粒度的确定性和切片来迎合安全老板的安全感、监管欲、掌控欲、质量管理才是效率。编排工具是组织刚需，不是技术落后。agent搭建门槛更低、更通用，看起来替代了编排工具。但2b场景Agent内部推理链、Multi-Agent间协商过程，必须以可视化的流/图形式显式呈现，并支持在关键节点插入约束、审批、回滚。编排工具不会消失，而是根据信任粒度(参考三)的变化，而改变 被编排的对象。
- n个全才做事，会出现部分环节的生产资料阻塞、空闲，出现瓶颈环节。管理n个长线程是困难的，不如管理m个专才并按照各自环节的功率和依赖关系进行配比，实现综合节拍相同，生产资料100%利用率。
- 参考演变：Dify（编排llm/mcp/function等）→ Manus（全自主黑盒）→ Claude Code（Human-in-the-Loop）→openclaw（灵活自由配置）→ Hermes（自我管理）→ MASFactory（显性图呈现 multi agent编排）→ 企业管理咨询的组织设计 、vsm价值流程图 ?
- 一 和 二延申。客户对Ai输出啥粒度是信任的？客户只管给钱，产品直接给你XX，XX到哪个粒度。则X可以升级为啥。例如AI帮企业带来高转化意愿的客户。 消耗量是成本，结果才是利润。定价单位从 消耗的Token → AI完成的任务→ AI带来的价值 / 决策，类似向外包或咨询公司下单。ai把除了实物操作、真人服务 之外的一切数据服务都承包，则人和机器只是执行被下达的任务-- 决策即服务？
- 参考演变：IaaS → PaaS → SaaS → FaaS → AaaS → outcome as-a-Service ；（业务人员不再感知Agent，只感知结果，即主客易位，AI first，员工变机器。）
四、AI in the Supply chain
- 在 数据、AI决策能力、配套工具的加持下企业对客侧的产品、服务、策略、交互方式可以实现对客人的 实时动态、针对性的组合或生成。即AI可以参与实时供应链（信息流/商品流/资金流）。企业为每个客服的服务都是私人定制。
-  AI 不是插件，而是企业实时运行的操作系统。这不是简单的自动化，而是基于数据孪生的实时资源调度。AI 参与到信息流、商品流、资金流的实时耦合中，将企业的供应能力转化为一种“流式服务”。大量的事物需要数据、匹配。数据、建模能力 价值重提。数字孪生等概念可能迎来支持其落地的时代。

**【培训】各种AI工具的应用分享**

| 后记，会议视频：https://trip.larkenterprise.com/minutes/obcniv5t6ou7645v6n34ul44 |
| ------------------------------------------------------------------------ |

本次AI分享不是讲AI给公司做什么项目、也不是聊AI对社会对人类有什么影响，而是专注【日常生活】场景的AI应用，能个人落地、比较实用。分为以下2个部分：

* 各种AI工具的分类与选择       -----    避免错过好的工具，同时搞清它们的本质避免被新闻噱头搞得焦虑

* DIFY、Cursor、OpenClaw     ----     应用场景举例和实操   （选DIFY、Cursor 是因为公司买单为我们提供这些工具，不代表它们是最好的）

本次培训会后会发送文档和培训视频给各位。 &#x20;

# **AI工具分类与选择**

<table><colgroup><col width="230"><col width="230"><col width="230"></colgroup>
<thead>
<tr>
<th><strong>纯模型：只会接收消息并回复的脑子   </strong><ul>
<li>
<p>获取：本地部署或 直接访问模型产品app或网页 或 购买模型的API 服务</p>
<ul>
<li>各模型和榜单: <a href="https://openrouter.ai/rankings"><span style="color: rgb(36,91,219); background-color: inherit">Openrouter LLM Ranking</span></a>、<a href="https://huggingface.co/"><span style="color: rgb(36,91,219); background-color: inherit">huggingface</span></a>、<a href="https://ollama.com/search"><span style="color: rgb(36,91,219); background-color: inherit">ollama</span></a></li>
<li>携程内网可免费使用：</li>
</ul>
</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=Mjk4ODRlNGNlMzIyMWVhZDMzN2Q1N2Y4NzA3Yjc3OThfRE1hTU5PRU1VVmNHQ0NkbDFUbWpZbjNsR1RYMHBSNlZfVG9rZW46SlFGM2JLNk5Rb0lDbE54YW0ycWM2bVZYbkplXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MTI0MDNiYmFiYzNiYWUwMjgyNzI0YTY4N2UwOWNjOTFfQlJLdnlpVk52ZXYxam9KNmhIS2dLQnc4MHo2R0c4bGNfVG9rZW46UEJvVGJSY0Jsb0QxdWp4am8xZWNnYzV4blRlXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt="">Peta 各类模型试用和模型榜单https://peta.ctripcorp.com/view/modelSquare<img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=OWQzMjU3YjFhZjBkNmExNzA4Mzg2MWM5YzUwOTQxYjNfTHl1UHJ0ZW9oM0pVN2Y0QzI4aTVxQ0Mwa0xOMjNDZGlfVG9rZW46S2hiWWJyR3Vyb0hWR0t4ZG0wVGNnTTZ0bjJkXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><ul>
<li>
<p>模型API：</p>
<ul>
<li>token：模型服务按<span style="color: inherit; background-color: rgb(255,165,61)">token</span>数计费，类似我们上网按流量计费。流量单位是字节，1英文字符=1b=1/1024 kb，而模型处理的最小单元是token，不恰当的解释约等于 最小词义，1 token约0.75个单词约1~ 2个汉字。 <a href="https://console.volcengine.com/ark/region:ark+cn-beijing/tokenCalculator"><span style="color: rgb(36,91,219); background-color: inherit">token计算器</span></a></li>
</ul>
</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NzBmOGIwYzVkYWUyZGYwMWViZjNjZmUwMzNjZWQ0NTVfSWRRbjJhNVRqUmhDRlNoMkw1SWtlUW5rRWprdlVHSVBfVG9rZW46UXVvVGI4dGVPbzRNbDV4UkFKRmMyMEdubmZmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><ul>
<li>携程内网购买：<a href="https://trip.larkenterprise.com/wiki/XaF3wGb0GiFYC5kTC3IciHgAnjf"><span style="color: rgb(36,91,219); background-color: inherit">大模型申请</span></a>（公司买单）</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=Y2I0ZGQyOTNkMjA5OGYyNmI1OWJlYjgwNGFmNzNjNjRfaFZLTHFxS3BWSTlBWjllb0NKbm02b0JabkdKYUd1Y2RfVG9rZW46V2Y5b2I1aHNobzFBMHl4REpvT2M4M2ppbkloXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><ul>
<li>外网购买举例：可在<a href="https://bailian.console.aliyun.com/cn-beijing/?spm=5176.12818093_47.resourceCenter.1.2cf716d0iIHBec&#x26;tab=coding-plan#/efm/detail"><span style="color: rgb(36,91,219); background-color: inherit">阿里百炼</span></a>、<a href="https://www.volcengine.com/activity/codingplan"><span style="color: rgb(36,91,219); background-color: inherit">字节火山方舟</span></a> 等各大模型官网订阅api服务</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YzNiZDhlYzZiOTQwZWU0NTBiZmY0OGY2ZGY4NTc3ZDFfRDhVMGREZVh4OFRRRUdodU5ISnF3ZUUyZnVFTk9hd05fVG9rZW46TmdOVmI5aEVob2ZvejJ4N2Z4ZGNUWWliblhoXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></th>
<th><strong>AI工作流：按固定流水线工作的m个脑子+n个机械手臂  </strong><ul>
<li>获取：模型+编程  或者  模型+ 低代码编程（dify/coze/n8n的工作流模式）</li>
<li>点击展开 携程内网 <a href="https://tdify.ctripcorp.com/explore/apps"><span style="color: rgb(36,91,219); background-color: inherit">T-dify</span></a>示例</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MWI2ZTBkYjVhNDA1ODBmNTRmNGY5ZDUzNDZlYWMyOTZfcVBZSWJzUmNtT3p1TDhuOHZQOUp3MGVZOWFGMXFINnZfVG9rZW46QkVYOGJJdTFVbzRVMUZ4dGxUMGN0MnVxbkllXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></th>
<th><strong>Agent：配备电脑的人</strong>（自主决定执行何动作并基于结果自主调整 并循环）<ul>
<li>
<p>获取：模型+ 编程    或  模型+ 低代码编程 或 已经框架搭完的Agent</p>
</li>
<li>
<p>agent 示例 点击展开： </p>
<ul>
<li>名词解释 Skill：流水线运转需要设备需要组装、严丝合缝，而找人干活，只需给它手册即可，且是先看“目录”使用，需要时才占用token。工具tool是执行的具体动作，例如调接口、执行xx命令行、调符合mcp协议的接口服务（简称调mcp）。工具像菜刀、放xx调料、切xx，技能是烹饪方法，是用自然语言描述的行为规范和执行策略，告诉Agent在什么场景下如何组合使用工具、以什么方式达成目标。技能中可写如何调用所需要的工具。</li>
<li>普通agent（例如Manus）被调教好、技能和工具预设和固定好的的agent，远程用电脑服务你的agent（3.18最新消息，使用本地电脑版 manus上线）</li>
</ul>
</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=OGZkN2M5MzU1NzUzNDU0ZTA1NDFlOGI1YzY0NWYxZWFfaTA5UlhPMXllc3hJN0t3Y1BpNHNPWVJ3V3pGaXdURWZfVG9rZW46Q09LQmJwZGFTbzMxZjh4MGJhVWNoSDdTbmRoXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><ul>
<li>openClaw 类agent：<span style="color: inherit; background-color: rgba(254,212,164,0.8)">允许你自己配置 </span> 模型+人设与规则+记忆+交互通道+技能（skill)+可执行的工具 的，<span style="color: inherit; background-color: rgb(255,165,61)">能够创建多个agent、运行agent、 24h运行的系统</span>。<a href="https://clawhub.ai/skills?sort=downloads"><span style="color: rgb(36,91,219); background-color: inherit">clawhub技能商店</span></a></li>
</ul><ul>
<li>
<p>写代码垂类agent ：执行层限制在代码（文本）读写和调试范围内</p>
<ul>
<li>Cursor、claude code、Devin 等  以cursor举例</li>
</ul>
</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ZGYyYThmOTc4OTA4NjJkZjU1ZDBlMzRhNDQ0MTQwNzZfdU5pR0hOZlZLek5FR1dnZ3A2V2hVbXFjNkJQSFh3MUVfVG9rZW46RW9kMGJzaFZJb0pJNDd4SUZSS2N2T2hZbldiXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></th>
</tr>
</thead>
</table>



<table><colgroup><col width="230"><col width="230"><col width="114"><col width="114"></colgroup>
<thead>
<tr>
<th><strong>纯模型适用场景</strong><br /><strong>纯模型应用场景举例</strong><ul>
<li>日常百科、知识问答、写sql、写简短代码、写简短分析</li>
<li><span style="color: inherit; background-color: rgba(254,212,164,0.8)">借助文本实现其他内容</span>的生产：文&#x3C;->图&#x3C;->代码&#x3C;->程序 。示例展开：</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MTA4M2Q1YzA4N2UwNWM1NjI4MTZhODExMTc0MDVjNDVfajVqSVpRcERRYU5aWG9FZWh4TnlwN1ZlSXZ0ZzVHQlZfVG9rZW46U1pZeWJvaGJCb2tBa254RzB0cWNOZkxtbmRTXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><ul>
<li>写提示词，写提示词的提示词，文图视频模型接力增加质量和可控性，文&#x3C;>提示词文&#x3C;->图&#x3C;->视频。示例展开：</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=N2EyMTE3MGE2YzlhODJkZDYxOWVmNzZlNTJiOWEyODFfQUU5QWlxOVh5T1hwalhjd29uWkRtWncxQmw4RzZMOXRfVG9rZW46T0VRR2I2dlVnb2UzcEV4azJ4SWNFQzBJbjhjXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDQyZGZlYzEwODVmYzVhZWNhZDgyODhkMzU1N2ZjZTFfa0g2OG9wTWFyS3U0ZWNibERwNmh5SFJTc0Q2d2lDUTVfVG9rZW46SXFzdmJWQ2VGb3Z6cWx4dUV0M2NDNlJkbnBnXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ZWJkY2E5M2I0OWVjYTJhZDA4MWVkYjk1Y2FmNDM5NGJfM2I1Z0JEVEVra2ZLUjB5dUpiZmFWNlg3WTZkU3BnTGtfVG9rZW46Q2lYMmJPMnZmb2c0QmN4cEpoZ2NFdVR3bk5mXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MGUxYjZkN2MxOGFhMmJiNzdhYjlhNDg0ZTRkNjBkM2FfdGdIa04xVGZ6S2w5VzNJQkUxNnMyV0JuMXhSRU50UlVfVG9rZW46T3Z0YmJjWkl5bzJvRDl4YjNEdmNTZHpxbm11XzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></th>
<th><strong>AI工作流适用场景</strong><br /><strong>Ai工作流应用场景举例（具体示例 参见下一章节。）</strong><ul>
<li>多个大模型合作：大模型检查大模型结果，图文视频接力（可控，高质）</li>
<li>固定逻辑调用工具：+联网搜索、+知识库、+飞书、+调接口、等</li>
<li>批量执行需要大模型能力的任务</li>
</ul></th>
<th><strong>写代码垂类Agent 特点</strong><ul>
<li>成本：模型费 、个别工具费</li>
<li><span style="color: inherit; background-color: rgb(255,165,61)">文件夹和文件协作方式</span>、过程可视且需要人参与确认</li>
<li>记忆存储以项目为单位</li>
<li>写代码相关工具和插件丰富</li>
</ul>写代码垂类Agent适用场景特点<ul>
<li>
<p>本地文件、项目、<span style="color: inherit; background-color: rgb(255,165,61)">人机协作</span></p>
</li>
<li>
<p>适合代码处理的</p>
<ul>
<li><span style="color: inherit; background-color: rgb(255,165,61)">百万行数据</span>、开发软件</li>
<li>html产品原型、交互稿等</li>
</ul>
</li>
</ul></th>
<th><strong>Openclaw 特点</strong><ul>
<li>成本：模型费<span style="color: inherit; background-color: rgb(255,165,61)">（更费token）</span> + 部分工具调用费+配置与优化成本</li>
<li>技能/工具/插件 生态丰富，开源，<span style="color: inherit; background-color: rgb(255,165,61)">全能</span></li>
<li><span style="color: inherit; background-color: rgb(255,165,61)">7*24h  * N、</span>   <span style="color: inherit; background-color: rgba(254,212,164,0.8)">主动</span>/心跳、可<span style="color: inherit; background-color: rgb(255,165,61)">和周期性</span>执行</li>
<li><span style="color: inherit; background-color: rgb(255,165,61)">持久化记忆、可调教</span></li>
</ul>通用型Agent适用场景特点<ul>
<li><span style="color: inherit; background-color: rgb(255,165,61)">拟“人”托管、需要24h执行的、多”人”协作、自动化要求（串联各种工具）</span></li>
<li>愿意承担<span style="color: inherit; background-color: rgb(255,165,61)">金钱 和养成成本</span></li>
<li>可线上文档协作</li>
</ul></th>
</tr>
</thead>
</table>

备注

* 以上分类只是为了方便说明特点，实际各个工具的能力都在融合。 也有很多工具暂未介绍。

  * 例如纯模型对客的app/网页 都会支持联网搜索、支持越来越多的文件格式、agent模式等（近似Manus）；飞书的知识问答支持知识检索；例如dify/coze/N8n 也能搭建对话式 agent、app等

  * AIGC垂类工作流，如 comfyui、oii、可灵的画布等。

* AI时代带来的只是“脑子”，即思考是智能的，现在各类AI自动化工具，依赖执行层的工具（tool）（<span style="color: inherit; background-color: rgb(255,165,61)">这些工具不是智能的</span>，在ai时代之前它们也是存在的，有了ai 但可能没有你想要的tool，也可能有但是需要收费），

| ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=OTYzMWMzZTg1OGYwZDM3ZTNhZmZmZjFiYTA4ZDZlZWVfNEhQdG95RktWSDBxNFI0MnFqVkxtT1hscXhoODdLa1lfVG9rZW46RzY1d2JSa0xUbzNySzJ4VTVmV2NQOFl4bktmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ZTgyZTk3NWRjMmIzODlhMDRhYzFkMWNiNzBlZTJlOTlfOGxRR3RPVW1rZzg2MnhLQ1I5clQzOVVRek1VcG9FdUpfVG9rZW46VURuc2JtakM1b21lTEJ4bFFKN2NPMXRxbkJnXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

之前靠自己公司的开发人员，现在靠全球的”开发人员“，且以前只需要提需求，现在需要自己选方案，验证，优化。甚至需要了解工具的原理，要不断”养“AI。AI可以替代人执行一些工作，但工作本身没有减少。思考和判断的责任仍在人。越选择自动化高的、胶水能力强的AI工具，用户体验越接近全栈工程师，不一定最适合自己。 看完后面的示例会有更具体的感受。



***

# **Dify案例和实操**

* 上次我们中台同事已经分享了携程-dify的一些介绍[<span style="color: rgb(36,91,219); background-color: inherit">旅游 - Dify工具&amp;落地案例分享</span>](https://trip.larkenterprise.com/wiki/Cud2wctwBiwfUVk3iVecPFCknic)，  携程T-dify社区教程 [<span style="color: rgb(36,91,219); background-color: inherit">TripDify 使用文档</span>](https://trip.larkenterprise.com/wiki/Xl9pwtnI3iu7EWk2NvGcsd11nGg?from=from_copylink)  、  [<span style="color: rgb(36,91,219); background-color: inherit">TripDify问题汇总</span>](https://trip.larkenterprise.com/wiki/VQR7wKYTEiU0GPkos7icYfTUnjb)

* 携程dify支持群点击https://applink.larkenterprise.com/client/chat/chatter/add\_by\_link?link\_token=465p2620-24d0-4b51-b801-4bb45838161d加入吧！

* 本次重点是分享一些案例和直接实操复刻。地址：[<span style="color: rgb(36,91,219); background-color: inherit">T-dify</span>](https://tdify.ctripcorp.com/explore/apps) 、加入或创建空间(模型api 买单)

Dify案例

| 应用场景                                                                              | 工作流页面                                                                                                                                                                                                                                                                                                                                   | 输出示例                                                                                                                                                                                                                                                     | 实操要点                                                                                                                                                        |
| --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 基础示例                                                                              | https://tdify.ctripcorp.com/explore/apps                                                                                                                                                                                                                                                                                                |                                                                                                                                                                                                                                                          | 基础界面、权限、导入导出、画布界面、模型节点、调试、运行、批量                                                                                                                             |
| 对比模型差异：gemini vs seedream                                                         | https://tdify.ctripcorp.com/app/a051bb66-6fea-40cf-988f-6adfbfbcba20/workflow![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDAzMjI4MjBmYzUyOGZlMjk3NTgzMzYzN2RhMWIyZTZfV1VRSEJ4UGxETHBYV1FyanBNQkdTeFE4WWN4Y3VaVDVfVG9rZW46VmQ2V2IxNEx3b2ZLQkZ4TTlFUmNlWVZBbm5jXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)   |                                                                                                                                                                                                                                                          | 条件分支、<br />代码执行字符串合并（不用代码解析。写大模型会慢。）                                                                                                                        |
| 景玩标题sem：按已有经验处理文本                                                                 | https://tdify.ctripcorp.com/app/2ab837bd-bd75-461c-817e-1baf2418746f/workflow![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NTg5NGRiMTY5MzkwMmEyOTFmZDAxZDk2NmQ0MDk2ZTFfMEVrY0ZhY3k3UzJpUHZ1OXlnVWdSb1pqT2t0ZFVoRUNfVG9rZW46TVVqbWJjTmxKb3pCRUZ4ZFhWOGNpaHBGblhnXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)   |                                                                                                                                                                                                                                                          | 知识库                                                                                                                                                         |
| 查询商品详情                                                                            | https://tdify.ctripcorp.com/app/18ac6ddb-d641-4046-8810-aae683cef0d2/workflow![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=M2JlOWU0ZjYyODg2YjgzZTkxZjQzNGQ2NzdhODQyZDdfZUUxdktwS0dndHZNYkREaVg3Uk56Wk5NcW8wV0VndGZfVG9rZW46SnJMYWJCS1BzbzR2bTV4Zk5PbGNabkczbm9kXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)   |                                                                                                                                                                                                                                                          | 分支、调携程内部接口<br />、环境变量                                                                                                                                       |
| 签证  图+文生成工具                                                                       | https://tdify.ctripcorp.com/app/d6d05cd4-cf10-41fb-8d15-132590d43153/workflow![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YjQ5YmU0ZDlmMDM3YzFiZTFmN2QyODU3OWQ2NWIxMWZfenVUYXdpSDBCVExPalNzRnlDTWJzcms2cEFOM2phdkVfVG9rZW46T05lNmJoUmlGbzZ1SnR4Rk9JOWM2ZU5Bbjk5XzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)   | <br /><br />                                                                                                                                                                                                                                             | 文图接力、图生图                                                                                                                                                    |
| <span style="color: inherit; background-color: rgba(255,246,122,0.8)">写入飞书</span> | https://tdify.ctripcorp.com/app/18da625d-e650-4b1b-89a8-b01bfd7d0fe9/workflow                                                                                                                                                                                                                                                           | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=M2U5YzJlYjQ4YWMxNWI1OGI2ZGE5YTgzNmYzOWI0YjlfT2Y0eXdIcnNBaU95MkpsV1NUdXZZSXMwb0xXaHNwZ1hfVG9rZW46WHZyNmJibEoxb3ozYTV4OWFIN2NuSk81bkZiXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) | [<span style="color: rgb(36,91,219); background-color: inherit">【教程】Dify联动飞书文档和表格</span>](https://trip.larkenterprise.com/wiki/DK0RwTVr5i5uxZkhCtzcE2Rbnre) |
| 视频关键帧生成                                                                           | https://tdify.ctripcorp.com/app/fdbab801-da4a-4 704-8307-1566721808dd/workflow ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=M2Q5ZWFkMTc2NWE0YTBmODRjYTA4NWNkMzZjZjk2OWZfTDV2ZENDMjlCM3FtektaV3AzM1B5bU1vRGNGVERaMmlfVG9rZW46Q0xUU2JBQm55b0xRSDZ4Q0tPdGM1aWJXbnpmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) | 视频为图生视频+人工剪辑拼接配乐  <br />                                                                                                                                                                                                                                 | 循环结构（循环也可以改为固定数量的分支，每一个单独接分支）、文图接力、图生图                                                                                                                      |
| 灵感工具                                                                              | https://tdify.ctripcorp.com/app/415126a3-f08f-43ec-b353-ef4fb51f6291/workflow![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=N2FhMzA2ZGRkNWI0ZjdjY2VjMmQzNWFhZTYwY2E1OGNfZWZSOUVkaHlHMmRjSnY5TWdOQ2hteEZTNzNNbVBxbWJfVG9rZW46VldWYmJsNEdCb3NWTHB4eEJldWMwNUpIbmlmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)   |                                                                                                                                                                                                                                                          | 调百度的符合MCP协议的搜索接口、调携程内部接口、循环、串一起                                                                                                                             |
| 图文贴功能集合                                                                           | https://tdify.ctripcorp.com/app/90c8ce9b-18d6-4ce0-9f12-c2d0d956f0f1/workflow![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MWZmZjVlOGJkZmUwOTI5NDMxZmNhODdjYThkOTBkZTdfTlRENk84ajVyUkl4dmxXY0k4cFExTXBxeXRZcElxaE1fVG9rZW46RjJIT2JxV1Jkb01qM2x4NlBNVGNaVXlmbjFkXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)   |                                                                                                                                                                                                                                                          | 固化模板（选项）<br />、变量聚合                                                                                                                                         |
| 视频                                                                                | https://tdify.ctripcorp.com/app/12728138-bf1e-4205-82e4-0c996e5654a2/workflow![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDk0OTIxZjc5NDg3ZTU2YmE3NDQ4MTc4MTc2NmNlM2RfeWN2MFMyN1VLY1FuUHpPWkg3ZVZZQzBpMFh6VnRDclFfVG9rZW46Rk9vQ2I0czNyb05uVEx4Z1RXdWNBanFabmtmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)   |                                                                                                                                                                                                                                                          |                                                                                                                                                             |
| 邮件                                                                                |                                                                                                                                                                                                                                                                                                                                         |                                                                                                                                                                                                                                                          |                                                                                                                                                             |

dify官方社区：https://marketplace.dify.ai/plugins/all、携程内网可用mcp接口：https://peta.ctripcorp.com/view/mcpService、 https://aicoding.portal.ctripcorp.com/mcp-server/market

# **Cursor案例**

* 下载链接： https://cursor.com/cn           携程cursor教程：  [<span style="color: rgb(36,91,219); background-color: inherit">编程工具：Cursor使用手册</span>](https://trip.larkenterprise.com/wiki/AsqYweSuOiAy4WkIdBrcyr25nIb)

* 携程员工申请：检查自己所在的预算中心是否在[<span style="color: rgb(36,91,219); background-color: inherit">Copilot/Cursor BU 管理员及配额</span>](https://trip.larkenterprise.com/wiki/HOQ0wFhWXip8LbkZ4J0cfU1qn5b) 中，不在的化和自己部门预算中心负责人确认后 找  Junhu Li (李俊虎) 添加，完成后在 https://aitools.release.ctripcorp.com/  中申请 cursor

* 携程AI coding支持群：快点击https://applink.larkenterprise.com/client/chat/chatter/add\_by\_link?link\_token=df8r0205-6c07-4378-b67d-f9d9a225cc2a加入吧！

| 示例                                                                                                         | 场景特点                                                                                                     | 图示                                                                                                                                                                                                                                                       |
| ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 写文档：年会主持稿                                                                                                  | 多类型文档，人机协作                                                                                               | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YzQ2ODE0ZjZjNmY4ZWY2NTMxNzkxMDQ1NTM0ZDBkN2FfM1NrVU1QRmpTc1FBSWtGNWxacDZ6OXVyTlpvZE81dUlfVG9rZW46RDM3VWJEdGxvb3c4Rnd4ckFoSWNiaTJ0bmhkXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) |
| 分析大量数据：用户意图分析                                                                                              | 写代码分析数据 大量数据<br />（写代码是智能，写出的代码不是智能的，代码分析）                                                               | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YzAxOTE0OGI1NTliM2Q0MTZiMDI3MWJhNzNmYjhlZTFfVXU4cE1XY3hCbmxPTmVJM3pldHh3SGNJVmhtWUVWaUdfVG9rZW46UHFoYmJ0YWM2b0R1UGd4cHhBNWN3NVZUbmhmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) |
| 数据计算与验证：门店信息分                                                                                              | 快速准确，多维校验，任劳任怨                                                                                           | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=Y2I3MGQ1Zjk2ZTZlMTc1ODgzYjRmMTA3MTgzYjA4NjNfTUphSmV2MmJpS2NJMENVMkxwc0pDaU9DMDhla1hTYzJfVG9rZW46WEZzaWI5NHFqb3ByUUJ4VjN1R2NtU2phbllnXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) |
| 高级数据分析：清洗、降维、聚类等手段                                                                                         | 进阶工具型代码实现                                                                                                | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YzY0YWM4ZTE5Y2JhM2FjY2UxMDRkMjc4YTBhNDJiMGZfTjRBdDNnV1hzYmR1QUFDRURmcFNmZGVrUGtSWFRVcGxfVG9rZW46RlpBbmJXaWlMb3lXbVh4WjBraWNjMnNMbm1jXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) |
| 画原型<br /><span style="color: inherit; background-color: rgba(254,212,164,0.8)">Cursor 插件商店下载 pencil</span> | <span style="color: inherit; background-color: rgba(254,212,164,0.8)">html代码与原型 双向同步</span><br />支持参考图输入 | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MDZhOWNmOTE0YzhlYzY0MWEzNjUyZWZhMjQ5Y2IzZjlfZFE1SzlwNEtXM2hwSWE1UGNJRjNnYTBIbnVGUkhSSXNfVG9rZW46VnZYRWJTUnlOb1JBU0R4aU5ETWNzNDFKbkNlXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) |
| 写微博爬虫代码分析原神和王者荣耀粉丝的交际程度                                                                                    | 涉及公网数据                                                                                                   | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=Yjk2ZDk4N2E0ZTYxNTY0N2E0NGFlZDAxZmMyNmQ2YWFfd1FJNkRCYURLWVQ1NmxlYkxGSHQyWUkzc3lSbE5SdGhfVG9rZW46WEdGTWJiRVZIb0hlemt4OGVyaWNQRjFNbjNlXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) |
| 开发网页、小游戏                                                                                                   |                                                                                                          | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ODI3ZmQ4MDcyZmE3MWExYzBjZmQ3NDhhOTU4OTExOTVfM2hWbnVKYlZySkoydzB0dkJtYU1vYnl3Q0hwOWFKdlNfVG9rZW46VzNiRWJKb09ub1BpYVF4empCSWNaYklKbk1oXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) |
| 线上代码【案例来自前端开发工程师 】                                                                                         | 应用于生产级代码                                                                                                 | [<span style="color: rgb(36,91,219); background-color: inherit">[旅游租车]B端前端AI生成代码方案 </span>](https://trip.larkenterprise.com/wiki/LRaVw5AsriwPg6kNF05clZ9SnE5)                                                                                            |

可以用来辅助安装软件，部署大模型等

# **Openclaw 本地安装和实操**

现在市面上有各种一键安装或直接开袋即食的龙虾类产品，携程版龙虾 [<span style="color: rgb(36,91,219); background-color: inherit">openClaw携程版Ctrip-Claw使用文档</span>](https://trip.larkenterprise.com/docx/Ka49d2LAqosdTdxCCGbcJhq7nlh)

但考虑 个人定制化精细化配置、协作控制个人电脑和数据的便利性、执行过程可控性、拓展性、更新实时性 、方便了解底层原理，建议本地(家里个人电脑)安装原始版本。

### **大龙虾安装**

准备工作：准备模型api（参考第一章节）， 演示：glm-5  qwen3.5-plus  https://coding.dashscope.aliyuncs.com/v1   sk-sp-a2f70de8155a418d9574cba58313f6b9 (演示完会重置，)

<table><colgroup><col width="72"><col width="167"><col width="151"><col width="297"></colgroup>
<thead>
<tr>
<th></th>
<th>步骤</th>
<th>图示</th>
<th>注意</th>
</tr>
</thead>
<tbody>
<tr>
<td>开启安装</td>
<td>打开powershell，依次执行<br />指令：Invoke-WebRequest -Uri "https://openclaw.ai/install.ps1" -OutFile "$env:TEMP\install.ps1" -UseBasicParsing<br /><br />指令：&#x26; "$env:TEMP\install.ps1" -Tag latest</td>
<td><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=OTU1ZGFiYjBlMjViZTY2YTJmZWE5MzIwZjgzODUxYTFfSGY4UFRySk9NOVg5SzFBZnlxQXRrMURuVEdLRDRQeFVfVG9rZW46V3YyU2JPUG84b05kSXV4aXZOWWNJZElzbmlRXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt="">使用键盘上下左右空格选择、回车（确认）、esc（退出）：<img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=N2EzNDAyOWMzNzA0OGQ5NTg3NDAyYzgyMzllYTM3MWFfTFZMOTR5TG95OXNJVXFmRHJwRG1QVnR5OXBncGtnamVfVG9rZW46WEpROGI0d0dEb2xSTVV4TWI0cWN5T1BwbmhiXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt="">选择快速 或 手动 （多了一些配置选项） <img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YTUxMjg3NTg0MDM4NTdmM2IzNjgxYjFhODQwMDRhNDVfSUlXV25jN2Y0d0JjTHJ2ODlCT2hYT2F5enZwbEhJc2FfVG9rZW46U3pLa2JjT1lib1Bmb0V4QjlsQWNZRmRVbk9kXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
<td>1、如果需要指定路径安装需要先执行 $enV:OPENCLAW_HOME= "D:\Apps\openclaw"<ul>
<li>默认安装路径（一般无需过问，内置skill在其中）：某盘下的\Users（用户）\用户名\AppData（默认隐藏，需要开启隐藏）\Roaming\npm\node_modules\openclaw</li>
<li>默认工作空间路径：某盘下的\Users（用户）\用户名 \.openclaw</li>
<li>安装后可执行 openclaw info 或者和龙虾对话  查看路径</li>
</ul>2、nodenjs安装会会有弹窗 问是否同意联网<br />3、Mac用户：curl -fsSL https://openclaw.ai/install.sh | bash<br />如果提示缺失Homebrew 可再执行  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"    按提示配置环境变量后，再执行curl -fsSL https://openclaw.ai/install.sh | bash</td>
</tr>
<tr>
<td rowspan="2">安装完成后的配置</td>
<td>配置模型api服务</td>
<td><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NTkyMDVlZDQzNTBhMzM0MTM3NmRjMDM4MGZjODU2Yzdfd0xrNm82cnlweHYzQ054ZWJaNWQ3eHNtcmVsQ1JNdHlfVG9rZW46TEVkMGJ5d0pabzN2Yld4R2ZHZmN3S09lbldjXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
<td rowspan="2"><ul>
<li>可使用openclaw onboard 指令 重新进入</li>
<li>可以通过  命令行、自带网页后台、<span style="color: inherit; background-color: rgb(255,165,61)">本地配置文件修改</span>、命令行修改配置文件、<span style="color: inherit; background-color: rgb(255,165,61)">与龙虾对话（低智模型易改崩） </span> 四种方式实现配置的修改。</li>
</ul></td>
</tr>
<tr>
<td>....其余建议先跳过....<br />通信频道、安装技能、个别服务的api key、hook、</td>
<td></td>
</tr>
<tr>
<td>使用</td>
<td><ul>
<li>选择web ui ，自动打开浏览器进入后台页面。进行使用和配置</li>
<li>后面打开可直接通过 http://127.0.0.1:18789/</li>
</ul></td>
<td><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MWM5ZDYzMjhmNmMxOTA5Zjg1NzFjM2M5MTFjNGU0NzVfUjNkN3NqQW1DcnNVdWp6OGpEQXpoaURHUTFsQ0c5WHVfVG9rZW46RDlhamJiTmpvb21jdjZ4Vk1Tc2MyemNBbkdqXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NTAyMTJhN2ZjMmNjYjVjMDdmZGI1MGYzZTZlNWIzZmVfZ3VXS3FUZWl4UDJwWExBZ3J5SFNqbmRJZGl3NzU0dklfVG9rZW46T3ZCemJnVTdKb2hSMGF4UjR2MGNtUnU1bnRlXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NjI5MDVlYTFiYWEzMzY1YjBjNTgyZDhiZTJlMmUzOWRfVXBzQmh5YkYwalFEbEhjaXVLWWprY2tFczhvZVpGcFVfVG9rZW46QkZPWGJOUDQ3bzZCTkd4OTNMYmNVQTJOblk1XzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
<td><ul>
<li>如果没有自动跳出网页，可以复制图上链接 http://127.0.0.1:18789/ 首次需要带token（令牌）主动进入，如果打不开，可以重启服务 执行openclaw gateway 或者先 openclaw gateway stop 再openclaw gateway</li>
<li>如果首次进入，忘记token（令牌），可以在  某盘下的\Users（用户）\用户名 \.openclaw\openclaw.json文件中找，粘贴至后台</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NDFiMzQ5ODU5NjRmY2RjYjllMjI1NTMzNTZkOWMwM2JfMkk5NW9ZcW5mZzczUFVhZnh6a21BQmhBeWlDSEY5SWxfVG9rZW46TVNkZ2JncndPb0xINXJ4blVGbGN6bmt4bm1nXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
</tr>
<tr>
<td>开启/关闭服务</td>
<td>关闭服务：powershell 服务中  Ctrl c  或者 关闭 powershell 窗口 或者 执行 openclaw stop<br />开启服务：执行 openclaw gateway<br />（可执行 openclaw help 查看所有指令）</td>
<td><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YmVmNDE5ZTNjMjUwNzRlYWIxMDAyY2MxNTJmOTAwMjFfUFl0SDluYkI2TUdjaUdyRWVYRml0Y3NwbExFS25pRkNfVG9rZW46SlZJUmJ6S0hlb1h5bXZ4cmZFbGNRS1N6blhmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
<td></td>
</tr>
</tbody>
</table>

### **常用配置**

<table><colgroup><col width="73"><col width="91"><col width="218"><col width="73"><col width="121"><col width="112"></colgroup>
<thead>
<tr>
<th></th>
<th>终端命令行</th>
<th><span style="color: inherit; background-color: rgb(98,210,86)">修改文件</span><br /><span style="color: inherit; background-color: rgb(98,210,86)">注意备份，可在ai的帮助下</span></th>
<th><span style="color: inherit; background-color: rgb(98,210,86)">通过与龙虾对话进行配置</span></th>
<th>网页后台修改配置文件<br />菜单->配置->RAW模式</th>
<th>网页后台配置（不推荐，bug多 不齐全）</th>
</tr>
</thead>
<tbody>
<tr>
<td>模型\记忆召回embedding模型</td>
<td></td>
<td rowspan="3"><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NTFjZTQxNjU5MWY4MDJiMTcyOTk3ZGIyNTEyZWM2ODJfMVp6STZmclJPTU0wbVg2SGdva0RGcVpydkRROGtrZ1FfVG9rZW46Q2g3eWJtMmYzb3FuY1N4MjZCd2NGMGE4bmlmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><span style="color: inherit; background-color: rgb(255,233,40)">重点：</span><br /></td>
<td rowspan="3">先让他打印当前配置，查询 如何更改xx配置，有啥影响（保证一次改彻底），然后再让它改<img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ZjRlODNmOTYyMWUxMGU1MjM2MDE4NjdkYWRhZGYwODlfMTJxRDBCZGpmeE1XNDJ3ZDRKOVZ2eU10WTJNRzBPWGFfVG9rZW46VkNRTmI5S3Jtb1p0Q0l4QlJYNGNaRHhDbkRlXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=Yzg5ZjZhMDViYTE1MmRkYTg2ZGU2NTk2ZTZlMTFmZDFfRkNYWlVjMUFnN09ISTduclNEenRLc04zdU9jcjFmSlVfVG9rZW46UnRTbGJJd2J5b3VKVEJ4QzNkRWNnUTFibkVlXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""><span style="color: inherit; background-color: rgba(254,212,164,0.8)">注意别人使用你的龙虾可以问出你的key可以使用环境变量实现保密</span></td>
<td rowspan="4"><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MTJiZjkzZTllYWVjMGRmYTg2OGNmODI3ZmYwNmM4NTRfdVpjVUJubDJ1WnJvWnZqWU80ZmY3OUhFd2NwUDNsWlZfVG9rZW46UWZ0cWJQTWJ4b29qc2F4ejdqbGNKalVxblRoXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
<td rowspan="4"><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NWY3ZDE2YzUxNmE0YWMwOTg3YjVmZjBjMDVmYWMyMTdfaTZ3bDMxQkNwQnB6ZENpdnoxSnhNUFRlN1dwSWI2M2ZfVG9rZW46SWs2WGJKVGhBb29hd294d09PNGM3RFl2blBjXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
</tr>
<tr>
<td>频道（以飞书为例）<br /><br />1、飞书开发者后台新建应用：app id、 secret id、<span style="color: inherit; background-color: rgb(255,233,40)"> 配置权限</span><br /><span style="color: inherit; background-color: rgb(255,233,40)">（建议个人飞书账号）</span><br />2、openclaw侧配置。 3、飞书侧开启事件回调和发布应用</td>
<td><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MmRjZWIwYjc4MWQ5Y2YwYjk3MDAxYzQzNjBhYjExNTVfeE9wV3ZlOVFxWFN2Z1BVM2FwM2tyTHR2Z0t1MElvSmxfVG9rZW46QjA1T2JZNDJ3b1NyNHl4T2FTamNQZlJDbmxlXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt="">openclaw channels add</td>
</tr>
<tr>
<td>多agent &#x26; 频道</td>
<td><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YTNjMDRjNjE5OGY3MTExNGMzMjM1MjIwZmQ0NjhmYjJfNnhMWTB5UWgxaEhjMVMxTzVlaVo4R2psZDdOeE4zNUVfVG9rZW46SHFSaWJOWGFpb0dTQWl4QU8wTmNpOUF2bmZmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt="">openclaw agents add</td>
</tr>
<tr>
<td>人格定义</td>
<td>-</td>
<td>（打开文件夹演示 agents 文件）</td>
<td></td>
</tr>
<tr>
<td>技能</td>
<td>-</td>
<td colspan="2"><ul>
<li>https://clawhub.ai/skills?sort=downloads 下载后 整个文件（带skill名 ）放到.openclaw/skills、agent workspace/skills下 效果不一样</li>
<li>可与龙虾对话测试技能是否读取。注意 笨龙虾可能需要直白的技能唤醒词（例如告知这是飞书文档链接，它才会调飞书的skill）</li>
<li>有多模态模型，需要让龙虾配置 不同需求调用不同模型的技能</li>
<li>注意沙箱模式</li>
</ul><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NmViMzdmOWM1ODhkZWFlOGVhYWU3ZTA1NDQ3ODgzM2ZfWHVYNzVXejJaZFNRUU1xMnNTRFBhMGVpNWtrcmZyZ3pfVG9rZW46RWJJNmJKMW1Sb1NVc2d4Vmh0V2NyZzZEbjFmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>培养（参见下一章节最后）</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>

### **应用场景**

龙虾需要调教，特别是每个任务第一次执行时。所以以下案例保留了对话NG记录。

<table><colgroup><col width="120"><col width="397"><col width="172"></colgroup>
<thead>
<tr>
<th>类型</th>
<th>场景示例</th>
<th>注意事项</th>
</tr>
</thead>
<tbody>
<tr>
<td>【龙虾执行api】<ul>
<li>定期自动读邮件 分析邮件发报告、</li>
<li>定期执行dify 工作流</li>
</ul></td>
<td></td>
<td><ul>
<li>如果你告知龙虾 api的调用方法，或者龙虾可以自己查到（官方api）龙虾可以帮你执行。</li>
<li><span style="color: inherit; background-color: rgba(254,212,164,0.8)">有权限的话，可以执行任意软件或系统的 api，操作万物，之前是前端的交互、代码限制你 不乱输入、乱操作，现在一句话小龙虾就去直接调api了，所以非常危险。</span></li>
</ul></td>
</tr>
<tr>
<td>【无api、网页类  AI 实现自动化操作】<br />需登陆类： 每天8点打开IQ 页面 再点击每条IQ 再分析总结<br />无需登陆类：某官网信息查询<br /></td>
<td></td>
<td>养需要一定的技术含量，或者先问 有什么方案，明确最好的方案后再执行</td>
</tr>
<tr>
<td>【无api，客户端类 AI 实现自动化操作】</td>
<td><img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YTdkMjM1NWQzYWE1Y2Q4MjMwMWFkZDQ3NDE4ZjdkNjNfWENJR1d0dW9IWjB0bEF3eVV3bEpxQmRnNnI0dmVvYnBfVG9rZW46WGtmcWJrSFhNb2x2eFh4dHcxSGM1TXR1bnhkXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
<td><br />本质就是 ai创作和执行rpa工具，可以网上搜罗现成的各大软件的 rpa 技能。<br />或者现成rpa 配置文件，然后让龙虾写skill </td>
</tr>
<tr>
<td><span style="color: inherit; background-color: rgba(254,212,164,0.8)">多agent用云文档 协作</span> ：小红书运营<br />agent a : 每周1  都去小红书上查本周热门的 旅行目的地 帖子  、分析评论，然后登记在这个表格上。<br /><br />Agent b：每周2检查这个表格，如果有新的目的地或内容，都按要求 制作图片和帖子<br /><br />agent a : 每天下午6点  用小红书skill  按顺序发2个帖子出去，每天只发2篇。现在给我发一下前2篇 并在表格上登记新帖子的url。<br /><br />agent a : 每周1 分析热门的时候，同时看下之前我们发的帖子的评论内容分析记录下来。</td>
<td><br /><br /></td>
<td>1、云文档编辑利用了飞书skill，注意飞书侧的应用权限是否打开。<br />2、本案例借助了小红书skill（skil中教ai使用 小红书mcp ）即使用api方式 有被封号风险）<img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=OTgwYmY2YzAzODk3NWFlZWUyMWViZjJmMmZmMjQ2OGZfdjA0RlBOZzFxOGFQSG9kOGluUll3SEo5VlZ1THNRVXpfVG9rZW46RVFSZmJqdGJEb3NIUTR4UzhiMGNaMWh2bktiXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt="">3、使用前文 网页打开 和点击也可以实现，但速度会很慢。</td>
</tr>
<tr>
<td>多agent协作：娱乐案例</td>
<td>合理设置不同agent的人设 、监控所有群消息还是 只回答被@的消息<img src="https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NWViZmVjYzAyYmMzYTM5MjFjOTdiNDk3YmRhNDM1N2RfV2hpd1NDdVFqSEJwNXlMcGxLRGt3Mllid2RrVFFKckZfVG9rZW46UHhGQmI5YzBkb1JXdjd4NU9MOWNMbzlNbnpjXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA" alt=""></td>
<td></td>
</tr>
<tr>
<td>写代码做数据分析<br />（其它ai会的 ，它肯定会）</td>
<td></td>
<td>如图 小龙虾 是托管模式，更拟人，cursor是协作模式，更像工作台。</td>
</tr>
</tbody>
</table>

* 笨龙虾养护实录：

![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YmRhMjRhOWNhYjAyNzAzNjYwMWRmZDc0YTE2ODk1OTlfY2pqSEY1ejJwbm9CeXMycDlRSDUwcmVOclgwTmdPNjJfVG9rZW46UWFETWJISGJBb00xckN4eDJ3eGNQQzJObkhkXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)

* openclaw的和其它的agent相比，最大的优势是 24h\*n的执行者，即自动化能力。至于思考、创作工具、调用工具，其它agent也可以。示例：

| ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=YzE3MTM1MGQ0ZDgxYjUwNTczYjhjNzE4ZjIxZjYyNmVfc1dkYUNiT0hCRHlnenFTdkVYU29hb05WMVh2dmpyREFfVG9rZW46SnhyUmJnbWhCb0toZzF4RlM0T2M3bW8wbkVmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)Cursor 也可以 写代码实现 上述自动化，但是 是cursor产出的代码后，人执行代码 部署代码 实现 功能，而非cursor 去实现。dify也可以调用 小红书mcp执行 信息抓取和发帖。  从用户体验上来看 cursor是写 代码并调试，代码在 我们电脑上执行后 实现了打开浏览器、爬虫等，<span style="color: inherit; background-color: rgba(254,212,164,0.8)">人在控制 要不要执行、如何部署、24h时刻运行</span>，openclaw是自己在通过代码执行电脑，除非你关闭openclaw，所以说 openclaw是一个系统，cursor 是一个软件。 |   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | - |



***



***



Openclaw 卸载教程

回看第一章节，还是那句话，ai时代带来的是脑子，其使用的 xx工具，不是智能的，需要ai创作或者人类创作。。AI可以替代人执行一些工作，但工作本身没有减少，还是需要质量把控。 当你再看到 龙虾自动剪辑视频发抖音的 公众号文章 你会想什么？ &#x20;

| ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ZjU4NzVhYTFiODA0YTZlNDg0NDhkNDMzOTI4MjdiMDdfOVlFZ05ST1pnWVQ4bUdYbExjV0U4YnVlTWVBcXdlSVdfVG9rZW46R3llZmIzRTlMb1RQN3F4WjV5b2NWOFdybkdiXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)最贵模型 claude 4.6 opus  百万token 是10\~20块钱，满负荷使用一天花费在2000元，便宜模型大概十分之一![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=NWNhNDVjNTM4YzA2NTk5YjRmNTA0MzIwMTBmZGFlZWVfNTQ5eXB0ODNFZk9FUVFQUnBPdUltbnllUDcxNUJOV2FfVG9rZW46Rk5qOGJQU29vbzA5T3V4UmVLUmN0bnVobnZmXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA) | ![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=Njc2MGNhMjhlZjE3YTJkNDdkNWNiMDNjOGRlNGVkMTVfY3ZaUkl2Y3VaOUxMQnBYaXJrUkU4Y0tjNHNjbzV2bXpfVG9rZW46QXlONmJTR0FEbzJ0cnN4eWhNVWNVeVVhbjVjXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=Y2U4NTI4NzY0MjcwZGY5NWU1OWQwOGFjZmUzNWU0ODdfOFF5YkRFQWplUnB3NGwyUENHTnVVQlZQY0pLRFpZREdfVG9rZW46TFZ1VmJWTGZhb3RPNjN4bGhEVGNaeWZ6bkNjXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=MjY5YzBlZWQ5ZmQyM2M5OGMyYjI0NzdiMWIzMjU0NjdfUFJVUFM2amxyVDM1eFYxeEJGNHVmNXVUMGtDRlJZMXVfVG9rZW46UVM4SmJnWklzbzc2QVB4SWVVMWMzOUxsbmJkXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)公司电脑建议安装 公司封装的claw，参考前文  |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

# **未来几个关注点：**

* 能力主要取决于模型，选择一个好的模型最重要，否则就是学渣文具多。详询 第一部分的模型榜单、社区，时刻关注AI最新情况。

* 提示词工程，如何提问：可以让ai教你如何提问，重要性降低，[<span style="color: rgb(36,91,219); background-color: inherit">名词库</span>](https://trip.larkenterprise.com/wiki/OAezwaN0IilmqikiYQwcYnqtnSh) [<span style="color: rgb(36,91,219); background-color: inherit">旅游项目智能助理（分享）</span>](https://trip.larkenterprise.com/wiki/FoAgwlFuYiXDRNkYdhFcHjzznfe) [<span style="color: rgb(36,91,219); background-color: inherit">🎁 黄金提示词构建原则，claude code分享(2025/08/19  经验分享｜你的Prompt Engineering )</span>](https://trip.larkenterprise.com/wiki/Szsrwh5jViUyB9kTC0AcNOW8nLc)   [<span style="color: rgb(36,91,219); background-color: inherit">Prompt（提示词）</span>](https://trip.larkenterprise.com/wiki/NHRzwz6VziVLslk7QbqcTr4Dnfc)

* 上下文工程：多轮对话，模型累积的所有信息的管理。如何找准关键信息，去除无关信息？

![](https://scnltn2b2l4y.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDdkMGZhZGI4YjRhZWU2MjZiMzRmNTIwOWJjZGViZTFfWHpvajhKTDFzU2FSdDNrUEhZNFlGTFpBVmI5TTRFbFZfVG9rZW46RkxnVmJhZzlTbzh6VUd4QWNZT2NSUlhKbkFnXzE3Nzg4MTY2Nzg6MTc3ODgyMDI3OF9WNA)

* 知识库：智力都达到上限后，最终拼的是背后的优质 数据或内容，举例 ued团队搭建 调用ued专业美学知识的 aigc  dify工具

***
