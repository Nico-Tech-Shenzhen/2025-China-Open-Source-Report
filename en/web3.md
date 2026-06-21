# Web3.0 Open Source Ecosystem: Contribution Insights from Chinese-Speaking Developers

## Report Notes

### Research Background

This report is the supporting document for the Web3.0 insights chapter of the 2025 China Open Source Annual Report. The analysis and writing were conducted by OpenBuild and Web3insight.ai.

Web3.0 is built on open source protocols. Whether Ethereum, Bitcoin, Solana, or other ecosystems, the underlying infrastructure is developed, maintained, and evolved in the open. The scale and quality of Chinese-speaking developers' contributions to these protocols form an important lens for understanding how China's open source community participates in global technical collaboration. Yet this topic has long lacked systematic data.

This report addresses three questions:

- What is the scale and quality of Chinese-speaking developers' contributions to global Web3.0 open source protocols?
- Over the past five years, how have Chinese-speaking communities shifted their protocol preferences?
- What bottlenecks do Chinese-speaking developers face in deeper open source contribution, and how can those barriers be reduced?

### Data Sources

**Primary data: Electric Capital Open Source Developer Data**

Electric Capital is a crypto-native venture capital firm. Since 2019, it has maintained one of the most authoritative datasets on Web3.0 developer activity. The dataset covers:

- Commit activity from more than 3 million developers across blockchain-related open source repositories
- Developer attribution across 500+ blockchain ecosystems
- Time range: 2008 to present. This report uses version 20260321T133239, with data through March 13, 2026
- License: CC BY 4.0, allowing reuse and redistribution with attribution
- Data URL: https://data.opendevdata.org

**Supplementary data: 2025 Web3.0 Chinese-Speaking Developer Survey Report**

The survey was jointly initiated by OpenBuild, GCC, DengLian, Creators, and OpenCAS, with data analysis provided by Web3insight.ai. It collected 220 valid responses in late 2025, covering career paths, technical preferences, income structures, and open source participation among Chinese-speaking Web3.0 developers. This report references its qualitative findings alongside Electric Capital's quantitative data.

::: tip Further Reading: OpenBuild Web3 Developer Report
The Chinese-speaking developer survey cited in this chapter, along with future annual updates, will continue to be organized on the OpenBuild developer report site. For full charts, methodology notes, and historical versions, visit: https://report.openbuild.xyz/

2025 Chinese-Speaking Developer Report: https://report.openbuild.xyz/zh/2025/

Source repository: https://github.com/openbuildxyz/web3-chinese-speaking-devs-report
:::

### Data Limitations

**Geographic attribution coverage**: In the Electric Capital dataset, about 870,000 developers, or roughly 27% of the total, have clear geographic records. Chinese developers are significantly less likely than developers in Europe and North America to fill in GitHub location fields. As a result, the number of Chinese-speaking contributors is systematically underestimated. Based on cross-checks with GitHub Octoverse and other sources, this report estimates that the actual scale of Chinese-speaking Web3.0 developers may be **3-4 times** the observed number.

**Monthly active developer (MAD) definition**: A monthly active developer is defined as someone who made at least one valid commit to a blockchain-related open source repository in the past 30 days. This metric favors core contributors and does not include people who only read code, submit issues, or participate in discussions.

**Ecosystem attribution method**: One developer may be active in multiple ecosystems. Therefore, ecosystem-level developer counts can sum to more than the global total. Chinese-speaking shares in this report are calculated under the same methodology.

**Open source data as the main lens**: The analysis is primarily based on GitHub open source contribution data. Developers who contribute through private repositories or non-open-source channels may not be included, so the data may differ from community impressions.

### Reading Guide

| Section | Core Question |
| ------- | ------------- |
| 1. Global Trends | Long-term contributor trends and professionalization in Web3.0 open source protocols |
| 2. Global Position | The real share and "invisibility" of Chinese-speaking contributors in global protocols |
| 3. Ecosystem Distribution | Which open source protocols attract the most Chinese-speaking contributors |
| 4. Preference Shifts | Protocol preference shifts among Chinese-speaking communities from 2021 to 2025 |
| 5. City Distribution | The spatial structure of Web3.0 open source contributors in Mainland China |
| 6. Protocol Health | Contributor health across major Web3.0 open source protocols |
| 7. Open Source Contribution | Current contribution depth and improvement paths for Chinese-speaking developers |
| 8. Recommendations and Outlook | Actionable suggestions for developers, communities, and ecosystems |

