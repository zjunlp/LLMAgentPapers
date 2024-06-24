# LLM Agents Papers

[![Awesome](https://awesome.re/badge.svg)](https://github.com/zjunlp/LLMAgentPapers) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/zjunlp/LLMAgentPapers?color=green) 

Must-read Papers on Large Language Model Agents.

---

*"Here are some other paper lists you might be interested in:*

💡 **[Prompt4ReasoningPapers](https://github.com/zjunlp/Prompt4ReasoningPapers):** Reasoning with Language Model Prompting Papers.

🔬 **[KnowledgeditingPapers](https://github.com/zjunlp/KnowledgeEditingPapers):**  Must-read papers on knowledge editing for large language models.

*We sincerely invite you to dive into these collections of papers and resources, each offering a distinct journey of exploration and discovery.*  :partying_face:”



## 🔔 News

- **[2024-03]** We release a new paper: "[KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents](https://arxiv.org/abs/2403.03101)".
- **[2023-06]** We create this repository to maintain a paper list on *Multi-agents*.



## 📜Content

- [LLM Agents Papers](#llm-agents-papers)
  - [🔔 News](#-news)
  - [📜Content](#content)
  - [🌄 Papers](#-papers)
    - [Overview](#overview)
    - [🤖 Agent](#-agent)
      - [Personality. 🧛🧙](#personality-)
      - [Memory. 💭💫](#memory-)
      - [Planning. 🧩♟️](#planning-️)
      - [Tool use. 👩‍🔧🔧](#tool-use-)
    - [🤖💬🤖 Multiple Agents](#-multiple-agents)
      - [Task-Oriented Communication](#task-oriented-communication)
        - [Collaborative Exchanges 👨‍💻👩‍💻](#collaborative-exchanges-)
        - [Adversarial Interactions 👨🏻‍🦳🗣](#adversarial-interactions-)
      - [Casual/Open Conversations 👥💬](#casualopen-conversations-)
    - [🪐 Application](#-application)
    - [🖼️ Framework](#️-framework)
    - [🔖 Others](#-others)
  - [🧰 Resources](#-resources)
    - [Benchmarks](#benchmarks)
    - [Types of Tools](#types-of-tools)
    - [📜 Tool List](#-tool-list)
  - [🎉 Contribution](#-contribution)
    - [Contributing to this paper list](#contributing-to-this-paper-list)
    - [Contributors](#contributors)



---

## 🌄 Papers

### Overview

1. **Interactive Natural Language Processing**

   *Zekun Wang, Ge Zhang, Kexin Yang, Ning Shi, Wangchunshu Zhou, Shaochun Hao, Guangzheng Xiong, Yizhi Li, Mong Yuan Sim, Xiuying Chen, Qingqing Zhu, Zhenzhu Yang, Adam Nik, Qi Liu, Chenghua Lin, Shi Wang, Ruibo Liu, Wenhu Chen, Ke Xu, Dayiheng Liu, Yike Guo, Jie Fu.* [[abs]](https://arxiv.org/abs/2305.13246), 2023.5

2. **A Survey on Large Language Model based Autonomous Agents**

   *Lei Wang, Chen Ma, Xueyang Feng, Zeyu Zhang, Hao Yang, Jingsen Zhang, Zhiyuan Chen, Jiakai Tang, Xu Chen, Yankai Lin, Wayne Xin Zhao, Zhewei Wei, Ji-Rong Wen.* [[abs](https://arxiv.org/abs/2308.11432)], 2023.8

3. **The Rise and Potential of Large Language Model Based Agents: A Survey**

   *Zhiheng Xi, Wenxiang Chen, Xin Guo, Wei He, Yiwen Ding, Boyang Hong, Ming Zhang, Junzhe Wang, Senjie Jin, Enyu Zhou, Rui Zheng, Xiaoran Fan, Xiao Wang, Limao Xiong, Yuhao Zhou, Weiran Wang, Changhao Jiang, Yicheng Zou, Xiangyang Liu, Zhangyue Yin, Shihan Dou, Rongxiang Weng, Wensen Cheng, Qi Zhang, Wenjuan Qin, Yongyan Zheng, Xipeng Qiu, Xuanjing Huang, Tao Gui.* [[abs](https://arxiv.org/abs/2309.07864)], 2023.9

4. **If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents**

    *Ke Yang, Jiateng Liu, John Wu, Chaoqi Yang, Yi R. Fung, Sha Li, Zixuan Huang, Xu Cao, Xingyao Wang, Yiquan Wang, Heng Ji, Chengxiang Zhai.* [[abs](https://arxiv.org/abs/2401.00812)], 2024.1

5. **Agent AI: Surveying the Horizons of Multimodal Interaction**

   *Zane Durante, Qiuyuan Huang, Naoki Wake, Ran Gong, Jae Sung Park, Bidipta Sarkar, Rohan Taori, Yusuke Noda, Demetri Terzopoulos, Yejin Choi, Katsushi Ikeuchi, Hoi Vo, Li Fei-Fei, Jianfeng Gao.* [[abs](https://arxiv.org/pdf/2401.03568.pdf)], 2024.1

6. **Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security**

   *Yuanchun Li, Hao Wen, Weijun Wang, Xiangyu Li, Yizhen Yuan, Guohong Liu, Jiacheng Liu, Wenxing Xu, Xiang Wang, Yi Sun, Rui Kong, Yile Wang, Hanfei Geng, Jian Luan, Xuefeng Jin, Zilong Ye, Guanjing Xiong, Fan Zhang, Xiang Li, Mengwei Xu, Zhijun Li, Peng Li, Yang Liu, Ya-Qin Zhang, Yunxin Liu.* [[abs](https://arxiv.org/pdf/2401.05459.pdf)], 2024.1
   
---

### 🤖 Agent

#### Personality. 🧛🧙

1. **Theory of Mind May Have Spontaneously Emerged in Large Language Models**

   *Michal Kosinski.* [[abs](https://arxiv.org/abs/2302.02083)], 2023.2

2. **Toxicity in ChatGPT: Analyzing Persona-assigned Language Models**

   *Ameet Deshpande, Vishvak Murahari, Tanmay Rajpurohit, Ashwin Kalyan, Karthik Narasimhan.* [[abs](https://arxiv.org/abs/2304.05335)], 2023.4

3. **Playing repeated games with Large Language Models**

   *Elif Akata, Lion Schulz, Julian Coda-Forno, Seong Joon Oh, Matthias Bethge, Eric Schulz.* [[abs](https://arxiv.org/abs/2305.16867)], 2023.5

4. **ExpertPrompting: Instructing Large Language Models to be Distinguished Experts**

   *Benfeng Xu, An Yang, Junyang Lin, Quan Wang, Chang Zhou, Yongdong Zhang, Zhendong Mao.*  [[abs](https://arxiv.org/abs/2305.14688)], 2023.5

5. **Role-Play with Large Language Models**

   *Murray Shanahan, Kyle McDonell, Laria Reynolds.* [[abs](https://arxiv.org/abs/2305.16367)], 2023.5

6. **TidyBot: Personalized Robot Assistance with Large Language Models**

   *Jimmy Wu, Rika Antonova, Adam Kan, Marion Lepert, Andy Zeng, Shuran Song, Jeannette Bohg, Szymon Rusinkiewicz, Thomas Funkhouser.* [[abs](https://arxiv.org/abs/2305.05658)], 2023.5

7. **Personality Traits in Large Language Models**

   *Mustafa Safdari, Greg Serapio-García, Clément Crepy, Stephen Fitz, Peter Romero, Luning Sun, Marwa Abdulhai, Aleksandra Faust, Maja Matarić.* [[abs](https://arxiv.org/abs/2307.00184)], 2023.7

8. **Do LLMs Possess a Personality? Making the MBTI Test an Amazing Evaluation for Large Language Models**

   *Keyu Pan, Yawen Zeng.* [[abs](https://arxiv.org/abs/2307.16180)], 2023.7

9. **Consciousness in Artificial Intelligence: Insights from the Science of Consciousness**

   *Patrick Butlin, Robert Long, Eric Elmoznino, Yoshua Bengio, Jonathan Birch, Axel Constant, George Deane, Stephen M. Fleming, Chris Frith, Xu Ji, Ryota Kanai, Colin Klein, Grace Lindsay, Matthias Michel, Liad Mudrik, Megan A. K. Peters, Eric Schwitzgebel, Jonathan Simon, Rufin VanRullen.* [[abs](https://arxiv.org/abs/2308.08708)], 2023.8

10. **Taken out of context: On measuring situational awareness in LLMs**

    *Lukas Berglund, Asa Cooper Stickland, Mikita Balesni, Max Kaufmann, Meg Tong, Tomasz Korbak, Daniel Kokotajlo, Owain Evans.* [[abs](https://arxiv.org/abs/2309.00667)], 2023.9

11. **Can Large Language Model Agents Simulate Human Trust Behaviors?**

    *Chengxing Xie, Canyu Chen, Feiran Jia, Ziyu Ye, Kai Shu, Adel Bibi, Ziniu Hu, Philip Torr, Bernard Ghanem, Guohao Li.* [[abs](https://arxiv.org/abs/2402.04559)], 2024.02
    
    
#### Memory. 💭💫

1. **CoLT5: Faster Long-Range Transformers with Conditional Computation**

   *Joshua Ainslie, Tao Lei, Michiel de Jong, Santiago Ontañón, Siddhartha Brahma, Yury Zemlyanskiy, David Uthus, Mandy Guo, James Lee-Thorp, Yi Tay, Yun-Hsuan Sung, Sumit Sanghai.* [[abs](https://arxiv.org/abs/2303.09752)], 2023.3

2. **Emergent and Predictable Memorization in Large Language Models**

   *Stella Biderman, USVSN Sai Prashanth, Lintang Sutawika, Hailey Schoelkopf, Quentin Anthony, Shivanshu Purohit, Edward Raff.* [[abs](https://arxiv.org/abs/2304.11158)], 2023.4

3. **Unleashing Infinite-Length Input Capacity for Large-scale Language Models with Self-Controlled Memory System**

   *Xinnian Liang, Bing Wang, Hui Huang, Shuangzhi Wu, Peihao Wu, Lu Lu, Zejun Ma, Zhoujun Li.* [[abs](https://arxiv.org/abs/2304.13343)], 2023.4

4. **ChatLog: Recording and Analyzing ChatGPT Across Time**

   *Shangqing Tu, Chunyang Li, Jifan Yu, Xiaozhi Wang, Lei Hou, Juanzi Li.* [[abs](https://arxiv.org/abs/2304.14106)], 2023.4

5. **Learning to Reason and Memorize with Self-Notes**

   *Jack Lanchantin, Shubham Toshniwal, Jason Weston, Arthur Szlam, Sainbayar Sukhbaatar.* [[abs](https://arxiv.org/abs/2305.00833)], 2023.5

6. **Unlimiformer: Long-Range Transformers with Unlimited Length Input**

   *Amanda Bertsch, Uri Alon, Graham Neubig, Matthew R. Gormley.* [[abs](https://arxiv.org/abs/2305.01625)], 2023.5

7. **Small Models are Valuable Plug-ins for Large Language Models**

   *Canwen Xu, Yichong Xu, Shuohang Wang, Yang Liu, Chenguang Zhu, Julian McAuley.* [[abs](https://arxiv.org/abs/2305.08848)], 2023.5

8. **MemoryBank: Enhancing Large Language Models with Long-Term Memory**

   *Wanjun Zhong, Lianghong Guo, Qiqi Gao, He Ye, Yanlin Wang.* [[abs](https://arxiv.org/abs/2305.10250)], 2023.5

9. **ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings**

   *Shibo Hao, Tianyang Liu, Zhen Wang, Zhiting Hu.* [[abs](https://arxiv.org/abs/2305.11554)], 2023.5

10. **RecurrentGPT: Interactive Generation of (Arbitrarily) Long Text**

    *Wangchunshu Zhou, Yuchen Eleanor Jiang, Peng Cui, Tiannan Wang, Zhenxin Xiao, Yifan Hou, Ryan Cotterell, Mrinmaya Sachan.* [[abs](https://arxiv.org/abs/2305.13304)], 2023.5

11. **RET-LLM: Towards a General Read-Write Memory for Large Language Models**

    *Ali Modarressi, Ayyoob Imani, Mohsen Fayyaz, Hinrich Schütze.* [[abs](https://arxiv.org/abs/2305.14322)], 2023.5

12. **Adapting Language Models to Compress Contexts**

    *Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen.* [[abs](https://arxiv.org/abs/2305.14788)], 2023.5 

13. **Revisiting Parallel Context Windows: A Frustratingly Simple Alternative and Chain-of-Thought Deterioration**

    *Kejuan Yang, Xiao Liu, Kaiwen Men, Aohan Zeng, Yuxiao Dong, Jie Tang.* [[abs](https://arxiv.org/abs/2305.15262)], 2023.5

14. **Landmark Attention: Random-Access Infinite Context Length for Transformers**

    *Amirkeivan Mohtashami, Martin Jaggi.* [[abs](https://arxiv.org/abs/2305.16300)], 2023.5

15. **Randomized Positional Encodings Boost Length Generalization of Transformers**

    *Anian Ruoss, Grégoire Delétang, Tim Genewein, Jordi Grau-Moya, Róbert Csordás, Mehdi Bennani, Shane Legg, Joel Veness.* [[abs](https://arxiv.org/abs/2305.16843)], 2023.5

16. **Monotonic Location Attention for Length Generalization**

    *Jishnu Ray Chowdhury, Cornelia Caragea.* [[abs](https://arxiv.org/abs/2305.20019)], 2023.5

17. **ChatDB: Augmenting LLMs with Databases as Their Symbolic Memory**

    *Chenxu Hu, Jie Fu, Chenzhuang Du, Simian Luo, Junbo Zhao, Hang Zhao.* [[abs](https://arxiv.org/abs/2306.03901)], 2023.6

18. **Cognitive Architectures for Language Agents**

    *Theodore Sumers, Shunyu Yao, Karthik Narasimhan, Thomas L. Griffiths* [[abs](https://arxiv.org/abs/2309.02427)], 2023.9

19. **JARVIS-1: Open-world Multi-task Agents with Memory-Augmented Multimodal Language Models**

    *Zihao Wang, Shaofei Cai, Anji Liu, Yonggang Jin, Jinbing Hou, Bowei Zhang, Haowei Lin, Zhaofeng He, Zilong Zheng, Yaodong Yang, Xiaojian Ma, Yitao Liang*. [[abs](https://arxiv.org/abs/2311.05997)], 2023.11

20. **A Survey on the Memory Mechanism of Large Language Model based Agents**

    *Zeyu Zhang, Xiaohe Bo, Chen Ma, Rui Li, Xu Chen, Quanyu Dai, Jieming Zhu, Zhenhua Dong, Ji-Rong Wen*. [[abs](https://arxiv.org/abs/2404.13501)], 2024.4

21. **HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models**

    *Bernal Jiménez Gutiérrez, Yiheng Shu, Yu Gu, Michihiro Yasunaga, Yu Su.* [[abs](https://arxiv.org/abs/2405.14831)], 2024.5
    
23. **Buffer of Thoughts: Thought-Augmented Reasoning with Large Language Models**

    *Ling Yang, Zhaochen Yu, Tianjun Zhang, Shiyi Cao, Minkai Xu, Wentao Zhang, Joseph E. Gonzalez, Bin Cui.*  [[abs](https://arxiv.org/abs/2406.04271)],2024,6


#### Planning. 🧩♟️

1. **Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents**

   *Wenlong Huang, Pieter Abbeel, Deepak Pathak, Igor Mordatch*. [[abs](https://arxiv.org/abs/2201.07207)], 2022.1

2. **Inner Monologue: Embodied Reasoning through Planning with Language Models**

   *Wenlong Huang , Fei Xia , Ted Xiao , Harris Chan, Jacky Liang, Pete Florence, Andy Zeng, Jonathan Tompson, Igor Mordatch, Yevgen Chebotar, Pierre Sermanet, Noah Brown, Tomas Jackson, Linda Luu, Sergey Levine, Karol Hausman, Brian Ichter*. [[abs](https://arxiv.org/abs/2207.05608)], 2022.7

3. **ReAct: Synergizing Reasoning and Acting in Language Models**

   *Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik Narasimhan, Yuan Cao.* [[abs](https://arxiv.org/abs/2210.03629)], 2022.10

4. **Mind's Eye: Grounded Language Model Reasoning through Simulation**

   *Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M. Dai.* [[abs](https://arxiv.org/abs/2210.05359)], 2022.10

5. **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**

   *Chan Hee Song, Jiaman Wu, Clayton Washington, Brian M. Sadler, Wei-Lun Chao, Yu Su*. [[abs](https://arxiv.org/abs/2212.04088)], 2022.12

6. **Don’t Generate, Discriminate: A Proposal for Grounding Language Models to Real-World Environments**

   *Yu Gu, Xiang Deng, Yu Su.* [[abs](https://arxiv.org/abs/2212.09736)], 2022.12

7. **Do Embodied Agents Dream of Pixelated Sheep?: Embodied Decision Making using Language Guided World Modelling**

   *Kolby Nottingham, Prithviraj Ammanabrolu, Alane Suhr, Yejin Choi, Hannaneh Hajishirzi, Sameer Singh, Roy Fox*. [[abs](https://arxiv.org/abs/2301.12050)], 2023.1

8. **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents**

   *Zihao Wang, Shaofei Cai, Anji Liu, Xiaojian Ma, Yitao Liang*. [[abs](https://arxiv.org/abs/2302.01560)], 2023.2

9. **PaLM-E: An embodied multimodal language model**

   *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, Corey Lynch, Aakanksha Chowdhery, Brian Ichter, Ayzaan Wahid, Jonathan Tompson, Quan Vuong, Tianhe Yu, Wenlong Huang, Yevgen Chebotar, Pierre Sermanet, Daniel Duckworth, Sergey Levine, Vincent Vanhoucke, Karol Hausman, Marc Toussaint, Klaus Greff, Andy Zeng, Igor Mordatch, Pete Florence.* [[abs](https://arxiv.org/abs/2303.03378)], 2023.3

10. **Reflexion: Language Agents with Verbal Reinforcement Learning**

    *Noah Shinn, Federico Cassano, Beck Labash, Ashwin Gopinath, Karthik Narasimhan, Shunyu Yao.* [[abs](https://arxiv.org/abs/2303.11366)], 2023.3

11. **Chat with the Environment: Interactive Multimodal Perception using Large Language Models**

    *Xufeng Zhao, Mengdi Li, Cornelius Weber, Muhammad Burhan Hafez, Stefan Wermter*. [[abs](https://arxiv.org/abs/2303.08268)], 2023.3

12. **Plan4MC: Skill Reinforcement Learning and Planning for Open-World Minecraft Tasks**

    *Haoqi Yuan, Chi Zhang, Hongcheng Wang, Feiyang Xie, Penglin Cai, Hao Dong, Zongqing Lu.* [[abs](https://arxiv.org/abs/2303.16563)], 2023.3

13. **Self-Refine: Iterative Refinement with Self-Feedback**

    *Aman Madaan, Niket Tandon, Prakhar Gupta, Skyler Hallinan, Luyu Gao, Sarah Wiegreffe, Uri Alon, Nouha Dziri, Shrimai Prabhumoye, Yiming Yang, Shashank Gupta, Bodhisattwa Prasad Majumder, Katherine Hermann, Sean Welleck, Amir Yazdanbakhsh, Peter Clark.* [[abs](https://arxiv.org/abs/2303.17651)], 2023.3

14. **Teaching Large Language Models to Self-Debug**

    *Xinyun Chen, Maxwell Lin, Nathanael Schärli, Denny Zhou.* [[abs](https://arxiv.org/abs/2304.05128)], 2023.4

15. **WizardLM: Empowering Large Language Models to Follow Complex Instructions**

    *Can Xu, Qingfeng Sun, Kai Zheng, Xiubo Geng, Pu Zhao, Jiazhan Feng, Chongyang Tao, Daxin Jiang.* [[abs](https://arxiv.org/abs/2304.12244)], 2023.4

16. **FrugalGPT: How to Use Large Language Models While Reducing Cost and Improving Performance**

    *Lingjiao Chen, Matei Zaharia, James Zou.* [[abs](https://arxiv.org/abs/2305.05176)], 2023.5

17. **Tree of Thoughts: Deliberate Problem Solving with Large Language Models**

    *Shunyu Yao, Dian Yu, Jeffrey Zhao, Izhak Shafran, Thomas L. Griffiths, Yuan Cao, Karthik Narasimhan.* [[abs](https://arxiv.org/abs/2305.10601)], 2023.5

18. **Plan, Eliminate, and Track -- Language Models are Good Teachers for Embodied Agents**

    *Yue Wu, So Yeon Min, Yonatan Bisk, Ruslan Salakhutdinov, Amos Azaria, Yuanzhi Li, Tom Mitchell, Shrimai Prabhumoye*. [[abs](https://arxiv.org/abs/2305.02412)], 2023.5

19. **Knowledge-enhanced Agents for Interactive Text Games**

    *Prateek Chhikara, Jiarui Zhang, Filip Ilievski, Jonathan Francis, Kaixin Ma.* [[abs](https://arxiv.org/abs/2305.05091)], 2023.5 

20. **Voyager: An Open-Ended Embodied Agent with Large Language Models**

    *Guanzhi Wang, Yuqi Xie, Yunfan Jiang, Ajay Mandlekar, Chaowei Xiao, Yuke Zhu, Linxi Fan, Anima Anandkumar*. [[abs](https://arxiv.org/abs/2305.16291)], 2023.5

21. **SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks**

    *Bill Yuchen Lin, Yicheng Fu, Karina Yang, Prithviraj Ammanabrolu, Faeze Brahman, Shiyu Huang, Chandra Bhagavatula, Yejin Choi, Xiang Ren.* [[abs](https://arxiv.org/abs/2305.17390)], 2023.5

22. **Language Models Meet World Models: Embodied Experiences Enhance Language Models**

    *Jiannan Xiang, Tianhua Tao, Yi Gu, Tianmin Shu, Zirui Wang, Zichao Yang, Zhiting Hu.* [[abs](https://arxiv.org/abs/2305.10626)], 2023.5

23. **Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory**

    *Xizhou Zhu, Yuntao Chen, Hao Tian, Chenxin Tao, Weijie Su, Chenyu Yang, Gao Huang, Bin Li, Lewei Lu, Xiaogang Wang, Yu Qiao, Zhaoxiang Zhang, Jifeng Dai.* [[abs](https://arxiv.org/abs/2305.17144)], 2023.5

24. **AdaPlanner: Adaptive Planning from Feedback with Language Models**

    *Haotian Sun, Yuchen Zhuang, Lingkai Kong, Bo Dai, Chao Zhang.* [[abs](https://arxiv.org/abs/2305.16653)], 2023.5 

25. **Reasoning with Language Model is Planning with World Model**

    *Shibo Hao, Yi Gu, Haodi Ma, Joshua Jiahua Hong, Zhen Wang, Daisy Zhe Wang, Zhiting Hu.* [[abs](https://arxiv.org/abs/2305.14992)], 2023.5

26. **Plan-and-Solve Prompting: Improving Zero-Shot Chain-of-Thought Reasoning by Large Language Models**

    *Lei Wang, Wanyu Xu, Yihuai Lan, Zhiqiang Hu, Yunshi Lan, Roy Ka-Wei Lee, Ee-Peng Lim.* [[abs](https://arxiv.org/abs/2305.04091)], 2023.5

27. **Enabling Intelligent Interactions between an Agent and an LLM: A Reinforcement Learning Approach**

    *Bin Hu, Chenyang Zhao, Pu Zhang, Zihao Zhou, Yuanhang Yang, Zenglin Xu, Bin Liu.* [[abs](https://arxiv.org/abs/2306.03604)], 2023.6

28. **RecAgent: A Novel Simulation Paradigm for Recommender Systems**

    *Lei Wang, Jingsen Zhang, Xu Chen, Yankai Lin, Ruihua Song, Wayne Xin Zhao, Ji-Rong Wen.* [[abs](https://arxiv.org/abs/2306.02552)], 2023.6

29. **Towards A Unified Agent with Foundation Models.**

    *Norman Di Palo, Arunkumar Byravan, Leonard Hasenclever, Markus Wulfmeier, Nicolas Heess, Martin Riedmiller.* [[abs](https://arxiv.org/abs/2307.09668)], 2023.7

30. **PanGu-Coder2: Boosting Large Language Models for Code with Ranking Feedback**

    *Bo Shen, Jiaxin Zhang, Taihong Chen, Daoguang Zan, Bing Geng, An Fu, Muhan Zeng, Ailun Yu, Jichuan Ji, Jingyang Zhao, Yuenan Guo, Qianxiang Wang.* [[abs](https://arxiv.org/abs/2307.14936)], 2023.7

31. **A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis**

    *Izzeddin Gur, Hiroki Furuta, Austin Huang, Mustafa Safdari, Yutaka Matsuo, Douglas Eck, Aleksandra Faust.* [[abs](https://arxiv.org/abs/2307.12856)], 2023.7

32. **Retroformer: Retrospective Large Language Agents with Policy Gradient Optimization**

    *Weiran Yao, Shelby Heinecke, Juan Carlos Niebles, Zhiwei Liu, Yihao Feng, Le Xue, Rithesh Murthy, Zeyuan Chen, Jianguo Zhang, Devansh Arpit, Ran Xu, Phil Mui, Huan Wang, Caiming Xiong, Silvio Savarese.* [[abs](https://arxiv.org/abs/2308.02151)], 2023.8

33. **SelfCheck: Using LLMs to Zero-Shot Check Their Own Step-by-Step Reasoning**

    *Ning Miao, Yee Whye Teh, Tom Rainforth.* [[abs](https://arxiv.org/abs/2308.00436)], 2023.8

34. **ExpeL: LLM Agents Are Experiential Learners**

    *Andrew Zhao, Daniel Huang, Quentin Xu, Matthieu Lin, Yong-Jin Liu, Gao Huang.* [[abs](https://arxiv.org/abs/2308.10144)], 2023.8

35. **Self-driven Grounding: Large Language Model Agents with Automatical Language-aligned Skill Learning**

    *Shaohui Peng, Xing Hu, Qi Yi, Rui Zhang, Jiaming Guo, Di Huang, Zikang Tian, Ruizhi Chen, Zidong Du, Qi Guo, Yunji Chen, Ling Li.* [[abs](https://arxiv.org/abs/2309.01352)], 2023.9

36. **JARVIS-1: Open-world Multi-task Agents with Memory-Augmented Multimodal Language Models**

    *Zihao Wang, Shaofei Cai, Anji Liu, Yonggang Jin, Jinbing Hou, Bowei Zhang, Haowei Lin, Zhaofeng He, Zilong Zheng, Yaodong Yang, Xiaojian Ma, Yitao Liang*. [[abs](https://arxiv.org/abs/2311.05997)], 2023.11

37. **LEO: An Embodied Generalist Agent in 3D World**

    *Jiangyong Huang, Silong Yong, Xiaojian Ma, Xiongkun Linghu*, Puhao Li, Yan Wang, Qing Li, Song-Chun Zhu, Baoxiong Jia, Siyuan Huang* [[abs](https://arxiv.org/abs/2311.12871)], 2023.11

38. **Chain of Code: Reasoning with a Language Model-Augmented Code Emulator**

    *Chengshu Li, Jacky Liang, Andy Zeng, Xinyun Chen, Karol Hausman, Dorsa Sadigh, Sergey Levine, Li Fei-Fei, Fei Xia, Brian Ichter.* [[abs](https://arxiv.org/abs/2312.04474)], 2023.12

39. **ReST meets ReAct: Self-Improvement for Multi-Step Reasoning LLM Agent**

    *Renat Aksitov, Sobhan Miryoosefi, Zonglin Li, Daliang Li, Sheila Babayan, Kavya Kopparapu, Zachary Fisher, Ruiqi Guo, Sushant Prakash, Pranesh Srinivasan, Manzil Zaheer, Felix Yu, Sanjiv Kumar.* [[abs](https://arxiv.org/abs/2312.10003)], 2023.12

40. **Self-Contrast: Better Reflection Through Inconsistent Solving Perspectives**

    *Wenqi Zhang, Yongliang Shen, Linjuan Wu, Qiuying Peng, Jun Wang, Yueting Zhuang, Weiming Lu.* [[abs](https://arxiv.org/abs/2401.02009)], 2024.01

41. **AutoAct: Automatic Agent Learning from Scratch via Self-Planning**

    *Shuofei Qiao, Ningyu Zhang, Runnan Fang, Yujie Luo, Wangchunshu Zhou, Yuchen Eleanor Jiang, Chengfei Lv, Huajun Chen.* [[abs](https://arxiv.org/abs/2401.05268)], 2024.01

42. **TravelPlanner: A Benchmark for Real-World Planning with Language Agents**
   
    *Jian Xie, Kai Zhang, Jiangjie Chen, Tinghui Zhu, Renze Lou, Yuandong Tian, Yanghua Xiao, Yu Su.* [[abs](https://arxiv.org/pdf/2402.01622.pdf)],2024.02

43. **Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization**
    
    *Wenqi Zhang, Ke Tang, Hai Wu, Mengna Wang, Yongliang Shen, Guiyang Hou, Zeqi Tan, Peng Li, Yueting Zhuang, Weiming Lu.* [[abs](https://arxiv.org/pdf/2402.17574)],2024.02

44. **KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents**

    *Yuqi Zhu, Shuofei Qiao, Yixin Ou, Shumin Deng, Ningyu Zhang, Shiwei Lyu, Yue Shen, Lei Liang, Jinjie Gu, Huajun Chen.* [[abs](https://arxiv.org/abs/2403.03101)], 2024.03

45. **SOTOPIA-π: Interactive Learning of Socially Intelligent Language Agents**

    *Ruiyi Wang, Haofei Yu, Wenxin Zhang, Zhengyang Qi, Maarten Sap, Graham Neubig, Yonatan Bisk, Hao Zhu.* [[abs](https://arxiv.org/abs/2403.08715)], 2024.03

46. **AutoGuide: Automated Generation and Selection of State-Aware Guidelines for Large Language Model Agents**

    *Yao Fu, Dong-Ki Kim, Jaekyeom Kim, Sungryull Sohn, Lajanugen Logeswaran, Kyunghoon Bae, Honglak Lee.* [[abs](https://arxiv.org/abs/2403.08978)], 2024.03

47. **Empowering Large Language Model Agents through Action Learning**

    *Haiteng Zhao, Chang Ma, Guoyin Wang, Jing Su, Lingpeng Kong, Jingjing Xu, Zhi-Hong Deng, Hongxia Yang.* [[abs](https://arxiv.org/abs/2402.15809)], 2024.02

48. **Devil’s Advocate: Anticipatory Reflection for LLM Agents**

    *Haoyu Wang, Tao Li, Zhiwei Deng, Dan Roth, Yang Li.* [[abs](https://arxiv.org/abs/2405.16334v3)], 2024.05
    
49. **Agent Planning with World Knowledge Model**

    *Shuofei Qiao, Runnan Fang, Ningyu Zhang, Yuqi Zhu, Xiang Chen, Shumin Deng, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen.* [[abs](https://arxiv.org/abs/2405.14205)], 2024.05

50. **Intelligent Go-Explore: Standing on the Shoulders of Giant Foundation Models**

    *Cong Lu, Shengran Hu, Jeff Clune.* [[abs](https://arxiv.org/abs/2405.15143)], 2024.05

51. **Faithful Logical Reasoning via Symbolic Chain-of-Thought**

    *Jundong Xu, Hao Fei, Liangming Pan, Qian Liu, Mong-Li Lee, Wynne Hsu.* [[abs](https://arxiv.org/abs/2405.18357)], 2024.05

52. **Alice in Wonderland：Simple Tasks Showing Complete Reasoning Breakdown in State-Of-the-Art Large Language Models**

    *Marianna Nezhurina, Lucia Cipolina-Kun, Mehdi Cherti, Jenia Jitsev.* [[abs](https://arxiv.org/abs/2406.02061)], 2024.06
    
53. **TextGrad: Automatic “Differentiation” via Text**

    *Mert Yuksekgonul, Federico Bianchi, Joseph Boen, Sheng Liu, Zhi Huang, Carlos Guestrin, James Zou.* [[abs](https://arxiv.org/abs/2406.07496)], 2024.06
    
#### Tool use. 👩‍🔧🔧

1. **WebGPT: Browser-assisted question-answering with human feedback**

   *Reiichiro Nakano, Jacob Hilton, Suchir Balaji, Jeff Wu, Long Ouyang, Christina Kim, Christopher Hesse, Shantanu Jain, Vineet Kosaraju, William Saunders, Xu Jiang, Karl Cobbe, Tyna Eloundou, Gretchen Krueger, Kevin Button, Matthew Knight, Benjamin Chess, John Schulman.* [[abs](https://arxiv.org/abs/2112.09332)], 2021.12

2. **Toolformer: Language Models Can Teach Themselves to Use Tools**

   *Timo Schick, Jane Dwivedi-Yu, Roberto Dessì, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom.* [[abs](https://arxiv.org/abs/2302.04761)], 2023.2

3. **MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action**

   *Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Ehsan Azarnasab, Faisal Ahmed, Zicheng Liu, Ce Liu, Michael Zeng, Lijuan Wang.* [[abs](https://arxiv.org/abs/2303.11381)], 2023.3

4. **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face**

   *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang.* [[abs](https://arxiv.org/abs/2303.17580)], 2023.3

5. **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models**

   *Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan.* [[abs](https://arxiv.org/abs/2303.04671)], 2023.3

6. **ART: Automatic multi-step reasoning and tool-use for large language models**

   *Bhargavi Paranjape, Scott Lundberg, Sameer Singh, Hannaneh Hajishirzi, Luke Zettlemoyer, Marco Tulio Ribeiro.* [[abs](https://arxiv.org/abs/2303.09014)], 2023.3

7. **TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs**

   *Yaobo Liang, Chenfei Wu, Ting Song, Wenshan Wu, Yan Xia, Yu Liu, Yang Ou, Shuai Lu, Lei Ji, Shaoguang Mao, Yun Wang, Linjun Shou, Ming Gong, Nan Duan.* [[abs](https://arxiv.org/abs/2303.16434)], 2023.3

8. **Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models**

   *Pan Lu, Baolin Peng, Hao Cheng, Michel Galley, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Jianfeng Gao.* [[abs](https://arxiv.org/abs/2304.09842)], 2023.4

9. **ChemCrow: Augmenting large-language models with chemistry tools**

   *Andres M Bran, Sam Cox, Andrew D White, Philippe Schwaller.* [[abs](https://arxiv.org/abs/2304.05376)], 2023.4

10. **TALM: Tool Augmented Language Models**

    *Aaron Parisi, Yao Zhao, Noah Fiedel.* [[abs](https://arxiv.org/abs/2205.12255)], 2022.5

11. **CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing**

    *Zhibin Gou, Zhihong Shao, Yeyun Gong, Yelong Shen, Yujiu Yang, Minlie Huang, Nan Duan, Weizhu Chen.*  [[abs](https://arxiv.org/pdf/2305.11738.pdf)] [[code](https://github.com/microsoft/ProphetNet/tree/master/CRITIC)], 2023.5

12. **Making Language Models Better Tool Learners with Execution Feedback**

    *Shuofei Qiao, Honghao Gui, Huajun Chen, Ningyu Zhang.* [[abs](https://arxiv.org/abs/2305.13068)],2023.5

13. **ChatCoT: Tool-Augmented Chain-of-Thought Reasoning on Chat-based Large Language Models**

    *Zhipeng Chen, Kun Zhou, Beichen Zhang, Zheng Gong, Wayne Xin Zhao, Ji-Rong Wen.* [[abs](https://arxiv.org/abs/2305.14323)], 2023.5

14. **Gorilla: Large Language Model Connected with Massive APIs**

    *Shishir G. Patil, Tianjun Zhang, Xin Wang, Joseph E. Gonzalez.* [[abs](https://arxiv.org/abs/2305.15334)], 2023.5

15. **ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs**

    *Yujia Qin, Shihao Liang, Yining Ye, Kunlun Zhu, Lan Yan, Yaxi Lu, Yankai Lin, Xin Cong, Xiangru Tang, Bill Qian, Sihan Zhao, Runchu Tian, Ruobing Xie, Jie Zhou, Mark Gerstein, Dahai Li, Zhiyuan Liu, Maosong Sun.* [[abs](https://arxiv.org/abs/2307.16789)], 2023.7

16. **GEAR: Augmenting Language Models with Generalizable and Efficient Tool Resolution**

    *Yining Lu, Haoping Yu, Daniel Khashabi.* [[abs](https://arxiv.org/abs/2307.08775)], 2023.7  

17. **Gentopia: A Collaborative Platform for Tool-Augmented LLMs**

    *Binfeng Xu, Xukun Liu, Hua Shen, Zeyu Han, Yuhan Li, Murong Yue, Zhiyuan Peng, Yuchen Liu, Ziyu Yao, Dongkuan Xu.* [[abs](https://arxiv.org/abs/2308.04030)], 2023.8

18. **Identifying the Risks of LM Agents with an LM-Emulated Sandbox**

    *Yangjun Ruan, Honghua Dong, Andrew Wang, Silviu Pitis, Yongchao Zhou, Jimmy Ba, Yann Dubois, Chris J. Maddison, Tatsunori Hashimoto.* [[abs](https://arxiv.org/abs/2309.15817)], 2023.9

19. **Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning**

    *Lin Guan, Karthik Valmeekam, Sarath Sreedharan, Subbarao Kambhampati* [[abs](https://arxiv.org/abs/2305.14909)], 2023.5

20. **Data-Copilot: Bridging Billions of Data and Humans with Autonomous Workflow**

    *Wenqi Zhang, Yongliang Shen, Weiming Lu, Yueting Zhuang* [[abs](https://arxiv.org/abs/2306.07209)], 2023.6

21. **CLOVA: A Closed-LOop Visual Assistant with Tool Usage and Update**

    *Zhi Gao, Yuntao Du, Xintong Zhang, Xiaojian Ma, Wenjuan Han, Song-Chun Zhu, Qing Li* [[abs](https://arxiv.org/abs/2312.10908)], 2023.12

23. **GitAgent: Facilitating Autonomous Agent with GitHub by Tool Extension**

    *Bohan Lyu, Xin Cong, Heyang Yu, Pan Yang, Yujia Qin, Yining Ye, Yaxi Lu, Zhong Zhang, Yukun Yan, Yankai Lin, Zhiyuan Liu, Maosong Sun.* [[abs](https://arxiv.org/pdf/2312.17294.pdf)], 2023.12

24. **EASYTOOL: Enhancing LLM-based Agents with Concise Tool Instruction**

    *Siyu Yuan, Kaitao Song, Jiangjie Chen, Xu Tan, Yongliang Shen, Kan Ren, Dongsheng Li, Deqing Yang.* [[abs](https://arxiv.org/abs/2401.06201)], 2024.1
    

### 🤖💬🤖 Multiple Agents

#### Task-Oriented Communication

##### Collaborative Exchanges 👨‍💻👩‍💻

1. **Language Model Cascades**

   *David Dohan, Winnie Xu, Aitor Lewkowycz, Jacob Austin, David Bieber, Raphael Gontijo Lopes, Yuhuai Wu, Henryk Michalewski, Rif A. Saurous, Jascha Sohl-dickstein, Kevin Murphy, Charles Sutton.* [[abs](https://arxiv.org/abs/2207.10342)], 2022.7

2. **Collaborating with language models for embodied reasoning**

   *Ishita Dasgupta, Christine Kaeser-Chen, Kenneth Marino, Arun Ahuja, Sheila Babayan, Felix Hill, Rob Fergus.* [[abs](https://arxiv.org/abs/2302.00763)], 2023.2

3. **CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society**

   *Guohao Li, Hasan Abed Al Kader Hammoud, Hani Itani, Dmitrii Khizbullin, Bernard Ghanem.* [[abs](https://arxiv.org/abs/2303.17760)], 2023.3

4. **Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models**

   *Jimmy Wei, Kurt Shuster, Arthur Szlam, Jason Weston, Jack Urbanek, Mojtaba Komeili.* [[abs](https://arxiv.org/abs/2304.13835)], 2023.4

5. **ChatLLM Network: More brains, More intelligence**

   *Rui Hao, Linmei Hu, Weijian Qi, Qingliu Wu, Yirui Zhang, Liqiang Nie.* [[abs](https://arxiv.org/abs/2304.12998)], 2023.4

6. **Self-collaboration Code Generation via ChatGPT**

   *Yihong Dong, Xue Jiang, Zhi Jin, Ge Li.* [[abs](https://arxiv.org/abs/2304.07590)], 2023.4

7. **Emergent autonomous scientific research capabilities of large language models**

   *Daniil A. Boiko, Robert MacKnight, Gabe Gomes.* [[abs](https://arxiv.org/abs/2304.05332)], 2023.4

8. **ChatGPT/GPT-4 for Knowledge Graph Construction and Reasoning: Recent Capabilities and Future Opportunities**

   *Yuqi Zhu, Xiaohan Wang, Jing Chen, Shuofei Qiao, Yixin Ou, Yunzhi Yao, Shumin Deng, Huajun Chen, Ningyu Zhang.* [[abs](https://arxiv.org/abs/2305.13168)], 2023.5

9. **Large Language Models as Tool Makers**

   *Tianle Cai, Xuezhi Wang, Tengyu Ma, Xinyun Chen, Denny Zhou*. [[abs](https://arxiv.org/abs/2305.17126)], 2023.5

10. **Inferring the Goals of Communicating Agents from Actions and Instructions**

    *Lance Ying, Tan Zhi-Xuan, Vikash Mansinghka, Joshua B. Tenenbaum.* [[abs](https://arxiv.org/abs/2306.16207)], 2023.6

11. **Wireless Multi-Agent Generative AI: From Connected Intelligence to Collective Intelligence**

    *Hang Zou, Qiyang Zhao, Lina Bariah, Mehdi Bennis, Merouane Debbah.* [[abs](https://arxiv.org/abs/2307.02757)], 2023.7

12. **RoCo: Dialectic Multi-Robot Collaboration with Large Language Models**

    *Zhao Mandi, Shreeya Jain, Shuran Song.* [[abs](https://arxiv.org/abs/2307.04738)], 2023.7

13. **Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration**

    *Zhenhailong Wang, Shaoguang Mao, Wenshan Wu, Tao Ge, Furu Wei, Heng Ji.* [[abs](https://arxiv.org/abs/2307.05300)], 2023.7

14. **Communicative Agents for Software Development**

    *Chen Qian, Xin Cong, Cheng Yang, Weize Chen, Yusheng Su, Juyuan Xu, Zhiyuan Liu, Maosong Sun.* [[abs](https://arxiv.org/abs/2307.07924)], 2023.7

15. **To Infinity and Beyond: SHOW-1 and Showrunner Agents in Multi-Agent Simulations**

    *Philipp Maas, Frank Carey, Chris Wheeler, Edward Saatchi, Pete Billington, Jessica Yaffa Shamash.* [[abs](https://fablestudio.github.io/showrunner-agents/static/pdfs/To_Infinity_and_Beyond_SHOW-1_And_Showrunner_Agents_in_Multi_Agent_Simulations.pdf)], 2023.7

16. **MetaGPT: Meta Programming For Multi-Agent Collaborative Framework**

    *Sirui Hong, Xiawu Zheng, Jonathan Chen, Yuheng Cheng, Ceyao Zhang, Zili Wang, Steven Ka Shing Yau, Zijuan Lin, Liyang Zhou, Chenyu Ran, Lingfeng Xiao, Chenglin Wu.* [[abs](https://arxiv.org/abs/2308.00352)], 2023.8

17. **Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback**

    *Yao Fu, Hao Peng, Tushar Khot, Mirella Lapata.* [[abs](https://arxiv.org/abs/2305.10142)], 2023.5

18. **Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents**

    *Yashar Talebirad, Amirhossein Nadiri.* [[abs](https://arxiv.org/abs/2306.03314)], 2023.6

19. **RestGPT: Connecting Large Language Models with Real-World Applications via RESTful APIs**

    *Yifan Song, Weimin Xiong, Dawei Zhu, Cheng Li, Ke Wang, Ye Tian, Sujian Li*. [[abs](https://arxiv.org/abs/2306.06624)], 2023.6

20. **Building Cooperative Embodied Agents Modularly with Large Language Models**

    *Hongxin Zhang, Weihua Du, Jiaming Shan, Qinhong Zhou, Yilun Du, Joshua B. Tenenbaum, Tianmin Shu, Chuang Gan.* [[abs](https://arxiv.org/abs/2307.02485)], 2023.7

21. **InterAct: Exploring the Potentials of ChatGPT as a Cooperative Agent**

    *Po-Lin Chen, Cheng-Shang Chang.* [[abs](https://arxiv.org/abs/2308.01552)], 2023.8

22. **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework**

    *Qingyun Wu, Gagan Bansal, Jieyu Zhang, Yiran Wu, Shaokun Zhang, Erkang Zhu, Beibin Li, Li Jiang, Xiaoyun Zhang, Chi Wang.* [[abs](https://arxiv.org/abs/2308.08155)], 2023.8

23. **Exploring the Intersection of Large Language Models and Agent-Based Modeling via Prompt Engineering**

    *Edward Junprung.* [[abs](https://arxiv.org/abs/2308.07411)], 2023.8

24. **Neural Amortized Inference for Nested Multi-agent Reasoning**

    *Kunal Jha, Tuan Anh Le, Chuanyang Jin, Yen-Ling Kuo, Joshua B. Tenenbaum, Tianmin Shu.* [[abs](https://arxiv.org/abs/2308.11071)], 2023.8

25. **GPT-in-the-Loop: Adaptive Decision-Making for Multiagent Systems**

    *Nathalia Nascimento, Paulo Alencar, Donald Cowan.* [[abs](https://arxiv.org/abs/2308.10435)], 2023.8

26. **ProAgent: Building Proactive Cooperative AI with Large Language Models**

    *Ceyao Zhang, Kaijie Yang, Siyi Hu, Zihao Wang, Guanghe Li, Yihang Sun, Cheng Zhang, Zhaowei Zhang, Anji Liu, Song-Chun Zhu, Xiaojun Chang, Junge Zhang, Feng Yin, Yitao Liang, Yaodong Yang.* [[abs](https://arxiv.org/abs/2308.11339)], 2023.8

27. **MindAgent: Emergent Gaming Interaction**

    *Ran Gong, Qiuyuan Huang, Xiaojian Ma, Hoi Vo, Zane Durante Yusuke Noda, Zilong Zheng, Song-Chun Zhu Demetri Terzopoulos, Li Fei-Fei, Jianfeng Gao.* [[abs](https://arxiv.org/abs/2309.09971)], 2023.9

28. **Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View**

    *Jintian Zhang, Xin Xu, Shumin Deng.* [[abs](https://arxiv.org/abs/2310.02124)], 2023.10

29. **Lumos: Learning Agents with Unified Data, Modular Design, and Open-Source LLMs**

    *Da Yin, Faeze Brahman, Abhilasha Ravichander, Khyathi Chandu, Kai-Wei Chang, Yejin Choi, Bill Yuchen Lin.* [[abs](https://arxiv.org/pdf/2311.05657.pdf)], 2023.11

30. **AutoAct: Automatic Agent Learning from Scratch via Self-Planning**

    *Shuofei Qiao, Ningyu Zhang, Runnan Fang, Yujie Luo, Wangchunshu Zhou, Yuchen Eleanor Jiang, Chengfei Lv, Huajun Chen.* [[abs](https://arxiv.org/abs/2401.05268)], 2024.01




##### Adversarial Interactions 👨🏻‍🦳🗣

1. **Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate**

   *Tian Liang, Zhiwei He, Wenxiang Jiao, Xing Wang, Yan Wang, Rui Wang, Yujiu Yang, Zhaopeng Tu, Shuming Shi.* [[abs](https://arxiv.org/abs/2305.19118)], 2023.5

2. **Improving Factuality and Reasoning in Language Models through Multiagent Debate**

   *Yilun Du, Shuang Li, Antonio Torralba, Joshua B. Tenenbaum, Igor Mordatch.* [[abs](https://arxiv.org/abs/2305.14325)], 2023.5

3. **Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback**

   *Yao Fu, Hao Peng, Tushar Khot, Mirella Lapata.* [[abs](https://arxiv.org/abs/2305.10142)], 2023.5

4. **ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate**

   *Chi-Min Chan, Weize Chen, Yusheng Su, Jianxuan Yu, Wei Xue, Shanghang Zhang, Jie Fu, Zhiyuan Liu.* [[abs](https://arxiv.org/abs/2308.07201)], 2023.8

5. **How susceptible are LLMs to Logical Fallacies?**

   *Amirreza Payandeh, Dan Pluth, Jordan Hosier, Xuesu Xiao, Vijay K. Gurbani.* [[abs](https://arxiv.org/abs/2308.09853)], 2023.8

6. **Identifying the Risks of LM Agents with an LM-Emulated Sandbox**

   *Yangjun Ruan, Honghua Dong, Andrew Wang, Silviu Pitis, Yongchao Zhou, Jimmy Ba, Yann Dubois, Chris J. Maddison, Tatsunori Hashimoto.* [[abs](https://arxiv.org/abs/2309.15817)], 2023.9

7. **Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View**

   *Jintian Zhang, Xin Xu, Shumin Deng.* [[abs](https://arxiv.org/abs/2310.02124)], 2023.10
   
---

#### Casual/Open Conversations 👥💬

1. **Generative Agents: Interactive Simulacra of Human Behavior**

   *Joon Sung Park, Joseph C. O'Brien, Carrie J. Cai, Meredith Ringel Morris, Percy Liang, Michael S. Bernstein.* [[abs](https://arxiv.org/abs/2304.03442)], 2023.4

2. **Training Socially Aligned Language Models in Simulated Human Society.**

   *Ruibo Liu, Ruixin Yang, Chenyan Jia, Ge Zhang, Denny Zhou, Andrew M. Dai, Diyi Yang, Soroush Vosoughi.* [[abs](https://arxiv.org/abs/2305.16960)], 2023.5

3. **The Role of Summarization in Generative Agents: A Preliminary Perspective**

   *Xiachong Feng, Xiaocheng Feng, Bing Qin.* [[abs](https://arxiv.org/abs/2305.01253)], 2023.5

4. **Epidemic Modeling with Generative Agents.**

   *Ross Williams, Niyousha Hosseinichimeh, Aritra Majumdar, Navid Ghaffarzadegan.* [[abs](https://arxiv.org/abs/2307.04986)], 2023.7

5. **S^3: Social-network Simulation System with Large Language Model-Empowered Agents**

   *Chen Gao, Xiaochong Lan, Zhihong Lu, Jinzhu Mao, Jinghua Piao, Huandong Wang, Depeng Jin, Yong Li.* [[abs](https://arxiv.org/abs/2307.14984)],2023.7

6. **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation**

   *Jiaju Lin, Haoran Zhao, Aochi Zhang, Yiting Wu, Huqiuyue Ping, Qin Chen*. [[abs](https://arxiv.org/abs/2308.04026)], 2023.8

7. **CGMI: Configurable General Multi-Agent Interaction Framework**

   *Shi Jinxin, Zhao Jiabao, Wang Yilei, Wu Xingjiao, Li Jiawen, He Liang.* [[abs](https://arxiv.org/abs/2308.12503)], 2023.8

### 🪐 Application

1. **EduChat: A Large-Scale Language Model-based Chatbot System for Intelligent Education**

   *Yuhao Dan, Zhikai Lei, Yiyang Gu, Yong Li, Jianghao Yin, Jiaju Lin, Linhao Ye, Zhiyan Tie, Yougen Zhou, Yilei Wang, Aimin Zhou, Ze Zhou, Qin Chen, Jie Zhou, Liang He, Xipeng Qiu.* [[abs](https://arxiv.org/abs/2308.02773)], 2023.8

2. **SuperAgent: A Customer Service Chatbot for E-commerce Websites**

   *Lei Cui, Shaohan Huang, Furu Wei, Chuanqi Tan, Chaoqun Duan, Ming Zhou.* [[paper](https://aclanthology.org/P17-4017/)], 2017

3. **WebArena: A Realistic Web Environment for Building Autonomous Agents**

    *Shuyan Zhou, Frank F. Xu, Hao Zhu, Xuhui Zhou, Robert Lo, Abishek Sridhar, Xianyi Cheng, Yonatan Bisk, Daniel Fried, Uri Alon, Graham Neubig.* [[abs](https://arxiv.org/abs/2307.13854)], 2023.7

4. **LLM As DBA**

    *Xuanhe Zhou, Guoliang Li, Zhiyuan Liu.* [[abs](https://arxiv.org/abs/2308.05481)], 2023.8

5. **RoboAgent: Generalization and Efficiency in Robot Manipulation via Semantic Augmentations and Action Chunking**

   *Homanga Bharadhwaj, Jay Vakil, Mohit Sharma, Abhinav Gupta, Shubham Tulsiani, Vikash Kumar.* [[paper](https://robopen.github.io/media/roboagent.pdf)], 2023

6.  **Is There Any Social Principle for LLM-Based Agents?**

    *Jitao Bai, Simiao Zhang, Zhonghao Chen.* [[abs](https://arxiv.org/abs/2308.11136)], 2023.8

7. **ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving**

    *Zhibin Gou, Zhihong Shao, Yeyun Gong, Yelong Shen, Yujiu Yang, Minlie Huang, Nan Duan, Weizhu Chen.* [[abs](https://arxiv.org/abs/2309.17452)] [[code](https://github.com/microsoft/ToRA)], 2023.9


### 🖼️ Framework

1. **Agents: An Open-source Framework for Autonomous Language Agents**

   *Wangchunshu Zhou, Yuchen Eleanor Jiang, Long Li, Jialong Wu, Tiannan Wang, Shi Qiu, Jintian Zhang, Jing Chen, Ruipu Wu, Shuai Wang, Shiding Zhu, Jiyu Chen, Wentao Zhang, Ningyu Zhang, Huajun Chen, Peng Cui, Mrinmaya Sachan.* [[abs](https://arxiv.org/abs/2309.07870)], 2023.9

2. **Dynamic LLM-Agent Network: An LLM-agent Collaboration Framework with Agent Team Optimization**

   *Zijun Liu, Yanzhe Zhang, Peng Li, Yang Liu, Diyi Yang.* [[abs](https://arxiv.org/abs/2310.02170)], 2023.10

3. **OpenAgents: An Open Platform for Language Agents in the Wild**

   *Tianbao Xie, Fan Zhou, Zhoujun Cheng, Peng Shi, Luoxuan Weng, Yitao Liu, Toh Jing Hua, Junning Zhao, Qian Liu, Che Liu, Leo Z. Liu, Yiheng Xu, Hongjin Su, Dongchan Shin, Caiming Xiong, Tao Yu.* [[abs](https://arxiv.org/abs/2310.10634)], 2023.10

4. **AutoAct: Automatic Agent Learning from Scratch via Self-Planning**

   *Shuofei Qiao, Ningyu Zhang, Runnan Fang, Yujie Luo, Wangchunshu Zhou, Yuchen Eleanor Jiang, Chengfei Lv, Huajun Chen.* [[abs](https://arxiv.org/abs/2401.05268)], 2024.01

5. **An Interactive Agent Foundation Model**

   *Zane Durante, Bidipta Sarkar, Ran Gong, Rohan Taori, Yusuke Noda, Paul Tang, Ehsan Adeli, Shrinidhi Kowshika Lakshmikanth, Kevin Schulman, Arnold Milstein, Demetri Terzopoulos, Ade Famoti, Noboru Kuno, Ashley Llorens, Hoi Vo, Katsu Ikeuchi, Li Fei-Fei, Jianfeng Gao, Naoki Wake, Qiuyuan Huang* [[abs](https://arxiv.org/abs/2402.05929)], 2024.02



### 🔖 Others

1. **Enhancing Trust in LLM-Based AI Automation Agents: New Considerations and Future Challenges**

   *Sivan Schwartz, Avi Yaeli, Segev Shlomov.* [[abs](https://arxiv.org/abs/2308.05391)], 2023.8
   
---

## 🧰 Resources

### Benchmarks

1. **Mind2Web: Towards a Generalist Agent for the Web**

   *Xiang Deng, Yu Gu, Boyuan Zheng, Shijie Chen, Samuel Stevens, Boshi Wang, Huan Sun, Yu Su.* [[abs](https://arxiv.org/abs/2306.06070)], 2023.6

3. **The Tong Test: Evaluating Artificial General Intelligence Through Dynamic Embodied Physical and Social Interactions**
   
    *Yujia Peng , Jiaheng Han, Zhenliang Zhang , Lifeng Fan , Tengyu Liu, Siyuan Qi, Xue Feng, Yuxi Ma, Yizhou Wang, Song-Chun Zhu.* [[abs](https://www.sciencedirect.com/science/article/pii/S209580992300293X)], 2023.7
   
4. **AgentBench: Evaluating LLMs as Agents**

   *Xiao Liu, Hao Yu, Hanchen Zhang, Yifan Xu, Xuanyu Lei, Hanyu Lai, Yu Gu, Hangliang Ding, Kaiwen Men, Kejuan Yang, Shudan Zhang, Xiang Deng, Aohan Zeng, Zhengxiao Du, Chenhui Zhang, Sheng Shen, Tianjun Zhang, Yu Su, Huan Sun, Minlie Huang, Yuxiao Dong, Jie Tang*. [[abs](https://arxiv.org/abs/2308.03688)], 2023.8

5. **BOLAA: Benchmarking and Orchestrating LLM-augmented Autonomous Agents.**

   *Zhiwei Liu, Weiran Yao, Jianguo Zhang, Le Xue, Shelby Heinecke, Rithesh Murthy, Yihao Feng, Zeyuan Chen, Juan Carlos Niebles, Devansh Arpit, Ran Xu, Phil Mui, Huan Wang, Caiming Xiong, Silvio Savarese.* [[abs](https://arxiv.org/abs/2308.05960)], 2023.8

6. **Identifying the Risks of LM Agents with an LM-Emulated Sandbox**

   *Yangjun Ruan, Honghua Dong, Andrew Wang, Silviu Pitis, Yongchao Zhou, Jimmy Ba, Yann Dubois, Chris J. Maddison, Tatsunori Hashimoto.* [[abs](https://arxiv.org/abs/2309.15817)], 2023.9

7. **T-Eval: Evaluating the Tool Utilization Capability of Large Language Models Step by Step**

   *Zehui Chen, Weihua Du, Wenwei Zhang, Kuikun Liu, Jiangning Liu, Miao Zheng, Jingming Zhuo, Songyang Zhang, Dahua Lin, Kai Chen, Feng Zhao.* [[abs](https://arxiv.org/abs/2312.14033)], 2023.12
   
8. **TravelPlanner: A Benchmark for Real-World Planning with Language Agents**

   *Jian Xie, Kai Zhang, Jiangjie Chen, Tinghui Zhu, Renze Lou, Yuandong Tian, Yanghua Xiao, Yu Su.* [[abs](https://arxiv.org/pdf/2402.01622.pdf)],2024.02

9. **AgentBoard: An Analytical Evaluation Board of Multi-turn LLM Agents**

   *Chang Ma, Junlei Zhang, Zhihao Zhu, Cheng Yang, Yujiu Yang, Yaohui Jin, Zhenzhong Lan, Lingpeng Kong, Junxian He.*  [[abs](https://arxiv.org/abs/2401.13178)],2024.01

10. **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments**
   
    *Tianbao Xie, Danyang Zhang, Jixuan Chen, Xiaochuan Li, Siheng Zhao, Ruisheng Cao, Toh Jing Hua, Zhoujun Cheng, Dongchan Shin, Fangyu Lei, Yitao Liu, Yiheng Xu, Shuyan Zhou, Silvio Savarese, Caiming Xiong, Victor Zhong, Tao Yu.*  [[abs](https://arxiv.org/abs/2404.07972)],2024.04

11. **TimeChara: Evaluating Point-in-Time Character Hallucination of Role-Playing Large Language Models**

    *Jaewoo Ahn, Taehyun Lee, Junyoung Lim, Jin-Hwa Kim, Sangdoo Yun, Hwaran Lee, Gunhee Kim.* [[abs](https://arxiv.org/abs/2405.18027)],2024.05

###  Types of Tools

|      Types      | Tools                                                        |
| :-------------: | ------------------------------------------------------------ |
| Agent with tool | [AutoGPT](https://github.com/Significant-Gravitas/Auto-GPT)、[LangChain](https://github.com/hwchase17/langchain)、[Transformer Agents](https://huggingface.co/docs/transformers/transformers_agents)、[WorkGPT](https://github.com/team-openpm/workgpt)、[AutoChain ](https://github.com/Forethought-Technologies/AutoChain)、[Langroid](https://github.com/langroid/langroid)、 [WebArena](https://github.com/web-arena-x/webarena)、[GPT Researcher](https://github.com/assafelovic/gpt-researcher)、[BMTools](https://github.com/OpenBMB/BMTools)、[ToolBench](https://github.com/OpenBMB/ToolBench) 、[AgentGPT](https://github.com/reworkd/AgentGPT)、[xlang](https://github.com/xlang-ai/xlang) |
|   Multi-Agent   | [CAMEL](https://github.com/camel-ai/camel)、[GPTeam](https://github.com/101dotxyz/GPTeam)、[AgentVerse](https://github.com/OpenBMB/AgentVerse)、[MetaGPT](https://github.com/geekan/MetaGPT)、[Langroid](https://github.com/langroid/langroid)、[SocraticAI](https://github.com/RunzheYang/SocraticAI)、[AutoGen](https://microsoft.github.io/FLAML/docs/Use-Cases/Autogen/)、[Agents](https://github.com/aiwaves-cn/agents) |
|     Others      | [AutoAgents](https://github.com/AutoLLM/AutoAgents)![img](https://img.shields.io/badge/-Reasoning-blue) 、[GPT Engineer](https://github.com/AntonOsika/gpt-engineer)  ![img](https://img.shields.io/badge/-Code-pink) |

### 📜 Tool List

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
  
- **[BMTools](https://github.com/OpenBMB/BMTools).** Tool Learning for Big Models, Open-Source Solutions of ChatGPT-Plugins
  
- **[ToolBench](https://github.com/OpenBMB/ToolBench).** An open platform for training, serving, and evaluating large language model for tool learning.

- **[AgentGPT](https://github.com/reworkd/AgentGPT).** Assemble, configure, and deploy autonomous AI Agents in your browser.

- **[xlang](https://github.com/xlang-ai/xlang).** An open-source framework for building and evaluating language model agents via executable language grounding

- **[Agently](https://github.com/Maplemx/Agently).**  A fast way to build LLM Agent based Application 🤵 A light weight framework helps developers to create amazing LLM based applications. 

- **[Lagent](https://github.com/InternLM/lagent).** A lightweight framework for building LLM-based agents.
  
- **[ToolEmu](https://github.com/ryoungj/ToolEmu)** An LLM-based emulation framework for testing and identifying the risks of LLM-based agents

---

## 🎉 Contribution

### Contributing to this paper list

⭐" **Join us in improving this repository!** If you know of any important works we've missed, please contribute. Your efforts are highly valued!   "

### Contributors

<a href="https://github.com/zjunlp/LLMAgentPapers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zjunlp/LLMAgentPapers" />
</a>
