
## Personality	
- 一组精神特质（类型）
    - 解释和预测思想，感觉和方式的模式 行为
    - 随着时间和环境保持相对稳定
- 人与人之间的差异来源
    - 影响关系，工作，学习等的成功概率
    - 解释35％的生活满意度差异
- 比较：收入（4％），就业（4％），婚姻状况（1％到4％）
- 检测与欺骗行为相互作用，意见，情感等

## Application

- 人格检测
- 精准广告
- 自适应接口和机器人行为
    - 音乐，风格，色调，色彩等
- 心理诊断，法医学
    - 精神病患者，大规模杀人犯，欺凌者，受害者
    - 抑郁，自杀倾向
- 人力资源管理
- 文学科学研究，社会心理学，社会语言学等
- 明确的学习对话中的固有属性是提高对话多样性和连贯性的一种方法，在不同的属性中，主题和个性被广泛的探索。 

## Dataset

- Question-Answer Datasets

    - The WikiQA corpus: A publicly available set of question and sentence pairs, collected and annotated for research on open-domain question answering. In order to reflect the true information need of general users, we used Bing query logs as the question source. Each question is linked to a Wikipedia page that potentially has the answer.

    - Yahoo Language Data: This page features manually curated QA datasets from Yahoo Answers from Yahoo.

    - TREC QA Collection: TREC has had a question answering track since 1999. In each track, the task was defined such that the systems were to retrieve small snippets of text that contained an answer for open-domain, closed-class questions.

- Customer Support Datasets

    - Ubuntu Dialogue Corpus: Consists of almost one million two-person conversations extracted from the Ubuntu chat logs, used to receive technical support for various Ubuntu-related problems. The full dataset contains 930,000 dialogues and over 100,000,000 words

    - Relational Strategies in Customer Service Dataset: A collection of travel-related customer service data from four sources. The conversation logs of three commercial customer service IVAs and the Airline forums on TripAdvisor.com during August 2016.

    - Customer Support on Twitter: This dataset on Kaggle includes over 3 million tweets and replies from the biggest brands on Twitter.

- Dialogue Datasets

    - Semantic Web Interest Group IRC Chat Logs: This automatically generated IRC chat log  is available in RDF, back to 2004, on a daily basis, including time stamps and nicknames.

    - Cornell movie-dialogs corpus: This corpus contains a large metadata-rich collection of fictional conversations extracted from raw movie scripts.

        - 220,579 conversational exchanges between 10,292 pairs of movie characters.
        - Involves 9,035 characters from 617 movies.
        - In total 304,713 utterances.
        - Link: http://www.cs.cornell.edu/~cristian/Cornell_MovieDialogs_Corpus.html.

    - ConvAI2 Dataset: The dataset contains more than 2000 dialogues for PersonaChat task where human evaluators recruited via the crowd sourcing platform Yandex. Toloka chatted with bots submitted by teams.

    - Santa Barbara Corpus of Spoken American English: This dataset includes approximately 249,000 words of transcription, audio, and timestamps at the level of individual intonation units.

    - The NPS Chat Corpus: This corpus consists of 10,567 posts out of approximately 500,000 posts gathered from various online chat services in accordance with their terms of service.

    - Maluuba goal-oriented dialogue: Open dialogue dataset where the conversation aims at accomplishing a task or taking a decision – specifically, finding flights and a hotel. The dataset contains complex conversations and decision-making covering 250+ hotels, flights, and destinations.

- Multilingual Chatbot Datasets

    - NUS Corpus: This corpus was created for social media text normalization and translation. It is built by randomly selecting 2,000 messages from the NUS English SMS corpus and then translated into formal Chinese.

    - EXCITEMENT data sets: These datasets, available in English and Italian, contain negative feedbacks from customers where they state reasons for dissatisfaction with a given company.

## Word Embedding

- Glove: Global vectors for word representation

## Personality Generation in Text

1. An Embodied Dialogue System with Personality and Emotions
> 一种具有个性和情绪的嵌入式对话系统 </br>
> **价值不大** </br>
> Date: 2010 

2. Varying Personality in Spoken Dialogue with a Virtual Human
> 与虚拟人口语对话中的人格变化 </br>
> **价值不大** </br>
> Date: 2009 

