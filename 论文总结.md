##### ==7.4==

##### 1.设计一个新机制，优化推荐系统

###### expand the coverage

- CERAM: Coverage Expansion for Recommendations by Associating Discarded Models

  利用被遗弃的模型，来扩大其他模型的推广覆盖度，并应用到实际中。76.9倍

###### improve the accuracy

- Task-optimized User Clustering based on Mobile App Usage for Cold-start Recommendations

  基于mobile app，提高对cold-start用户的文章推荐的精确度。用user clustering来代替高维嵌入，解决算力要求高、难以应用到online的问题；关注用户不同行为（app使用和文章阅读偏好）之间的关联；消除active users和cold-start用户在app使用模式之间的差别，优化cold-start用户的推荐系统

- Feature-aware Diversified Re-ranking with Disentangled Representations for Relevant Recommendation

  基于revelant recommendation，多样化推荐系统以防止信息茧房，平衡相关推荐和多样推荐。设计了一个通用的重排框架，以捕获相关推荐中的特征感知多样性

- AdaFS: Adaptive Feature Selection in Deep Recommender System

  解决传统的推荐系统在选择feature时只选择固定的子集，无法适应多元的、变化的推荐需要的问题，建立了一个自动选择最相关的feature并对用户和项目之间的交互进行打分的控制器网络

- Automatically Discovering User Consumption Intents in Meituan

  自动挖掘隐含的消费意向。建立三组对偶超图来获取相关关系，并基于此神经网络来提取解耦的意图特征

- Affective Signals in a Social Media Recommender System

  通过学习用户对post的情感，判断用户的喜好，来优化推广系统

###### performence

- Persia: An Open, Hybrid System Scaling Deep Learning-based Recommenders up to 100 Trillion Parameters

  建立了一个100万亿个参数规模的推荐系统

##### 2.评估某个factor的效果

- Modeling Persuasion Factor of User Decision for Recommendation

  对于页面中的“persuasion text”，进行显式建模explicit modling，评估其对于消费者决策的影响。建立了说服因素图卷积层，进行图表征学习；基于反事实学习的数据增强方法来增强监督信号，解决了小样本学习问题

- Personalized Chit-Chat Generation for Recommendation Using External Chat Corpora

  个性化的“闲聊”，来优化新闻推荐。评估带有chit-chat post的新闻标题是否能提高阅读推荐新闻的兴趣

