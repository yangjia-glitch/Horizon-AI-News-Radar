---
layout: default
title: "Horizon Summary: 2026-06-18 (EN)"
date: 2026-06-18
lang: en
---

> From 63 items, 16 important content pieces were selected

---

1. [U.S. science in crisis as funding and talent vanish](#item-1) ⭐️ 9.0/10
2. [GLM-5.2: Most Powerful Open-Weight LLM Released](#item-2) ⭐️ 9.0/10
3. [Epic Games Open-Sources Lore VCS for Game Dev](#item-3) ⭐️ 8.0/10
4. [US Delays Blacklisting DeepSeek, Targets 100+ Chinese Firms](#item-4) ⭐️ 8.0/10
5. [Leaked Docs Reveal OpenAI Losing Billions Annually](#item-5) ⭐️ 8.0/10
6. [Adam (YC W25) Launches CADAM: Open-Source AI CAD Agent](#item-6) ⭐️ 8.0/10
7. [Tesco migrates 40,000 workloads off VMware over Broadcom pricing](#item-7) ⭐️ 8.0/10
8. [RFC 10008 Defines New HTTP QUERY Method](#item-8) ⭐️ 8.0/10
9. [AI Demands More Engineering Discipline, Not Less](#item-9) ⭐️ 8.0/10
10. [AI Chemist Using GPT-5.4 Improves Key Drug Reaction](#item-10) ⭐️ 8.0/10
11. [Google's AMIE AI Matches Doctors in Disease Management](#item-11) ⭐️ 8.0/10
12. [MolmoMotion: Language-Guided 3D Motion Forecasting](#item-12) ⭐️ 8.0/10
13. [Hugging Face Hub to Robot Hardware with Strands Agents and LeRobot](#item-13) ⭐️ 8.0/10
14. [Charity Majors: AI Demands More Engineering Discipline](#item-14) ⭐️ 8.0/10
15. [Self-Driving Labs Are the Moat in Materials Science](#item-15) ⭐️ 7.0/10
16. [Brent Simmons Retires, Focuses on NetNewsWire](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [U.S. science in crisis as funding and talent vanish](https://www.scientificamerican.com/article/americas-compact-between-science-and-politics-is-broken/) ⭐️ 9.0/10

A Scientific American article reports that U.S. science is in chaos due to drying research funding, visa restrictions blocking foreign talent, and researchers leaving the country or abandoning careers, signaling a broken compact between science and politics. This crisis threatens U.S. leadership in science and innovation, potentially leading to a brain drain that weakens the nation's research enterprise and economic competitiveness for years to come. The article highlights high engagement (649 points, 770 comments) with deeply personal comments from affected scientists, indicating a widespread impact on research careers and international talent.

hackernews · presspot · Jun 17, 09:54 · [Discussion](https://news.ycombinator.com/item?id=48568058)

**Background**: The compact between science and politics in the U.S. has historically involved government funding for research in exchange for scientific advice and innovation. Recent policy changes, including visa restrictions and budget cuts, have eroded this relationship, leading to uncertainty and exodus of talent.

**Discussion**: Commenters share personal stories: one user's wife, an expert in optical traps, is leaving the U.S. due to the mess; another notes that grant funding dried up and visa restrictions prevented hiring foreign grad students. Many express that the mood has shifted from cautious optimism to palpable tension, with promising PhDs and postdocs leaving science or the country.

**Tags**: `#science policy`, `#research funding`, `#U.S. science`, `#brain drain`, `#academia`

---

<a id="item-2"></a>
## [GLM-5.2: Most Powerful Open-Weight LLM Released](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

Z.ai released GLM-5.2, a 753B-parameter open-weight LLM with a 1M token context window under MIT license, achieving top scores on the Artificial Analysis Intelligence Index. This marks a significant advancement in open-source AI, as GLM-5.2 outperforms other open models like DeepSeek V4 Pro and Kimi K2.6, and is priced much lower than proprietary models like GPT-5.5 and Claude Opus. GLM-5.2 uses a Mixture-of-Experts architecture with 40 active parameters, and its 1M token context window is a fivefold increase over GLM-5.1's 200K. However, it is token-hungry, using 43K output tokens per task on the Intelligence Index.

rss · Simon Willison · Jun 17, 23:58

**Background**: Large language models (LLMs) are AI systems trained on vast text data to generate human-like text. Open-weight models allow anyone to download and run them, fostering innovation. Mixture-of-Experts (MoE) activates only a subset of parameters per token, balancing performance and efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/GLM-5.2 · Hugging Face</a></li>
<li><a href="https://docs.z.ai/guides/llm/glm-5.2">GLM-5.2 - Overview - Z.AI DEVELOPER DOCUMENT</a></li>

</ul>
</details>

**Discussion**: Community members praised GLM-5.2's performance and low cost, with some noting it rivals proprietary models at a fraction of the price. However, concerns were raised about reasoning efficiency, as one user reported 15-minute reasoning times for a simple coding task.

**Tags**: `#LLM`, `#open-source`, `#AI`, `#GLM-5.2`, `#benchmarks`

---

<a id="item-3"></a>
## [Epic Games Open-Sources Lore VCS for Game Dev](https://lore.org/) ⭐️ 8.0/10

Epic Games has open-sourced Lore, a new version control system designed for scalability with large binary files, announced at State of Unreal 2026 alongside Unreal Engine 5.8. Lore directly challenges Perforce's dominance in game development by offering an open-source alternative that handles large binary assets, exclusive file locking, and team scalability, potentially reducing costs and vendor lock-in for studios. Lore is written in Rust, licensed under MIT, and built from scratch to handle binary-heavy workflows, aiming to make both Perforce and Git LFS irrelevant for such use cases.

hackernews · regnerba · Jun 17, 14:30 · [Discussion](https://news.ycombinator.com/item?id=48571081)

**Background**: Version control systems like Git are optimized for text files but struggle with large binary files common in game development (textures, 3D models, audio). Perforce has been the industry standard for games due to its support for large files and exclusive file locking, but it is proprietary and complex to administer. Lore aims to provide similar capabilities as an open-source solution.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/EpicGames/lore">Lore is a next-generation, open source revision control system</a></li>
<li><a href="https://www.phoronix.com/news/Epic-Games-Lore-VCS">Epic Games Announces Lore Open-Source Version Control System</a></li>
<li><a href="https://byteiota.com/epic-games-open-sources-lore-a-vcs-built-for-binary-files/">Epic Games Open-Sources Lore: A VCS Built for Binary Files</a></li>

</ul>
</details>

**Discussion**: The Hacker News community expressed strong interest, with many noting Lore's potential as a Perforce competitor for game development. Commenters highlighted Perforce's complexity and Git's inadequacy for binary assets, while some questioned Lore's maturity and adoption challenges.

**Tags**: `#version control`, `#game development`, `#open source`, `#scalability`, `#Perforce`

---

<a id="item-4"></a>
## [US Delays Blacklisting DeepSeek, Targets 100+ Chinese Firms](https://www.reuters.com/world/china/us-holds-off-blacklisting-chinas-deepseek-more-than-100-firms-deemed-security-2026-06-17/) ⭐️ 8.0/10

The Trump administration has delayed adding Chinese AI startup DeepSeek, memory chipmaker CXMT, and over 100 other Chinese firms to the Entity List, despite interagency approval, to avoid escalating tensions with Beijing. This marks the longest pause in new Entity List additions in over a decade, signaling a potential shift in US-China tech decoupling strategy. The decision affects AI chip access and national security enforcement, with implications for the global AI supply chain. DeepSeek, known for its cost-effective open-weight models like R1, has already been subject to export restrictions on NVIDIA GPUs. Being on the Entity List would prohibit US companies from selling goods and services to these firms, but they could still buy from them.

hackernews · giuliomagnifico · Jun 17, 03:55 · [Discussion](https://news.ycombinator.com/item?id=48565498)

**Background**: The Entity List is a US trade blacklist that restricts exports of sensitive technologies to designated entities. DeepSeek is a Chinese AI company that developed the R1 model, which rivaled OpenAI's GPT-4 at a fraction of the cost, using less advanced chips due to US export controls. The US has been concerned about China's access to advanced AI chips and technology.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://finance.yahoo.com/news/exclusive-us-holds-off-blacklisting-000212827.html">Exclusive- US holds off blacklisting China 's DeepSeek, more than 100...</a></li>
<li><a href="https://economictimes.indiatimes.com/news/international/business/u-s-held-back-blacklisting-deepseek-over-100-chinese-firms-despite-security-concerns-sources-say/articleshow/131792688.cms">U . S . held back blacklisting DeepSeek, over 100 Chinese firms ...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed views: some praised DeepSeek's affordability and quality for everyday coding tasks, while others criticized US enforcement as hypocritical and impractical, comparing it to a 'Great Firewall of America.' Some noted that many Chinese AI firms already have limited dependence on US goods except for NVIDIA GPUs, which are already restricted.

**Tags**: `#AI regulation`, `#geopolitics`, `#DeepSeek`, `#US-China trade`, `#tech policy`

---

<a id="item-5"></a>
## [Leaked Docs Reveal OpenAI Losing Billions Annually](https://arstechnica.com/ai/2026/06/leaked-financial-docs-show-openai-is-losing-billions-of-dollars-a-year/) ⭐️ 8.0/10

Leaked financial documents reveal that OpenAI is losing billions of dollars each year due to extremely high overhead and astronomical R&D costs, raising serious questions about its long-term sustainability. This news is significant because it exposes the financial unsustainability of one of the most prominent AI companies, potentially impacting investor confidence and the broader AI industry's business models. The documents show that OpenAI's SG&A costs are 55% of revenue, which is very high, and its R&D spending is astronomical, far exceeding revenue. The company has over 900 million weekly active users but only about 50 million paid subscribers.

hackernews · greenchair · Jun 17, 21:31 · [Discussion](https://news.ycombinator.com/item?id=48577208)

**Background**: OpenAI was originally founded as a non-profit AI research organization but later transitioned to a capped-profit model to attract investment. The company's flagship product, ChatGPT, has seen explosive growth, but the costs of training and running large language models are enormous, leading to persistent losses.

**Discussion**: Commenters are divided: some argue the losses are unsustainable due to high overhead and R&D costs, while others believe the company can grow into profitability. A notable point is that many free users may never convert to paid, given the availability of free alternatives like DeepSeek.

**Tags**: `#OpenAI`, `#financial analysis`, `#AI industry`, `#business model`, `#startup economics`

---

<a id="item-6"></a>
## [Adam (YC W25) Launches CADAM: Open-Source AI CAD Agent](https://github.com/Adam-CAD/CADAM) ⭐️ 8.0/10

Adam (YC W25) has launched CADAM, an open-source AI agent that generates parametric 3D mechanical CAD models from natural language descriptions or images, outputting OpenSCAD code with interactive sliders for dimension tweaking. CADAM represents a novel paradigm of text-to-CAD, potentially lowering the barrier for rapid prototyping and design iteration, especially for makers and engineers who want to quickly generate mechanical parts without deep CAD expertise. The system uses a single agentic endpoint with two modes: parametric mode writes/edits OpenSCAD code, while mesh mode generates 3D textured meshes; it is model-agnostic via the Vercel AI SDK, supporting Claude, Gemini, and OpenAI models, with Gemini 3.1 Pro performing best in evaluations.

hackernews · zachdive · Jun 17, 16:14 · [Discussion](https://news.ycombinator.com/item?id=48572553)

**Background**: CADAM is built on OpenSCAD, a script-based CAD tool that defines 3D models using code, making it well-suited for AI generation. The project is open-source under GPL-3.0 and uses a React frontend (TanStack Start) with a Supabase backend, compiling OpenSCAD to WebAssembly for in-browser rendering via Three.js.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Adam-CAD/CADAM">GitHub - Adam-CAD/CADAM: CADAM is the open source text-to-CAD web ...</a></li>
<li><a href="https://adam.new/cadam/">CADAM</a></li>
<li><a href="https://tanstack.com/start/v0/docs/framework/react/overview">TanStack Start Overview | TanStack Start React Docs</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some engineers question the practical utility for precise mechanical design, citing time savings and accuracy concerns, while others report successful generation of functional parts like a grommet seal. There is also discussion about the limitations of LLMs in spatial reasoning and the potential for future improvements.

**Tags**: `#AI`, `#CAD`, `#open-source`, `#YC`, `#mechanical design`

---

<a id="item-7"></a>
## [Tesco migrates 40,000 workloads off VMware over Broadcom pricing](https://arstechnica.com/information-technology/2026/06/tesco-moving-40000-server-workloads-off-vmware-amid-broadcoms-abusive-conduct/) ⭐️ 8.0/10

Tesco, the UK's largest supermarket chain, is migrating 40,000 server workloads off VMware due to Broadcom's pricing and licensing changes, as revealed in recent legal filings. The company alleges Broadcom is abusing its market power and has turned to third-party support providers for its VMware estate. This migration signals a major enterprise exodus from VMware following Broadcom's acquisition, potentially reshaping the virtualization market. It highlights the lack of fully equivalent open-source alternatives, forcing companies to accept reduced functionality or bear high costs. Tesco has not found a fully equivalent open-source alternative and has had to procure solutions with reduced functionality. The legal dispute with Broadcom is set for UK High Court consideration no sooner than November 2027.

hackernews · Bender · Jun 17, 21:00 · [Discussion](https://news.ycombinator.com/item?id=48576838)

**Background**: Broadcom acquired VMware in November 2023 and subsequently replaced perpetual licenses with subscriptions, introduced a 72-core minimum, and enforced bundled purchases, significantly increasing costs for many customers. VMware has long been the dominant virtualization platform for enterprise data centers, making migration complex and risky.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/information-technology/2026/06/tesco-moving-40000-server-workloads-off-vmware-amid-broadcoms-abusive-conduct/">Tesco moving 40,000 server workloads off VMware amid Broadcom ...</a></li>
<li><a href="https://cloudinfra.blog/comprehensive-analysis-of-broadcoms-vmware-license-pricing-changes-and-their-impact/">Comprehensive Analysis of Broadcom's VMware License Pricing Changes and ...</a></li>

</ul>
</details>

**Discussion**: Commenters express distrust of Broadcom, with one noting a senior banker swearing off Broadcom hardware entirely. Others lament the lack of a viable open-source alternative, as Tesco had to accept reduced functionality, and hope the situation changes as more customers migrate.

**Tags**: `#VMware`, `#Broadcom`, `#enterprise migration`, `#virtualization`, `#cloud`

---

<a id="item-8"></a>
## [RFC 10008 Defines New HTTP QUERY Method](https://www.rfc-editor.org/info/rfc10008/) ⭐️ 8.0/10

RFC 10008 introduces a new HTTP QUERY method that allows safe and idempotent requests with a request body, distinct from GET and POST. This standard was published by the IETF and is now an official RFC. The QUERY method fills a long-standing gap in HTTP for complex queries that need a body but should remain safe and idempotent, such as GraphQL or large JSON filter structures. It provides a standardized alternative to misusing GET with a body or POST for read-only operations, improving interoperability and caching semantics. The QUERY method is safe and idempotent, meaning it does not change server state and multiple identical requests have the same effect as a single request. Caching of QUERY responses is possible but challenging because the cache key must include the request body, and the RFC does not mandate specific caching limits.

hackernews · schappim · Jun 17, 10:51 · [Discussion](https://news.ycombinator.com/item?id=48568502)

**Background**: HTTP traditionally uses GET for safe, idempotent data retrieval without a body, and POST for unsafe operations that may change state. However, modern APIs like GraphQL often require sending complex query structures in the request body, leading developers to misuse GET with a body or use POST for read-only queries. The QUERY method standardizes a safe, idempotent alternative with a body, addressing these use cases.

<details><summary>References</summary>
<ul>
<li><a href="https://httpwg.org/http-extensions/draft-ietf-httpbis-safe-method-w-body.html">The HTTP QUERY Method</a></li>
<li><a href="https://news.ycombinator.com/item?id=48568502">RFC 10008 : The new HTTP Query Method | Hacker News</a></li>
<li><a href="https://http.dev/query">QUERY - Expert Guide to HTTP methods</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion shows strong interest, with comments exploring caching challenges, potential support in HTML forms, and the historical misuse of GET with a body. Some commenters note the difficulty of caching QUERY responses due to unbounded cache keys, while others welcome the new method as a cleaner solution for complex queries.

**Tags**: `#HTTP`, `#RFC`, `#web standards`, `#protocol design`

---

<a id="item-9"></a>
## [AI Demands More Engineering Discipline, Not Less](https://charitydotwtf.substack.com/p/ai-demands-more-engineering-discipline) ⭐️ 8.0/10

An article argues that AI-assisted coding increases the need for rigorous engineering discipline to manage evaluation and understanding challenges, contrary to the belief that AI reduces the need for such discipline. This matters because it challenges the prevailing narrative that AI tools simplify software engineering, highlighting that they actually introduce new complexities in code evaluation and system understanding, which could affect code quality and team dynamics. The article emphasizes that code becomes precious when it is the only place knowledge lives, and reading AI-generated code can be agonizing due to the lack of a productive feedback loop. It also notes that the economics of code production have shifted, making code disposable and regenerable overnight.

hackernews · BerislavLopac · Jun 17, 14:20 · [Discussion](https://news.ycombinator.com/item?id=48570948)

**Background**: The article is a response to the rapid adoption of AI coding assistants like GitHub Copilot and ChatGPT, which have made code generation fast and cheap. This shift has led to concerns about code quality and the ability of engineers to understand and evaluate AI-generated code, requiring more discipline in engineering practices.

**Discussion**: Commenters expressed diverse views: some agreed that AI increases the need for discipline, while others argued that AI can reduce the burden of boilerplate and allow focus on higher-level design. There was also discussion about the difficulty of distinguishing competent engineers from those who merely use AI to produce superficially correct code.

**Tags**: `#AI`, `#software engineering`, `#code quality`, `#engineering discipline`

---

<a id="item-10"></a>
## [AI Chemist Using GPT-5.4 Improves Key Drug Reaction](https://openai.com/index/ai-chemist-improves-reaction) ⭐️ 8.0/10

OpenAI and Molecule.one demonstrated a near-autonomous AI chemist powered by GPT-5.4 that successfully improved a challenging reaction used in medicinal chemistry. The system autonomously designed and executed experiments to optimize the reaction conditions. This breakthrough showcases how large language models can accelerate drug discovery by autonomously optimizing complex chemical reactions, potentially reducing the time and cost of developing new medicines. It marks a significant step toward fully autonomous chemical research. The AI chemist used GPT-5.4, which features improved reasoning and computer-use capabilities, to plan and execute experiments with minimal human intervention. The system improved a key reaction in medicinal chemistry, though specific reaction details were not disclosed.

rss · OpenAI News · Jun 17, 10:00

**Background**: Autonomous AI chemists combine large language models with robotic platforms to perform chemical experiments without constant human guidance. GPT-5.4 is OpenAI's latest model, released in March 2026, with enhanced factual accuracy and computer-use abilities. Molecule.one is a company that uses AI and robotics to accelerate drug discovery.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.4">GPT-5.4</a></li>
<li><a href="https://molecule.one/">molecule.one - Making Molecules. Discovering Chemistry</a></li>

</ul>
</details>

**Tags**: `#AI`, `#chemistry`, `#drug discovery`, `#GPT-5.4`, `#autonomous systems`

---

<a id="item-11"></a>
## [Google's AMIE AI Matches Doctors in Disease Management](https://blog.google/innovation-and-ai/models-and-research/google-research/amie-for-disease-management-in-nature/) ⭐️ 8.0/10

Google Research published a study in Nature showing that its conversational AI system, AMIE (Articulate Medical Intelligence Explorer), can manage complex health conditions as effectively as primary care physicians. This marks a significant milestone in medical AI, demonstrating that conversational AI can handle long-term disease management, not just one-off diagnoses, potentially expanding access to quality healthcare. The study, published in Nature, shows AMIE evolved from diagnostic conversations to managing diseases using drug formularies and clinical guidelines, matching primary care physician performance.

rss · Google AI Blog · Jun 17, 15:00

**Background**: AMIE is a research AI system based on large language models (LLMs) for diagnostic reasoning and dialogue. It was trained on real-world datasets including medical reasoning, summarization, and clinical conversations. Previous work focused on one-off diagnostic consultations, while this new research extends to ongoing disease management.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/google-research/amie-for-disease-management-in-nature/">Google advances its AMIE research medical AI from diagnosis ...</a></li>
<li><a href="https://research.google/blog/amie-a-research-ai-system-for-diagnostic-medical-reasoning-and-conversations/">AMIE: A research AI system for diagnostic medical reasoning ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Healthcare`, `#Medical AI`, `#Conversational AI`, `#Research`

---

<a id="item-12"></a>
## [MolmoMotion: Language-Guided 3D Motion Forecasting](https://huggingface.co/blog/allenai/molmomotion) ⭐️ 8.0/10

Allen AI has introduced MolmoMotion, an open-source framework that predicts future 3D trajectories of objects based on visual history and natural language instructions. This enables more intuitive human-robot interaction by allowing users to guide robot actions through language, and it reduces computational cost by representing motion as object-attached 3D points instead of full video. MolmoMotion represents motion as object-attached 3D points in world space, capturing motion without rendering full video. It is goal-conditioned, taking visual history, 3D query points, and a language instruction to predict future point trajectories.

rss · Hugging Face Blog · Jun 17, 15:26

**Background**: 3D motion forecasting is crucial for autonomous systems like robots and self-driving cars to anticipate future movements. Traditional methods often rely on dense video data, which is computationally expensive. Language-guided approaches aim to make these systems more accessible and controllable by humans.

<details><summary>References</summary>
<ul>
<li><a href="https://allenai.org/blog/molmo-motion">MolmoMotion : Language-guided 3D motion forecasting | Ai2</a></li>
<li><a href="https://molmomotion.github.io/">MolmoMotion: Forecasting Point Trajectories in 3D with Language Instruction</a></li>

</ul>
</details>

**Tags**: `#3D motion forecasting`, `#language-guided AI`, `#robotics`, `#machine learning`, `#Hugging Face`

---

<a id="item-13"></a>
## [Hugging Face Hub to Robot Hardware with Strands Agents and LeRobot](https://huggingface.co/blog/amazon/strands-lerobot-hub-to-hardware) ⭐️ 8.0/10

AWS and Hugging Face introduced Strands Agents and LeRobot, enabling deployment of robot learning models from the Hugging Face Hub directly onto physical robots. This bridges the gap between AI model development and real-world robotics, making it easier for researchers and developers to test and deploy models on actual hardware, accelerating robotics research and applications. Strands Agents is an open-source SDK for building AI agents, while LeRobot provides models, datasets, and tools for real-world robotics in PyTorch. The integration allows seamless deployment from the Hub to hardware.

rss · Hugging Face Blog · Jun 17, 10:18

**Background**: Hugging Face Hub is a popular platform for sharing AI models. LeRobot is a Hugging Face project focused on making AI for robotics more accessible. Strands Agents is an AWS open-source SDK for creating AI agents. Combining them allows users to take models from the Hub and run them on physical robots.

<details><summary>References</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/opensource/introducing-strands-agents-an-open-source-ai-agents-sdk/">Introducing Strands Agents , an Open Source AI Agents SDK</a></li>
<li><a href="https://github.com/huggingface/lerobot">GitHub - huggingface/lerobot: 🤗 LeRobot: Making AI for Robotics more accessible with end-to-end learning</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#AI`, `#Hugging Face`, `#robot learning`, `#deployment`

---

<a id="item-14"></a>
## [Charity Majors: AI Demands More Engineering Discipline](https://simonwillison.net/2026/Jun/17/charity-majors/#atom-everything) ⭐️ 8.0/10

Charity Majors argues that AI has made code generation cheap and disposable, requiring more engineering discipline, not less. This insight challenges the common assumption that AI reduces the need for rigorous engineering practices, highlighting a paradigm shift in software development economics. Majors notes that lines of code went from being treasured and carefully curated to being disposable and regenerable practically overnight, turning the economics of code production upside down.

rss · Simon Willison · Jun 17, 17:12

**Background**: Historically, writing code was expensive and time-consuming, so developers carefully crafted and reused code. With generative AI, code can be produced instantly at near-zero cost, changing how engineers approach development.

**Tags**: `#ai-assisted-programming`, `#software-engineering`, `#generative-ai`, `#industry-insight`

---

<a id="item-15"></a>
## [Self-Driving Labs Are the Moat in Materials Science](https://www.latent.space/p/radical-ai) ⭐️ 7.0/10

Joseph Krause of Radical AI argues that in materials science, the competitive advantage lies in automated labs rather than AI models alone, emphasizing that the lab infrastructure is the key differentiator. This perspective shifts focus from model-centric AI to integrated automation, potentially accelerating materials discovery and reducing costs, which could impact industries from energy to electronics. Self-driving labs combine robotics, AI, and automation to run closed-loop experiments, collecting up to 10 times more data than traditional methods, as noted in recent studies.

rss · Latent Space · Jun 17, 17:58

**Background**: Self-driving laboratories (SDLs) are integrated systems that use AI and robotics to autonomously conduct experiments, accelerating materials and molecular discovery. They differ from self-driving cars, which focus on autonomous navigation. SDLs have gained traction in chemistry and materials science, with platforms like the A-Lab demonstrating accelerated synthesis of inorganic materials.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s44160-022-00231-0">The rise of self-driving labs in chemical and materials sciences | Nature Synthesis</a></li>
<li><a href="https://www.nature.com/articles/s41586-023-06734-w">An autonomous laboratory for the accelerated synthesis of inorganic materials | Nature</a></li>
<li><a href="https://phys.org/news/2025-07-automated-labs-materials.html">Automated labs collect 10 times more data, accelerating materials research and reducing costs</a></li>

</ul>
</details>

**Tags**: `#AI`, `#materials science`, `#automation`, `#self-driving lab`, `#research`

---

<a id="item-16"></a>
## [Brent Simmons Retires, Focuses on NetNewsWire](https://simonwillison.net/2026/Jun/17/netnewswire-status/#atom-everything) ⭐️ 6.0/10

Brent Simmons, the original developer of NetNewsWire, retired a year ago and has been dedicating his retirement to improving the open-source RSS reader, free from commercial pressure. This highlights how open-source projects can thrive without commercial incentives, and it underscores the enduring value of RSS readers in an era of algorithm-driven content. NetNewsWire was first released in 2002 and became open source in 2018; it is available for Mac, iPhone, and iPad, and is described as "like podcasts, but for reading."

rss · Simon Willison · Jun 17, 03:36

**Background**: NetNewsWire is a free and open-source RSS reader originally developed by Brent and Sheila Simmons through Ranchero Software. RSS (Really Simple Syndication) allows users to subscribe to blogs and news sites and receive updates in a single feed reader, bypassing algorithmic feeds.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NetNewsWire">NetNewsWire - Wikipedia</a></li>
<li><a href="https://netnewswire.com/">NetNewsWire: Free and Open Source RSS Reader for Mac, iPhone, and iPad</a></li>
<li><a href="https://grokipedia.com/page/brent_simmons">Brent Simmons — Grokipedia</a></li>

</ul>
</details>

**Discussion**: The Lobste.rs discussion expressed admiration for Simmons' dedication and the quality of NetNewsWire, with some noting the importance of RSS in maintaining an open web.

**Tags**: `#open-source`, `#RSS`, `#NetNewsWire`, `#retirement`, `#software development`

---