---

## 1. Global Web3.0 Open Source Contributor Trends

In open source, the health of a protocol ultimately depends on how many people continue contributing to its codebase, rather than on price movements or social media attention. Since all major Web3.0 base protocols operate as open source systems, long-term contributor trends are a core signal for judging whether an ecosystem can keep evolving.

### 1.1 Contributor Quality: The 2025 Peak Was More Solid Than 2022

![Monthly active developers vs full-time developers, 2022-2026](/image/web3/global-mad-fulltime.png)

| Date | Monthly Active Developers | Full-Time Developers | Full-Time Share |
| ---- | ------------------------- | -------------------- | --------------- |
| 2022-01 | 31,394 | 7,879 | 25.1% |
| 2022-06 | 34,553 | 9,511 | 27.5% |
| 2022-12 | 31,716 | 9,617 | 30.3% |
| 2023-12 | 31,729 | 9,665 | 30.5% |
| 2024-06 | 36,857 | 10,278 | 27.9% |
| 2025-05 | 44,261 | 10,973 | 24.8% |
| 2026-03 | 29,679 | 9,291 | 31.3% |

Monthly active contributors reached a historical peak of **44,000** in May 2025, surpassing the 2022 bull-market high of 35,000. By early 2026, the number had corrected to around **29,700** (YoY -15%), but full-time contributors remained relatively stable at more than 9,000.

The key signal: **the share of full-time contributors rose from 25% in 2022 to 31% in 2026**. Full-time contributors are core maintainers who consistently submit code every month. A higher share means the long-term maintenance capacity of Web3.0 open source protocols is strengthening. Even when total contributor counts fluctuate with market cycles, the underlying maintenance base has not collapsed.

> **Insight 1**: Web3.0 open source protocols are undergoing a deeper transition from hype-driven participation to professionalized core maintenance. Bear markets act as filters; those who remain are the long-term builders. The resilience of open source protocols comes from full-time contributors who do not simply follow the market.

---

## 2. The Position of Chinese-Speaking Developers in Global Protocols

Chinese names remain rare in the contributor lists of mainstream Web3.0 open source protocols. Whether among core maintainers of Ethereum clients or major contributors to Solana runtime components, Chinese-speaking developers often appear "invisible." But is this invisibility a real absence, or a systematic undercount caused by data methodology?

### 2.1 Country Distribution of Global Web3.0 Developers, Past Year, With Geographic Records

![Top 10 countries by monthly active Web3.0 developers](/image/web3/global-country-top10.png)

| Rank | Country | Active Developers | Share |
| ---- | ------- | ----------------- | ----- |
| 1 | India | 4,768 | 28.1% |
| 2 | United States | 3,645 | 21.5% |
| 3 | Nigeria | 1,088 | 6.4% |
| **4** | **China (Mainland)** | **871** | **5.1%** |
| 5 | United Kingdom | 852 | 5.0% |
| 6 | Canada | 763 | 4.5% |
| 7 | Brazil | 762 | 4.5% |
| 8 | Germany | 733 | 4.3% |
| 9 | France | 692 | 4.1% |
| 10 | Indonesia | 674 | 4.0% |

> **Statistical gap note**: The table only reflects the roughly 27% of developers with geographic records. Chinese developers are much less likely than European and North American developers to fill in GitHub location fields, leading to systematic undercounting. Cross-checking with GitHub Octoverse and related data suggests that Chinese-speaking developers, including Taiwan and Hong Kong, may account for **15-20%** of the global Web3.0 open source ecosystem, about 3-4 times the observed figure.

### 2.2 Country Distribution in the Ethereum Ecosystem, Past Year

![Top 10 countries in the Ethereum ecosystem by monthly active developers](/image/web3/ethereum-country-top10.png)

| Rank | Country/Region | Developers | Share |
| ---- | -------------- | ---------- | ----- |
| 1 | India | 2,830 | 38.8% |
| 2 | United States | 1,797 | 24.7% |
| 3 | China (Mainland) | 496 | 6.8% |
| 4 | United Kingdom | 415 | 5.7% |
| 5 | Brazil | 391 | 5.4% |
| Appendix | Taiwan | 116 | 1.6% |
| Appendix | Hong Kong | 84 | 1.2% |

*Taiwan and Hong Kong are shown as appendix data and are not included in the ranking.*

