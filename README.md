# SEO 概念

一、Indexability（可索引性）

比排名更重要：能不能进索引池

核心一句话

SEO 的第一关不是“排第几”，而是“有没有资格被排”。

你要牢记的点
	•	robots.txt → 决定能不能抓
	•	noindex → 决定能不能收
	•	canonical → 决定算哪个 URL
	•	sitemap → 决定优先抓谁

Stake 风格理解
	•	play / demo / user / modal
👉 不是 SEO 页面，直接剥夺索引资格
	•	casino / blog / promotions
👉 给足信号，让它们进索引池

⸻

二、Index Bloat（索引膨胀）

比没收录更可怕

什么是 index bloat

Google 索引里有一堆
你自己都不想让用户搜到的垃圾页

赌场 / Next.js 的典型来源
	•	?modal=xxx
	•	?tab=xxx
	•	play / demo 页
	•	无限 filter / sort / page
	•	utm 未 canonical

后果
	•	crawl budget 被吃
	•	权重被稀释
	•	核心页反而排不上

📌 Stake 的 robots 本质就是在防 index bloat

⸻

三、Canonicalization（规范化）

“这堆 URL，Google 到底该信哪一个？”

一句话

canonical 是你对 Google 说：
“内容是同一份，但我只认这个 URL。”

你必须记住
	•	canonical ≠ redirect
	•	canonical 是“建议”，不是“命令”
	•	canonical 错了 = SEO 自杀

Stake 风格应用
	•	所有 utm / tracking / modal URL
👉 canonical 到主页面
	•	绝不让 play 页成为 canonical

⸻

四、Internal Linking（内链权重分配）

你自己决定权重往哪流

核心认知

Google 不是“自动理解你的网站”，
它是靠链接结构猜的。

Stake 的隐性策略
	•	casino 首页 → 分类 → 游戏详情（非 play）
	•	blog / guides → casino / promotions
	•	footer 强内链品牌 / 合规页

对你非常重要的一点

不要用 JS-only 的不可 crawl 链接做核心导航

⸻

五、Search Intent（搜索意图匹配）

不是关键词，而是“用户到底想干嘛”

三类最重要的意图
	1.	Informational
	•	how / guide / what is
	2.	Navigational
	•	brand / product / feature
	3.	Transactional（最值钱）
	•	play / bonus / promotion / free

Stake 的聪明之处
	•	Transactional 页面：casino / promotions
	•	Informational 页面：blog / guides
	•	play 页：完全不参与 SEO

⸻

六、Content Quality ≠ 长，而是“可被理解”

Google 不是人，但它会判断“是不是在糊弄”

你要牢记
	•	casino 类目页 ≠ 纯 UI
	•	一定要有：
	•	可读文本
	•	结构化段落
	•	FAQ / lists
	•	AI 生成内容 必须人工校正

📌 Stake 的 casino/home 页面，本质就是“高转化 landing + SEO 内容”。

⸻

七、Freshness & Update Signals（更新信号）

Google 更爱“活着的网站”

不是所有页面都要常更新
	•	blog / promotions：需要
	•	静态政策页：不需要
	•	play 页：不该存在于 SEO 世界

关键点
	•	sitemap lastmod
	•	页面真实内容变化（不是时间戳作假）

⸻

八、Soft 404 / Thin Content

“看起来是页面，其实什么都没有”

赌场站常见
	•	provider / game 页只有一个卡片
	•	geo block 后返回空壳页面
	•	未登录状态下的“半页面”

处理原则
	•	不满足最低内容阈值 → noindex
	•	或统一重定向到可读 landing

⸻

九、Page Experience（不是 Core Web Vitals 本身）

你不需要记每个分数
你只要记住一句话：

SEO 页面 ≠ 游戏页面

	•	SEO 页面：
	•	快
	•	稳
	•	可预渲染（SSG / ISR）
	•	play 页面：
	•	可以慢
	•	可以重 JS
	•	但必须 noindex

Stake 本质是把两种页面彻底解耦。

⸻

十、E-E-A-T（赌场 / sweepstakes 特别重要）

你至少要做到
	•	明确的品牌主体
	•	可访问的合规 / policy 页面
	•	联系方式 / 公司信息
	•	sponsorship / PR 内容

Stake 的 sponsorship sitemap
👉 本质就是 E-E-A-T 的外显资产

⸻

一张「SEO 记忆卡片」（你可以直接保存）

SEO = 管资源，而不是堆技巧

你必须长期记住的 10 个关键词：
	1.	Crawl Budget
	2.	Indexability
	3.	Index Bloat
	4.	Canonical
	5.	Internal Linking
	6.	Search Intent
	7.	Content Quality
	8.	Freshness
	9.	Soft 404 / Thin Content
	10.	E-E-A-T

⸻

给你一个非常实用的判断标准（Stake 级）

问自己一句话：

“如果我是 Google，
我愿不愿意
把 crawl budget 用在这个页面上？”

如果答案不是 毫不犹豫的 YES：
👉 那这个页面就 不该进 SEO 世界。

