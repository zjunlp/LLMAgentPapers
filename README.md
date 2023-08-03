# LLMAgents

[![Awesome](https://camo.githubusercontent.com/64f8905651212a80869afbecbf0a9c52a5d1e70beab750dea40a994fa9a9f3c6/68747470733a2f2f617765736f6d652e72652f62616467652e737667)](https://github.com/zjunlp/LLMAgentPapers) [![License: MIT](https://camo.githubusercontent.com/fd551ba4b042d89480347a0e74e31af63b356b2cac1116c7b80038f41b04a581/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d677265656e2e737667)](https://opensource.org/licenses/MIT) <img src="https://img.shields.io/github/last-commit/tensorflow/tensorflow.svg"/> [![img](https://camo.githubusercontent.com/eafac29b763e18c4d80c680d6a179f348cfa2afbc8d3a45642df19fd580d2404/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d57656c636f6d652d726564)](https://camo.githubusercontent.com/eafac29b763e18c4d80c680d6a179f348cfa2afbc8d3a45642df19fd580d2404/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d57656c636f6d652d726564)

Must-read Papers on Multi-agents of large language models.


## 📜Content

- [🌄 Papers](#-papers)
  - [Overview](#overview)
  - [Agent + Environment](#agent--environment)
  - [Multiple Agents](#multiple-agents)
    
- [🧰 Tools](#-tools)



## 🌄 Papers

### Overview

1. **Interactive Natural Language Processing**

   Zekun Wang, Ge Zhang, Kexin Yang, Ning Shi, Wangchunshu Zhou, Shaochun Hao, Guangzheng Xiong, Yizhi Li, Mong Yuan Sim, Xiuying Chen, Qingqing Zhu, Zhenzhu Yang, Adam Nik, Qi Liu, Chenghua Lin, Shi Wang, Ruibo Liu, Wenhu Chen, Ke Xu, Dayiheng Liu, Yike Guo, Jie Fu. [[abs]](https://arxiv.org/abs/2305.13246), 2023.5

### Agent + Environment

1. **Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents**

   *Wenlong Huang, Pieter Abbeel, Deepak Pathak, Igor Mordatch*. [[abs](https://arxiv.org/abs/2201.07207)], 2022.1

2. **Inner Monologue: Embodied Reasoning through Planning with Language Models**

   *Wenlong Huang , Fei Xia , Ted Xiao , Harris Chan, Jacky Liang, Pete Florence, Andy Zeng, Jonathan Tompson, Igor Mordatch, Yevgen Chebotar, Pierre Sermanet, Noah Brown, Tomas Jackson, Linda Luu, Sergey Levine, Karol Hausman, Brian Ichter*. [[abs](https://arxiv.org/abs/2207.05608)], 2022.7

3. **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**

   *Chan Hee Song, Jiaman Wu, Clayton Washington, Brian M. Sadler, Wei-Lun Chao, Yu Su*. [[abs](https://arxiv.org/abs/2212.04088)], 2022.12

4. **Do Embodied Agents Dream of Pixelated Sheep?: Embodied Decision Making using Language Guided World Modelling**

   *Kolby Nottingham, Prithviraj Ammanabrolu, Alane Suhr, Yejin Choi, Hannaneh Hajishirzi, Sameer Singh, Roy Fox*. [[abs](https://arxiv.org/abs/2301.12050)], 2023.1

5. **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents**

   *Zihao Wang, Shaofei Cai, Anji Liu, Xiaojian Ma, Yitao Liang*. [[abs](https://arxiv.org/abs/2302.01560)], 2023.2

6. **PaLM-E: An embodied multimodal language model**

   *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, Corey Lynch, Aakanksha Chowdhery, Brian Ichter, Ayzaan Wahid, Jonathan Tompson, Quan Vuong, Tianhe Yu, Wenlong Huang, Yevgen Chebotar, Pierre Sermanet, Daniel Duckworth, Sergey Levine, Vincent Vanhoucke, Karol Hausman, Marc Toussaint, Klaus Greff, Andy Zeng, Igor Mordatch, Pete Florence.* [[abs](https://arxiv.org/abs/2303.03378)], 2023.3

7. **Chat with the Environment: Interactive Multimodal Perception using Large Language Models**

   *Xufeng Zhao, Mengdi Li, Cornelius Weber, Muhammad Burhan Hafez, Stefan Wermter*. [[abs](https://arxiv.org/abs/2303.08268)], 2023.3

8. **Generative Agents: Interactive Simulacra of Human Behavior**

   *Joon Sung Park, Joseph C. O'Brien, Carrie J. Cai, Meredith Ringel Morris, Percy Liang, Michael S. Bernstein.* [[abs](https://arxiv.org/abs/2304.03442)], 2023.4

9. **Plan, Eliminate, and Track -- Language Models are Good Teachers for Embodied Agents**

   *Yue Wu, So Yeon Min, Yonatan Bisk, Ruslan Salakhutdinov, Amos Azaria, Yuanzhi Li, Tom Mitchell, Shrimai Prabhumoye*. [[abs](https://arxiv.org/abs/2305.02412)], 2023.5

10. **Voyager: An Open-Ended Embodied Agent with Large Language Models**

    *Guanzhi Wang, Yuqi Xie, Yunfan Jiang, Ajay Mandlekar, Chaowei Xiao, Yuke Zhu, Linxi Fan, Anima Anandkumar*. [[abs](https://arxiv.org/abs/2305.16291)], 2023.5

11. **SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks**

    *Bill Yuchen Lin, Yicheng Fu, Karina Yang, Prithviraj Ammanabrolu, Faeze Brahman, Shiyu Huang, Chandra Bhagavatula, Yejin Choi, Xiang Ren.* [[abs](https://arxiv.org/abs/2305.17390)], 2023.5

12. **Language Models Meet World Models: Embodied Experiences Enhance Language Models**

    *Jiannan Xiang, Tianhua Tao, Yi Gu, Tianmin Shu, Zirui Wang, Zichao Yang, Zhiting Hu.* [[abs](https://arxiv.org/abs/2305.10626)], 2023.5

13. **Training Socially Aligned Language Models in Simulated Human Society.**

    *Ruibo Liu, Ruixin Yang, Chenyan Jia, Ge Zhang, Denny Zhou, Andrew M. Dai, Diyi Yang, Soroush Vosoughi.* [[abs](https://arxiv.org/abs/2305.16960)], 2023.5

14. **Towards A Unified Agent with Foundation Models.**

    *Norman Di Palo, Arunkumar Byravan, Leonard Hasenclever, Markus Wulfmeier, Nicolas Heess, Martin Riedmiller.* [[abs](https://arxiv.org/abs/2307.09668)], 2023.7


### Multiple Agents

1. **CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society**

   *Guohao Li, Hasan Abed Al Kader Hammoud, Hani Itani, Dmitrii Khizbullin, Bernard Ghanem.* [[abs](https://arxiv.org/abs/2303.17760)], 2023.3

2. **ChatLLM Network: More brains, More intelligence**

   *Rui Hao, Linmei Hu, Weijian Qi, Qingliu Wu, Yirui Zhang, Liqiang Nie.* [[abs](https://arxiv.org/abs/2304.12998)], 2023.4

3. **Self-collaboration Code Generation via ChatGPT** 

   *Yihong Dong, Xue Jiang, Zhi Jin, Ge Li.* [[abs](https://arxiv.org/abs/2304.07590)], 2023.4

4. **Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate**

   *Tian Liang, Zhiwei He, Wenxiang Jiao, Xing Wang, Yan Wang, Rui Wang, Yujiu Yang, Zhaopeng Tu, Shuming Shi.*  [[abs](https://arxiv.org/abs/2305.19118)], 2023.5

5. **Improving Factuality and Reasoning in Language Models through Multiagent Debate**

   *Yilun Du, Shuang Li, Antonio Torralba, Joshua B. Tenenbaum, Igor Mordatch.* [[abs](https://arxiv.org/abs/2305.14325)], 2023.5

6. **Playing repeated games with Large Language Models**

   *Elif Akata, Lion Schulz, Julian Coda-Forno, Seong Joon Oh, Matthias Bethge, Eric Schulz.* [[abs](https://arxiv.org/abs/2305.16867)], 2023.5

7. **ChatGPT/GPT-4 for Knowledge Graph Construction and Reasoning: Recent Capabilities and Future Opportunities**

   *Yuqi Zhu, Xiaohan Wang, Jing Chen, Shuofei Qiao, Yixin Ou, Yunzhi Yao, Shumin Deng, Huajun Chen, Ningyu Zhang.* [[abs](https://arxiv.org/abs/2305.13168)], 2023.5

8. **Emergent autonomous scientific research capabilities of large language models**

   *Daniil A. Boiko, Robert MacKnight, Gabe Gomes.* [[abs](https://arxiv.org/abs/2304.05332)], 2023.4

9. **Large Language Models as Tool Makers**

   *Tianle Cai, Xuezhi Wang, Tengyu Ma, Xinyun Chen, Denny Zhou*. [[abs](https://arxiv.org/abs/2305.17126)],2023.5

10. **Collaborating with language models for embodied reasoning**

    *Ishita Dasgupta, Christine Kaeser-Chen, Kenneth Marino, Arun Ahuja, Sheila Babayan, Felix Hill, Rob Fergus.* [[abs](https://arxiv.org/abs/2302.00763)], 2023.2

11. **Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models**

    *Jimmy Wei, Kurt Shuster, Arthur Szlam, Jason Weston, Jack Urbanek, Mojtaba Komeili.* [[abs](https://arxiv.org/abs/2304.13835)], 2023.4

12. **Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration**

    *Zhenhailong Wang, Shaoguang Mao, Wenshan Wu, Tao Ge, Furu Wei, Heng Ji.* [[abs](https://arxiv.org/abs/2307.05300)], 2023.7
13. **Communicative Agents for Software Development**

    *Chen Qian, Xin Cong, Cheng Yang, Weize Chen, Yusheng Su, Juyuan Xu, Zhiyuan Liu, Maosong Sun.* [[abs](https://arxiv.org/abs/2307.07924)], 2023.7
14. **To Infinity and Beyond: SHOW-1 and Showrunner Agents in Multi-Agent Simulations**

    *Philipp Maas, Frank Carey, Chris Wheeler, Edward Saatchi, Pete Billington, Jessica Yaffa Shamash.* [[abs](https://fablestudio.github.io/showrunner-agents/static/pdfs/To_Infinity_and_Beyond_SHOW-1_And_Showrunner_Agents_in_Multi_Agent_Simulations.pdf)], 2023.7

15. **MetaGPT: Meta Programming For Multi-Agent  Collaborative Framework**

    *Sirui Hong, Xiawu Zheng, Jonathan Chen, Yuheng Cheng, Ceyao Zhang, Zili Wang, Steven Ka Shing Yau, Zijuan Lin, Liyang Zhou, Chenyu Ran, Lingfeng Xiao, Chenglin Wu.* [[abs](https://arxiv.org/abs/2308.00352)], 2023.8

16. **RestGPT: Connecting Large Language Models with Real-World Applications via RESTful APIs**
    
    *Yifan Song, Weimin Xiong, Dawei Zhu, Cheng Li, Ke Wang, Ye Tian, Sujian Li*. [[abs](https://arxiv.org/abs/2306.06624)], 2023.6

17. **Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback**

    *Yao Fu, Hao Peng, Tushar Khot, Mirella Lapata.* [[abs](https://arxiv.org/abs/2305.10142)], 2023.5

18. **Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents**

    *Yashar Talebirad, Amirhossein Nadiri.* [[abs](https://arxiv.org/pdf/2306.03314.pdf)], 2023.6

19. **Building Cooperative Embodied Agents Modularly with Large Language Models**

    *Hongxin Zhang, Weihua Du, Jiaming Shan, Qinhong Zhou, Yilun Du, Joshua B. Tenenbaum, Tianmin Shu, Chuang Gan.*  [[abs](https://arxiv.org/abs/2307.02485)], 2023.7
    


## 🧰 Tools

###  Types of Tools

|      Types      | Tools                                                        |
| :-------------: | ------------------------------------------------------------ |
| Agent with tool | [AutoGPT](https://github.com/Significant-Gravitas/Auto-GPT)、[LangChain](https://github.com/hwchase17/langchain)、[Transformer Agents](https://huggingface.co/docs/transformers/transformers_agents)、[WorkGPT](https://github.com/team-openpm/workgpt)、[AutoChain ](https://github.com/Forethought-Technologies/AutoChain)、[Langroid](https://github.com/langroid/langroid)、 [WebArena](https://github.com/web-arena-x/webarena)、[GPT Researcher](https://github.com/assafelovic/gpt-researcher)、 |
|   Multi-Agent   | [CAMEL](https://github.com/camel-ai/camel)、[GPTeam](https://github.com/101dotxyz/GPTeam)、[AgentVerse](https://github.com/OpenBMB/AgentVerse)、[MetaGPT](https://github.com/geekan/MetaGPT)、[Langroid](https://github.com/langroid/langroid)、[SocraticAI](https://github.com/RunzheYang/SocraticAI) |
|     Others      | [AutoAgents](https://github.com/AutoLLM/AutoAgents)![img](https://img.shields.io/badge/-Reasoning-blue) 、[GPT Engineer](https://github.com/AntonOsika/gpt-engineer)  ![img](https://img.shields.io/badge/-Code-pink) |

### 📜 List

- **[Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT).** An experimental open-source attempt to make GPT-4 fully autonomous.

- **[LangChain](https://github.com/hwchase17/langchain).**  Building applications with LLMs through composability.

- **[CAMEL](https://github.com/camel-ai/camel).**  Communicative Agents for “Mind” Exploration of Large Scale Language Model Society.

- **[GPTeam](https://github.com/101dotxyz/GPTeam).**  GPTeam: An open-source multi-agent simulation. 

- **[Transformer Agents](https://huggingface.co/docs/transformers/transformers_agents).**  In short, it provides a natural language API on top of transformers: we define a set of curated tools and design an agent to interpret natural language and to use these tools.  

- **[AgentVerse](https://github.com/OpenBMB/AgentVerse) .**  A Framework for Multi-LLM Environment Simulation.  

- **[AutoAgents](https://github.com/AutoLLM/AutoAgents).** Complex question answering in LLMs with enhanced reasoning and information-seeking capabilities.

- **[GPT Engineer](https://github.com/AntonOsika/gpt-engineer) .**  Specify what you want it to build, the AI asks for clarification, and then builds it.  

- **[MetaGPT](https://github.com/geekan/MetaGPT).** The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo

- **[WorkGPT](https://github.com/team-openpm/workgpt).** A GPT agent framework for invoking APIs.  

- **[AutoChain](https://github.com/Forethought-Technologies/AutoChain).** Build lightweight, extensible, and testable LLM Agents. 

- **[Langroid](https://github.com/langroid/langroid).** Harness LLMs with Multi-Agent Programming.

- **[SocraticAI](https://github.com/RunzheYang/SocraticAI).** Problem solving by engaging multiple AI agents in conversation with each other and the user. 

- **[WebArena](https://github.com/web-arena-x/webarena).** A Realistic Web Environment for Building Autonomous Agents. 

- **[GPT Researcher](https://github.com/assafelovic/gpt-researcher).** GPT based autonomous agent that does online comprehensive research on any given topic.