3. PERSONAGE: Personality Generation for Dialogue
> PERSONAGE: 对话个性生成器 </br>
> 使用决策树识别句子当中的性格:内向还是外向 </br>
> Date: 2007

4. Using Linguistic Cues for the Automatic Recognition of Personality in Conversation and Text
> 采用语言线索实现对会话及文本中个性的自动识别 </br>
> 使用句子中的词语和决策树技术对作者的性格进行识别:内向还是外向 </br>
> Date: 2007

5. Personality Modeling in Dialogue Systems 
> 对话系统中个性建模 </br>
> 使用句子中的词语和决策树技术对作者的性格进行识别:内向还是外向 </br>
> Date: 2008

6. A Persona-Based Neural Conversation Model
> 基于角色的神经会话模型 </br>
> Seq2Seq模型 使用LSTM对单个角色的对话进行学习 </br>
> Date: 2016

7. Assigning Personality/Identity to a Chatting Machine for Coherent Conversation Generation
> 为聊天机器分配个性/身份以进行连续对话生成 </br>
> Gave the system an identity with profile so that the system can answer personalized question consistently. </br>
> 为机器人分配固有属性，从问答数据、微博数据等中学习根据被分配的固有属性进行回答。 </br>
> 缺点：需要处理和标记的数据太多，并且只针对属性相关的问答进行优化。 </br>
> Date: 2017

8. A Neural Chatbot with Personality
> 具有个性的神经聊天机器人 </br>
> 通过对不同角色的对话进行单独建模，学习该角色的个性信息，从而产生具有个性的机器人。 </br>
> 有源代码 </br>
> Date: 2017

9. Personalizing Dialogue Agents: I have a dog, do you have pets too?
> 个性化对话代理：我有一只狗，你也养宠物吗？</br>
> 将给定的个人简介信息作为条件，利用正在交谈的人的信息来预测下一句对话。</br>
> 已知对方的角色对结果影响不大。因为人们趋向于谈自己感兴趣的事情。</br>
- 采用信息检索模型，监督嵌入模型构建基线模型
- 添加个人简介信息的排序记忆网络模型
- Key-Value个人简介记忆网络
- Seq2Seq
- 生成个人简介记忆网络
> Date: 2018

10. A Persona-Based Neural Conversation Model
> 基于人物角色的神经网络对话模型 </br>
> Based on LSTM and individual's tweets </br>
> Date: 2016

11. Personality for Your Chatbot with Recurrent Neural Networks
> https://towardsdatascience.com/personality-for-your-chatbot-with-recurrent-neural-networks-2038f7f34636 </br>
> Date: 2017

12. Topic Aware Neural Response Generation
> 在生成对话中加入主题信息 </br>
> 人类的聊天过程中常常围绕在一个显性或者隐性的主题下的概念中，并且回答的内容也根据概念而生成。 </br>
> 该论文使用推特数据结合LDA算法建立对话主题识别模型，将句子的主题信息和输入相结合生成主题相关的回答。 </br>
> Date: 2016

13. Domain Aware Neural Dialog System
> 在生成对话中加入领域信息 </br>
> 将对话中的每一次发言中的主题信息进行识别，并生成回复的主题信息和详细内容</br>
> Date: 2017

14. Multiresolution Recurrent Neural Networks: An Application to Dialogue Response Generation
> 该论文对高级浅层标记序列和对话生成进行联合建模，其中标记序列旨在挖掘高级语义信息。为了进行粗浅序列表示，他们从对话中发现名词和活动实体。</br>
> Date: 2016

15. Emotional chatting machine: Emotional conversation generation with internal and external memory
> 将情感信息嵌入到对话生成模型中，在困惑度中表现良好. </br>
> Date: 2017

16. Affective Neural Response Generation
> 从三个方面增强了产生具有情绪反应的对话模型：1.结合认知工程的情感词嵌入，2.使用受影响的目标函数增强损失对象，3.在不同的波束搜索推理过程中注入情感差异。 </br>
> Date: 2017

17. Diverse Beam Search: Decoding Diverse Solutions from Neural Sequence Models </br>
> Beam Search: 第一步选择候选词的TopN，此后每次将候选词与此表进行组合，选择候选组合的TopN作为结果
> Diverse Beam Search: 分多组做Beam Search, 并且保持组间的多样性 </br>
> Date: 2016


