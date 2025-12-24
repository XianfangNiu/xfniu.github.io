---
title: "我的第一篇AI教育文章"
date: 2025-12-24
categories: AI教育
tags: 教育投资, AI重构教育
---

# 写在前面
我大概是行业里少见的「全场景覆盖型」从业者——9年教育战略投资经历，完整见证了上一轮移动互联网浪潮下，在线教育从预热、爆发到疫情后的调整周期。疫情期间的行业停摆，反倒给了我深耕的机会：职业教育、家庭教育、健康教育、K12教育……我扎进了各类教育细分赛道的细节里，摸遍了不同场景的项目逻辑。

单论教育战略的全生命周期覆盖与纵深，若说「能把中国教育培训的细分场景与核心需求讲透」，我有足够的底气说一句：全行业舍我其谁。

选择在GitHub发文，源于一个简单的诉求：国内少有能承载深度行业分析的平台。今天是12月24日，从这一刻起，我会持续更新内容——核心目标只有一个：**给有志于用AI重做教育的技术人，完整描绘中国在线教育的全场景图谱**，让我们一起点燃AI服务教育的这把火。

# 这篇文章，将贯穿人的终身学习
教育从来不是某一个阶段的事，而是贯穿一生的持续行为：从牙牙学语的早期教育，到3-6岁的幼儿启蒙，6-18岁的K12体系，再到职高教育、高等教育；毕业后面临的考公考研、职业技能提升，乃至金融知识、生活技能的补充；人到中年的终身学习需求，直至晚年的老年大学……

全生命周期的教育，必然存在共通的底层逻辑。若抓不住这份共性，**所谓的「重构教育场景」不过是空中楼阁**。

如今的教育行业，最大的问题在于**过度碎片化**——我们从未站在真实用户的视角，思考过他们的多元需求。互联网产品人都懂：没有哪个成功的产品是纯垂直割裂的。就像视频平台，只会分频道，不会为综艺单独做一个APP、为纪录片再做一个APP……

但教育行业偏不。不同阶段、不同品类的教育需求，被拆成了一个个独立的赛道，各自为战。综艺有专属APP，纪录片有专属APP，育儿有专属APP，职场提升又有专属APP……大家辛辛苦苦做产品，最终却都陷入「小而散」的困境，连大厂都难以规模化切入———**要知道，这背后可是少说也是2-3亿人的刚性学习需求**。
| 学段       | 在校生人数 (万人) | 数据来源                                   |
| :--------- | ----------------: | :----------------------------------------- |
| 小学       |         10,584.37 | 2024 年全国教育事业发展统计公报             |
| 初中       |          5,386.16 | 2024 年全国教育事业发展统计公报             |
| 普通高中   |          2,922.30 | 国家统计局数据                             |
| 总计       | 18,892.83 (约1.89 亿) | 小学 + 初中 + 高中在校生人数之和 |

| 年龄段       | 对应出生年份 | 人口数量 (万人) |
| :----------- | :----------- | --------------: |
| 0 岁 (婴儿)  | 2024 年      |             954 |
| 1 岁         | 2023 年      |             902 |
| 2 岁         | 2022 年      |             956 |
| 3 岁         | 2021 年      |           1,062 |
| 4 岁         | 2020 年      |           1,200 |
| 5 岁         | 2019 年      |           1,465 |
| 6 岁         | 2018 年      |           1,523 |
| 7 岁         | 2017 年      |           1,723 |
| 总计         | 2017-2024 年 |           6,623 |


| 毕业年份 | 毕业生总数 (万人) | 同比增长 | 累计毕业生总数（万人） | 数据来源 |
| :------- | ----------------: | :------- | ----------------------: | :------- |
| 2020 年  |             874.0 | 4.8%     |                   874.0 | 教育部公布 |
| 2021 年  |             909.0 | 3.9%     |                  1783.0 | 教育部公布 |
| 2022 年  |            1076.0 | 18.4%    |                  2859.0 | 教育部公布 |
| 2023 年  |            1158.0 | 7.6%     |                  4017.0 | 教育部公布 |
| 2024 年  |            1179.0 | 1.8%     |                  5196.0 | 教育部公布 |

**真实用户的需求从来都是多元的**：一个年轻人可能今天想学占星，明天想补恋爱技巧，后天要学化妆；结婚前要了解婚礼流程，婚后要研究装修知识……这和购物逻辑一样，她既会买iPhone，也会逛拼多多，需求并不冲突。

也正因为这种碎片化，**现在的教育项目大多只能靠「做品牌、买流量」续命**。

站在传统教育公司的视角看AI，确实会瑟瑟发抖——那种「万箭齐发」的冲击感，让人确实完全不知道从哪里防守。

我也曾为这种冲击失眠一整晚，但转念一想：我已不在教育公司的位置上，何必纠结「防守」？不如和互联网大厂、技术创业者们一起，**主动「进攻」——用AI把教育重做一遍，这才是最有意思的事**。

# 就从-1岁开始吧：孕期教育
先分享一个行业真相：**如果能抓住孕期这个入口，理论上你能锁定一个用户至少6年**——从孕期陪伴到孩子4-5岁，妥妥的重度用户生命周期。

但看看之前的产品们，又把这个场景做碎了。