Mainland China ranks third with 496 developers, or 6.8%. Including Taiwan (116) and Hong Kong (84), Chinese-speaking developers account for **9.6%** of the Ethereum ecosystem, making them the third-largest language community.

**Source cross-check**: The 2025 Web3.0 Chinese-Speaking Developer Survey Report points to the root cause of this "invisibility": English collaboration ability is the key visibility threshold. Most Chinese-speaking developers can read English documentation independently, but far fewer can participate fluently in international protocol PR reviews, submit RFCs, or join core protocol discussions. Chinese-speaking developers are often present but quiet. Code contributions exist, but influence within international open source communities is not accumulated at the same pace.

> **Insight 2**: Chinese-speaking developers' contributions to global Web3.0 protocols are significantly underestimated. The reasons include both statistical methodology and real gaps in depth of participation. Improving visibility requires two parallel efforts: individual developers improving English collaboration skills, and ecosystems and community organizations actively building Chinese technical documentation to lower contribution barriers.

---

## 3. Distribution of Chinese-Speaking Developers Across Major Protocols

The appeal of different open source protocols to Chinese-speaking developers reflects real technical preferences within the community. Which protocol codebases concentrate the most Chinese-speaking contributors? A high Chinese-speaking share may indicate stronger Chinese documentation and community resources, or, in some cases, early and deep participation by Chinese-speaking communities in building the protocol.

### Contribution Distribution of Chinese-Speaking Developers Across Major Protocols, Past Year

![Chinese-speaking developer ecosystem distribution, Mainland China vs Hong Kong and Taiwan, monthly active](/image/web3/chinese-ecosystem-distribution.png)

| Ecosystem | Mainland China | Hong Kong and Taiwan | Chinese-Speaking Total | Global With Records | Chinese-Speaking Share |
| --------- | -------------- | -------------------- | ---------------------- | ------------------- | ---------------------- |
| Ethereum | 496 | 200 | 696 | 48,112 | **1.4%** |
| Solana | 269 | 71 | 340 | 26,543 | 1.3% |
| Sui | 111 | 41 | 152 | 6,138 | **2.5%** |
| Base | 99 | 42 | 141 | 12,699 | 1.1% |
| BNB Chain | 107 | 33 | 140 | 7,232 | 1.9% |
| Bitcoin | 113 | 26 | 139 | 8,646 | 1.6% |
| Polygon | 104 | 27 | 131 | 10,830 | 1.2% |
| Arbitrum | 84 | 38 | 122 | 7,725 | 1.6% |
| Cosmos | 34 | 10 | 44 | 2,032 | **2.2%** |
| Starknet | 24 | 8 | 32 | 3,561 | 0.9% |
| Stellar | 12 | 0 | 12 | 5,546 | **0.2%** |

**Key findings:**

- **Sui has a Chinese-speaking share of 2.5%**, the highest among major ecosystems and nearly twice Ethereum's 1.4%. Move has formed a concentration effect in Chinese-speaking communities.
- **Cosmos has a Chinese-speaking share of 2.2%**, related to community accumulation since the Tendermint era.
- **BNB Chain's Chinese-speaking share is only 1.9%**, meaning actual open source contribution does not match the chain's visibility in Chinese-speaking communities.
- **Stellar's Chinese-speaking share is only 0.2%**, with almost no Chinese technical documentation or community infrastructure.

**Source cross-check**: The survey shows that Ethereum leads public-chain attention by a large margin, while Move is repeatedly mentioned as the "second language most worth learning." This strongly aligns with Sui's high Chinese-speaking contributor share. Developer intention in the survey and actual behavior in commit data point in the same direction.

> *Chart: public-chain attention among Chinese-speaking developers. Source: 2025 Web3.0 Chinese-Speaking Developer Survey Report.*
> ![Public-chain attention among Chinese-speaking developers](/image/web3/chain-attention.png)

> **Insight 3**: The high share of Chinese-speaking developers in the Sui ecosystem is both an advantage and a responsibility. The serious shortage of Chinese documentation, tutorials, and community support is an urgent gap to fill.

---

## 4. Protocol Preference Shifts in Chinese-Speaking Communities, 2021-2025

Over five years, which open source protocols have Chinese-speaking developers continued to contribute to? The chart below reflects more than market preference. It records collective judgment and migration paths in open source technical choices.

### Annual Active Chinese-Speaking Contributors Across Major Protocols, Deduplicated