18. Neural Personalized Response Generation as Domain Adaptation
> 进一步考虑了对话接收者的信息，以创建一个更现实的聊天机器人。 由于训练数据来自不同的发言者，能够稳定的产生不同的聊天风格. </br>
> Date: 2017

19. Personalizing a Dialogue System with Transfer Reinforcement Learning
> 使用转移强化学习来增强对话连贯性 </br>
> Date: 2016

## Personality Detection in Text

1. 25 Tweets to Know You: A New Model to Predict Personality with Social Media
> 25条微博就能了解你: 一种在社交媒体中预测用户个性的全新模型 </br>
> 使用词嵌入和高斯回归的方法对推文作者的性格进行预测 </br>
> Date: 2017

2. Exploring personality prediction from text on social media: A literature review
> 于社交媒体文本中探索用户的个性的预测方法: 一个文献综述 </br>
> 简单的论文数量，使用数据类型，调查用户数量进行了统计 </br>
> Date: 2017

3. PROFILING A SET OF PERSONALITY TRAITS OF TEXT AUTHOR: WHAT OUR WORDS REVEAL ABOUT US
> 剖析文本作者的个性特征: 词汇的使用是揭露我们个性的 </br>
> 根据具有不同词性的词语的使用频率、词汇多样性等信息，对用户的自毁行为倾向进行预测 </br>
> Date: 2016

4. Personality Detection by Analysis of Twitter Profiles
> 通过分析Twitter个人信息进行个性检测 </br>
> Date: 2017

## Chatbot / NLP

1. Visualizing and Understanding Neural Models in NLP
> 可视化和理解自然语言处理中的神经网络模型 </br>
> Date: 2015

2. A New Chatbot for Customer Service on Social Media
> 一种基于LSTM的社交媒体客户服务聊天机器人 </br>
> Date: 2017

3. Intelligent Chatbot using Deep Learning
> A Master Thesis, A Chatbot based on LSTM </br>
> Date: 2017

## Dialogue Systems

1. A Survey on Dialogue Systems: Recent Advances and New Frontiers
> 对话系统调查：近期进展与前沿 </br>
> Date: 2017

2. Deep Reinforcement Learning for Dialogue Generation
> 使用深度强化学习生成对话 </br>
> Date: 2016

3. Adversarial Learning for Neural Dialogue Generation
> 使用对抗网络生成对话 </br>
> Date: 2017

4. Dialogue Learning With Human-In-The-Loop
> 基于人类循环的对话学习 </br>
> Date: 2016

## Chatbot Evaluation

1. Automatic Evaluation of Neural Personality-based Chatbots
> 基于人格的神经网络聊天机器人的自动评估 </br>
> Date: 2018

2. Why people use chatbots?
> 为什么人们要使用聊天机器人? </br>
> 该文章能够作为聊天机器人的设计指南 </br>
> 部分原因：Productivity, Entertainment, Social/relational, Novelty/Curiosity. </br>
> Date: 2017

### Evaluation Method

- Turing Test

- Perplexity
>困惑度（perplexity）的基本思想是：给测试集的句子赋予较高概率值的语言模型较好,当语言模型训练完之后，测试集中的句子都是正常的句子，那么训练好的模型就是在测试集上的概率越高越好，公式如下：

![123](https://latex.codecogs.com/png.latex?P(W)=P(w_{1}w_{2}...w_{N})^{-\frac{1}{N}}=\sqrt[N]{\frac{1}{P(w_{1}w_{2}...w_{N})}})

由公式可知，句子概率越大，语言模型越好，迷惑度越小。

- BLEU
> BLEU 是一种对模型输出和参考答案的 n-gram 进行比较并计算匹配片段个数的方法. 这些匹配片段与它们在上下文 (Context) 中存在的位置无关, 这里仅认为匹配片段数越多, 模型输出的质量越好. BLEU 首先会对语料库中所有语料进行 n-gram 的精度 (Precision) 计算 (这里假设对于每一条文本, 都有且只有一条候选回复):

![123](https://latex.codecogs.com/png.latex?P_{n}(r,\hat{r})=\frac{\sum_{k} min(h(k,r), h(k,r_{i}))}{\sum_{k}h(k,r_{i})})
- METEOR
- ROUGE

## Proposals

- Visualization and Understanding Personality in Dialogue

- Chatting under User's Personality: A Intelligent Neural Chatbot 

- A Survey on Personalizing Dialogue Agents