# Preface
I am probably one of the rare "full-scenario coverage practitioners" in the industry—with 9 years of experience in strategic education investment, I have witnessed the entire cycle of online education from its warm-up phase, boom, to post-pandemic adjustment driven by the last wave of mobile internet. The industry shutdown during the pandemic, instead, gave me the opportunity to delve deeper: vocational education, family education, health education, K12 education... I immersed myself in the details of various segmented education tracks and explored the project logic across different scenarios.

When it comes to the full lifecycle coverage and depth of education strategy, I have every confidence to say: if anyone can thoroughly explain the segmented scenarios and core needs of China's education and training industry, it’s none other than me.

I chose to publish on GitHub out of a simple need: there are few platforms in China that can host in-depth industry analysis. Today is December 24th, and from this moment on, I will continue to update content—with one core goal: **to provide a complete map of China's online education scenarios for technologists aspiring to reinvent education with AI**, and let us together ignite the spark of AI serving education.

# This Article Will Span Lifelong Learning
Education has never been limited to a single stage; it is a continuous process throughout life: from early childhood education for babbling infants, to preschool enlightenment for children aged 3-6, the K12 system for ages 6-18, followed by vocational high school education and higher education; after graduation, there are needs for civil service and graduate exam preparation, professional skill enhancement, as well as supplementary learning in financial knowledge and life skills; lifelong learning needs for middle-aged people, and even senior universities in old age...

Education across the entire lifecycle inevitably shares common underlying logic. If we fail to grasp this commonality, **the so-called "reconstructing education scenarios" will be nothing but castles in the air**.

The biggest problem in today's education industry is **excessive fragmentation**—we have never considered users' diverse needs from their perspective. Internet product professionals all understand: no successful product is purely vertically segmented. Just like video platforms, they only have channels instead of developing a separate app for variety shows or documentaries...

But the education industry is different. Educational needs at different stages and in different categories have been split into independent tracks, each operating in isolation. There are exclusive apps for variety shows, documentaries, parenting, and career advancement... Everyone works hard on product development, yet ultimately falls into the predicament of being "small and scattered", making it difficult even for major tech companies to scale up—**and let’s not forget, this represents a rigid learning demand of at least 200 to 300 million people**.

| Education Stage | Number of Enrolled Students (10,000) | Data Source |
| :-------------- | -----------------------------------: | :---------- |
| Primary School  |                            10,584.37 | 2024 National Statistical Communique on Education Development |
| Junior High School |                             5,386.16 | 2024 National Statistical Communique on Education Development |
| Senior High School |                             2,922.30 | National Bureau of Statistics Data |
| Total           |                18,892.83 (≈189 million) | Sum of enrolled students in primary, junior high, and senior high schools |

| Age Group       | Corresponding Birth Year | Population (10,000) |
| :-------------- | :----------------------- | ------------------: |
| 0 years old (infants) | 2024                     |                 954 |
| 1 year old      | 2023                     |                 902 |
| 2 years old     | 2022                     |                 956 |
| 3 years old     | 2021                     |               1,062 |
| 4 years old     | 2020                     |               1,200 |
| 5 years old     | 2019                     |               1,465 |
| 6 years old     | 2018                     |               1,523 |
| 7 years old     | 2017                     |               1,723 |
| Total           | 2017-2024                |               6,623 |

| Graduation Year | Number of Graduates (10,000) | Year-on-Year Growth | Cumulative Number of Graduates (10,000) | Data Source |
| :-------------- | ---------------------------: | :----------------- | --------------------------------------: | :---------- |
| 2020            |                         874.0 | 4.8%               |                                   874.0 | Ministry of Education Announcement |
| 2021            |                         909.0 | 3.9%               |                                 1,783.0 | Ministry of Education Announcement |
| 2022            |                       1,076.0 | 18.4%              |                                 2,859.0 | Ministry of Education Announcement |
| 2023            |                       1,158.0 | 7.6%               |                                 4,017.0 | Ministry of Education Announcement |
| 2024            |                       1,179.0 | 1.8%               |                                 5,196.0 | Ministry of Education Announcement |

**Users' real needs have always been diverse**: a young person may want to learn astrology today, make up for relationship skills tomorrow, and study makeup the day after; before marriage, they need to understand wedding procedures, and after marriage, they need to research home decoration... Just like shopping logic—they may buy an iPhone and also shop on Pinduoduo, with no conflict between needs.

Precisely because of this fragmentation, **most current education projects can only survive by "building brands and buying traffic"**.

From the perspective of traditional education companies, AI is truly intimidating—the sense of being "attacked from all sides" leaves people completely unsure where to defend.

I once lost sleep all night over this impact, but then I thought: I am no longer in the position of a traditional education company, so why dwell on "defense"? Instead, together with internet giants and tech entrepreneurs, **we should take the initiative to "attack"—reinventing education with AI is the most interesting endeavor**.

# Let’s Start from -1 Year Old: Prenatal Education
First, share an industry truth: **if we can capture the prenatal education entry point, theoretically we can retain a user for at least 6 years**—from prenatal companionship to the child being 4-5 years old, a solid lifecycle of heavy user engagement.

But look at previous products—they have fragmented this scenario yet again.