![Chinese-speaking developer counts across major ecosystems, 2021-2025](/image/web3/ecosystem-contributors-2021-2025.png)

| Year | Ethereum | Solana | BNB Chain | Sui | Bitcoin | TON | Aptos |
| ---- | -------- | ------ | --------- | --- | ------- | --- | ----- |
| 2021 | 252 | 139 | 86 | 8 | 49 | 5 | 13 |
| 2022 | 528 | 201 | **160** | 57 | 47 | 17 | 84 |
| 2023 | 425 | 149 | 120 | 90 | 72 | 35 | 63 |
| 2024 | 446 | **334** | 74 | **204** | 107 | 99 | 69 |
| 2025 | **670** | 352 | 132 | 170 | 139 | 44 | 65 |

**Four key curves:**

**Decline in BNB Chain open source contribution**: Active contributors fell from a 2022 peak of 160 to 74 in 2024 (**-54%**). The data suggests that maintenance activity in BNB Chain's open source protocols has not sustained continued participation by Chinese-speaking communities. There is a clear gap between contribution data and external narratives.

**Solana's V-shaped open source recovery**: After market shocks in 2023, contributor numbers fell to 149, then rebounded to 334 in 2024 (**+124%**). Solana's continued maintenance of core repositories during the downturn was key to attracting Chinese-speaking contributors back. Sustained technical investment is more convincing than market sentiment.

**Continuous growth of Chinese-speaking contributors to Sui**: Contributor count rose from 8 in 2021 to 204 in 2024 (**+2450%**). As an emerging smart contract paradigm, Move attracted large-scale participation from Chinese-speaking communities early in the protocol's development, forming sustained contribution accumulation rather than a short-lived hype wave.

**TON's short-lived contributor surge**: TON peaked at 99 contributors in 2024 before falling quickly to 44. Contributors came with market attention, but TON's documentation quality, toolchain maturity, and community response speed did not retain them. This confirms the limitation of hype-driven participation.

**Source cross-check**: The survey identifies three top factors in protocol selection: ecosystem scale and opportunities, long-term technical direction, and the quality of Chinese community support. Chinese documentation and open source community support directly affect whether Chinese-speaking developers can accumulate sustained contributions in a protocol.

> **Insight 4**: Chinese-speaking developers' protocol choices are a leading indicator of open source ecosystem health. A protocol can retain Chinese-speaking contributors when its technical direction has long-term value, its open source community keeps maintaining through downturns, and Chinese documentation and contribution paths are clearly visible.

---

## 5. City Distribution of Open Source Contributors in Mainland China

The spatial distribution of Web3.0 open source contributors reflects the regional pattern of China's open source ecosystem. Which cities gather the most developers who continuously contribute to Web3.0 protocols?

### Top 10 Cities for Web3.0 Open Source Contributors, Past Year, With Geographic Records

![Top 10 Chinese cities by active Web3.0 developers](/image/web3/china-city-top10.png)

| Rank | City | Active Developers | Share of Chinese-Speaking Total |
| ---- | ---- | ----------------- | ------------------------------- |
| 1 | Beijing | 171 | 12.4% |
| 2 | Shanghai | 168 | 12.2% |
| 3 | Hangzhou | 99 | 7.2% |
| 4 | Shenzhen | 94 | 6.8% |
| 5 | Chengdu | 44 | 3.2% |
| 6 | Guangzhou | 32 | 2.3% |
| 7 | Wuhan | 18 | 1.3% |
| 8 | Nanjing | 15 | 1.1% |
| 9 | Xi'an | 11 | 0.8% |
| 10 | Xiamen | 10 | 0.7% |

**Three noteworthy patterns:**

**Dual centers rather than a single pole**: Beijing (171) and Shanghai (168) are nearly equal, together accounting for about 24.6%. This is much less concentrated than the traditional internet industry's "Beijing-Shanghai-Shenzhen above 75%" pattern. The decentralized nature of Web3.0 open source contribution is reflected in geographic distribution.

**Hangzhou surpasses Shenzhen**: Hangzhou ranks third with 99 developers, ahead of Shenzhen's 94. Hangzhou has active blockchain technology open source communities, such as DengLian and multiple EVM toolchain maintainer groups. Combined with Zhejiang University's engineering culture, this has created a strong open source contribution atmosphere.

**Chengdu as the western contribution center**: Chengdu ranks first in western China with 44 developers. Active Chinese-speaking Web3.0 learning communities such as Dapp-Learning and HOH have important nodes in Chengdu. This "learning-driven contribution" model is an important reason for the city's concentration of contributors.

**Source cross-check**: The survey reveals a "geographic arbitrage" pattern: many developers choose to live in second-tier cities, maintain domestic living costs, and receive compensation in dollars or stablecoins to maximize purchasing power. This explains why Web3.0's city distribution is much more even than that of the internet industry. When workplace location no longer equals employer city, developers choose more rationally among cost of living, livability, and community density.

> *Chart: geographic distribution of Chinese-speaking developers. Source: 2025 Web3.0 Chinese-Speaking Developer Survey Report.*
> ![Geographic distribution of Chinese-speaking developers](/image/web3/geographic-distribution.png)

> **Insight 5**: Web3.0's remote collaboration culture is reshaping the spatial distribution of Chinese developers. Hangzhou, Chengdu, Wuhan, and other cities are becoming new Web3.0 talent hubs. The monopoly of Beijing, Shanghai, and Shenzhen over technical talent is being weakened.

---

## 6. Contributor Health of Major Web3.0 Open Source Protocols, 2026-03

The health of an open source protocol should not be measured only by total contributor count. Contributor structure matters: the share of full-time maintainers for long-term sustainability, inflow of new contributors for ecosystem vitality, and contributor exclusivity for community stickiness. The table below presents a six-dimensional snapshot of contributor health across 15 major Web3.0 protocols.

### Contributor Health Overview of Major Protocols

| Ecosystem | Monthly Active Developers | YoY | Full-Time Share | Newcomer Share | Exclusive Share | Chinese-Speaking Share* |
| --------- | ------------------------- | --- | --------------- | -------------- | --------------- | ----------------------- |
| Ethereum | 10,926 | -23% | 33% | 38% | 45% | 1.4% |
| Solana | 3,904 | -26% | 29% | 45% | 49% | 1.3% |
| Bitcoin | 2,941 | -15% | 33% | 39% | 56% | 1.6% |
| **Base** | **2,525** | **+25%** | 23% | **52%** | 20% | 1.1% |
| Polygon | 2,032 | +3% | 27% | 49% | 19% | 1.2% |
| Arbitrum | 1,829 | +1% | 26% | 43% | 15% | 1.6% |
| **ICP** | **1,661** | **+83%** | 11% | **82%** | **91%** | 0.7% |
| Cosmos | 1,449 | -37% | 26% | 29% | 47% | 2.2% |
| **Stellar** | **1,218** | **+40%** | 20% | 49% | 57% | 0.2% |
| Polkadot | 1,090 | -34% | 34% | 25% | 42% | 1.7% |
| BNB Chain | 1,074 | -24% | 25% | 44% | 19% | 1.9% |
| Optimism | 1,065 | -13% | 22% | 39% | 13% | 1.5% |
| Sui | 940 | -20% | 30% | 36% | 45% | **2.5%** |
| Starknet | 764 | -41% | 24% | 35% | 35% | 0.9% |
| TON | 550 | -29% | 27% | 37% | 50% | 1.3% |

*Chinese-speaking share is based on the subset with geographic records. The actual value may be higher.*

![YoY growth rates of major ecosystems, 2026-03](/image/web3/ecosystem-yoy-growth.png)

### How to Read the Table

**Five protocols growing against the trend**: ICP (+83%), Stellar (+40%), Base (+25%), Polygon (+3%), and Arbitrum (+1%). Against the broader pullback in contributor counts, these protocols attracted net inflows of new contributors, indicating real building demand in their open source ecosystems.

**ICP's hidden concern**: ICP shows +83% YoY growth, but newcomers account for 82% and exclusivity reaches 91%, meaning there is little migration from experienced contributors in other protocols. Behind the rapid growth, the depth of accumulated community knowledge remains to be proven. Its Chinese-speaking share is only 0.7%, and Chinese contribution guides are almost absent.

**Base's healthy signal**: Base shows +25% YoY growth, a newcomer share of 52%, and an exclusivity rate of only 20%. Many developers with EVM open source experience are also active in Base, creating a healthy mix of new and experienced contributors.

**Source cross-check**: In the survey, developers ranked "ecosystem opportunity density" (grants, bounties, and product demand) as the top consideration for choosing which protocol to contribute to, above purely technical advancement. The maturity of open source incentive mechanisms directly affects Chinese-speaking contributors' willingness to participate.

> *Chart: primary motivations for Chinese-speaking developers entering Web3.0. Source: 2025 Web3.0 Chinese-Speaking Developer Survey Report.*
> ![Motivations for Chinese-speaking developers entering Web3.0](/image/web3/entry-motivation.png)

> **Insight 6**: Contributor health across Web3.0 open source protocols is diverging quickly. The key indicators for whether a protocol is worth long-term building are not scale alone, but contributor structure: full-time contributor share for sustainability, new contributor inflow for vitality, and cross-protocol contributor share for openness. For Chinese-speaking open source communities, Sui, Base, and ICP represent three different entry points: Sui has the highest Chinese-speaking contributor share and needs Chinese knowledge infrastructure; Base has a low contribution barrier and transferable EVM skills; ICP has almost no Chinese contribution guides and therefore a clear gap to fill.

---

## 7. Current Open Source Contribution Status of Chinese-Speaking Developers

The Web3.0 ecosystem is built on open source protocols, but there is a large gap between "using open source" and "contributing to open source." Understanding the real contribution depth of Chinese-speaking communities in Web3.0 is this chapter's core contribution to the China Open Source Annual Report.

### 7.1 High Dependency, Insufficient Depth of Participation

The 2025 Web3.0 Chinese-Speaking Developer Survey Report reveals a typical "free-rider structure": almost all Chinese-speaking Web3.0 developers rely heavily on open source components, but very few become long-term maintainers or core contributors.

- **Many submit issues; fewer submit PRs**: Far more developers can read code and identify problems than can submit fixes.
- **Primary motivation**: learning and skill improvement rank first, followed by solving problems encountered in their own work.
- **Primary barriers**: lack of time, unclear paths, difficulty finding suitable beginner projects, and insufficient English collaboration ability.

> *Chart: contribution activity of Chinese-speaking developers in core Web3.0 repositories. Source: 2025 Web3.0 Chinese-Speaking Developer Survey Report.*
> ![Contribution activity in core Web3.0 repositories](/image/web3/core-repo-contribution.png)

Behind this pattern is the long-term absence of **Chinese technical knowledge infrastructure**. High-quality Chinese protocol documentation, beginner-friendly contribution guides, and active Chinese technical discussion communities are necessary for Chinese-speaking developers to move from users to contributors.

### 7.3 New Experiments in Web3.0 Open Source Incentives

Web3.0 is experimenting with grants, bounties, token rewards, and on-chain reputation systems to reshape the incentive structure for open source contribution. These mechanisms offer global developers, including Chinese-speaking developers, new paths beyond the traditional voluntary contribution model. They are still experimental, but their direction is worth watching:

- **Grant programs** such as Ethereum Foundation and Solana Foundation grants provide protocol-level funding for independent developers and teams.
- **Bounty platforms** such as Gitcoin turn specific needs into paid tasks, lowering contribution barriers.
- **On-chain reputation** can put contribution records on-chain and create verifiable technical credit.

> **Insight 7**: The main weakness of Chinese-speaking communities in Web3.0 open source is not technical capability, but the visibility of participation paths. Building high-quality Chinese technical documentation, providing clear onboarding for junior contributors, and improving Chinese access to grant and bounty information are direct contributions that China's open source community can make to the global Web3.0 ecosystem.

---

## 8. Recommendations and Outlook

Chinese-speaking participation in the Web3.0 open source ecosystem has evolved from early "followers" into a force that cannot be ignored. By scale, Chinese-speaking developers are the world's second-largest language community. In some protocols such as Sui and Cosmos, their contribution share is already above the global average. But there remains a clear gap between scale and influence.

### 8.1 Recommendations for Individual Developers

**Go deep in protocols with Chinese community support instead of chasing every trend**

Data shows that Chinese-speaking developers have significantly higher contribution shares in protocols with mature Chinese communities, such as Sui (2.5%) and Cosmos (2.2%). Choosing one protocol with Chinese documentation, active discussions, and a clear contribution path creates more long-term value than restarting with every new market trend.

**Upgrade from submitting issues to submitting PRs**

The survey shows that Chinese-speaking developers often stop at the "finding problems" stage rather than moving into the "fixing problems" stage. Joining organized learning communities with clear contribution paths, such as Dapp-Learning and letsmove, is one of the lowest-cost ways to move from reader to contributor. Together, those two repositories have accumulated more than 3,700 PRs, proving that this path works.

**English collaboration ability is the basic threshold for visibility**

The short-term practical way to improve the "present but quiet" problem is not to wait for ecosystems to provide Chinese interfaces, but to actively participate in English PR reviews and technical discussions. This is the necessary path for Chinese-speaking contributors to grow from code contributors into protocol influencers.

### 8.2 Recommendations for Open Source Communities and Ecosystems

**Build Chinese knowledge infrastructure systematically, not as one-off translation**

The biggest barrier for Chinese-speaking developers entering a new protocol is often not technical difficulty, but the lack of trustworthy Chinese onboarding material. Ethereum's Chinese documentation at ethereum.org/zh is one of the few examples of systematic maintenance. For many other protocols, including ICP, Stellar, and Polkadot, Chinese contribution guides are almost nonexistent. This is a gap where open source communities can directly intervene.

**Connect bootcamps and open source contribution in a systematic way**

Platforms such as OpenBuild and DengLian have validated the model of "bootcamp completion equals PR submission." OpenBuild's nine bootcamp repositories have accumulated more than 665 independent contribution records across six ecosystems. WTF Academy covers Solidity and multiple Web3.0 foundational stacks through open source tutorials and has a mature GitHub contributor system, making it one of the lowest-barrier paths from technical onboarding to open source contribution. 706 Creators and LXDAO represent another model: organizing learning around community co-learning, so participants naturally form open source contribution habits through collaboration rather than relying only on external incentives. Extending these different paths to more protocol ecosystems is one of the most efficient ways for Chinese-speaking communities to supply contributors to global Web3.0 open source.

**Chinese access to grant and bounty information must improve**

The survey shows that Chinese-speaking developers rank "ecosystem opportunity density" as the top consideration for participating in open source. Yet core funding programs such as Ethereum Foundation Grants and Solana Foundation Grants have very low Chinese information reach. Establishing regular information synchronization between ecosystems and Chinese-speaking community organizations can directly improve participation conversion. GCC, the Global Chinese Community of Universal Digital Commons, is already building a public goods donation mechanism for Web3.0 open source projects within Chinese-speaking communities. It has funded more than 45 projects and is one local channel for Chinese-speaking developers seeking support for open source work.

### 8.3 Outlook

The Web3.0 open source ecosystem in 2026 is entering the "core builder era" after bear-market clearing. The share of full-time contributors has reached a historical high. Speculative participants have left, and those who remain are developers focused on long-term technical value. This is a rare opportunity for Chinese-speaking open source communities: after the noise fades, sustained contribution to protocol foundations becomes the best time to accumulate long-term influence.

The next step for Chinese-speaking communities in Web3.0 open source is not to create another Chinese-language public chain, but to **become indispensable builders of Chinese knowledge infrastructure and core protocol contributors within globally recognized open source protocols**.

> **Insight 8**: Chinese-speaking developers' contribution to the global Web3.0 open source ecosystem is shifting from participant scale to infrastructure building. The quality of Chinese technical documentation, contributor development paths, and grant information reach will determine the depth of Chinese-speaking communities' influence in the next Web3.0 open source cycle.

---

## Conclusion

According to Electric Capital's open source developer data, the Web3.0 ecosystem in early 2026 is at a critical point. Global monthly active contributors have fallen about 33% from the 2025 peak, but the share of full-time contributors has reached a historical high. After the bubble clears, the long-term open source builders remain.

For China's open source community, three realities in Web3.0 deserve serious attention:

1. **Contribution scale is systematically underestimated**: The real scale of Chinese-speaking Web3.0 open source contributors may be 3-4 times the observed count, yet their voice in international protocol communities does not match their contribution scale.
2. **Protocol selection is becoming more mature**: Chinese-speaking communities have moved from early hype-driven choices such as BNB Chain toward more mature technical choices such as Ethereum, Solana, and Sui. The long-term nature of open source contribution is strengthening.
3. **Geographic distribution is decentralizing**: Remote open source collaboration is pushing contributors beyond Beijing, Shanghai, and Shenzhen. Building local open source communities is becoming central to regional open source ecosystems.

The largest opportunity for China's open source community to participate deeply in global Web3.0 protocol building is not to create a closed ecosystem from scratch. It is to **systematically build knowledge infrastructure for Chinese-speaking communities on globally recognized open source protocols**. High-quality Chinese protocol documentation, clear contributor onboarding guides, and active Chinese technical discussion communities are the key paths for turning Chinese-speaking developers from users into core contributors.
