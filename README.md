 # A Survey of Surveys (NLP & ML)

In this document, we survey hundreds of survey papers on Natural Language  Processing (NLP) and Machine Learning (ML). We categorize these papers into popular topics and do simple counting for some interesting problems. In addition, we show the list of the papers with urls (813 papers). 

## Categorization

We follow the ACL and ICML submission guideline of recent years, covering a broad range of areas in NLP and ML. The categorization is as follows:
+ Natural Language Processing
    + <a href="#computational-social-science-and-social-media">Computational Social Science and Social Media</a>
    + <a href="#dialogue-and-interactive-systems">Dialogue and Interactive Systems</a>
    + <a href="#generation">Generation</a>
    + <a href="#information-extraction">Information Extraction</a>
    + <a href="#information-retrieval-and-text-mining">Information Retrieval and Text Mining</a>
    + <a href="#interpretability-and-analysis-of-models-for-nLP">Interpretability and Analysis of Models for NLP</a>
    + <a href="#knowledge-graph">Knowledge Graph</a>
    + <a href="#language-grounding-to-vision-robotics-and-beyond">Language Grounding to Vision, Robotics and Beyond</a>
    + <a href="#linguistic-theories-cognitive-modeling-and-psycholinguistics">Linguistic Theories, Cognitive Modeling and Psycholinguistics</a>
    + <a href="#machine-learning-for-nlp">Machine Learning for NLP</a>
    + <a href="#machine-translation">Machine Translation</a>
    + <a href="#named-entity-recognition">Named Entity Recognition</a>
    + <a href="#natural-language-inference">Natural Language Inference</a>
    + <a href="#natural-language-processing">Natural Language Processing</a>
    + <a href="#nlp-applications">NLP Applications</a>
    + <a href="#pre-training">Pre-training</a>
    + <a href="#question-answering">Question Answering</a>
    + <a href="#reading-comprehension">Reading Comprehension</a>
    + <a href="#recommender-systems">Recommender Systems</a>
    + <a href="#resources-and-evaluation">Resources and Evaluation</a>
    + <a href="#semantics">Semantics</a>
    + <a href="#sentiment-analysis-stylistic-analysis-and-argument-mining">Sentiment Analysis, Stylistic Analysis and Argument Mining</a>
    + <a href="#speech-and-multimodality">Speech and Multimodality</a>
    + <a href="#summarization">Summarization</a>
    + <a href="#tagging-chunking-syntax-and-parsing">Tagging, Chunking, Syntax and Parsing</a>
    + <a href="#text-classification">Text Classification</a>
+ Machine Learning
    + <a href="#architectures">Architectures</a>
    + <a href="#automl">AutoML</a>
    + <a href="#bayesian-methods">Bayesian Methods</a>
    + <a href="#classification-clustering-and-regression">Classification, Clustering and Regression</a>
    + <a href="#computer-vision">Computer Vision</a>
    + <a href="#contrastive-learning">Contrastive Learning</a>
    + <a href="#curriculum-learning">Curriculum Learning</a>
    + <a href="#data-augmentation">Data Augmentation</a>
    + <a href="#deep-learning-general-methods">Deep Learning General Methods</a>
    + <a href="#deep-reinforcement-learning">Deep Reinforcement Learning</a>
    + <a href="#federated-learning">Federated Learning</a>
    + <a href="#few-shot-and-zero-shot-learning">Few-Shot and Zero-Shot Learning</a>
    + <a href="#general-machine-learning">General Machine Learning</a>
    + <a href="#generative-adversarial-networks">Generative Adversarial Networks</a>
    + <a href="#graph-neural-networks">Graph Neural Networks</a>
    + <a href="#interpretability-and-analysis">Interpretability and Analysis</a>
    + <a href="#knowledge-distillation">Knowledge Distillation</a>
    + <a href="#meta-learning">Meta Learning</a>
    + <a href="#metric-learning">Metric Learning</a>
    + <a href="#ml-and-dl-applications">ML and DL Applications</a>
    + <a href="#model-compression-and-acceleration">Model Compression and Acceleration</a>
    + <a href="#multi-label-learning">Multi-Label Learning</a>
    + <a href="#multi-task-and-multi-view-learning">Multi-Task and Multi-View Learning</a>
    + <a href="#online-learning">Online Learning</a>
    + <a href="#optimization">Optimization</a>
    + <a href="#semi-supervised-weakly-supervised-and-unsupervised-learning">Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning</a>
    + <a href="#transfer-learning">Transfer Learning</a>
    + <a href="#trustworthy-machine-learning">Trustworthy Machine Learning</a>


To reduce class imbalance, we separate some of the hot sub-topics from the original categorization of ACL and ICML submissions. E.g., Named Entity Recognition is a first-level area in our categorization because it is the focus of several surveys.

## Statistics

We show the number of paper in each area in Figures 1-2.

<p align="center"><img src="https://i.loli.net/2020/12/13/uN2IiLQVXMZ9vm3.png"  width="70%" height="70%" /></p>

<p align="center">Figure 1: # of papers in each NLP area.</p>

<p align="center"><img src="https://i.loli.net/2020/12/13/AdhCzxSsQFZ6pNO.png" width="70%" height="70%" /></p>

<p align="center">Figure 2:  # of papers in each ML area..</p>

Also, we plot paper number as a function of publication year (see Figure 3).

<p align="center"><img src="https://i.loli.net/2020/12/13/FlDJGP2pbLKy8xn.png" width="70%" height="70%"/></p>

<p align="center">Figure 3: # of papers vs publication year.</p>

In addition, we generate word clouds to show hot topics in these surveys (see Figures 4-5).

<p align="center"><img src="https://i.loli.net/2020/07/15/Iywg9lxEGYRvpHO.png" width="70%" height="70%" /></p>

<p align="center">Figure 4: The word cloud for NLP.</p>

<p align="center"><img src="https://i.loli.net/2020/07/15/VYgHR6dhQc2J7Wx.png" width="70%" height="70%" /></p>

<p align="center">Figure 5: The word cloud for ML.</p>


## The NLP Paper List

#### [Computational Social Science and Social Media](#content)

1. **A Comprehensive Survey on Community Detection with Deep Learning.** arXiv 2021 [paper](https://arxiv.org/pdf/2105.12584.pdf) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Su2021A.md)

    *Xing Su, Shan Xue, Fanzhen Liu, Jia Wu, Jian Yang, Chuan Zhou, Wenbin Hu, Cécile Paris, Surya Nepal, Di Jin, Quan Z. Sheng, Philip S. Yu*

2. **A Survey of Fake News: Fundamental Theories, Detection Methods, and Opportunities.** ACM Comput. Surv. 2020 [paper](https://arxiv.org/abs/1812.00315) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Zhou2020A.md)

    *Xinyi Zhou, Reza Zafarani*

3. **A Survey of Race, Racism, and Anti-Racism in NLP.** ACL 2021 [paper](https://arxiv.org/abs/2106.11410) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Field2021A.md)

    *Anjalie Field, Su Lin Blodgett, Zeerak Waseem, Yulia Tsvetkov*

4. **A Survey on Computational Propaganda Detection.** IJCAI 2020 [paper](https://arxiv.org/pdf/2007.08024.pdf) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Martino2020A.md)

    *Giovanni Da San Martino, Stefano Cresci, Alberto Barrón-Cedeño, Seunghak Yu, Roberto Di Pietro, Preslav Nakov*

5. **Computational Sociolinguistics: A Survey.** Comput. Linguistics 2016 [paper](https://arxiv.org/abs/1508.07544) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Nguyen2016Computational.md)

    *Dong Nguyen, A. Seza Dogruöz, Carolyn Penstein Rosé, Franciska de Jong*

6. **Confronting Abusive Language Online: A Survey from the Ethical and Human Rights Perspective.** J. Artif. Intell. Res. 2021 [paper](https://arxiv.org/abs/2012.12305) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Kiritchenko2021Confronting.md)

    *Svetlana Kiritchenko, Isar Nejadgholi, Kathleen C. Fraser*

7. **From Symbols to Embeddings: A Tale of Two Representations in Computational Social Science.** J. Soc. Comput. 2021 [paper](https://arxiv.org/pdf/2106.14198) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Chen2021From.md)

    *Huimin Chen, Cheng Yang, Xuanming Zhang, Zhiyuan Liu, Maosong Sun, Jianbin Jin*

8. **Language (Technology) is Power: A Critical Survey of "Bias" in NLP.** ACL 2020 [paper](https://arxiv.org/abs/2005.14050) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Blodgett2020Language.md)

    *Su Lin Blodgett, Solon Barocas, Hal Daumé III, Hanna M. Wallach*

9. **Societal Biases in Language Generation: Progress and Challenges.** ACL 2021 [paper](https://arxiv.org/pdf/2105.04054.pdf) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Sheng2021Societal.md)

    *Emily Sheng, Kai-Wei Chang, Prem Natarajan, Nanyun Peng*

10. **Tackling Online Abuse: A Survey of Automated Abuse Detection Methods.** arXiv 2019 [paper](https://arxiv.org/pdf/1908.06024.pdf) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Mishra2019Tackling.md)

    *Pushkar Mishra, Helen Yannakoudakis, Ekaterina Shutova*

11. **When do Word Embeddings Accurately Reflect Surveys on our Beliefs About People?.** ACL 2020 [paper](https://arxiv.org/abs/2004.12043) [bib](/bib/Natural-Language-Processing/Computational-Social-Science-and-Social-Media/Joseph2020When.md)

    *Kenneth Joseph, Jonathan H. Morgan*

#### [Dialogue and Interactive Systems](#content)

1. **A Survey of Arabic Dialogues Understanding for Spontaneous Dialogues and Instant Message.** IJNLC 2015 [paper](https://arxiv.org/abs/1505.03084) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Elmadany2015A.md)

    *AbdelRahim A. Elmadany, Sherif M. Abdou, Mervat Gheith*

2. **A Survey of Available Corpora For Building Data-Driven Dialogue Systems: The Journal Version.** Dialogue Discourse 2018 [paper](https://journals.uic.edu/ojs/index.php/dad/article/view/10733/9501) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Serban2018A.md)

    *Iulian Vlad Serban, Ryan Lowe, Peter Henderson, Laurent Charlin, Joelle Pineau*

3. **A Survey of Document Grounded Dialogue Systems (DGDS).** arXiv 2020 [paper](https://arxiv.org/abs/2004.13818) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Ma2020A.md)

    *Longxuan Ma, Wei-Nan Zhang, Mingda Li, Ting Liu*

4. **A Survey of Natural Language Generation Techniques with a Focus on Dialogue Systems - Past, Present and Future Directions.** arXiv 2019 [paper](https://arxiv.org/abs/1906.00500) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Santhanam2019A.md)

    *Sashank Santhanam, Samira Shaikh*

5. **A Survey on Dialog Management: Recent Advances and Challenges.** arXiv 2020 [paper](https://arxiv.org/abs/2005.02233) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Dai2020A.md)

    *Yinpei Dai, Huihua Yu, Yixuan Jiang, Chengguang Tang, Yongbin Li, Jian Sun*

6. **A Survey on Dialogue Systems: Recent Advances and New Frontiers.** SIGKDD Explor. 2017 [paper](https://arxiv.org/abs/1711.01731) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Chen2017A.md)

    *Hongshen Chen, Xiaorui Liu, Dawei Yin, Jiliang Tang*

7. **Advances in Multi-turn Dialogue Comprehension: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2103.03125) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Zhang2021Advances.md)

    *Zhuosheng Zhang, Hai Zhao*

8. **Challenges in Building Intelligent Open-domain Dialog Systems.** ACM Trans. Inf. Syst. 2020 [paper](https://arxiv.org/abs/1905.05709) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Huang2020Challenges.md)

    *Minlie Huang, Xiaoyan Zhu, Jianfeng Gao*

9. **Conversational Machine Comprehension: a Literature Review.** COLING 2020 [paper](https://arxiv.org/abs/2006.00671) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Gupta2020Conversational.md)

    *Somil Gupta, Bhanu Pratap Singh Rawat, Hong Yu*

10. **Neural Approaches to Conversational AI.** ACL 2018 [paper](https://arxiv.org/pdf/1809.08267) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Gao2018Neural.md)

    *Jianfeng Gao, Michel Galley, Lihong Li*

11. **Neural Approaches to Conversational AI: Question Answering, Task-oriented Dialogues and Social Chatbots.** Now Foundations and Trends 2019 [paper](https://ieeexplore.ieee.org/document/8649787) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Gao2019Neural.md)

    *Jianfeng Gao, Michel Galley, Lihong Li*

12. **POMDP-Based Statistical Spoken Dialog Systems: A Review.** Proc. IEEE 2013 [paper](https://ieeexplore.ieee.org/document/6407655/) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Young2013POMDP-Based.md)

    *Steve J. Young, Milica Gasic, Blaise Thomson, Jason D. Williams*

13. **Recent Advances and Challenges in Task-oriented Dialog System.** arXiv 2020 [paper](https://arxiv.org/pdf/2003.07490) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Zhang2020Recent.md)

    *Zheng Zhang, Ryuichi Takanobu, Minlie Huang, Xiaoyan Zhu*

14. **Recent Advances in Deep Learning Based Dialogue Systems: A Systematic Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2105.04387.pdf) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Ni2021Recent.md)

    *Jinjie Ni, Tom Young, Vlad Pandelea, Fuzhao Xue, Vinay Adiga, Erik Cambria*

15. **Utterance-level Dialogue Understanding: An Empirical Study.** arXiv 2020 [paper](https://arxiv.org/abs/2009.13902) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Ghosal2020Utterance-level.md)

    *Deepanway Ghosal, Navonil Majumder, Rada Mihalcea, Soujanya Poria*

16. **How to Evaluate Your Dialogue Models: A Review of Approaches.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.01369.pdf) [bib](/bib/Natural-Language-Processing/Dialogue-and-Interactive-Systems/Li2021How.md)

    *Xinmeng Li, Wansen Wu, Long Qin, Quanjun Yin*

#### [Generation](#content)

1. **A Survey of Knowledge-Enhanced Text Generation.** arXiv 2020 [paper](https://arxiv.org/pdf/2010.04389.pdf) [bib](/bib/Natural-Language-Processing/Generation/Yu2020A.md)

    *Wenhao Yu, Chenguang Zhu, Zaitang Li, Zhiting Hu, Qingyun Wang, Heng Ji, Meng Jiang*

2. **A Survey on Text Simplification.** arXiv 2020 [paper](https://arxiv.org/abs/2008.08612) [bib](/bib/Natural-Language-Processing/Generation/Sikka2020A.md)

    *Punardeep Sikka, Vijay Mago*

3. **Automatic Detection of Machine Generated Text: A Critical Survey.** COLING 2020 [paper](https://arxiv.org/pdf/2011.01314.pdf) [bib](/bib/Natural-Language-Processing/Generation/Jawahar2020Automatic.md)

    *Ganesh Jawahar, Muhammad Abdul-Mageed, Laks V. S. Lakshmanan*

4. **Automatic Story Generation: Challenges and Attempts.** arXiv 2021 [paper](https://arxiv.org/abs/2102.12634) [bib](/bib/Natural-Language-Processing/Generation/Alabdulkarim2021Automatic.md)

    *Amal Alabdulkarim, Siyan Li, Xiangyu Peng*

5. **Content Selection in Data-to-Text Systems: A Survey.** arXiv 2016 [paper](https://arxiv.org/abs/1610.08375) [bib](/bib/Natural-Language-Processing/Generation/Gkatzia2016Content.md)

    *Dimitra Gkatzia*

6. **Data-Driven Sentence Simplification: Survey and Benchmark.** Comput. Linguistics 2020 [paper](https://www.mitpressjournals.org/doi/pdf/10.1162/COLI_a_00370) [bib](/bib/Natural-Language-Processing/Generation/Alva2020Data-Driven.md)

    *Fernando Alva-Manchego, Carolina Scarton, Lucia Specia*

7. **Deep Learning for Text Style Transfer: A Survey.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.00416.pdf) [bib](/bib/Natural-Language-Processing/Generation/Jin2020Deep.md)

    *Di Jin, Zhijing Jin, Zhiting Hu, Olga Vechtomova, Rada Mihalcea*

8. **Evaluation of Text Generation: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2006.14799) [bib](/bib/Natural-Language-Processing/Generation/Celikyilmaz2020Evaluation.md)

    *Asli Celikyilmaz, Elizabeth Clark, Jianfeng Gao*

9. **Human Evaluation of Creative NLG Systems: An Interdisciplinary Survey on Recent Papers.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.00308.pdf) [bib](/bib/Natural-Language-Processing/Generation/Hämäläinen2021Human.md)

    *Mika Hämäläinen, Khalid Al-Najjar*

10. **Keyphrase Generation: A Multi-Aspect Survey.** FRUCT 2019 [paper](https://arxiv.org/abs/1910.05059) [bib](/bib/Natural-Language-Processing/Generation/Çano2019Keyphrase.md)

    *Erion Çano, Ondrej Bojar*

11. **Neural Language Generation: Formulation, Methods, and Evaluation.** arXiv 2020 [paper](https://arxiv.org/pdf/2007.15780.pdf) [bib](/bib/Natural-Language-Processing/Generation/Garbacea2020Neural.md)

    *Cristina Garbacea, Qiaozhu Mei*

12. **Neural Text Generation: Past, Present and Beyond.** arXiv 2018 [paper](https://arxiv.org/pdf/1803.07133.pdf) [bib](/bib/Natural-Language-Processing/Generation/Lu2018Neural.md)

    *Sidi Lu, Yaoming Zhu, Weinan Zhang, Jun Wang, Yong Yu*

13. **Quiz-Style Question Generation for News Stories.** WWW 2021 [paper](https://arxiv.org/abs/2102.09094) [bib](/bib/Natural-Language-Processing/Generation/Lelkes2021Quiz-Style.md)

    *Ádám D. Lelkes, Vinh Q. Tran, Cong Yu*

14. **Recent Advances in Neural Question Generation.** arXiv 2019 [paper](https://arxiv.org/abs/1905.08949) [bib](/bib/Natural-Language-Processing/Generation/Pan2019Recent.md)

    *Liangming Pan, Wenqiang Lei, Tat-Seng Chua, Min-Yen Kan*

15. **Recent Advances in SQL Query Generation: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2005.07667) [bib](/bib/Natural-Language-Processing/Generation/Kalajdjieski2020Recent.md)

    *Jovan Kalajdjieski, Martina Toshevska, Frosina Stojanovska*

16. **Survey of the State of the Art in Natural Language Generation: Core tasks, applications and evaluation.** J. Artif. Intell. Res. 2018 [paper](https://arxiv.org/abs/1703.09902) [bib](/bib/Natural-Language-Processing/Generation/Gatt2018Survey.md)

    *Albert Gatt, Emiel Krahmer*

#### [Information Extraction](#content)

1. **A Compact Survey on Event Extraction: Approaches and Applications.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.02126.pdf) [bib](/bib/Natural-Language-Processing/Information-Extraction/Li2021A.md)

    *Qian Li, Hao Peng, Jianxin Li, Yiming Hei, Rui Sun, Jiawei Sheng, Shu Guo, Lihong Wang, Philip S. Yu*

2. **A Review on Fact Extraction and Verification.** arXiv 2020 [paper](http://arxiv.org/abs/2010.03001) [bib](/bib/Natural-Language-Processing/Information-Extraction/Bekoulis2020A.md)

    *Giannis Bekoulis, Christina Papagiannopoulou, Nikos Deligiannis*

3. **A Survey of Deep Learning Methods for Relation Extraction.** arXiv 2017 [paper](https://arxiv.org/abs/1705.03645) [bib](/bib/Natural-Language-Processing/Information-Extraction/Kumar2017A.md)

    *Shantanu Kumar*

4. **A Survey of Event Extraction From Text.** IEEE Access 2019 [paper](https://ieeexplore.ieee.org/document/8918013) [bib](/bib/Natural-Language-Processing/Information-Extraction/Xiang2019A.md)

    *Wei Xiang, Bang Wang*

5. **A Survey of event extraction methods from text for decision support systems.** Decis. Support Syst. 2016 [paper](https://www.sciencedirect.com/science/article/abs/pii/S0167923616300173) [bib](/bib/Natural-Language-Processing/Information-Extraction/Hogenboom2016A.md)

    *Frederik Hogenboom, Flavius Frasincar, Uzay Kaymak, Franciska de Jong, Emiel Caron*

6. **A survey of joint intent detection and slot-filling models in natural language understanding.** arXiv 2021 [paper](https://arxiv.org/abs/2101.08091) [bib](/bib/Natural-Language-Processing/Information-Extraction/Weld2021A.md)

    *Henry Weld, Xiaoqi Huang, Siqi Long, Josiah Poon, Soyeon Caren Han*

7. **A Survey of Textual Event Extraction from Social Networks.** LPKM 2017 [paper](http://ceur-ws.org/Vol-1988/LPKM2017_paper_15.pdf) [bib](/bib/Natural-Language-Processing/Information-Extraction/Mejri2017A.md)

    *Mohamed Mejri, Jalel Akaichi*

8. **A Survey on Open Information Extraction.** COLING 2018 [paper](https://arxiv.org/abs/1806.05599) [bib](/bib/Natural-Language-Processing/Information-Extraction/Niklaus2018A.md)

    *Christina Niklaus, Matthias Cetto, André Freitas, Siegfried Handschuh*

9. **A Survey on Temporal Reasoning for Temporal Information Extraction from Text (Extended Abstract).** IJCAI 2020 [paper](https://arxiv.org/abs/2005.06527) [bib](/bib/Natural-Language-Processing/Information-Extraction/Leeuwenberg2020A.md)

    *Artuur Leeuwenberg, Marie-Francine Moens*

10. **An Overview of Event Extraction from Text.** DeRiVE@ISWC 2011 [paper](http://ceur-ws.org/Vol-779/derive2011_submission_1.pdf) [bib](/bib/Natural-Language-Processing/Information-Extraction/Hogenboom2011An.md)

    *Frederik Hogenboom, Flavius Frasincar, Uzay Kaymak, Franciska de Jong*

11. **Automatic Extraction of Causal Relations from Natural Language Texts: A Comprehensive Survey.** arXiv 2016 [paper](https://arxiv.org/abs/1605.07895) [bib](/bib/Natural-Language-Processing/Information-Extraction/Asghar2016Automatic.md)

    *Nabiha Asghar*

12. **Complex Relation Extraction: Challenges and Opportunities.** arXiv 2020 [paper](https://arxiv.org/pdf/2012.04821.pdf) [bib](/bib/Natural-Language-Processing/Information-Extraction/Jiang2020Complex.md)

    *Haiyun Jiang, Qiaoben Bao, Qiao Cheng, Deqing Yang, Li Wang, Yanghua Xiao*

13. **Extracting Events and Their Relations from Texts: A Survey on Recent Research Progress and Challenges.** AI Open 2020 [paper](https://www.sciencedirect.com/science/article/pii/S266665102100005X/pdfft?md5=3983861e9ae91ce7b45f0c5533071077&pid=1-s2.0-S266665102100005X-main.pdf) [bib](/bib/Natural-Language-Processing/Information-Extraction/Liu2020Extracting.md)

    *Kang Liu, Yubo Chen, Jian Liu, Xinyu Zuo, Jun Zhao*

14. **More Data, More Relations, More Context and More Openness: A Review and Outlook for Relation Extraction.** AACL 2020 [paper](https://arxiv.org/abs/2004.03186) [bib](/bib/Natural-Language-Processing/Information-Extraction/Han2020More.md)

    *Xu Han, Tianyu Gao, Yankai Lin, Hao Peng, Yaoliang Yang, Chaojun Xiao, Zhiyuan Liu, Peng Li, Jie Zhou, Maosong Sun*

15. **Neural relation extraction: a survey.** arXiv 2020 [paper](https://arxiv.org/abs/2007.04247) [bib](/bib/Natural-Language-Processing/Information-Extraction/Aydar2020Neural.md)

    *Mehmet Aydar, Ozge Bozal, Furkan Özbay*

16. **Recent Neural Methods on Slot Filling and Intent Classification for Task-Oriented Dialogue Systems: A Survey.** COLING 2020 [paper](https://arxiv.org/abs/2011.00564) [bib](/bib/Natural-Language-Processing/Information-Extraction/Louvan2020Recent.md)

    *Samuel Louvan, Bernardo Magnini*

17. **Relation Extraction : A Survey.** arXiv 2017 [paper](https://arxiv.org/abs/1712.05191) [bib](/bib/Natural-Language-Processing/Information-Extraction/Pawar2017Relation.md)

    *Sachin Pawar, Girish K. Palshikar, Pushpak Bhattacharyya*

18. **Techniques for Jointly Extracting Entities and Relations: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2103.06118) [bib](/bib/Natural-Language-Processing/Information-Extraction/Pawar2021Techniques.md)

    *Sachin Pawar, Pushpak Bhattacharyya, Girish K. Palshikar*

#### [Information Retrieval and Text Mining](#content)

1. **A Brief Survey of Text Mining: Classification, Clustering and Extraction Techniques.** arXiv 2017 [paper](https://arxiv.org/abs/1707.02919) [bib](/bib/Natural-Language-Processing/Information-Retrieval-and-Text-Mining/Allahyari2017A.md)

    *Mehdi Allahyari, Seyed Amin Pouriyeh, Mehdi Assefi, Saied Safaei, Elizabeth D. Trippe, Juan B. Gutierrez, Krys J. Kochut*

2. **A survey of methods to ease the development of highly multilingual text mining applications.** Lang. Resour. Evaluation 2012 [paper](https://arxiv.org/abs/1401.2937) [bib](/bib/Natural-Language-Processing/Information-Retrieval-and-Text-Mining/Steinberger2012A.md)

    *Ralf Steinberger*

3. **Data Mining and Information Retrieval in the 21st century: A bibliographic review.** Comput. Sci. Rev. 2019 [paper](https://www.sciencedirect.com/science/article/abs/pii/S1574013719301297) [bib](/bib/Natural-Language-Processing/Information-Retrieval-and-Text-Mining/Liu2019Data.md)

    *Jiaying Liu, Xiangjie Kong, Xinyu Zhou, Lei Wang, Da Zhang, Ivan Lee, Bo Xu, Feng Xia*

4. **Neural Entity Linking: A Survey of Models Based on Deep Learning.** arXiv 2020 [paper](https://arxiv.org/abs/2006.00575) [bib](/bib/Natural-Language-Processing/Information-Retrieval-and-Text-Mining/Sevgili2020Neural.md)

    *Özge Sevgili, Artem Shelmanov, Mikhail Y. Arkhipov, Alexander Panchenko, Chris Biemann*

5. **Neural Models for Information Retrieval.** arXiv 2017 [paper](https://arxiv.org/pdf/1705.01509.pdf) [bib](/bib/Natural-Language-Processing/Information-Retrieval-and-Text-Mining/Mitra2017Neural.md)

    *Bhaskar Mitra, Nick Craswell*

6. **Opinion Mining and Analysis: A survey.** IJNLC 2013 [paper](https://arxiv.org/abs/1307.3336) [bib](/bib/Natural-Language-Processing/Information-Retrieval-and-Text-Mining/Buche2013Opinion.md)

    *Arti Buche, M. B. Chandak, Akshay Zadgaonkar*

7. **Relational World Knowledge Representation in Contextual Language Models: A Review.** EMNLP 2021 [paper](https://arxiv.org/abs/2104.05837) [bib](/bib/Natural-Language-Processing/Information-Retrieval-and-Text-Mining/Safavi2021Relational.md)

    *Tara Safavi, Danai Koutra*

8. **Short Text Topic Modeling Techniques, Applications, and Performance: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1904.07695) [bib](/bib/Natural-Language-Processing/Information-Retrieval-and-Text-Mining/Qiang2019Short.md)

    *Jipeng Qiang, Zhenyu Qian, Yun Li, Yunhao Yuan, Xindong Wu*

9. **Topic Modelling Meets Deep Neural Networks: A Survey.** IJCAI 2021 [paper](https://arxiv.org/abs/2103.00498) [bib](/bib/Natural-Language-Processing/Information-Retrieval-and-Text-Mining/Zhao2021Topic.md)

    *He Zhao, Dinh Q. Phung, Viet Huynh, Yuan Jin, Lan Du, Wray L. Buntine*

#### [Interpretability and Analysis of Models for NLP](#content)

1. **A Primer in BERTology: What we know about how BERT works.** Trans. Assoc. Comput. Linguistics 2020 [paper](https://arxiv.org/pdf/2002.12327.pdf) [bib](/bib/Natural-Language-Processing/Interpretability-and-Analysis-of-Models-for-NLP/Rogers2020A.md)

    *Anna Rogers, Olga Kovaleva, Anna Rumshisky*

2. **A Survey of the State of Explainable AI for Natural Language Processing.** AACL 2020 [paper](https://arxiv.org/pdf/2010.00711.pdf) [bib](/bib/Natural-Language-Processing/Interpretability-and-Analysis-of-Models-for-NLP/Danilevsky2020A.md)

    *Marina Danilevsky, Kun Qian, Ranit Aharonov, Yannis Katsis, Ban Kawas, Prithviraj Sen*

3. **A Survey on Deep Learning and Explainability for Automatic Report Generation from Medical Images.** arXiv 2020 [paper](https://arxiv.org/pdf/2010.10563.pdf) [bib](/bib/Natural-Language-Processing/Interpretability-and-Analysis-of-Models-for-NLP/Messina2020A.md)

    *Pablo Messina, Pablo Pino, Denis Parra, Alvaro Soto, Cecilia Besa, Sergio Uribe, Marcelo andía, Cristian Tejos, Claudia Prieto, Daniel Capurro*

4. **A Survey on Explainability in Machine Reading Comprehension.** arXiv 2020 [paper](http://arxiv.org/pdf/2010.00389.pdf) [bib](/bib/Natural-Language-Processing/Interpretability-and-Analysis-of-Models-for-NLP/Thayaparan2020A.md)

    *Mokanarangan Thayaparan, Marco Valentino, André Freitas*

5. **Analysis Methods in Neural Language Processing: A Survey.** Trans. Assoc. Comput. Linguistics 2019 [paper](https://arxiv.org/abs/1812.08951) [bib](/bib/Natural-Language-Processing/Interpretability-and-Analysis-of-Models-for-NLP/Belinkov2019Analysis.md)

    *Yonatan Belinkov, James R. Glass*

6. **Analyzing and Interpreting Neural Networks for NLP: A Report on the First BlackboxNLP Workshop.** Nat. Lang. Eng. 2019 [paper](http://arxiv.org/pdf/1904.04063.pdf) [bib](/bib/Natural-Language-Processing/Interpretability-and-Analysis-of-Models-for-NLP/Alishahi2019Analyzing.md)

    *Afra Alishahi, Grzegorz Chrupala, Tal Linzen*

7. **Post-hoc Interpretability for Neural NLP: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.04840.pdf) [bib](/bib/Natural-Language-Processing/Interpretability-and-Analysis-of-Models-for-NLP/Madsen2021Post-hoc.md)

    *Andreas Madsen, Siva Reddy, Sarath Chandar*

8. **Teach Me to Explain: A Review of Datasets for Explainable Natural Language Processing.** arXiv 2021 [paper](https://arxiv.org/pdf/2102.12060) [bib](/bib/Natural-Language-Processing/Interpretability-and-Analysis-of-Models-for-NLP/Wiegreffe2021Teach.md)

    *Sarah Wiegreffe, Ana Marasović*

9. **Which *BERT? A Survey Organizing Contextualized Encoders.** EMNLP 2020 [paper](https://arxiv.org/pdf/2010.00854.pdf) [bib](/bib/Natural-Language-Processing/Interpretability-and-Analysis-of-Models-for-NLP/Xia2020Which.md)

    *Patrick Xia, Shijie Wu, Benjamin Van Durme*

#### [Knowledge Graph](#content)

1. **A Review of Relational Machine Learning for Knowledge Graphs.** Proc. IEEE 2016 [paper](https://arxiv.org/pdf/1503.00759) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Nickel2016A.md)

    *Maximilian Nickel, Kevin Murphy, Volker Tresp, Evgeniy Gabrilovich*

2. **A survey of embedding models of entities and relationships for knowledge graph completion.** arXiv 2017 [paper](https://arxiv.org/pdf/1703.08098.pdf) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Nguyen2017A.md)

    *Dat Quoc Nguyen*

3. **A Survey of Embedding Space Alignment Methods for Language and Knowledge Graphs.** arXiv 2020 [paper](https://arxiv.org/pdf/2010.13688.pdf) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Kalinowski2020A.md)

    *Alexander Kalinowski, Yuan An*

4. **A Survey of Techniques for Constructing Chinese Knowledge Graphs and Their Applications.** Sustainability 2018 [paper](https://www.mdpi.com/2071-1050/10/9/3245/htm) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Wu2018A.md)

    *Tianxing Wu, Guilin Qi, Cheng Li, Meng Wang*

5. **A Survey on Graph Neural Networks for Knowledge Graph Completion.** arXiv 2020 [paper](https://arxiv.org/abs/2007.12374) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Arora2020A.md)

    *Siddhant Arora*

6. **A Survey on Knowledge Graphs: Representation, Acquisition and Applications.** arXiv 2020 [paper](https://arxiv.org/abs/2002.00388) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Ji2020A.md)

    *Shaoxiong Ji, Shirui Pan, Erik Cambria, Pekka Marttinen, Philip S. Yu*

7. **Introduction to neural network-based question answering over knowledge graphs.** WIREs Data Mining Knowl. Discov. 2021 [paper](https://onlinelibrary.wiley.com/doi/epdf/10.1002/widm.1389) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Chakraborty2021Introduction.md)

    *Nilesh Chakraborty, Denis Lukovnikov, Gaurav Maheshwari, Priyansh Trivedi, Jens Lehmann, Asja Fischer*

8. **Knowledge Graph Embedding for Link Prediction: A Comparative Analysis.** ACM Trans. Knowl. Discov. Data 2021 [paper](https://arxiv.org/abs/2002.00819) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Rossi2021Knowledge.md)

    *Andrea Rossi, Denilson Barbosa, Donatella Firmani, Antonio Matinata, Paolo Merialdo*

9. **Knowledge Graph Embedding: A Survey of Approaches and Applications.** IEEE Trans. Knowl. Data Eng. 2017 [paper](https://ieeexplore.ieee.org/document/8047276) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Wang2017Knowledge.md)

    *Quan Wang, Zhendong Mao, Bin Wang, Li Guo*

10. **Knowledge Graph Refinement: A Survey of Approaches and Evaluation Methods.** Semantic Web 2017 [paper](http://www.semantic-web-journal.net/system/files/swj1167.pdf) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Paulheim2017Knowledge.md)

    *Heiko Paulheim*

11. **Knowledge Graphs.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2003.02320) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Hogan2021Knowledge.md)

    *Aidan Hogan, Eva Blomqvist, Michael Cochez, Claudia d'Amato, Gerard de Melo, Claudio Gutiérrez, Sabrina Kirrane, José Emilio Labra Gayo, Roberto Navigli, Sebastian Neumaier, Axel-Cyrille Ngonga Ngomo, Axel Polleres, Sabbir M. Rashid, Anisa Rula, Lukas Schmelzeisen, Juan Sequeda, Steffen Staab, Antoine Zimmermann*

12. **Knowledge Graphs: An Information Retrieval Perspective.** Found. Trends Inf. Retr. 2020 [paper](https://www.nowpublishers.com/article/Details/INR-063) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Reinanda2020Knowledge.md)

    *Ridho Reinanda, Edgar Meij, Maarten de Rijke*

13. **知识表示学习研究进展.** 计算机研究与发展 2016 [paper](https://crad.ict.ac.cn/EN/Y2016/V53/I2/247) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Liu2016Knowledge.md)

    *刘知远, 孙茂松, 林衍凯, 谢若冰*

14. **Neural, Symbolic and Neural-symbolic Reasoning on Knowledge Graphs.** AI Open 2021 [paper](https://www.sciencedirect.com/science/article/pii/S2666651021000061/pdfft?md5=41dae412c5802b063f8ff0615ba12622&pid=1-s2.0-S2666651021000061-main.pdf) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Zhang2021Neural.md)

    *Jing Zhang, Bo Chen, Lingxi Zhang, Xirui Ke, Haipeng Ding*

15. **Survey and Open Problems in Privacy Preserving Knowledge Graph: Merging, Query, Representation, Completion and Applications.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.10180.pdf) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Chen2020Survey.md)

    *Chaochao Chen, Jamie Cui, Guanfeng Liu, Jia Wu, Li Wang*

16. **领域知识图谱研究综述.** 计算机系统应用 2020 [paper](http://www.c-s-a.org.cn/html/2020/6/7431.html#top) [bib](/bib/Natural-Language-Processing/Knowledge-Graph/Liu2020Survey.md)

    *刘烨宸, 李华昱*

#### [Language Grounding to Vision, Robotics and Beyond](#content)

1. **A comprehensive survey of mostly textual document segmentation algorithms since 2008.** Pattern Recognit. 2017 [paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320316303399) [bib](/bib/Natural-Language-Processing/Language-Grounding-to-Vision,-Robotics-and-Beyond/Eskenazi2017A.md)

    *Sébastien Eskenazi, Petra Gomez-Krämer, Jean-Marc Ogier*

2. **Emotionally-Aware Chatbots: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1906.09774) [bib](/bib/Natural-Language-Processing/Language-Grounding-to-Vision,-Robotics-and-Beyond/Pamungkas2019Emotionally-Aware.md)

    *Endang Wahyu Pamungkas*

3. **From Show to Tell: A Survey on Deep Learning-based Image Captioning.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.06912.pdf) [bib](/bib/Natural-Language-Processing/Language-Grounding-to-Vision,-Robotics-and-Beyond/Stefanini2021From.md)

    *Matteo Stefanini, Marcella Cornia, Lorenzo Baraldi, Silvia Cascianelli, Giuseppe Fiameni, Rita Cucchiara*

4. **Trends in Integration of Vision and Language Research: A Survey of Tasks, Datasets, and Methods.** arXiv 2019 [paper](https://arxiv.org/abs/1907.09358) [bib](/bib/Natural-Language-Processing/Language-Grounding-to-Vision,-Robotics-and-Beyond/Mogadala2019Trends.md)

    *Aditya Mogadala, Marimuthu Kalimuthu, Dietrich Klakow*

#### [Linguistic Theories, Cognitive Modeling and Psycholinguistics](#content)

1. **A Survey of Code-switching: Linguistic and Social Perspectives for Language Technologies.** ACL 2021 [paper](https://aclanthology.org/2021.acl-long.131.pdf) [bib](/bib/Natural-Language-Processing/Linguistic-Theories,-Cognitive-Modeling-and-Psycholinguistics/Dogruöz2021A.md)

    *A. Seza Dogruöz, Sunayana Sitaram, Barbara E. Bullock, Almeida Jacqueline Toribio*

2. **Modeling Language Variation and Universals: A Survey on Typological Linguistics for Natural Language Processing.** Comput. Linguistics 2019 [paper](https://arxiv.org/abs/1807.00914) [bib](/bib/Natural-Language-Processing/Linguistic-Theories,-Cognitive-Modeling-and-Psycholinguistics/Ponti2019Modeling.md)

    *Edoardo Maria Ponti, Helen O'Horan, Yevgeni Berzak, Ivan Vulic, Roi Reichart, Thierry Poibeau, Ekaterina Shutova, Anna Korhonen*

3. **Survey on the Use of Typological Information in Natural Language Processing.** COLING 2016 [paper](https://arxiv.org/abs/1610.03349) [bib](/bib/Natural-Language-Processing/Linguistic-Theories,-Cognitive-Modeling-and-Psycholinguistics/Horan2016Survey.md)

    *Helen O'Horan, Yevgeni Berzak, Ivan Vulic, Roi Reichart, Anna Korhonen*

#### [Machine Learning for NLP](#content)

1. **A Comprehensive Survey on Word Representation Models: From Classical to State-Of-The-Art Word Representation Language Models.** ACM Trans. Asian Low Resour. Lang. Inf. Process. 2021 [paper](https://arxiv.org/pdf/2010.15036.pdf) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Naseem2021A.md)

    *Usman Naseem, Imran Razzak, Shah Khalid Khan, Mukesh Prasad*

2. **A Survey Of Cross-lingual Word Embedding Models.** J. Artif. Intell. Res. 2019 [paper](https://arxiv.org/abs/1706.04902) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Ruder2019A.md)

    *Sebastian Ruder, Ivan Vulic, Anders Søgaard*

3. **A Survey of Data Augmentation Approaches for NLP.** ACL 2021 [paper](https://arxiv.org/pdf/2105.03075) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Feng2021A.md)

    *Steven Y. Feng, Varun Gangal, Jason Wei, Sarath Chandar, Soroush Vosoughi, Teruko Mitamura, Eduard H. Hovy*

4. **A Survey of Neural Network Techniques for Feature Extraction from Text.** arXiv 2017 [paper](https://arxiv.org/abs/1704.08531) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/John2017A.md)

    *Vineet John*

5. **A Survey of Neural Networks and Formal Languages.** arXiv 2020 [paper](https://arxiv.org/abs/2006.01338) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Ackerman2020A.md)

    *Joshua Ackerman, George Cybenko*

6. **A Survey of the Usages of Deep Learning in Natural Language Processing.** arXiv 2018 [paper](https://arxiv.org/pdf/1807.10854) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Otter2018A.md)

    *Daniel W. Otter, Julian R. Medina, Jugal K. Kalita*

7. **A Survey on Contextual Embeddings.** arXiv 2020 [paper](https://arxiv.org/abs/2003.07278) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Liu2020A.md)

    *Qi Liu, Matt J. Kusner, Phil Blunsom*

8. **A Survey on Transfer Learning in Natural Language Processing.** arXiv 2020 [paper](https://arxiv.org/abs/2007.04239) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Alyafeai2020A.md)

    *Zaid Alyafeai, Maged Saeed AlShaibani, Irfan Ahmad*

9. **Adversarial Attacks and Defense on Texts: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2005.14108) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Huq2020Adversarial.md)

    *Aminul Huq, Mst. Tasnim Pervin*

10. **Adversarial Attacks on Deep-Learning Models in Natural Language Processing: A Survey.** ACM Trans. Intell. Syst. Technol. 2020 [paper](https://dl.acm.org/doi/pdf/10.1145/3374217) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Zhang2020Adversarial.md)

    *Wei Emma Zhang, Quan Z. Sheng, Ahoud Abdulrahmn F. Alhazmi, Chenliang Li*

11. **An Empirical Survey of Unsupervised Text Representation Methods on Twitter Data.** W-NUT@EMNLP 2020 [paper](https://www.aclweb.org/anthology/2020.wnut-1.27/) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Wang2020An.md)

    *Lili Wang, Chongyang Gao, Jason Wei, Weicheng Ma, Ruibo Liu, Soroush Vosoughi*

12. **Bangla Natural Language Processing: A Comprehensive Review of Classical, Machine Learning, and Deep Learning Based Methods.** arXiv 2021 [paper](https://arxiv.org/abs/2105.14875) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Sen2021Bangla.md)

    *Ovishake Sen, Mohtasim Fuad, Md. Nazrul Islam, Jakaria Rabbi, Md. Kamrul Hasan, Awal Ahmed Fime, Md. Tahmid Hasan Fuad, Delowar Sikder, Md. Akil Raihan Iftee*

13. **Federated Learning Meets Natural Language Processing: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.12603.pdf) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Liu2021Federated.md)

    *Ming Liu, Stella Ho, Mengqi Wang, Longxiang Gao, Yuan Jin, He Zhang*

14. **From static to dynamic word representations: a survey.** Int. J. Mach. Learn. Cybern. 2020 [paper](http://ir.hit.edu.cn/~car/papers/icmlc2020-wang.pdf) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Wang2020From.md)

    *Yuxuan Wang, Yutai Hou, Wanxiang Che, Ting Liu*

15. **From Word to Sense Embeddings: A Survey on Vector Representations of Meaning.** J. Artif. Intell. Res. 2018 [paper](https://arxiv.org/abs/1805.04032) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Camacho2018From.md)

    *José Camacho-Collados, Mohammad Taher Pilehvar*

16. **Graph Neural Networks for Natural Language Processing: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.06090.pdf) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Wu2021Graph.md)

    *Lingfei Wu, Yu Chen, Kai Shen, Xiaojie Guo, Hanning Gao, Shucheng Li, Jian Pei, Bo Long*

17. **Informed Machine Learning -- A Taxonomy and Survey of Integrating Knowledge into Learning Systems.** arXiv 2019 [paper](https://arxiv.org/abs/1903.12394) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Rueden2019Informed.md)

    *Laura von Rueden, Sebastian Mayer, Katharina Beckh, Bogdan Georgiev, Sven Giesselbach, Raoul Heese, Birgit Kirsch, Julius Pfrommer, Annika Pick, Rajkumar Ramamurthy, Michal Walczak, Jochen Garcke, Christian Bauckhage, Jannis Schuecker*

18. **Narrative Science Systems: A Review.** International Journal of Research in Computer Science 2015 [paper](https://arxiv.org/abs/1510.04420) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Sarao2015Narrative.md)

    *Paramjot Kaur Sarao, Puneet Mittal, Rupinder Kaur*

19. **Natural Language Processing Advancements By Deep Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2003.01200) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Torfi2020Natural.md)

    *Amirsina Torfi, Rouzbeh A. Shirvani, Yaser Keneshloo, Nader Tavaf, Edward A. Fox*

20. **Recent Trends in Deep Learning Based Natural Language Processing [Review Article].** IEEE Comput. Intell. Mag. 2018 [paper](https://ieeexplore.ieee.org/document/8416973) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Young2018Recent.md)

    *Tom Young, Devamanyu Hazarika, Soujanya Poria, Erik Cambria*

21. **网络表示学习算法综述.** 计算机科学 2020 [paper](http://www.jsjkx.com/CN/10.11896/jsjkx.190300004) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Yu2020Survey.md)

    *丁钰, 魏浩, 潘志松, 刘鑫*

22. **Symbolic, Distributed, and Distributional Representations for Natural Language Processing in the Era of Deep Learning: A Survey.** Frontiers Robotics AI 2019 [paper](https://arxiv.org/abs/1702.00764) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Ferrone2019Symbolic.md)

    *Lorenzo Ferrone, Fabio Massimo Zanzotto*

23. **Token-Modification Adversarial Attacks for Natural Language Processing: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2103.00676) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Roth2021Token-Modification.md)

    *Tom Roth, Yansong Gao, Alsharif Abuadbba, Surya Nepal, Wei Liu*

24. **Towards a Robust Deep Neural Network in Texts: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1902.07285) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Wang2019Towards.md)

    *Wenqi Wang, Lina Wang, Run Wang, Zhibo Wang, Aoshuang Ye*

25. **Word Embeddings: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1901.09069) [bib](/bib/Natural-Language-Processing/Machine-Learning-for-NLP/Almeida2019Word.md)

    *Felipe Almeida, Geraldo Xexéo*

#### [Machine Translation](#content)

1. **A Comprehensive Survey of Multilingual Neural Machine Translation.** arXiv 2020 [paper](https://arxiv.org/abs/2001.01115) [bib](/bib/Natural-Language-Processing/Machine-Translation/Dabre2020A.md)

    *Raj Dabre, Chenhui Chu, Anoop Kunchukuttan*

2. **A Survey of Deep Learning Techniques for Neural Machine Translation.** arXiv 2020 [paper](https://arxiv.org/abs/2002.07526) [bib](/bib/Natural-Language-Processing/Machine-Translation/Yang2020A.md)

    *Shuoheng Yang, Yuxin Wang, Xiaowen Chu*

3. **A Survey of Domain Adaptation for Neural Machine Translation.** COLING 2018 [paper](https://arxiv.org/abs/1806.00258) [bib](/bib/Natural-Language-Processing/Machine-Translation/Chu2018A.md)

    *Chenhui Chu, Rui Wang*

4. **A Survey of Methods to Leverage Monolingual Data in Low-resource Neural Machine Translation.** arXiv 2019 [paper](https://arxiv.org/abs/1910.00373) [bib](/bib/Natural-Language-Processing/Machine-Translation/Gibadullin2019A.md)

    *Ilshat Gibadullin, Aidar Valeev, Albina Khusainova, Adil Khan*

5. **A Survey of Orthographic Information in Machine Translation.** SN Comput. Sci. 2021 [paper](https://arxiv.org/abs/2008.01391) [bib](/bib/Natural-Language-Processing/Machine-Translation/Chakravarthi2021A.md)

    *Bharathi Raja Chakravarthi, Priya Rani, Mihael Arcan, John P. McCrae*

6. **A Survey of Word Reordering in Statistical Machine Translation: Computational Models and Language Phenomena.** Comput. Linguistics 2016 [paper](https://arxiv.org/abs/1502.04938) [bib](/bib/Natural-Language-Processing/Machine-Translation/Bisazza2016A.md)

    *Arianna Bisazza, Marcello Federico*

7. **A Survey on Document-level Neural Machine Translation: Methods and Evaluation.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/1912.08494) [bib](/bib/Natural-Language-Processing/Machine-Translation/Maruf2021A.md)

    *Sameen Maruf, Fahimeh Saleh, Gholamreza Haffari*

8. **A Survey on Low-Resource Neural Machine Translation.** IJCAI 2021 [paper](https://arxiv.org/pdf/2107.04239.pdf) [bib](/bib/Natural-Language-Processing/Machine-Translation/Wang2021A.md)

    *Rui Wang, Xu Tan, Renqian Luo, Tao Qin, Tie-Yan Liu*

9. **Domain Adaptation and Multi-Domain Adaptation for Neural Machine Translation: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2104.06951) [bib](/bib/Natural-Language-Processing/Machine-Translation/Saunders2021Domain.md)

    *Danielle Saunders*

10. **Gender Bias in Machine Translation.** arXiv 2021 [paper](https://arxiv.org/abs/2104.06001) [bib](/bib/Natural-Language-Processing/Machine-Translation/Savoldi2021Gender.md)

    *Beatrice Savoldi, Marco Gaido, Luisa Bentivogli, Matteo Negri, Marco Turchi*

11. **Machine Translation Approaches and Survey for Indian Languages.** Int. J. Comput. Linguistics Chin. Lang. Process. 2013 [paper](http://www.aclclp.org.tw/clclp/v18n1/v18n1a3.pdf) [bib](/bib/Natural-Language-Processing/Machine-Translation/Antony2013Machine.md)

    *P. J. Antony*

12. **Machine Translation Approaches and Survey for Indian Languages.** arXiv 2017 [paper](https://arxiv.org/abs/1701.04290) [bib](/bib/Natural-Language-Processing/Machine-Translation/Khan2017Machine.md)

    *Nadeem Jadoon Khan, Waqas Anwar, Nadir Durrani*

13. **Machine Translation Evaluation Resources and Methods: A Survey.** Ireland Postgraduate Research Conference 2018 [paper](https://arxiv.org/abs/1605.04515) [bib](/bib/Natural-Language-Processing/Machine-Translation/Han2018Machine.md)

    *Lifeng Han*

14. **Machine Translation using Semantic Web Technologies: A Survey.** J. Web Semant. 2018 [paper](https://arxiv.org/abs/1711.09476) [bib](/bib/Natural-Language-Processing/Machine-Translation/Moussallem2018Machine.md)

    *Diego Moussallem, Matthias Wauer, Axel-Cyrille Ngonga Ngomo*

15. **Machine-Translation History and Evolution: Survey for Arabic-English Translations.** CJAST 2017 [paper](https://arxiv.org/abs/1709.04685) [bib](/bib/Natural-Language-Processing/Machine-Translation/Alsohybe2017Machine-Translation.md)

    *Nabeel T. Alsohybe, Neama Abdulaziz Dahan, Fadl Mutaher Ba-Alwi*

16. **Multimodal Machine Translation through Visuals and Speech.** Mach. Transl. 2020 [paper](https://arxiv.org/abs/1911.12798) [bib](/bib/Natural-Language-Processing/Machine-Translation/Sulubacak2020Multimodal.md)

    *Umut Sulubacak, Ozan Caglayan, Stig-Arne Grönroos, Aku Rouhe, Desmond Elliott, Lucia Specia, Jörg Tiedemann*

17. **Neural Machine Translation and Sequence-to-sequence Models: A Tutorial.** arXiv 2017 [paper](https://arxiv.org/abs/1703.01619) [bib](/bib/Natural-Language-Processing/Machine-Translation/Neubig2017Neural.md)

    *Graham Neubig*

18. **Neural Machine Translation for Low-Resource Languages: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2106.15115 ) [bib](/bib/Natural-Language-Processing/Machine-Translation/Ranathunga2021Neural.md)

    *Surangika Ranathunga, En-Shiun Annie Lee, Marjana Prifti Skenduli, Ravi Shekhar, Mehreen Alam, Rishemjit Kaur*

19. **Neural Machine Translation: A Review.** J. Artif. Intell. Res. 2020 [paper](https://arxiv.org/abs/1912.02047) [bib](/bib/Natural-Language-Processing/Machine-Translation/Stahlberg2020Neural.md)

    *Felix Stahlberg*

20. **Neural machine translation: A review of methods, resources, and tools.** AI Open 2020 [paper](https://www.sciencedirect.com/science/article/pii/S2666651020300024) [bib](/bib/Natural-Language-Processing/Machine-Translation/Tan2020Neural.md)

    *Zhixing Tan, Shuo Wang, Zonghan Yang, Gang Chen, Xuancheng Huang, Maosong Sun, Yang Liu*

21. **Neural Machine Translation: Challenges, Progress and Future.** Science China Technological Sciences 2020 [paper](https://arxiv.org/abs/2004.05809) [bib](/bib/Natural-Language-Processing/Machine-Translation/Zhang2020Neural.md)

    *Jiajun Zhang, Chengqing Zong*

22. **Survey of Low-Resource Machine Translation.** arXiv 2021 [paper](https://export.arxiv.org/pdf/2109.00486) [bib](/bib/Natural-Language-Processing/Machine-Translation/Haddow2021Survey.md)

    *Barry Haddow, Rachel Bawden, Antonio Valerio Miceli Barone, Jindrich Helcl, Alexandra Birch*

23. **The Query Translation Landscape: a Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1910.03118) [bib](/bib/Natural-Language-Processing/Machine-Translation/Mami2019The.md)

    *Mohamed Nadjib Mami, Damien Graux, Harsh Thakkar, Simon Scerri, Sören Auer, Jens Lehmann*

24. **神经机器翻译前沿综述.** 中文信息学报 2020 [paper](http://www.cnki.com.cn/Article/CJFDTotal-MESS202007002.htm) [bib](/bib/Natural-Language-Processing/Machine-Translation/Feng2020Survey.md)

    *冯洋, 邵晨泽*

#### [Named Entity Recognition](#content)

1. **A Survey of Arabic Named Entity Recognition and Classification.** Comput. Linguistics 2014 [paper](https://direct.mit.edu/coli/article/40/2/469/1475/A-Survey-of-Arabic-Named-Entity-Recognition-and) [bib](/bib/Natural-Language-Processing/Named-Entity-Recognition/Shaalan2014A.md)

    *Khaled Shaalan*

2. **A survey of named entity recognition and classification.** Lingvisticae Investigationes 2007 [paper](https://nlp.cs.nyu.edu/sekine/papers/li07.pdf) [bib](/bib/Natural-Language-Processing/Named-Entity-Recognition/Nadeau2007A.md)

    *David Nadeau, Satoshi Sekine*

3. **A Survey of Named Entity Recognition in Assamese and other Indian Languages.** arXiv 2014 [paper](https://arxiv.org/abs/1407.2918) [bib](/bib/Natural-Language-Processing/Named-Entity-Recognition/Talukdar2014A.md)

    *Gitimoni Talukdar, Pranjal Protim Borah, Arup Baruah*

4. **A Survey on Deep Learning for Named Entity Recognition.** IEEE Trans. Knowl. Data Eng. 2022 [paper](https://arxiv.org/abs/1812.09449) [bib](/bib/Natural-Language-Processing/Named-Entity-Recognition/Li2022A.md)

    *Jing Li, Aixin Sun, Jianglei Han, Chenliang Li*

5. **A Survey on Recent Advances in Named Entity Recognition from Deep Learning models.** COLING 2018 [paper](https://arxiv.org/abs/1910.11470) [bib](/bib/Natural-Language-Processing/Named-Entity-Recognition/Yadav2018A.md)

    *Vikas Yadav, Steven Bethard*

6. **Design Challenges and Misconceptions in Neural Sequence Labeling.** COLING 2018 [paper](https://arxiv.org/abs/1806.04470) [bib](/bib/Natural-Language-Processing/Named-Entity-Recognition/Yang2018Design.md)

    *Jie Yang, Shuailong Liang, Yue Zhang*

#### [Natural Language Inference](#content)

1. **A Comparative Survey of Recent Natural Language Interfaces for Databases.** VLDB J. 2019 [paper](https://arxiv.org/abs/1906.08990) [bib](/bib/Natural-Language-Processing/Natural-Language-Inference/Affolter2019A.md)

    *Katrin Affolter, Kurt Stockinger, Abraham Bernstein*

2. **Beyond Leaderboards: A survey of methods for revealing weaknesses in Natural Language Inference data and models.** arXiv 2020 [paper](https://arxiv.org/abs/2005.14709) [bib](/bib/Natural-Language-Processing/Natural-Language-Inference/Schlegel2020Beyond.md)

    *Viktor Schlegel, Goran Nenadic, Riza Batista-Navarro*

3. **Recent Advances in Natural Language Inference: A Survey of Benchmarks, Resources, and Approaches.** arXiv 2019 [paper](https://arxiv.org/pdf/1904.01172) [bib](/bib/Natural-Language-Processing/Natural-Language-Inference/Storks2019Recent.md)

    *Shane Storks, Qiaozi Gao, Joyce Y Chai*

#### [Natural Language Processing](#content)

1. **A bit of progress in language modeling.** Comput. Speech Lang. 2001 [paper](https://www.sciencedirect.com/science/article/pii/S0885230801901743) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Goodman2001A.md)

    *Joshua T. Goodman*

2. **A Brief Survey and Comparative Study of Recent Development of Pronoun Coreference Resolution.** arXiv 2020 [paper](https://arxiv.org/pdf/2009.12721.pdf) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Zhang2020A.md)

    *Hongming Zhang, Xinran Zhao, Yangqiu Song*

3. **A Comprehensive Survey of Grammar Error Correction.** arXiv 2020 [paper](https://arxiv.org/abs/2005.06600) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Wang2020A.md)

    *Yu Wang, Yuelin Wang, Jie Liu, Zhuo Liu*

4. **A Neural Entity Coreference Resolution Review.** Expert Syst. Appl. 2021 [paper](https://arxiv.org/abs/1910.09329) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Stylianou2021A.md)

    *Nikolaos Stylianou, Ioannis P. Vlahavas*

5. **A Primer on Neural Network Models for Natural Language Processing.** J. Artif. Intell. Res. 2016 [paper](https://arxiv.org/abs/1510.00726) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Goldberg2016A.md)

    *Yoav Goldberg*

6. **A Review of Bangla Natural Language Processing Tasks and the Utility of Transformer Models.** arXiv 2021 [paper](https://arxiv.org/abs/2107.03844 ) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Alam2021A.md)

    *Firoj Alam, Md. Arid Hasan, Tanvirul Alam, Akib Khan, Jannatul Tajrin, Naira Khan, Shammur Absar Chowdhury*

7. **A Survey and Classification of Controlled Natural Languages.** Comput. Linguistics 2014 [paper](https://arxiv.org/abs/1507.01701) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Kuhn2014A.md)

    *Tobias Kuhn*

8. **A Survey on Neural Network Language Models.** arXiv 2019 [paper](https://arxiv.org/abs/1906.03591) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Jing2019A.md)

    *Kun Jing, Jungang Xu*

9. **A Survey on Recent Approaches for Natural Language Processing in Low-Resource Scenarios.** NAACL-HLT 2021 [paper](https://arxiv.org/pdf/2010.12309.pdf) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Hedderich2021A.md)

    *Michael A. Hedderich, Lukas Lange, Heike Adel, Jannik Strötgen, Dietrich Klakow*

10. **An Introductory Survey on Attention Mechanisms in NLP Problems.** IntelliSys 2019 [paper](https://arxiv.org/pdf/1811.05544.pdf) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Hu2019An.md)

    *Dichao Hu*

11. **Attention in Natural Language Processing.** IEEE Trans. Neural Networks Learn. Syst. 2021 [paper](https://paper.idea.edu.cn/paper/3031696893) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Galassi2021Attention.md)

    *Andrea Galassi, Marco Lippi, Paolo Torroni*

12. **Automatic Arabic Dialect Identification Systems for Written Texts: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2009.12622) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Althobaiti2020Automatic.md)

    *Maha J. Althobaiti*

13. **Chinese Word Segmentation: A Decade Review.** Journal of Chinese Information Processing 2007 [paper](https://en.cnki.com.cn/Article_en/CJFDTotal-MESS200703001.htm) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Huang2007Chinese.md)

    *Changning Huang, Hai Zhao*

14. **Continual Lifelong Learning in Natural Language Processing: A Survey.** COLING 2020 [paper](https://www.aclweb.org/anthology/2020.coling-main.574/) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Biesialska2020Continual.md)

    *Magdalena Biesialska, Katarzyna Biesialska, Marta R. Costa-jussà*

15. **Experience Grounds Language.** EMNLP 2020 [paper](https://arxiv.org/abs/2004.10151) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Bisk2020Experience.md)

    *Yonatan Bisk, Ari Holtzman, Jesse Thomason, Jacob Andreas, Yoshua Bengio, Joyce Chai, Mirella Lapata, Angeliki Lazaridou, Jonathan May, Aleksandr Nisnevich, Nicolas Pinto, Joseph P. Turian*

16. **How Commonsense Knowledge Helps with Natural Language Tasks: A Survey of Recent Resources and Methodologies.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.04674.pdf) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Xie2021How.md)

    *Yubo Xie, Pearl Pu*

17. **Jumping NLP curves: A review of natural language processing research [Review Article].** IEEE Comput. Intell. Mag. 2014 [paper](http://krchowdhary.com/ai/ai14/lects/nlp-research-com-intlg-ieee.pdf) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Cambria2014Jumping.md)

    *Erik Cambria, Bebo White*

18. **Natural Language Processing - A Survey.** arXiv 2012 [paper](https://arxiv.org/abs/1209.6238) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Mote2012Natural.md)

    *Kevin Mote*

19. **Natural Language Processing: State of The Art, Current Trends and Challenges.** arXiv 2017 [paper](https://arxiv.org/abs/1708.05148) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Khurana2017Natural.md)

    *Diksha Khurana, Aditya Koli, Kiran Khatter, Sukhdev Singh*

20. **Neural Network Models for Paraphrase Identification, Semantic Textual Similarity, Natural Language Inference, and Question Answering.** COLING 2018 [paper](https://arxiv.org/pdf/1806.04330.pdf) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Lan2018Neural.md)

    *Wuwei Lan, Wei Xu*

21. **Overview of the Transformer-based Models for NLP Tasks.** FedCSIS 2020 [paper](https://ieeexplore.ieee.org/document/9222960) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Gillioz2020Overview.md)

    *Anthony Gillioz, Jacky Casas, Elena Mugellini, Omar Abou Khaled*

22. **Progress in Neural NLP: Modeling, Learning, and Reasoning.** Engineering 2020 [paper](https://www.sciencedirect.com/science/article/pii/S2095809919304928) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Zhou2020Progress.md)

    *Ming Zhou, Nan Duan, Shujie Liu, Heung-Yeung Shum*

23. **Putting Humans in the Natural Language Processing Loop: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2103.04044) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Wang2021Putting.md)

    *Zijie J. Wang, Dongjin Choi, Shenyu Xu, Diyi Yang*

24. **Survey on Publicly Available Sinhala Natural Language Processing Tools and Research.** arXiv 2019 [paper](https://arxiv.org/abs/1906.02358) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Silva2019Survey.md)

    *Nisansa de Silva*

25. **Visualizing Natural Language Descriptions: A Survey.** ACM Comput. Surv. 2016 [paper](https://arxiv.org/abs/1607.00623) [bib](/bib/Natural-Language-Processing/Natural-Language-Processing/Hassani2016Visualizing.md)

    *Kaveh Hassani, Won-Sook Lee*

#### [NLP Applications](#content)

1. **A Short Survey of Biomedical Relation Extraction Techniques.** arXiv 2017 [paper](https://arxiv.org/abs/1707.05850) [bib](/bib/Natural-Language-Processing/NLP-Applications/Shahab2017A.md)

    *Elham Shahab*

2. **A survey on natural language processing (nlp) and applications in insurance.** arXiv 2020 [paper](http://arxiv.org/pdf/2010.00462.pdf) [bib](/bib/Natural-Language-Processing/NLP-Applications/Ly2020A.md)

    *Antoine Ly, Benno Uthayasooriyar, Tingting Wang*

3. **Android Security using NLP Techniques: A Review.** arXiv 2021 [paper](https://arxiv.org/abs/2107.03072 ) [bib](/bib/Natural-Language-Processing/NLP-Applications/Sen2021Android.md)

    *Sevil Sen, Burcu Can*

4. **Disinformation Detection: A review of linguistic feature selection and classification models in news veracity assessments.** arXiv 2019 [paper](https://arxiv.org/abs/1910.12073) [bib](/bib/Natural-Language-Processing/NLP-Applications/Tompkins2019Disinformation.md)

    *Jillian Tompkins*

5. **Extraction and Analysis of Fictional Character Networks: A Survey.** ACM Comput. Surv. 2019 [paper](https://arxiv.org/abs/1907.02704) [bib](/bib/Natural-Language-Processing/NLP-Applications/Labatut2019Extraction.md)

    *Vincent Labatut, Xavier Bost*

6. **How Does NLP Benefit Legal System: A Summary of Legal Artificial Intelligence.** ACL 2020 [paper](https://arxiv.org/pdf/2004.12158) [bib](/bib/Natural-Language-Processing/NLP-Applications/Zhong2020How.md)

    *Haoxi Zhong, Chaojun Xiao, Cunchao Tu, Tianyang Zhang, Zhiyuan Liu, Maosong Sun*

7. **Natural Language Based Financial Forecasting: A Survey.** Artif. Intell. Rev. 2018 [paper](https://dspace.mit.edu/bitstream/handle/1721.1/116314/10462_2017_9588_ReferencePDF.pdf?sequence=2&isAllowed=y) [bib](/bib/Natural-Language-Processing/NLP-Applications/Xing2018Natural.md)

    *Frank Z. Xing, Erik Cambria, Roy E. Welsch*

8. **Neural Natural Language Processing for Unstructured Data in Electronic Health Records: a Review.** arXiv 2021 [paper]( https://arxiv.org/abs/2107.02975 ) [bib](/bib/Natural-Language-Processing/NLP-Applications/Li2021Neural.md)

    *Irene Li, Jessica Pan, Jeremy Goldwasser, Neha Verma, Wai Pan Wong, Muhammed Yavuz Nuzumlali, Benjamin Rosand, Yixin Li, Matthew Zhang, David Chang, Richard Andrew Taylor, Harlan M. Krumholz, Dragomir R. Radev*

9. **SECNLP: A survey of embeddings in clinical natural language processing.** J. Biomed. Informatics 2020 [paper](https://www.sciencedirect.com/science/article/pii/S1532046419302436) [bib](/bib/Natural-Language-Processing/NLP-Applications/Kalyan2020SECNLP.md)

    *Katikapalli Subramanyam Kalyan, Sivanesan Sangeetha*

10. **Survey of Natural Language Processing Techniques in Bioinformatics.** Comput. Math. Methods Medicine 2015 [paper](https://pdfs.semanticscholar.org/7013/479be7dda124750aa22fb6231eea2671f630.pdf) [bib](/bib/Natural-Language-Processing/NLP-Applications/Zeng2015Survey.md)

    *Zhiqiang Zeng, Hua Shi, Yun Wu, Zhiling Hong*

11. **Survey of Text-based Epidemic Intelligence: A Computational Linguistics Perspective.** ACM Comput. Surv. 2020 [paper](https://dl.acm.org/doi/10.1145/3361141) [bib](/bib/Natural-Language-Processing/NLP-Applications/Joshi2020Survey.md)

    *Aditya Joshi, Sarvnaz Karimi, Ross Sparks, Cécile Paris, C. Raina MacIntyre*

12. **The Potential of Machine Learning and NLP for Handling Students' Feedback (A Short Survey).** arXiv 2020 [paper](https://arxiv.org/pdf/2011.05806) [bib](/bib/Natural-Language-Processing/NLP-Applications/Edalati2020The.md)

    *Maryam Edalati*

13. **Towards Improved Model Design for Authorship Identification: A Survey on Writing Style Understanding.** arXiv 2020 [paper](https://arxiv.org/pdf/2009.14445.pdf) [bib](/bib/Natural-Language-Processing/NLP-Applications/Ma2020Towards.md)

    *Weicheng Ma, Ruibo Liu, Lili Wang, Soroush Vosoughi*

#### [Pre-training](#content)

1. **A Primer on Contrastive Pretraining in Language Processing: Methods, Lessons Learned and Perspectives.** arXiv 2021 [paper](https://arxiv.org/abs/2102.12982) [bib](/bib/Natural-Language-Processing/Pre-training/Rethmeier2021A.md)

    *Nils Rethmeier, Isabelle Augenstein*

2. **A Short Survey of Pre-trained Language Models for Conversational AI-A NewAge in NLP.** arXiv 2021 [paper](https://arxiv.org/abs/2104.10810) [bib](/bib/Natural-Language-Processing/Pre-training/Zaib2021A.md)

    *Munazza Zaib, Quan Z. Sheng, Wei Emma Zhang*

3. **AMMUS : A Survey of Transformer-based Pretrained Models in Natural Language Processing.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.05542.pdf) [bib](/bib/Natural-Language-Processing/Pre-training/Kalyan2021AMMUS.md)

    *Katikapalli Subramanyam Kalyan, Ajit Rajasekharan, Sivanesan Sangeetha*

4. **Pre-train, Prompt, and Predict: A Systematic Survey of Prompting Methods in Natural Language Processing.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.13586.pdf) [bib](/bib/Natural-Language-Processing/Pre-training/Liu2021Pre-train.md)

    *Pengfei Liu, Weizhe Yuan, Jinlan Fu, Zhengbao Jiang, Hiroaki Hayashi, Graham Neubig*

5. **Pretrained Language Models for Text Generation: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2105.10311.pdf) [bib](/bib/Natural-Language-Processing/Pre-training/Li2021Pretrained.md)

    *Junyi Li, Tianyi Tang, Wayne Xin Zhao, Ji-Rong Wen*

6. **Pre-trained models for natural language processing: A survey.** Science China Technological Sciences 2020 [paper](https://link.springer.com/content/pdf/10.1007/s11431-020-1647-3.pdf) [bib](/bib/Natural-Language-Processing/Pre-training/Qiu2020Pre-trained.md)

    *Xipeng Qiu, Tianxiang Sun, Yige Xu, Yunfan Shao, Ning Dai, Xuanjing Huang*

7. **Pre-Trained Models: Past, Present and Future.** arXiv 2021 [paper](https://arxiv.org/abs/2106.07139) [bib](/bib/Natural-Language-Processing/Pre-training/Han2021Pre-Trained.md)

    *Xu Han, Zhengyan Zhang, Ning Ding, Yuxian Gu, Xiao Liu, Yuqi Huo, Jiezhong Qiu, Liang Zhang, Wentao Han, Minlie Huang, Qin Jin, Yanyan Lan, Yang Liu, Zhiyuan Liu, Zhiwu Lu, Xipeng Qiu, Ruihua Song, Jie Tang, Ji-Rong Wen, Jinhui Yuan, Wayne Xin Zhao, Jun Zhu*

8. **Pretrained Transformers for Text Ranking: BERT and Beyond.** WSDM 2021 [paper](https://dl.acm.org/doi/pdf/10.1145/3437963.3441667) [bib](/bib/Natural-Language-Processing/Pre-training/Yates2021Pretrained.md)

    *Andrew Yates, Rodrigo Nogueira, Jimmy Lin*

#### [Question Answering](#content)

1. **A Survey of Question Answering over Knowledge Base.** CCKS 2019 [paper](https://link.springer.com/chapter/10.1007%2F978-981-15-1956-7_8) [bib](/bib/Natural-Language-Processing/Question-Answering/Wu2019A.md)

    *Peiyun Wu, Xiaowang Zhang, Zhiyong Feng*

2. **A Survey on Complex Knowledge Base Question Answering: Methods, Challenges and Solutions.** IJCAI 2021 [paper](https://arxiv.org/abs/2105.11644) [bib](/bib/Natural-Language-Processing/Question-Answering/Lan2021A.md)

    *Yunshi Lan, Gaole He, Jinhao Jiang, Jing Jiang, Wayne Xin Zhao, Ji-Rong Wen*

3. **A Survey on Complex Question Answering over Knowledge Base: Recent Advances and Challenges.** arXiv 2020 [paper](https://arxiv.org/abs/2007.13069) [bib](/bib/Natural-Language-Processing/Question-Answering/Fu2020A.md)

    *Bin Fu, Yunqi Qiu, Chengguang Tang, Yang Li, Haiyang Yu, Jian Sun*

4. **A survey on question answering technology from an information retrieval perspective.** Inf. Sci. 2011 [paper](https://www.sciencedirect.com/science/article/pii/S0020025511003860) [bib](/bib/Natural-Language-Processing/Question-Answering/Kolomiyets2011A.md)

    *Oleksandr Kolomiyets, Marie-Francine Moens*

5. **A Survey on Why-Type Question Answering Systems.** arXiv 2019 [paper](https://arxiv.org/abs/1911.04879) [bib](/bib/Natural-Language-Processing/Question-Answering/Breja2019A.md)

    *Manvi Breja, Sanjay Kumar Jain*

6. **Complex Knowledge Base Question Answering: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.06688.pdf) [bib](/bib/Natural-Language-Processing/Question-Answering/Lan2021Complex.md)

    *Yunshi Lan, Gaole He, Jinhao Jiang, Jing Jiang, Wayne Xin Zhao, Ji-Rong Wen*

7. **Core techniques of question answering systems over knowledge bases: a survey.** Knowl. Inf. Syst. 2018 [paper](https://link.springer.com/article/10.1007/s10115-017-1100-y) [bib](/bib/Natural-Language-Processing/Question-Answering/Diefenbach2018Core.md)

    *Dennis Diefenbach, Vanessa López, Kamal Deep Singh, Pierre Maret*

8. **Introduction to Neural Network based Approaches for Question Answering over Knowledge Graphs.** arXiv 2019 [paper](https://arxiv.org/abs/1907.09361) [bib](/bib/Natural-Language-Processing/Question-Answering/Chakraborty2019Introduction.md)

    *Nilesh Chakraborty, Denis Lukovnikov, Gaurav Maheshwari, Priyansh Trivedi, Jens Lehmann, Asja Fischer*

9. **Narrative Question Answering with Cutting-Edge Open-Domain QA Techniques: A Comprehensive Study.** arXiv 2021 [paper](https://arxiv.org/abs/2106.03826) [bib](/bib/Natural-Language-Processing/Question-Answering/Mou2021Narrative.md)

    *Xiangyang Mou, Chenghao Yang, Mo Yu, Bingsheng Yao, Xiaoxiao Guo, Saloni Potdar, Hui Su*

10. **Question Answering Systems: Survey and Trends.** Procedia Computer Science 2015 [paper](https://www.sciencedirect.com/science/article/pii/S1877050915034663) [bib](/bib/Natural-Language-Processing/Question-Answering/Bouziane2015Question.md)

    *Abdelghani Bouziane, Djelloul Bouchiha, Noureddine Doumi, Mimoun Malki*

11. **Retrieving and Reading: A Comprehensive Survey on Open-domain Question Answering.** arXiv 2021 [paper](http://arxiv.org/pdf/2101.00774.pdf) [bib](/bib/Natural-Language-Processing/Question-Answering/Zhu2021Retrieving.md)

    *Fengbin Zhu, Wenqiang Lei, Chao Wang, Jianming Zheng, Soujanya Poria, Tat-Seng Chua*

12. **Survey of Visual Question Answering: Datasets and Techniques.** arXiv 2017 [paper](https://arxiv.org/abs/1705.03865) [bib](/bib/Natural-Language-Processing/Question-Answering/Gupta2017Survey.md)

    *Akshay Kumar Gupta*

13. **Text-based Question Answering from Information Retrieval and Deep Neural Network Perspectives: A Survey.** WIREs Data Mining Knowl. Discov. 2021 [paper](https://arxiv.org/abs/2002.06612) [bib](/bib/Natural-Language-Processing/Question-Answering/Abbasiantaeb2021Text-based.md)

    *Zahra Abbasiantaeb, Saeedeh Momtazi*

14. **Tutorial on Answering Questions about Images with Deep Learning.** arXiv 2016 [paper](https://arxiv.org/abs/1610.01076) [bib](/bib/Natural-Language-Processing/Question-Answering/Malinowski2016Tutorial.md)

    *Mateusz Malinowski, Mario Fritz*

15. **Visual Question Answering using Deep Learning: A Survey and Performance Analysis.** CVIP 2020 [paper](https://arxiv.org/abs/1909.01860) [bib](/bib/Natural-Language-Processing/Question-Answering/Srivastava2020Visual.md)

    *Yash Srivastava, Vaishnav Murali, Shiv Ram Dubey, Snehasis Mukherjee*

#### [Reading Comprehension](#content)

1. **A Survey on Explainability in Machine Reading Comprehension.** arXiv 2020 [paper](http://arxiv.org/pdf/2010.00389.pdf) [bib](/bib/Natural-Language-Processing/Reading-Comprehension/Thayaparan2020A.md)

    *Mokanarangan Thayaparan, Marco Valentino, André Freitas*

2. **A Survey on Machine Reading Comprehension Systems.** arXiv 2020 [paper](https://arxiv.org/abs/2001.01582) [bib](/bib/Natural-Language-Processing/Reading-Comprehension/Baradaran2020A.md)

    *Razieh Baradaran, Razieh Ghiasi, Hossein Amirkhani*

3. **A Survey on Machine Reading Comprehension—Tasks, Evaluation Metrics and Benchmark Datasets.** Applied Sciences 2020 [paper](https://www.mdpi.com/2076-3417/10/21/7640/html) [bib](/bib/Natural-Language-Processing/Reading-Comprehension/Zeng2020A.md)

    *Chengchang Zeng, Shaobo Li, Qin Li, Jie Hu, Jianjun Hu*

4. **A Survey on Neural Machine Reading Comprehension.** arXiv 2019 [paper](https://arxiv.org/abs/1906.03824) [bib](/bib/Natural-Language-Processing/Reading-Comprehension/Qiu2019A.md)

    *Boyu Qiu, Xu Chen, Jungang Xu, Yingfei Sun*

5. **English Machine Reading Comprehension Datasets: A Survey.** EMNLP 2021 [paper](https://arxiv.org/abs/2101.10421) [bib](/bib/Natural-Language-Processing/Reading-Comprehension/Dzendzik2021English.md)

    *Daria Dzendzik, Jennifer Foster, Carl Vogel*

6. **Machine Reading Comprehension: a Literature Review.** arXiv 2019 [paper](https://arxiv.org/abs/1907.01686) [bib](/bib/Natural-Language-Processing/Reading-Comprehension/Zhang2019Machine.md)

    *Xin Zhang, An Yang, Sujian Li, Yizhong Wang*

7. **Machine Reading Comprehension: The Role of Contextualized Language Models and Beyond.** arXiv 2020 [paper](https://arxiv.org/abs/2005.06249) [bib](/bib/Natural-Language-Processing/Reading-Comprehension/Zhang2020Machine.md)

    *Zhuosheng Zhang, Hai Zhao, Rui Wang*

8. **Neural Machine Reading Comprehension: Methods and Trends.** Applied Surface Science 2019 [paper](https://arxiv.org/abs/1907.01118) [bib](/bib/Natural-Language-Processing/Reading-Comprehension/Liu2019Neural.md)

    *Shanshan Liu, Xin Zhang, Sheng Zhang, Hui Wang, Weiming Zhang*

#### [Recommender Systems](#content)

1. **A review on deep learning for recommender systems: challenges and remedies.** Artif. Intell. Rev. 2019 [paper](https://link.springer.com/article/10.1007/s10462-018-9654-y) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Batmaz2019A.md)

    *Zeynep Batmaz, Ali Yürekli, Alper Bilge, Cihan Kaleli*

2. **A Survey of Explanations in Recommender Systems.** ICDE Workshops 2007 [paper](https://ieeexplore.ieee.org/document/4401070) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Tintarev2007A.md)

    *Nava Tintarev, Judith Masthoff*

3. **A survey on Adversarial Recommender Systems: from Attack/Defense strategies to Generative Adversarial Networks.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2005.10322) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Deldjoo2021A.md)

    *Yashar Deldjoo, Tommaso Di Noia, Felice Antonio Merra*

4. **A Survey on Conversational Recommender Systems.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2004.00646) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Jannach2021A.md)

    *Dietmar Jannach, Ahtsham Manzoor, Wanling Cai, Li Chen*

5. **A Survey on Knowledge Graph-Based Recommender Systems.** arXiv 2020 [paper](https://arxiv.org/abs/2003.00911) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Guo2020A.md)

    *Qingyu Guo, Fuzhen Zhuang, Chuan Qin, Hengshu Zhu, Xing Xie, Hui Xiong, Qing He*

6. **A Survey on Personality-Aware Recommendation Systems.** arXiv 2021 [paper](http://arxiv.org/pdf/2101.12153.pdf) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Dhelim2021A.md)

    *Sahraoui Dhelim, Nyothiri Aung, Mohammed Amine Bouras, Huansheng Ning, Erik Cambria*

7. **A Survey on Session-based Recommender Systems.** ACM Comput. Surv. 2022 [paper](https://arxiv.org/pdf/1902.04864.pdf) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Wang2022A.md)

    *Shoujin Wang, Longbing Cao, Yan Wang, Quan Z. Sheng, Mehmet A. Orgun, Defu Lian*

8. **Advances and Challenges in Conversational Recommender Systems: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2101.09459) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Gao2021Advances.md)

    *Chongming Gao, Wenqiang Lei, Xiangnan He, Maarten de Rijke, Tat-Seng Chua*

9. **Are we really making much progress? A worrying analysis of recent neural recommendation approaches.** RecSys 2019 [paper](https://dl.acm.org/doi/10.1145/3298689.3347058) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Dacrema2019Are.md)

    *Maurizio Ferrari Dacrema, Paolo Cremonesi, Dietmar Jannach*

10. **Bias and Debias in Recommender System: A Survey and Future Directions.** arXiv 2020 [paper](https://arxiv.org/abs/2010.03240) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Chen2020Bias.md)

    *Jiawei Chen, Hande Dong, Xiang Wang, Fuli Feng, Meng Wang, Xiangnan He*

11. **Content-based Recommender Systems: State of the Art and Trends.** Recommender Systems Handbook 2011 [paper](https://link.springer.com/chapter/10.1007/978-0-387-85820-3_3) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Lops2011Content-based.md)

    *Pasquale Lops, Marco de Gemmis, Giovanni Semeraro*

12. **Cross Domain Recommender Systems: A Systematic Literature Review.** ACM Comput. Surv. 2017 [paper](https://dl.acm.org/doi/10.1145/3073565) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Khan2017Cross.md)

    *Muhammad Murad Khan, Roliana Ibrahim, Imran Ghani*

13. **Deep Conversational Recommender Systems: A New Frontier for Goal-Oriented Dialogue Systems.** arXiv 2020 [paper](https://arxiv.org/abs/2004.13245) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Tran2020Deep.md)

    *Dai Hoang Tran, Quan Z. Sheng, Wei Emma Zhang, Salma Abdalla Hamad, Munazza Zaib, Nguyen H. Tran, Lina Yao, Nguyen Lu Dang Khoa*

14. **Deep Learning based Recommender System: A Survey and New Perspectives.** ACM Comput. Surv. 2019 [paper](https://arxiv.org/abs/1707.07435) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Zhang2019Deep.md)

    *Shuai Zhang, Lina Yao, Aixin Sun, Yi Tay*

15. **Deep Learning for Matching in Search and Recommendation.** Found. Trends Inf. Retr. 2020 [paper](http://staff.ustc.edu.cn/~hexn/papers/www18-tutorial-deep-matching-paper.pdf) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Xu2020Deep.md)

    *Jun Xu, Xiangnan He, Hang Li*

16. **Deep Learning on Knowledge Graph for Recommender System: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2004.00387) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Gao2020Deep.md)

    *Yang Gao, Yi-Fan Li, Yu Lin, Hang Gao, Latifur Khan*

17. **Diversity in recommender systems – A survey.** Knowledge-Based Systems 2017 [paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705117300680) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Kunavera2017Diversity.md)

    *Matevž Kunavera, Tomaž Požrl*

18. **Explainable Recommendation: A Survey and New Perspectives.** Found. Trends Inf. Retr. 2020 [paper](https://arxiv.org/abs/1804.11192) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Zhang2020Explainable.md)

    *Yongfeng Zhang, Xu Chen*

19. **Graph Learning based Recommender Systems: A Review.** IJCAI 2021 [paper](https://arxiv.org/pdf/2105.06339.pdf) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Wang2021Graph.md)

    *Shoujin Wang, Liang Hu, Yan Wang, Xiangnan He, Quan Z. Sheng, Mehmet A. Orgun, Longbing Cao, Francesco Ricci, Philip S. Yu*

20. **Graph Neural Networks in Recommender Systems: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2011.02260) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Wu2020Graph.md)

    *Shiwen Wu, Wentao Zhang, Fei Sun, Bin Cui*

21. **Hybrid Recommender Systems: Survey and Experiments.** User Model. User Adapt. Interact. 2002 [paper](https://link.springer.com/article/10.1023/A:1021240730564) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Burke2002Hybrid.md)

    *Robin D. Burke*

22. **Knowledge Transfer via Pre-training for Recommendation: A Review and Prospect.** Frontiers Big Data 2021 [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8013982/) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Zeng2021Knowledge.md)

    *Zheni Zeng, Chaojun Xiao, Yuan Yao, Ruobing Xie, Zhiyuan Liu, Fen Lin, Leyu Lin, Maosong Sun*

23. **Recommender systems survey.** Knowledge-Based Systems 2013 [paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705113001044) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Bobadilla2013Recommender.md)

    *Bobadilla J., Ortega F., Hernando A., Gutiérrez A.*

24. **Sequence-Aware Recommender Systems.** ACM Comput. Surv. 2018 [paper](https://arxiv.org/abs/1802.08452) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Quadrana2018Sequence-Aware.md)

    *Massimo Quadrana, Paolo Cremonesi, Dietmar Jannach*

25. **Survey for Trust-aware Recommender Systems: A Deep Learning Perspective.** arXiv 2020 [paper](http://arxiv.org/abs/2004.03774) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Dong2020Survey.md)

    *Manqing Dong, Feng Yuan, Lina Yao, Xianzhi Wang, Xiwei Xu, Liming Zhu*

26. **Toward the next generation of recommender systems: a survey of the state-of-the-art and possible extensions.** IEEE Trans. Knowl. Data Eng. 2005 [paper](https://ieeexplore.ieee.org/abstract/document/1423975) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Adomavicius2005Toward.md)

    *Gediminas Adomavicius, Alexander Tuzhilin*

27. **Use of Deep Learning in Modern Recommendation System: A Summary of Recent Works.** arXiv 2017 [paper](https://arxiv.org/abs/1712.07525) [bib](/bib/Natural-Language-Processing/Recommender-Systems/Singhal2017Use.md)

    *Ayush Singhal, Pradeep Sinha, Rakesh Pant*

#### [Resources and Evaluation](#content)

1. **A Review of Human Evaluation for Style Transfer.** arXiv 2021 [paper](https://arxiv.org/abs/2106.04747 ) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Briakou2021A.md)

    *Eleftheria Briakou, Sweta Agrawal, Ke Zhang, Joel R. Tetreault, Marine Carpuat*

2. **A Short Survey on Sense-Annotated Corpora.** LREC 2020 [paper](https://arxiv.org/abs/1802.04744) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Pasini2020A.md)

    *Tommaso Pasini, José Camacho-Collados*

3. **A Survey of Current Datasets for Vision and Language Research.** EMNLP 2015 [paper](https://arxiv.org/abs/1506.06833) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Ferraro2015A.md)

    *Francis Ferraro, Nasrin Mostafazadeh, Ting-Hao (Kenneth) Huang, Lucy Vanderwende, Jacob Devlin, Michel Galley, Margaret Mitchell*

4. **A Survey of Evaluation Metrics Used for NLG Systems.** arXiv 2020 [paper](https://arxiv.org/abs/2008.12009) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Sai2020A.md)

    *Ananya B. Sai, Akash Kumar Mohankumar, Mitesh M. Khapra*

5. **A Survey of Word Embeddings Evaluation Methods.** arXiv 2018 [paper](https://arxiv.org/abs/1801.09536) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Bakarov2018A.md)

    *Amir Bakarov*

6. **A Survey on Recognizing Textual Entailment as an NLP Evaluation.** arXiv 2020 [paper](https://arxiv.org/pdf/2010.03061.pdf) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Poliak2020A.md)

    *Adam Poliak*

7. **Corpora Annotated with Negation: An Overview.** Comput. Linguistics 2020 [paper](https://watermark.silverchair.com/coli_a_00371.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAqUwggKhBgkqhkiG9w0BBwagggKSMIICjgIBADCCAocGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMwFfpYsXe-j1WZLOYAgEQgIICWK8_os-_3bOw2Egxl-QP8k6_eaUBXbfLcdwSiN1AKd2RyuDFyjIlDYSZ5NTAAsDgDlMCD3TrhPG0ikKF7P7kuegNT5PvSubob_GmEmkrscxcBW6EJJepel-bEup-_A22uwRLCznueNRO_TIF1YCNc5jsTEopV_PzSEeI-vqG3BTbc_EtWxty9udu1sZYsHmXO2i8h7_m5MGt3nCX8aXXNkRPhrmNZ4IHU2moi76_JOuBQb6U6n6SItsdwObWewSPB3eGmx4DmUboNcB-Dv7OJAS9jmWHgsNzsSiRw9lRBcsf1O_0Nkv5YkFSkVNTiCldQ3B1fWgjDN0GWSOTsMS-6Je6keFnovcc8nQnxw-ubXQ57UZYQjZHa8jg6Ea1kOUHJem8uRdc4IMJuKCunIKRJLT1SSLFGYDgehwxQfOQk-H6LOIsbWOaiXwP9aDDqG4a6Pxl_bwnpi8JUp5dQYvqLNteQ-rjGS8FbRvlaV34wL49UAEBwa2DFlkTVhebzCkrzuzN-H3obLkhqnR-LDXbjSQhYOzROGh74Gq-beWVM7boVegN49iq-El7CzRqnoTIzVjtBrp3b-tnaevilOo05l0s2rhFLr-46GRyXgD11UTbz0tCy892aJACw6XYCsRvx2veM2tzBxg5D6a65ev1F3ViYbOlyz99M11QLllIMdoRT1R5fkdEyFrDQh-Q6VCJT3tJAOdlhWCc6kpie4jME3xACsVXSKXIW4q7OCXDHtdvmQnUWWJURJAYZ2Rwfvc9JwQ20jY37wr5ZyyQ8VuiRXwkiiOK4EScHg) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Zafra2020Corpora.md)

    *Salud María Jiménez Zafra, Roser Morante, María Teresa Martín-Valdivia, Luis Alfonso Ureña López*

8. **Critical Survey of the Freely Available Arabic Corpora.** arXiv 2017 [paper](https://arxiv.org/abs/1702.07835) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Zaghouani2017Critical.md)

    *Wajdi Zaghouani*

9. **Recent Advances in Natural Language Inference: A Survey of Benchmarks, Resources, and Approaches.** arXiv 2019 [paper](https://arxiv.org/abs/1904.01172) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Storks2019Recent.md)

    *Shane Storks, Qiaozi Gao, Joyce Y. Chai*

10. **Survey on Evaluation Methods for Dialogue Systems.** Artif. Intell. Rev. 2021 [paper](https://arxiv.org/abs/1905.04071) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Deriu2021Survey.md)

    *Jan Deriu, Álvaro Rodrigo, Arantxa Otegi, Guillermo Echegoyen, Sophie Rosset, Eneko Agirre, Mark Cieliebak*

11. **Survey on Publicly Available Sinhala Natural Language Processing Tools and Research.** arXiv 2019 [paper](https://arxiv.org/abs/1906.02358) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Silva2019Survey.md)

    *Nisansa de Silva*

12. **The Great Misalignment Problem in Human Evaluation of NLP Methods.** arXiv 2021 [paper](https://arxiv.org/abs/2104.05361) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Hämäläinen2021The.md)

    *Mika Hämäläinen, Khalid Al-Najjar*

13. **Towards Standard Criteria for human evaluation of Chatbots: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2105.11197) [bib](/bib/Natural-Language-Processing/Resources-and-Evaluation/Liang2021Towards.md)

    *Hongru Liang, Huaqing Li*

#### [Semantics](#content)

1. **A reproducible survey on word embeddings and ontology-based methods for word similarity: Linear combinations outperform the state of the art.** Eng. Appl. Artif. Intell. 2019 [paper](https://www.sciencedirect.com/science/article/pii/S0952197619301745) [bib](/bib/Natural-Language-Processing/Semantics/Lastra2019A.md)

    *Juan J. Lastra-Díaz, Josu Goikoetxea, Mohamed Ali Hadj Taieb, Ana García-Serrano, Mohamed Ben Aouicha, Eneko Agirre*

2. **A survey of loss functions for semantic segmentation.** CIBCB 2020 [paper](https://arxiv.org/abs/2006.14822) [bib](/bib/Natural-Language-Processing/Semantics/Jadon2020A.md)

    *Shruti Jadon*

3. **A Survey of Paraphrasing and Textual Entailment Methods.** J. Artif. Intell. Res. 2010 [paper](https://arxiv.org/abs/0912.3747) [bib](/bib/Natural-Language-Processing/Semantics/Androutsopoulos2010A.md)

    *Ion Androutsopoulos, Prodromos Malakasiotis*

4. **A Survey of Syntactic-Semantic Parsing Based on Constituent and Dependency Structures.** arXiv 2020 [paper](http://arxiv.org/pdf/2006.11056.pdf) [bib](/bib/Natural-Language-Processing/Semantics/Zhang2020A.md)

    *Meishan Zhang*

5. **A Survey on Semantic Parsing.** AKBC 2019 [paper](https://arxiv.org/pdf/1812.00978) [bib](/bib/Natural-Language-Processing/Semantics/Kamath2019A.md)

    *Aishwarya Kamath, Rajarshi Das*

6. **Argument Linking: A Survey and Forecast.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.08523.pdf) [bib](/bib/Natural-Language-Processing/Semantics/Gantt2021Argument.md)

    *William Gantt*

7. **Corpus-Based Paraphrase Detection Experiments and Review.** Inf. 2020 [paper](https://arxiv.org/abs/2106.00145) [bib](/bib/Natural-Language-Processing/Semantics/Vrbanec2020Corpus-Based.md)

    *Tedo Vrbanec, Ana Mestrovic*

8. **Diachronic word embeddings and semantic shifts: a survey.** COLING 2018 [paper](https://arxiv.org/abs/1806.03537) [bib](/bib/Natural-Language-Processing/Semantics/Kutuzov2018Diachronic.md)

    *Andrey Kutuzov, Lilja Øvrelid, Terrence Szymanski, Erik Velldal*

9. **Distributional Measures of Semantic Distance: A Survey.** arXiv 2012 [paper](https://arxiv.org/abs/1203.1858) [bib](/bib/Natural-Language-Processing/Semantics/Mohammad2012Distributional.md)

    *Saif Mohammad, Graeme Hirst*

10. **Evolution of Semantic Similarity - A Survey.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2004.13820) [bib](/bib/Natural-Language-Processing/Semantics/Chandrasekaran2021Evolution.md)

    *Dhivya Chandrasekaran, Vijay Mago*

11. **Measuring Sentences Similarity: A Survey.** Indian Journal of Science and Technology 2019 [paper](https://arxiv.org/abs/1910.03940) [bib](/bib/Natural-Language-Processing/Semantics/Farouk2019Measuring.md)

    *Mamdouh Farouk*

12. **Semantic search on text and knowledge bases.** Found. Trends Inf. Retr. 2016 [paper](http://ceur-ws.org/Vol-1883/invited6.pdf) [bib](/bib/Natural-Language-Processing/Semantics/Bast2016Semantic.md)

    *Hannah Bast, Björn Buchhold, Elmar Haussmann*

13. **Semantics, Modelling, and the Problem of Representation of Meaning - a Brief Survey of Recent Literature.** arXiv 2014 [paper](https://arxiv.org/abs/1402.7265) [bib](/bib/Natural-Language-Processing/Semantics/Gal2014Semantics.md)

    *Yarin Gal*

14. **Survey of Computational Approaches to Lexical Semantic Change.** arXiv 2018 [paper](https://arxiv.org/abs/1811.06278) [bib](/bib/Natural-Language-Processing/Semantics/Tahmasebi2018Survey.md)

    *Nina Tahmasebi, Lars Borin, Adam Jatowt*

15. **The Knowledge Acquisition Bottleneck Problem in Multilingual Word Sense Disambiguation.** IJCAI 2020 [paper](https://www.ijcai.org/Proceedings/2020/687) [bib](/bib/Natural-Language-Processing/Semantics/Pasini2020The.md)

    *Tommaso Pasini*

16. **Word Sense disambiguation: A Survey.** ACM Comput. Surv. 2009 [paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.153.8457&rep=rep1&type=pdf) [bib](/bib/Natural-Language-Processing/Semantics/Navigli2009Word.md)

    *Roberto Navigli*

17. **Word sense disambiguation: a survey.** IJCTCM 2015 [paper](https://arxiv.org/abs/1508.01346) [bib](/bib/Natural-Language-Processing/Semantics/Pal2015Word.md)

    *Alok Ranjan Pal, Diganta Saha*

#### [Sentiment Analysis, Stylistic Analysis and Argument Mining](#content)

1. **360 degree view of cross-domain opinion classification: a survey.** Artif. Intell. Rev. 2021 [paper](https://link.springer.com/article/10.1007/s10462-020-09884-9) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Singh2021360.md)

    *Rahul Kumar Singh, Manoj Kumar Sachan, R. B. Patel*

2. **A Comprehensive Survey on Aspect Based Sentiment Analysis.** arXiv 2020 [paper](https://arxiv.org/abs/2006.04611) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Yadav2020A.md)

    *Kaustubh Yadav*

3. **A Survey of Sentiment Analysis in Social Media.** Knowl. Inf. Syst. 2019 [paper](http://cse.iitkgp.ac.in/~saptarshi/courses/socomp2020a/sentiment-analysis-survey-yue2019.pdf) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Yue2019A.md)

    *Lin Yue, Weitong Chen, Xue Li, Wanli Zuo, Minghao Yin*

4. **A Survey on Sentiment and Emotion Analysis for Computational Literary Studies.** ZFDG 2019 [paper](https://arxiv.org/abs/1808.03137) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Kim2019A.md)

    *Evgeny Kim, Roman Klinger*

5. **Beneath the Tip of the Iceberg: Current Challenges and New Directions in Sentiment Analysis Research.** arXiv 2020 [paper](https://arxiv.org/abs/2005.00357) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Poria2020Beneath.md)

    *Soujanya Poria, Devamanyu Hazarika, Navonil Majumder, Rada Mihalcea*

6. **Deep Learning for Aspect-Level Sentiment Classification: Survey, Vision, and Challenges.** IEEE Access 2019 [paper](https://ieeexplore.ieee.org/document/8726353) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Zhou2019Deep.md)

    *Jie Zhou, Jimmy Xiangji Huang, Qin Chen, Qinmin Vivian Hu, Tingting Wang, Liang He*

7. **Deep Learning for Sentiment Analysis : A Survey.** arXiv 2018 [paper](https://arxiv.org/abs/1801.07883) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Zhang2018Deep.md)

    *Lei Zhang, Shuai Wang, Bing Liu*

8. **Emotion Recognition in Conversation: Research Challenges, Datasets, and Recent Advances.** IEEE Access 2019 [paper](https://ieeexplore.ieee.org/abstract/document/8764449) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Poria2019Emotion.md)

    *Soujanya Poria, Navonil Majumder, Rada Mihalcea, Eduard H. Hovy*

9. **Fine-grained Financial Opinion Mining: A Survey and Research Agenda.** arXiv 2020 [paper](https://arxiv.org/pdf/2005.01897.pdf) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Chen2020Fine-grained.md)

    *Chung-Chi Chen, Hen-Hsen Huang, Hsin-Hsi Chen*

10. **On Positivity Bias in Negative Reviews.** ACL 2021 [paper](https://arxiv.org/abs/2106.12056) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Aithal2021On.md)

    *Madhusudhan Aithal, Chenhao Tan*

11. **Sarcasm Detection: A Comparative Study.** arXiv 2021 [paper](https://arxiv.org/abs/2107.02276) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Yaghoobian2021Sarcasm.md)

    *Hamed Yaghoobian, Hamid R. Arabnia, Khaled Rasheed*

12. **Sentiment analysis algorithms and applications: A survey.** Ain Shams Engineering Journal 2014 [paper](https://www.sciencedirect.com/science/article/pii/S2090447914000550) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Medhat2014Sentiment.md)

    *Walaa Medhat, Ahmed Hassan, Hoda Korashy*

13. **Sentiment analysis for Arabic language: A brief survey of approaches and techniques.** arXiv 2018 [paper](https://arxiv.org/abs/1809.02782) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Alrefai2018Sentiment.md)

    *Mo'ath Alrefai, Hossam Faris, Ibrahim Aljarah*

14. **Sentiment Analysis of Czech Texts: An Algorithmic Survey.** ICAART 2019 [paper](https://arxiv.org/abs/1901.02780) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Çano2019Sentiment.md)

    *Erion Çano, Ondrej Bojar*

15. **Sentiment Analysis of Twitter Data: A Survey of Techniques.** IJCAI 2016 [paper](https://arxiv.org/abs/1601.06971) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Kharde2016Sentiment.md)

    *Vishal.A.Kharde, Prof. Sheetal.Sonawane*

16. **Sentiment Analysis on YouTube: A Brief Survey.** arXiv 2015 [paper](https://arxiv.org/abs/1511.09142) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Asghar2015Sentiment.md)

    *Muhammad Zubair Asghar, Shakeel Ahmad, Afsana Marwat, Fazal Masood Kundi*

17. **Sentiment/Subjectivity Analysis Survey for Languages other than English.** Soc. Netw. Anal. Min. 2016 [paper](https://arxiv.org/abs/1601.00087) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Korayem2016SentimentSubjectivity.md)

    *Mohammed Korayem, Khalifeh AlJadda, David J. Crandall*

18. **Towards Argument Mining for Social Good: A Survey.** ACL 2021 [paper](https://aclanthology.org/2021.acl-long.107.pdf) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Vecchi2021Towards.md)

    *Eva Maria Vecchi, Neele Falk, Iman Jundi, Gabriella Lapesa*

19. **Word Embeddings for Sentiment Analysis: A Comprehensive Empirical Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1902.00753) [bib](/bib/Natural-Language-Processing/Sentiment-Analysis,-Stylistic-Analysis-and-Argument-Mining/Çano2019Word.md)

    *Erion Çano, Maurizio Morisio*

#### [Speech and Multimodality](#content)

1. **A Comprehensive Survey on Cross-modal Retrieval.** arXiv 2016 [paper](https://arxiv.org/abs/1607.06215) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Wang2016A.md)

    *Kaiye Wang, Qiyue Yin, Wei Wang, Shu Wu, Liang Wang*

2. **A Multimodal Memes Classification: A Survey and Open Research Issues.** arXiv 2020 [paper](https://arxiv.org/abs/2009.08395) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Afridi2020A.md)

    *Tariq Habib Afridi, Aftab Alam, Muhammad Numan Khan, Jawad Khan, Young-Koo Lee*

3. **A Survey and Taxonomy of Adversarial Neural Networks for Text-to-Image Synthesis.** WIREs Data Mining Knowl. Discov. 2020 [paper](https://arxiv.org/abs/1910.09399) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Agnese2020A.md)

    *Jorge Agnese, Jonathan Herrera, Haicheng Tao, Xingquan Zhu*

4. **A Survey of Code-switched Speech and Language Processing.** arXiv 2019 [paper](https://arxiv.org/abs/1904.00784) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Sitaram2019A.md)

    *Sunayana Sitaram, Khyathi Raghavi Chandu, Sai Krishna Rallabandi, Alan W. Black*

5. **A Survey of Deep Learning Approaches for OCR and Document Understanding.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.13534.pdf) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Subramani2020A.md)

    *Nishant Subramani, Alexandre Matton, Malcolm Greaves, Adrian Lam*

6. **A Survey of Recent DNN Architectures on the TIMIT Phone Recognition Task.** TSD 2018 [paper](https://arxiv.org/abs/1806.07974) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Michálek2018A.md)

    *Josef Michálek, Jan Vanek*

7. **A Survey of Voice Translation Methodologies - Acoustic Dialect Decoder.** ICICES 2016 [paper](https://arxiv.org/abs/1610.03934) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Krupakar2016A.md)

    *Hans Krupakar, Keerthika Rajvel, Bharathi B, Angel Deborah S, Vallidevi Krishnamurthy*

8. **A Survey on Neural Speech Synthesis.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.15561.pdf) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Tan2021A.md)

    *Xu Tan, Tao Qin, Frank K. Soong, Tie-Yan Liu*

9. **A Survey on Spoken Language Understanding: Recent Advances and New Frontiers.** IJCAI 2021 [paper](https://arxiv.org/abs/2103.03095) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Qin2021A.md)

    *Libo Qin, Tianbao Xie, Wanxiang Che, Ting Liu*

10. **A Thorough Review on Recent Deep Learning Methodologies for Image Captioning.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.13114.pdf) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Elhagry2021A.md)

    *Ahmed Elhagry, Karima Kadaoui*

11. **Accented Speech Recognition: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2104.10747) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Hinsvark2021Accented.md)

    *Arthur Hinsvark, Natalie Delworth, Miguel Del Rio, Quinten McNamara, Joshua Dong, Ryan Westerman, Michelle Huang, Joseph Palakapilly, Jennifer Drexler, Ilya Pirkin, Nishchal Bhandari, Miguel Jette*

12. **Automatic Description Generation from Images: A Survey of Models, Datasets, and Evaluation Measures.** J. Artif. Intell. Res. 2016 [paper](https://arxiv.org/abs/1601.03896) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Bernardi2016Automatic.md)

    *Raffaella Bernardi, Ruket Çakici, Desmond Elliott, Aykut Erdem, Erkut Erdem, Nazli Ikizler-Cinbis, Frank Keller, Adrian Muscat, Barbara Plank*

13. **Automatic Speech Recognition using limited vocabulary: A survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.10254.pdf) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Fendji2021Automatic.md)

    *Jean Louis Ebongue Kedieng Fendji, Diane M. Tala, Blaise Omer Yenke, Marcellin Atemkeng*

14. **Deep Emotion Recognition in Dynamic Data using Facial, Speech and Textual Cues: A Survey.** TechRxiv 2021 [paper](https://www.techrxiv.org/articles/preprint/Deep_Emotion_Recognition_in_Dynamic_Data_using_Facial_Speech_and_Textual_Cues_A_Survey/15184302/1) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Zhang2021Deep.md)

    *Tao ZhangTao Zhang, Zhenhua Tan*

15. **Image Captioning based on Deep Learning Methods: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1905.08110) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Wang2019Image.md)

    *Yiyu Wang, Jungang Xu, Yingfei Sun, Ben He*

16. **Multimodal Intelligence: Representation Learning, Information Fusion, and Applications.** IEEE J. Sel. Top. Signal Process. 2020 [paper](https://ieeexplore.ieee.org/abstract/document/9068414) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Zhang2020Multimodal.md)

    *Chao Zhang, Zichao Yang, Xiaodong He, Li Deng*

17. **Multimodal Machine Learning: A Survey and Taxonomy.** IEEE Trans. Pattern Anal. Mach. Intell. 2019 [paper](https://arxiv.org/abs/1705.09406) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Baltrusaitis2019Multimodal.md)

    *Tadas Baltrusaitis, Chaitanya Ahuja, Louis-Philippe Morency*

18. **Perspectives and Prospects on Transformer Architecture for Cross-Modal Tasks with Language and Vision.** arXiv 2021 [paper](https://arxiv.org/abs/2103.04037) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Shin2021Perspectives.md)

    *Andrew Shin, Masato Ishii, Takuya Narihira*

19. **Recent Advances and Trends in Multimodal Deep Learning: A Review.** arXiv 2021 [paper](https://arxiv.org/pdf/2105.11087.pdf) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Summaira2021Recent.md)

    *Jabeen Summaira, Xi Li, Amin Muhammad Shoib, Songyuan Li, Jabbar Abdul*

20. **Referring Expression Comprehension: A Survey of Methods and Datasets.** IEEE Trans. Multim. 2021 [paper](https://arxiv.org/abs/2007.09554) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Qiao2021Referring.md)

    *Yanyuan Qiao, Chaorui Deng, Qi Wu*

21. **Review of end-to-end speech synthesis technology based on deep learning.** arXiv 2021 [paper](https://arxiv.org/abs/2104.09995) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Mu2021Review.md)

    *Zhaoxi Mu, Xinyu Yang, Yizhuo Dong*

22. **Speech and Language Processing.** Stanford 2019 [paper](http://web.stanford.edu/~jurafsky/slp3/) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Jurafsky2019Speech.md)

    *Dan Jurafsky, James H. Martin*

23. **Text Detection and Recognition in the Wild: A Review.** arXiv 2020 [paper](https://arxiv.org/abs/2006.04305) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Raisi2020Text.md)

    *Zobeir Raisi, Mohamed A. Naiel, Paul W. Fieguth, Steven Wardell, John S. Zelek*

24. **Text Recognition in the Wild: A Survey.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2005.03492) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Chen2021Text.md)

    *Xiaoxue Chen, Lianwen Jin, Yuanzhi Zhu, Canjie Luo, Tianwei Wang*

25. **Thank you for Attention: A survey on Attention-based Artificial Neural Networks for Automatic Speech Recognition.** arXiv 2021 [paper](https://arxiv.org/abs/2102.07259) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Karmakar2021Thank.md)

    *Priyabrata Karmakar, Shyh Wei Teng, Guojun Lu*

26. **Unsupervised Automatic Speech Recognition: A Review.** arXiv 2021 [paper](https://arxiv.org/abs/2106.04897 ) [bib](/bib/Natural-Language-Processing/Speech-and-Multimodality/Aldarmaki2021Unsupervised.md)

    *Hanan Aldarmaki, Asad Ullah, Nazar Zaki*

#### [Summarization](#content)

1. **A Survey of the State-of-the-Art Models in Neural Abstractive Text Summarization.** IEEE Access 2021 [paper](https://ieeexplore.ieee.org/abstract/document/9328413/) [bib](/bib/Natural-Language-Processing/Summarization/Syed2021A.md)

    *Ayesha Ayub Syed, Ford Lumban Gaol, Tokuro Matsuo*

2. **A Survey on Dialogue Summarization: Recent Advances and New Frontiers.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.03175) [bib](/bib/Natural-Language-Processing/Summarization/Feng2021A.md)

    *Xiachong Feng, Xiaocheng Feng, Bing Qin*

3. **A Survey on Neural Network-Based Summarization Methods.** arXiv 2018 [paper](https://arxiv.org/abs/1804.04589) [bib](/bib/Natural-Language-Processing/Summarization/Dong2018A.md)

    *Yue Dong*

4. **Abstractive Summarization: A Survey of the State of the Art.** AAAI 2019 [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5056) [bib](/bib/Natural-Language-Processing/Summarization/Lin2019Abstractive.md)

    *Hui Lin, Vincent Ng*

5. **Automated text summarisation and evidence-based medicine: A survey of two domains.** arXiv 2017 [paper](https://arxiv.org/abs/1706.08162) [bib](/bib/Natural-Language-Processing/Summarization/Sarker2017Automated.md)

    *Abeed Sarker, Diego Mollá Aliod, Cécile Paris*

6. **Automatic Keyword Extraction for Text Summarization: A Survey.** arXiv 2017 [paper](https://arxiv.org/abs/1704.03242) [bib](/bib/Natural-Language-Processing/Summarization/Bharti2017Automatic.md)

    *Santosh Kumar Bharti, Korra Sathya Babu*

7. **Automatic summarization of scientific articles: A survey.** Journal of King Saud University - Computer and Information Sciences 2020 [paper](https://www.sciencedirect.com/science/article/pii/S1319157820303554) [bib](/bib/Natural-Language-Processing/Summarization/Altmami2020Automatic.md)

    *Nouf Ibrahim Altmami, Mohamed El Bachir Menai*

8. **Deep Learning Based Abstractive Text Summarization: Approaches, Datasets, Evaluation Measures, and Challenges.** Mathematical Problems in Engineering 2020 [paper](https://www.hindawi.com/journals/mpe/2020/9365340/) [bib](/bib/Natural-Language-Processing/Summarization/Suleiman2020Deep.md)

    *Dima Suleiman, Arafat Awajan*

9. **From Standard Summarization to New Tasks and Beyond: Summarization with Manifold Information.** IJCAI 2020 [paper](https://arxiv.org/abs/2005.04684) [bib](/bib/Natural-Language-Processing/Summarization/Gao2020From.md)

    *Shen Gao, Xiuying Chen, Zhaochun Ren, Dongyan Zhao, Rui Yan*

10. **How to Evaluate a Summarizer: Study Design and Statistical Analysis for Manual Linguistic Quality Evaluation.** EACL 2021 [paper](https://aclanthology.org/2021.eacl-main.160.pdf) [bib](/bib/Natural-Language-Processing/Summarization/Steen2021How.md)

    *Julius Steen, Katja Markert*

11. **Neural Abstractive Text Summarization with Sequence-to-Sequence Models.** Trans. Data Sci. 2021 [paper](https://arxiv.org/abs/1812.02303) [bib](/bib/Natural-Language-Processing/Summarization/Shi2021Neural.md)

    *Tian Shi, Yaser Keneshloo, Naren Ramakrishnan, Chandan K. Reddy*

12. **Recent automatic text summarization techniques: a survey.** Artif. Intell. Rev. 2017 [paper](https://link.springer.com/article/10.1007%2Fs10462-016-9475-9) [bib](/bib/Natural-Language-Processing/Summarization/Gambhir2017Recent.md)

    *Mahak Gambhir, Vishal Gupta*

13. **Text Summarization Techniques: A Brief Survey.** arXiv 2017 [paper](https://arxiv.org/abs/1707.02268) [bib](/bib/Natural-Language-Processing/Summarization/Allahyari2017Text.md)

    *Mehdi Allahyari, Seyed Amin Pouriyeh, Mehdi Assefi, Saeid Safaei, Elizabeth D. Trippe, Juan B. Gutierrez, Krys J. Kochut*

14. **The Factual Inconsistency Problem in Abstractive Text Summarization: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2104.14839) [bib](/bib/Natural-Language-Processing/Summarization/Huang2021The.md)

    *Yi-Chong Huang, Xia-Chong Feng, Xiao-Cheng Feng, Bing Qin*

15. **What Have We Achieved on Text Summarization?.** EMNLP 2020 [paper](https://aclanthology.org/2020.emnlp-main.33.pdf) [bib](/bib/Natural-Language-Processing/Summarization/Huang2020What.md)

    *Dandan Huang, Leyang Cui, Sen Yang, Guangsheng Bao, Kun Wang, Jun Xie, Yue Zhang*

16. **Multi-document Summarization via Deep Learning Techniques: A Survey.** arXiv 2020 [paper](http://arxiv.org/pdf/2011.04843.pdf) [bib](/bib/Natural-Language-Processing/Summarization/Ma2020Multi-document.md)

    *Congbo Ma, Wei Emma Zhang, Mingyu Guo, Hu Wang, Quan Z. Sheng*

#### [Tagging, Chunking, Syntax and Parsing](#content)

1. **A survey of cross-lingual features for zero-shot cross-lingual semantic parsing.** arXiv 2019 [paper](https://arxiv.org/abs/1908.10461) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Yang2019A.md)

    *Jingfeng Yang, Federico Fancellu, Bonnie L. Webber*

2. **A Survey of Syntactic-Semantic Parsing Based on Constituent and Dependency Structures.** arXiv 2020 [paper](http://arxiv.org/pdf/2006.11056.pdf) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Zhang2020A.md)

    *Meishan Zhang*

3. **A Survey on Recent Advances in Sequence Labeling from Deep Learning Models.** arXiv 2020 [paper](https://arxiv.org/abs/2011.06727) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/He2020A.md)

    *Zhiyong He, Zanbo Wang, Wei Wei, Shanshan Feng, Xianling Mao, Sheng Jiang*

4. **A Survey on Semantic Parsing.** AKBC 2019 [paper](https://arxiv.org/abs/1812.00978) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Kamath2019A.md)

    *Aishwarya Kamath, Rajarshi Das*

5. **A Survey on Semantic Parsing from the perspective of Compositionality.** arXiv 2020 [paper](https://arxiv.org/pdf/2009.14116.pdf) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Kumar2020A.md)

    *Pawan Kumar, Srikanta Bedathur*

6. **Context Dependent Semantic Parsing: A Survey.** COLING 2020 [paper](https://arxiv.org/pdf/2011.00797.pdf) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Li2020Context.md)

    *Zhuang Li, Lizhen Qu, Gholamreza Haffari*

7. **Design Challenges and Misconceptions in Neural Sequence Labeling.** COLING 2018 [paper](https://arxiv.org/abs/1806.04470) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Yang2018Design.md)

    *Jie Yang, Shuailong Liang, Yue Zhang*

8. **Part‐of‐speech tagging.** Wiley Interdisciplinary Reviews: Computational Statistics 2011 [paper](https://wires.onlinelibrary.wiley.com/doi/epdf/10.1002/wics.195) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Martinez2011Part‐of‐speech.md)

    *Angel R. Martinez*

9. **Sememe knowledge computation: a review of recent advances in application and expansion of sememe knowledge bases.** Frontiers Comput. Sci. 2021 [paper](https://link.springer.com/article/10.1007/s11704-020-0002-4) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Qi2021Sememe.md)

    *Fanchao Qi, Ruobing Xie, Yuan Zang, Zhiyuan Liu, Maosong Sun*

10. **Syntactic Parsing: A Survey.** Computers and the Humanities 1989 [paper](https://link.springer.com/article/10.1007/BF00058766) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Sanders1989Syntactic.md)

    *Alton F. Sanders and Ruth H. Sanders*

11. **Syntax Representation in Word Embeddings and Neural Networks - A Survey.** ITAT 2020 [paper](http://arxiv.org/pdf/2010.01063.pdf) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Limisiewicz2020Syntax.md)

    *Tomasz Limisiewicz, David Marecek*

12. **The Gap of Semantic Parsing: A Survey on Automatic Math Word Problem Solvers.** IEEE Trans. Pattern Anal. Mach. Intell. 2020 [paper](https://arxiv.org/abs/1808.07290) [bib](/bib/Natural-Language-Processing/Tagging,-Chunking,-Syntax-and-Parsing/Zhang2020The.md)

    *Dongxiang Zhang, Lei Wang, Luming Zhang, Bing Tian Dai, Heng Tao Shen*

#### [Text Classification](#content)

1. **A Survey of Active Learning for Text Classification using Deep Neural Networks.** arXiv 2020 [paper](https://arxiv.org/abs/2008.07267) [bib](/bib/Natural-Language-Processing/Text-Classification/Schröder2020A.md)

    *Christopher Schröder, Andreas Niekler*

2. **A Survey of Naïve Bayes Machine Learning approach in Text Document Classification.** IJCSIS 2010 [paper](https://arxiv.org/abs/1003.1795) [bib](/bib/Natural-Language-Processing/Text-Classification/Vidhya2010A.md)

    *K. A. Vidhya, G. Aghila*

3. **A Survey on Data Augmentation for Text Classification.** arXiv 2021 [paper](https://arxiv.org/abs/2107.03158) [bib](/bib/Natural-Language-Processing/Text-Classification/Bayer2021A.md)

    *Markus Bayer, Marc-André Kaufhold, Christian Reuter*

4. **A Survey on Natural Language Processing for Fake News Detection.** LREC 2020 [paper](https://arxiv.org/abs/1811.00770) [bib](/bib/Natural-Language-Processing/Text-Classification/Oshikawa2020A.md)

    *Ray Oshikawa, Jing Qian, William Yang Wang*

5. **A survey on phrase structure learning methods for text classification.** IJNLC 2014 [paper](https://arxiv.org/abs/1406.5598) [bib](/bib/Natural-Language-Processing/Text-Classification/Prasad2014A.md)

    *Reshma Prasad, Mary Priya Sebastian*

6. **A Survey on Stance Detection for Mis- and Disinformation Identification.** arXiv 2021 [paper](https://arxiv.org/abs/2103.00242) [bib](/bib/Natural-Language-Processing/Text-Classification/Hardalov2021A.md)

    *Momchil Hardalov, Arnav Arora, Preslav Nakov, Isabelle Augenstein*

7. **A Survey on Text Classification: From Shallow to Deep Learning.** arXiv 2020 [paper](https://arxiv.org/pdf/2008.00364.pdf) [bib](/bib/Natural-Language-Processing/Text-Classification/Li2020A.md)

    *Qian Li, Hao Peng, Jianxin Li, Congying Xia, Renyu Yang, Lichao Sun, Philip S. Yu, Lifang He*

8. **Automatic Language Identification in Texts: A Survey.** J. Artif. Intell. Res. 2019 [paper](https://arxiv.org/abs/1804.08186) [bib](/bib/Natural-Language-Processing/Text-Classification/Jauhiainen2019Automatic.md)

    *Tommi Jauhiainen, Marco Lui, Marcos Zampieri, Timothy Baldwin, Krister Lindén*

9. **Deep Learning-based Text Classification: A Comprehensive Review.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2004.03705) [bib](/bib/Natural-Language-Processing/Text-Classification/Minaee2021Deep.md)

    *Shervin Minaee, Nal Kalchbrenner, Erik Cambria, Narjes Nikzad, Meysam Chenaghlu, Jianfeng Gao*

10. **Fake News Detection using Stance Classification: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1907.00181) [bib](/bib/Natural-Language-Processing/Text-Classification/Lillie2019Fake.md)

    *Anders Edelbo Lillie, Emil Refsgaard Middelboe*

11. **Semantic text classification: A survey of past and recent advances.** Inf. Process. Manag. 2018 [paper](https://www.sciencedirect.com/science/article/abs/pii/S0306457317305757) [bib](/bib/Natural-Language-Processing/Text-Classification/Altinel2018Semantic.md)

    *Berna Altinel, Murat Can Ganiz*

12. **Text Classification Algorithms: A Survey.** Inf. 2019 [paper](https://arxiv.org/abs/1904.08067) [bib](/bib/Natural-Language-Processing/Text-Classification/Kowsari2019Text.md)

    *Kamran Kowsari, Kiana Jafari Meimandi, Mojtaba Heidarysafa, Sanjana Mendu, Laura E. Barnes, Donald E. Brown*

#### [Architectures](#content)

1. **A Practical Survey on Faster and Lighter Transformers.** arXiv 2021 [paper](https://arxiv.org/pdf/2103.14636.pdf) [bib](/bib/Machine-Learning/Architectures/Fournier2021A.md)

    *Quentin Fournier, Gaétan Marceau Caron, Daniel Aloise*

2. **A Review of Binarized Neural Networks.** Electronics 2019 [paper](http://www.socolar.com/Article/Index?aid=100010075063&jid=100000022108) [bib](/bib/Machine-Learning/Architectures/Simons2019A.md)

    *Taylor Simons, Dah-Jye Lee*

3. **A State-of-the-Art Survey on Deep Learning Theory and Architectures.** Electronics 2019 [paper](https://www.mdpi.com/2079-9292/8/3/292) [bib](/bib/Machine-Learning/Architectures/Alom2019A.md)

    *Md Zahangir Alom, Tarek M. Taha, Chris Yakopcic, Stefan Westberg, Paheding Sidike, Mst Shamima Nasrin, Mahmudul Hasan, Brian C. Van Essen, Abdul A. S. Awwal and Vijayan K. Asari*

4. **A Survey of Convolutional Neural Networks: Analysis, Applications, and Prospects.** arXiv 2020 [paper](https://arxiv.org/abs/2004.02806) [bib](/bib/Machine-Learning/Architectures/Li2020A.md)

    *Zewen Li, Wenjie Yang, Shouheng Peng, Fan Liu*

5. **A Survey of End-to-End Driving: Architectures and Training Methods.** arXiv 2020 [paper](https://arxiv.org/abs/2003.06404) [bib](/bib/Machine-Learning/Architectures/Tampuu2020A.md)

    *Ardi Tampuu, Maksym Semikin, Naveed Muhammad, Dmytro Fishman, Tambet Matiisen*

6. **A Survey of Transformers.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.04554.pdf) [bib](/bib/Machine-Learning/Architectures/Lin2021A.md)

    *Tianyang Lin, Yuxin Wang, Xiangyang Liu, Xipeng Qiu*

7. **A Survey on Activation Functions and their relation with Xavier and He Normal Initialization.** arXiv 2020 [paper](https://arxiv.org/abs/2004.06632) [bib](/bib/Machine-Learning/Architectures/Datta2020A.md)

    *Leonid Datta*

8. **A Survey on Latent Tree Models and Applications.** J. Artif. Intell. Res. 2013 [paper](https://arxiv.org/abs/1402.0577) [bib](/bib/Machine-Learning/Architectures/Mourad2013A.md)

    *Raphaël Mourad, Christine Sinoquet, Nevin Lianwen Zhang, Tengfei Liu, Philippe Leray*

9. **A survey on modern trainable activation functions.** Neural Networks 2021 [paper](https://arxiv.org/abs/2005.00817) [bib](/bib/Machine-Learning/Architectures/Apicella2021A.md)

    *Andrea Apicella, Francesco Donnarumma, Francesco Isgrò, Roberto Prevete*

10. **A Survey on Vision Transformer.** arXiv 2020 [paper](https://arxiv.org/abs/2012.12556) [bib](/bib/Machine-Learning/Architectures/Han2020A.md)

    *Kai Han, Yunhe Wang, Hanting Chen, Xinghao Chen, Jianyuan Guo, Zhenhua Liu, Yehui Tang, An Xiao, Chunjing Xu, Yixing Xu, Zhaohui Yang, Yiman Zhang, Dacheng Tao*

11. **An Attentive Survey of Attention Models.** ACM Trans. Intell. Syst. Technol. 2021 [paper](https://arxiv.org/abs/1904.02874) [bib](/bib/Machine-Learning/Architectures/Chaudhari2021An.md)

    *Sneha Chaudhari, Varun Mithal, Gungor Polatkan, Rohan Ramanath*

12. **Attention mechanisms and deep learning for machine vision: A survey of the state of the art.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.07550.pdf) [bib](/bib/Machine-Learning/Architectures/Hafiz2021Attention.md)

    *Abdul Mueed Hafiz, Shabir Ahmad Parah, Rouf Ul Alam Bhat*

13. **Big Networks: A Survey.** Comput. Sci. Rev. 2020 [paper](https://arxiv.org/abs/2008.03638) [bib](/bib/Machine-Learning/Architectures/Bedru2020Big.md)

    *Hayat Dino Bedru, Shuo Yu, Xinru Xiao, Da Zhang, Liangtian Wan, He Guo, Feng Xia*

14. **Binary Neural Networks: A Survey.** Pattern Recognit. 2020 [paper](https://arxiv.org/abs/2004.03333) [bib](/bib/Machine-Learning/Architectures/Qin2020Binary.md)

    *Haotong Qin, Ruihao Gong, Xianglong Liu, Xiao Bai, Jingkuan Song, Nicu Sebe*

15. **Deep Echo State Network (DeepESN): A Brief Survey.** arXiv 2017 [paper](https://arxiv.org/abs/1712.04323) [bib](/bib/Machine-Learning/Architectures/Gallicchio2017Deep.md)

    *Claudio Gallicchio, Alessio Micheli*

16. **Deep Tree Transductions - A Short Survey.** INNSBDDL 2019 [paper](https://arxiv.org/abs/1902.01737) [bib](/bib/Machine-Learning/Architectures/Bacciu2019Deep.md)

    *Davide Bacciu, Antonio Bruno*

17. **Efficient Transformers: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2009.06732) [bib](/bib/Machine-Learning/Architectures/Tay2020Efficient.md)

    *Yi Tay, Mostafa Dehghani, Dara Bahri, Donald Metzler*

18. **Pooling Methods in Deep Neural Networks, a Review.** arXiv 2020 [paper](https://arxiv.org/abs/2009.07485) [bib](/bib/Machine-Learning/Architectures/Gholamalinezhad2020Pooling.md)

    *Hossein Gholamalinezhad, Hossein Khosravi*

19. **Position Information in Transformers: An Overview.** arXiv 2021 [paper](https://arxiv.org/abs/2102.11090) [bib](/bib/Machine-Learning/Architectures/Dufter2021Position.md)

    *Philipp Dufter, Martin Schmitt, Hinrich Schütze*

20. **Recent Advances in Convolutional Neural Networks.** Pattern Recognit. 2018 [paper](https://arxiv.org/abs/1512.07108) [bib](/bib/Machine-Learning/Architectures/Gu2018Recent.md)

    *Jiuxiang Gu, Zhenhua Wang, Jason Kuen, Lianyang Ma, Amir Shahroudy, Bing Shuai, Ting Liu, Xingxing Wang, Gang Wang, Jianfei Cai, Tsuhan Chen*

21. **Sum-product networks: A survey.** arXiv 2020 [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9363463) [bib](/bib/Machine-Learning/Architectures/París2020Sum-product.md)

    *Iago París, Raquel Sánchez-Cauce, Francisco Javier Díez*

22. **Survey of Dropout Methods for Deep Neural Networks.** arXiv 2019 [paper](https://arxiv.org/abs/1904.13310) [bib](/bib/Machine-Learning/Architectures/Labach2019Survey.md)

    *Alex Labach, Hojjat Salehinejad, Shahrokh Valaee*

23. **Survey on the attention based RNN model and its applications in computer vision.** arXiv 2016 [paper](https://arxiv.org/abs/1601.06823) [bib](/bib/Machine-Learning/Architectures/Wang2016Survey.md)

    *Feng Wang, David M. J. Tax*

24. **The History Began from AlexNet: A Comprehensive Survey on Deep Learning Approaches.** arXiv 2018 [paper](https://arxiv.org/abs/1803.01164) [bib](/bib/Machine-Learning/Architectures/Alom2018The.md)

    *Md. Zahangir Alom, Tarek M. Taha, Christopher Yakopcic, Stefan Westberg, Paheding Sidike, Mst Shamima Nasrin, Brian C. Van Essen, Abdul A. S. Awwal, Vijayan K. Asari*

25. **The NLP Cookbook: Modern Recipes for Transformer based Deep Learning Architectures.** IEEE Access 2021 [paper](https://arxiv.org/pdf/2104.10640.pdf) [bib](/bib/Machine-Learning/Architectures/Singh2021The.md)

    *Sushant Singh, Ausif Mahmood*

26. **Transformers in Vision: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2101.01169) [bib](/bib/Machine-Learning/Architectures/Khan2021Transformers.md)

    *Salman H. Khan, Muzammal Naseer, Munawar Hayat, Syed Waqas Zamir, Fahad Shahbaz Khan, Mubarak Shah*

27. **Understanding LSTM - a tutorial into Long Short-Term Memory Recurrent Neural Networks.** arXiv 2019 [paper](https://arxiv.org/abs/1909.09586) [bib](/bib/Machine-Learning/Architectures/Staudemeyer2019Understanding.md)

    *Ralf C. Staudemeyer, Eric Rothstein Morris*

#### [AutoML](#content)

1. **A Comprehensive Survey of Neural Architecture Search: Challenges and Solutions.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2006.02903) [bib](/bib/Machine-Learning/AutoML/Ren2021A.md)

    *Pengzhen Ren, Yun Xiao, Xiaojun Chang, Poyao Huang, Zhihui Li, Xiaojiang Chen, Xin Wang*

2. **A Comprehensive Survey on Hardware-Aware Neural Architecture Search.** arXiv 2021 [paper](https://arxiv.org/abs/2101.09336) [bib](/bib/Machine-Learning/AutoML/Benmeziane2021A.md)

    *Hadjer Benmeziane, Kaoutar El Maghraoui, Hamza Ouarnoughi, Smaïl Niar, Martin Wistuba, Naigang Wang*

3. **A Review of Meta-Reinforcement Learning for Deep Neural Networks Architecture Search.** arXiv 2018 [paper](https://arxiv.org/pdf/1812.07995.pdf) [bib](/bib/Machine-Learning/AutoML/Jaâfra2018A.md)

    *Yesmina Jaâfra, Jean Luc Laurent, Aline Deruyver, Mohamed Saber Naceur*

4. **A Survey on Neural Architecture Search.** arXiv 2019 [paper](https://arxiv.org/abs/1905.01392) [bib](/bib/Machine-Learning/AutoML/Wistuba2019A.md)

    *Martin Wistuba, Ambrish Rawat, Tejaswini Pedapati*

5. **Automated Machine Learning on Graphs: A Survey.** IJCAI 2021 [paper](https://arxiv.org/abs/2103.00742) [bib](/bib/Machine-Learning/AutoML/Zhang2021Automated.md)

    *Ziwei Zhang, Xin Wang, Wenwu Zhu*

6. **AutoML: A Survey of the State-of-the-Art.** Knowl. Based Syst. 2021 [paper](https://arxiv.org/abs/1908.00709) [bib](/bib/Machine-Learning/AutoML/He2021AutoML.md)

    *Xin He, Kaiyong Zhao, Xiaowen Chu*

7. **Benchmark and Survey of Automated Machine Learning Frameworks.** J. Artif. Intell. Res. 2021 [paper](https://www.jair.org/index.php/jair/article/view/11854) [bib](/bib/Machine-Learning/AutoML/Zöller2021Benchmark.md)

    *Marc-André Zöller, Marco F. Huber*

8. **Neural Architecture Search: A Survey.** J. Mach. Learn. Res. 2019 [paper](https://arxiv.org/abs/1808.05377) [bib](/bib/Machine-Learning/AutoML/Elsken2019Neural.md)

    *Thomas Elsken, Jan Hendrik Metzen, Frank Hutter*

9. **Reinforcement learning for neural architecture search: A review.** Image Vis. Comput. 2019 [paper](https://www.sciencedirect.com/science/article/abs/pii/S0262885619300885?via%3Dihub) [bib](/bib/Machine-Learning/AutoML/Jaâfra2019Reinforcement.md)

    *Yesmina Jaâfra, Jean Luc Laurent, Aline Deruyver, Mohamed Saber Naceur*

#### [Bayesian Methods](#content)

1. **A survey of non-exchangeable priors for Bayesian nonparametric models.** IEEE Trans. Pattern Anal. Mach. Intell. 2015 [paper](https://arxiv.org/abs/1211.4798) [bib](/bib/Machine-Learning/Bayesian-Methods/Foti2015A.md)

    *Nicholas J. Foti, Sinead A. Williamson*

2. **A Survey on Bayesian Deep Learning.** ACM Comput. Surv. 2020 [paper](http://arxiv.org/abs/1604.01662) [bib](/bib/Machine-Learning/Bayesian-Methods/Wang2020A.md)

    *Hao Wang, Dit-Yan Yeung*

3. **Bayesian Neural Networks: An Introduction and Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2006.12024) [bib](/bib/Machine-Learning/Bayesian-Methods/Goan2020Bayesian.md)

    *Ethan Goan, Clinton Fookes*

4. **Bayesian Nonparametric Space Partitions: A Survey.** IJCAI 2021 [paper](https://arxiv.org/abs/2002.11394) [bib](/bib/Machine-Learning/Bayesian-Methods/Fan2021Bayesian.md)

    *Xuhui Fan, Bin Li, Ling Luo, Scott A. Sisson*

5. **Deep Bayesian Active Learning, A Brief Survey on Recent Advances.** arXiv 2020 [paper](http://arxiv.org/pdf/2012.08044.pdf) [bib](/bib/Machine-Learning/Bayesian-Methods/Mohamadi2020Deep.md)

    *Salman Mohamadi, Hamidreza Amindavar*

6. **Hands-on Bayesian Neural Networks - a Tutorial for Deep Learning Users.** arXiv 2020 [paper](https://arxiv.org/abs/2007.06823) [bib](/bib/Machine-Learning/Bayesian-Methods/Jospin2020Hands-on.md)

    *Laurent Valentin Jospin, Wray L. Buntine, Farid Boussaïd, Hamid Laga, Mohammed Bennamoun*

7. **Taking the Human Out of the Loop: A Review of Bayesian Optimization.** Proc. IEEE 2016 [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7352306) [bib](/bib/Machine-Learning/Bayesian-Methods/Shahriari2016Taking.md)

    *Bobak Shahriari, Kevin Swersky, Ziyu Wang, Ryan P. Adams, Nando de Freitas*

#### [Classification, Clustering and Regression](#content)

1. **A continual learning survey: Defying forgetting in classification tasks.** TPAMI 2021 [paper](https://arxiv.org/pdf/1909.08383.pdf) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Lange2021A.md)

    *Matthias De Lange, Rahaf Aljundi, Marc Masana, Sarah Parisot, Xu Jia, Ales Leonardis, Gregory Slabaugh, Tinne Tuytelaars*

2. **A Survey of Classification Techniques in the Area of Big Data.** arXiv 2015 [paper](https://arxiv.org/abs/1503.07477) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Koturwar2015A.md)

    *Praful Koturwar, Sheetal Girase, Debajyoti Mukhopadhyay*

3. **A Survey of Constrained Gaussian Process Regression: Approaches and Implementation Challenges.** arXiv 2020 [paper](https://arxiv.org/abs/2006.09319) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Swiler2020A.md)

    *Laura P. Swiler, Mamikon Gulian, Ari Frankel, Cosmin Safta, John D. Jakeman*

4. **A Survey of Machine Learning Methods and Challenges for Windows Malware Classification.** arXiv 2020 [paper](https://arxiv.org/abs/2006.09271) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Raff2020A.md)

    *Edward Raff, Charles Nicholas*

5. **A Survey of Methods for Managing the Classification and Solution of Data Imbalance Problem.** arXiv 2020 [paper](https://arxiv.org/abs/2012.11870) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Hasib2020A.md)

    *Khan Md. Hasib, Md. Sadiq Iqbal, Faisal Muhammad Shah, Jubayer Al Mahmud, Mahmudul Hasan Popel, Md. Imran Hossain Showrov, Shakil Ahmed, Obaidur Rahman*

6. **A Survey of Techniques All Classifiers Can Learn from Deep Networks: Models, Optimizations, and Regularization.** arXiv 2019 [paper](https://arxiv.org/pdf/1909.04791.pdf) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Ghods2019A.md)

    *Alireza Ghods, Diane J. Cook*

7. **A Survey on Multi-View Clustering.** arXiv 2017 [paper](https://arxiv.org/abs/1712.06246) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Chao2017A.md)

    *Guoqing Chao, Shiliang Sun, Jinbo Bi*

8. **Comprehensive Comparative Study of Multi-Label Classification Methods.** arXiv 2021 [paper](https://arxiv.org/abs/2102.07113) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Bogatinovski2021Comprehensive.md)

    *Jasmin Bogatinovski, Ljupco Todorovski, Saso Dzeroski, Dragi Kocev*

9. **Deep learning for time series classification: a review.** Data Min. Knowl. Discov. 2019 [paper](https://arxiv.org/abs/1809.04356) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Fawaz2019Deep.md)

    *Hassan Ismail Fawaz, Germain Forestier, Jonathan Weber, Lhassane Idoumghar, Pierre-Alain Muller*

10. **How Complex is your classification problem?: A survey on measuring classification complexity.** ACM Comput. Surv. 2019 [paper](https://arxiv.org/abs/1808.03591) [bib](/bib/Machine-Learning/Classification,-Clustering-and-Regression/Lorena2019How.md)

    *Ana Carolina Lorena, Luís Paulo F. Garcia, Jens Lehmann, Marcílio Carlos Pereira de Souto, Tin Kam Ho*

#### [Computer Vision](#content)

1. **3D Object Detection for Autonomous Driving: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.10823.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Qian20213D.md)

    *Rui Qian, Xin Lai, Xirong Li*

2. **A Survey of Black-Box Adversarial Attacks on Computer Vision Models.** arXiv 2019 [paper](https://arxiv.org/pdf/1912.01667.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Bhambri2019A.md)

    *Siddhant Bhambri, Sumanyu Muku, Avinash Tulasi, Arun Balaji Buduru*

3. **A survey of loss functions for semantic segmentation.** CIBCB 2020 [paper](https://arxiv.org/pdf/2006.14822.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Jadon2020A.md)

    *Shruti Jadon*

4. **A Survey of Modern Deep Learning based Object Detection Models.** arXiv 2021 [paper](https://arxiv.org/pdf/2104.11892.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Zaidi2021A.md)

    *Syed Sahil Abbas Zaidi, Mohammad Samar Ansari, Asra Aslam, Nadia Kanwal, Mamoona Naveed Asghar, Brian Lee*

5. **A survey on applications of augmented, mixed and virtual reality for nature and environment.** HCI 2021 [paper](https://arxiv.org/abs/2008.12024) [bib](/bib/Machine-Learning/Computer-Vision/Rambach2021A.md)

    *Jason R. Rambach, Gergana Lilligreen, Alexander Schäfer, Ramya Bankanal, Alexander Wiebel, Didier Stricker*

6. **A survey on deep hashing for image retrieval.** arXiv 2020 [paper](https://arxiv.org/abs/2006.05627) [bib](/bib/Machine-Learning/Computer-Vision/Zhang2020A.md)

    *Xiaopeng Zhang*

7. **A Survey on Deep Learning in Medical Image Analysis.** Medical Image Anal. 2017 [paper](https://arxiv.org/abs/1702.05747) [bib](/bib/Machine-Learning/Computer-Vision/Litjens2017A.md)

    *Geert Litjens, Thijs Kooi, Babak Ehteshami Bejnordi, Arnaud Arindra Adiyoso Setio, Francesco Ciompi, Mohsen Ghafoorian, Jeroen A. W. M. van der Laak, Bram van Ginneken, Clara I. Sánchez*

8. **A Survey on Deep Learning Technique for Video Segmentation.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.01153.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Wang2021A.md)

    *Wenguan Wang, Tianfei Zhou, Fatih Porikli, David J. Crandall, Luc Van Gool*

9. **A Technical Survey and Evaluation of Traditional Point Cloud Clustering Methods for LiDAR Panoptic Segmentation.** ICCVW 2021 [paper](https://arxiv.org/pdf/2108.09522.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Zhao2021A.md)

    *Yiming Zhao, Xiao Zhang, Xinming Huang*

10. **Advances in adversarial attacks and defenses in computer vision: A survey.** IEEE Access 2021 [paper](https://arxiv.org/pdf/2108.00401.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Akhtar2021Advances.md)

    *Naveed Akhtar, Ajmal Mian, Navid Kardan, Mubarak Shah*

11. **Adversarial Examples on Object Recognition: A Comprehensive Survey.** ACM Comput. Surv. 2020 [paper](https://arxiv.org/abs/2008.04094) [bib](/bib/Machine-Learning/Computer-Vision/Serban2020Adversarial.md)

    *Alexandru Constantin Serban, Erik Poll, Joost Visser*

12. **Adversarial Machine Learning in Image Classification: A Survey Towards the Defender's Perspective.** arXiv 2020 [paper](https://arxiv.org/pdf/2009.03728.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Machado2020Adversarial.md)

    *Gabriel Resende Machado, Eugênio Silva, Ronaldo Ribeiro Goldschmidt*

13. **Affective Image Content Analysis: Two Decades Review and New Perspectives.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.16125.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Zhao2021Affective.md)

    *Sicheng Zhao, Xingxu Yao, Jufeng Yang, Guoli Jia, Guiguang Ding, Tat-Seng Chua, Björn W. Schuller, Kurt Keutzer*

14. **Applications of Artificial Neural Networks in Microorganism Image Analysis: A Comprehensive Review from Conventional Multilayer Perceptron to Popular Convolutional Neural Network and Potential Visual Transformer.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.00358.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Zhang2021Applications.md)

    *Jinghua Zhang, Chen Li, Marcin Grzegorzek*

15. **Automatic Gaze Analysis: A Survey of Deep Learning based Approaches.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.05479.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Ghosh2021Automatic.md)

    *Shreya Ghosh, Abhinav Dhall, Munawar Hayat, Jarrod Knibbe, Qiang Ji*

16. **Bridging Gap between Image Pixels and Semantics via Supervision: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.13757.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Duan2021Bridging.md)

    *Jiali Duan, C.-C. Jay Kuo*

17. **Deep Learning for 3D Point Cloud Understanding: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2009.08920) [bib](/bib/Machine-Learning/Computer-Vision/Lu2020Deep.md)

    *Haoming Lu, Humphrey Shi*

18. **Deep Learning for Embodied Vision Navigation: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.04097.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Zhu2021Deep.md)

    *Fengda Zhu, Yi Zhu, Xiaodan Liang, Xiaojun Chang*

19. **Deep Learning for Image Super-resolution: A Survey.** IEEE Trans. Pattern Anal. Mach. Intell. 2021 [paper](https://arxiv.org/abs/1902.06068) [bib](/bib/Machine-Learning/Computer-Vision/Wang2021Deep.md)

    *Zhihao Wang, Jian Chen, Steven C. H. Hoi*

20. **Deep Learning for Instance Retrieval: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2101.11282.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Chen2021Deep.md)

    *Wei Chen, Yu Liu, Weiping Wang, Erwin Bakker, Theodoros Georgiou, Paul Fieguth, Li Liu, Michael S. Lew*

21. **Deep Learning for Scene Classification: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2101.10531) [bib](/bib/Machine-Learning/Computer-Vision/Zeng2021Deep.md)

    *Delu Zeng, Minyu Liao, Mohammad Tavakolian, Yulan Guo, Bolei Zhou, Dewen Hu, Matti Pietikäinen, Li Liu*

22. **Image/Video Deep Anomaly Detection: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2103.01739) [bib](/bib/Machine-Learning/Computer-Vision/Mohammadi2021Image.md)

    *Bahram Mohammadi, Mahmood Fathy, Mohammad Sabokrou*

23. **Image-to-Image Translation: Methods and Applications.** arXiv 2021 [paper](https://arxiv.org/abs/2101.08629) [bib](/bib/Machine-Learning/Computer-Vision/Pang2021Image-to-Image.md)

    *Yingxue Pang, Jianxin Lin, Tao Qin, Zhibo Chen*

24. **Imbalance Problems in Object Detection: A Review.** IEEE Trans. Pattern Anal. Mach. Intell. 2021 [paper](https://arxiv.org/abs/1909.00169) [bib](/bib/Machine-Learning/Computer-Vision/Oksuz2021Imbalance.md)

    *Kemal Oksuz, Baris Can Cam, Sinan Kalkan, Emre Akbas*

25. **MmWave Radar and Vision Fusion for Object Detection in Autonomous Driving: A Review.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.03004.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Wei2021MmWave.md)

    *Zhiqing Wei, Fengkai Zhang, Shuo Chang, Yangyang Liu, Huici Wu, Zhiyong Feng*

26. **Object Detection in 20 Years: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1905.05055) [bib](/bib/Machine-Learning/Computer-Vision/Zou2019Object.md)

    *Zhengxia Zou, Zhenwei Shi, Yuhong Guo, Jieping Ye*

27. **The Impact of Machine Learning on 2D/3D Registration for Image-guided Interventions: A Systematic Review and Perspective.** Frontiers Robotics AI 2021 [paper](https://arxiv.org/pdf/2108.02238.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Unberath2021The.md)

    *Mathias Unberath, Cong Gao, Yicheng Hu, Max Judish, Russell H. Taylor, Mehran Armand, Robert B. Grupp*

28. **The Need and Status of Sea Turtle Conservation and Survey of Associated Computer Vision Advances.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.14061.pdf) [bib](/bib/Machine-Learning/Computer-Vision/Paul2021The.md)

    *Aditya Jyoti Paul*

#### [Contrastive Learning](#content)

1. **A Survey on Contrastive Self-supervised Learning.** arXiv 2020 [paper](https://arxiv.org/abs/2011.00362) [bib](/bib/Machine-Learning/Contrastive-Learning/Jaiswal2020A.md)

    *Ashish Jaiswal, Ashwin Ramesh Babu, Mohammad Zaki Zadeh, Debapriya Banerjee, Fillia Makedon*

2. **Contrastive Representation Learning: A Framework and Review.** IEEE Access 2020 [paper](http://doras.dcu.ie/25121/1/ACCESS3031549.pdf) [bib](/bib/Machine-Learning/Contrastive-Learning/Le-Khac2020Contrastive.md)

    *Phuc H. Le-Khac, Graham Healy, Alan F. Smeaton*

3. **Self-supervised Learning: Generative or Contrastive.** arXiv 2020 [paper](https://arxiv.org/abs/2006.08218) [bib](/bib/Machine-Learning/Contrastive-Learning/Liu2020Self-supervised.md)

    *Xiao Liu, Fanjin Zhang, Zhenyu Hou, Zhaoyu Wang, Li Mian, Jing Zhang, Jie Tang*

#### [Curriculum Learning](#content)

1. **A Survey on Curriculum Learning.** TPAMI 2021 [paper](https://arxiv.org/abs/2010.13166) [bib](/bib/Machine-Learning/Curriculum-Learning/Wang2021A.md)

    *Xin Wang, Yudong Chen, Wenwu Zhu*

2. **Automatic Curriculum Learning For Deep RL: A Short Survey.** IJCAI 2020 [paper](https://arxiv.org/abs/2003.04664) [bib](/bib/Machine-Learning/Curriculum-Learning/Portelas2020Automatic.md)

    *Rémy Portelas, Cédric Colas, Lilian Weng, Katja Hofmann, Pierre-Yves Oudeyer*

3. **Curriculum Learning for Reinforcement Learning Domains: A Framework and Survey.** J. Mach. Learn. Res. 2020 [paper](https://arxiv.org/abs/2003.04960) [bib](/bib/Machine-Learning/Curriculum-Learning/Narvekar2020Curriculum.md)

    *Sanmit Narvekar, Bei Peng, Matteo Leonetti, Jivko Sinapov, Matthew E. Taylor, Peter Stone*

4. **Curriculum Learning: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2101.10382) [bib](/bib/Machine-Learning/Curriculum-Learning/Soviany2021Curriculum.md)

    *Petru Soviany, Radu Tudor Ionescu, Paolo Rota, Nicu Sebe*

#### [Data Augmentation](#content)

1. **A survey on Image Data Augmentation for Deep Learning.** J. Big Data 2019 [paper](https://link.springer.com/article/10.1186/s40537-019-0197-0) [bib](/bib/Machine-Learning/Data-Augmentation/Shorten2019A.md)

    *Connor Shorten, Taghi M. Khoshgoftaar*

2. **An Empirical Survey of Data Augmentation for Time Series Classification with Neural Networks.** arXiv 2020 [paper](https://arxiv.org/abs/2007.15951) [bib](/bib/Machine-Learning/Data-Augmentation/Iwana2020An.md)

    *Brian Kenji Iwana, Seiichi Uchida*

3. **Time Series Data Augmentation for Deep Learning: A Survey.** IJCAI 2021 [paper](https://arxiv.org/abs/2002.12478) [bib](/bib/Machine-Learning/Data-Augmentation/Wen2021Time.md)

    *Qingsong Wen, Liang Sun, Fan Yang, Xiaomin Song, Jingkun Gao, Xue Wang, Huan Xu*

#### [Deep Learning General Methods](#content)

1. **A Survey of Deep Active Learning.** ACM Comput. Surv. 2022 [paper](https://arxiv.org/abs/2009.00236) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Ren2022A.md)

    *Pengzhen Ren, Yun Xiao, Xiaojun Chang, Po-Yao Huang, Zhihui Li, Brij B. Gupta, Xiaojiang Chen, Xin Wang*

2. **A Survey of Deep Learning for Data Caching in Edge Network.** Informatics 2020 [paper](https://arxiv.org/abs/2008.07235) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Wang2020A.md)

    *Yantong Wang, Vasilis Friderikos*

3. **A Survey of Deep Learning for Scientific Discovery.** arXiv 2020 [paper](https://arxiv.org/pdf/2003.11755.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Raghu2020A.md)

    *Maithra Raghu, Eric Schmidt*

4. **A Survey of Label-noise Representation Learning: Past, Present and Future.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.04406.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Han2020A.md)

    *Bo Han, Quanming Yao, Tongliang Liu, Gang Niu, Ivor W. Tsang, James T. Kwok, Masashi Sugiyama*

5. **A Survey of Neuromorphic Computing and Neural Networks in Hardware.** arXiv 2017 [paper](https://arxiv.org/abs/1705.06963) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Schuman2017A.md)

    *Catherine D. Schuman, Thomas E. Potok, Robert M. Patton, J. Douglas Birdwell, Mark E. Dean, Garrett S. Rose, James S. Plank*

6. **A Survey of Uncertainty in Deep Neural Networks.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.03342.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Gawlikowski2021A.md)

    *Jakob Gawlikowski, Cedrique Rovile Njieutcheu Tassi, Mohsin Ali, Jongseok Lee, Matthias Humt, Jianxiang Feng, Anna M. Kruspe, Rudolph Triebel, Peter Jung, Ribana Roscher, Muhammad Shahzad, Wen Yang, Richard Bamler, Xiao Xiang Zhu*

7. **A Survey on Active Deep Learning: From Model-driven to Data-driven.** arXiv 2021 [paper](https://arxiv.org/abs/2101.09933) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Liu2021A.md)

    *Peng Liu, Lizhe Wang, Guojin He, Lei Zhao*

8. **A Survey on Assessing the Generalization Envelope of Deep Neural Networks: Predictive Uncertainty, Out-of-distribution and Adversarial Samples.** arXiv 2020 [paper](https://arxiv.org/abs/2008.09381) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Lust2020A.md)

    *Julia Lust, Alexandru Paul Condurache*

9. **A Survey on Concept Factorization: From Shallow to Deep Representation Learning.** Inf. Process. Manag. 2021 [paper](https://arxiv.org/abs/2007.15840) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Zhang2021A.md)

    *Zhao Zhang, Yan Zhang, Mingliang Xu, Li Zhang, Yi Yang, Shuicheng Yan*

10. **A Survey on Deep Hashing Methods.** arXiv 2020 [paper](https://arxiv.org/abs/2003.03369) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Luo2020A.md)

    *Xiao Luo, Chong Chen, Huasong Zhong, Hao Zhang, Minghua Deng, Jianqiang Huang, Xiansheng Hua*

11. **A Survey on Deep Learning with Noisy Labels: How to train your model when you cannot trust on the annotations?.** SIBGRAPI 2020 [paper](https://arxiv.org/pdf/2012.03061.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Cordeiro2020A.md)

    *Filipe R. Cordeiro, Gustavo Carneiro*

12. **A Survey on Dynamic Network Embedding.** arXiv 2020 [paper](https://arxiv.org/pdf/2006.08093.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Xie2020A.md)

    *Yu Xie, Chunyi Li, Bin Yu, Chen Zhang, Zhouhua Tang*

13. **A Survey on Network Embedding.** IEEE Trans. Knowl. Data Eng. 2019 [paper](https://arxiv.org/pdf/1711.08752) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Cui2019A.md)

    *Peng Cui, Xiao Wang, Jian Pei, Wenwu Zhu*

14. **A Tutorial on Network Embeddings.** arXiv 2018 [paper](https://arxiv.org/abs/1808.02590) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Chen2018A.md)

    *Haochen Chen, Bryan Perozzi, Rami Al-Rfou, Steven Skiena*

15. **Continual Lifelong Learning with Neural Networks: A Review.** Neural Networks 2019 [paper](https://arxiv.org/pdf/1802.07569.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Parisi2019Continual.md)

    *German Ignacio Parisi, Ronald Kemker, Jose L. Part, Christopher Kanan, Stefan Wermter*

16. **Convergence of Edge Computing and Deep Learning: A Comprehensive Survey.** IEEE Commun. Surv. Tutorials 2020 [paper](https://ieeexplore.ieee.org/document/8976180) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Wang2020Convergence.md)

    *Xiaofei Wang, Yiwen Han, Victor C. M. Leung, Dusit Niyato, Xueqiang Yan, Xu Chen*

17. **Deep learning.** Nat. 2015 [paper](https://www.nature.com/articles/nature14539) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/LeCun2015Deep.md)

    *Yann LeCun, Yoshua Bengio, Geoffrey Hinton*

18. **Deep Learning for Matching in Search and Recommendation.** SIGIR 2018 [paper](https://dl.acm.org/doi/abs/10.1145/3209978.3210181) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Xu2018Deep.md)

    *Jun Xu, Xiangnan He, Hang Li*

19. **Deep Learning Theory Review: An Optimal Control and Dynamical Systems Perspective.** arXiv 2019 [paper](https://arxiv.org/abs/1908.10920) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Liu2019Deep.md)

    *Guan-Horng Liu, Evangelos A. Theodorou*

20. **Dynamic Neural Networks: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2102.04906) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Han2021Dynamic.md)

    *Yizeng Han, Gao Huang, Shiji Song, Le Yang, Honghui Wang, Yulin Wang*

21. **Embracing Change: Continual Learning in Deep Neural Networks.** Trends in Cognitive Sciences 2020 [paper](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(20)30219-9?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS1364661320302199%3Fshowall%3Dtrue) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Hadsell2020Embracing.md)

    *Raia Hadsell, Dushyant Rao, Andrei A. Rusu, Razvan Pascanu*

22. **Geometric deep learning: going beyond Euclidean data.** IEEE Signal Process. Mag. 2017 [paper](https://arxiv.org/abs/1611.08097) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Bronstein2017Geometric.md)

    *Michael M. Bronstein, Joan Bruna, Yann LeCun, Arthur Szlam, Pierre Vandergheynst*

23. **Heuristic design of fuzzy inference systems: A review of three decades of research.** Eng. Appl. Artif. Intell. 2019 [paper](https://arxiv.org/abs/1908.10122) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Ojha2019Heuristic.md)

    *Varun Ojha, Ajith Abraham, Václav Snásel*

24. **Imitation Learning: Progress, Taxonomies and Opportunities.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.12177.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Zheng2021Imitation.md)

    *Boyuan Zheng, Sunny Verma, Jianlong Zhou, Ivor W. Tsang, Fang Chen*

25. **Improving Deep Learning Models via Constraint-Based Domain Knowledge: a Brief Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2005.10691) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Borghesi2020Improving.md)

    *Andrea Borghesi, Federico Baldo, Michela Milano*

26. **Learning from Noisy Labels with Deep Neural Networks: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2007.08199) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Song2020Learning.md)

    *Hwanjun Song, Minseok Kim, Dongmin Park, Jae-Gil Lee*

27. **Model Complexity of Deep Learning: A Survey.** Knowl. Inf. Syst. 2021 [paper](https://arxiv.org/abs/2103.05127) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Hu2021Model.md)

    *Xia Hu, Lingyang Chu, Jian Pei, Weiqing Liu, Jiang Bian*

28. **Network representation learning: A macro and micro view.** AI Open 2021 [paper](https://www.sciencedirect.com/science/article/pii/S2666651021000024) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Liu2021Network.md)

    *Xueyi Liu, Jie Tang*

29. **Network Representation Learning: A Survey.** IEEE Trans. Big Data 2020 [paper](https://ieeexplore.ieee.org/document/8395024) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Zhang2020Network.md)

    *Daokun Zhang, Jie Yin, Xingquan Zhu, Chengqi Zhang*

30. **Network representation learning: an overview.** SCIENTIA SINICA Informationis 2017 [paper](http://engine.scichina.com/publisher/scp/journal/SSI/47/8/10.1360/N112017-00145) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/TU2017Network.md)

    *Cunchao TU, Cheng YANG, Zhiyuan LIU, Maosong SUN*

31. **Opportunities and Challenges in Deep Learning Adversarial Robustness: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2007.00753) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Silva2020Opportunities.md)

    *Samuel Henrique Silva, Peyman Najafirad*

32. **Recent advances in deep learning theory.** arXiv 2020 [paper](https://arxiv.org/pdf/2012.10931.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/He2020Recent.md)

    *Fengxiang He, Dacheng Tao*

33. **Relational inductive biases, deep learning, and graph networks.** arXiv 2018 [paper](http://arxiv.org/abs/1806.01261) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Battaglia2018Relational.md)

    *Peter W. Battaglia, Jessica B. Hamrick, Victor Bapst, Alvaro Sanchez-Gonzalez, Vinícius Flores Zambaldi, Mateusz Malinowski, Andrea Tacchetti, David Raposo, Adam Santoro, Ryan Faulkner, Çaglar Gülçehre, H. Francis Song, Andrew J. Ballard, Justin Gilmer, George E. Dahl, Ashish Vaswani, Kelsey R. Allen, Charles Nash, Victoria Langston, Chris Dyer, Nicolas Heess, Daan Wierstra, Pushmeet Kohli, Matthew Botvinick, Oriol Vinyals, Yujia Li, Razvan Pascanu*

34. **Representation Learning: A Review and New Perspectives.** IEEE Trans. Pattern Anal. Mach. Intell. 2013 [paper](https://arxiv.org/pdf/1206.5538) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Bengio2013Representation.md)

    *Yoshua Bengio, Aaron C. Courville, Pascal Vincent*

35. **Review: Ordinary Differential Equations For Deep Learning.** arXiv 2019 [paper](https://arxiv.org/abs/1911.00502) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Chen2019Review.md)

    *Xinshi Chen*

36. **Sparsity in Deep Learning: Pruning and growth for efficient inference and training in neural networks.** J. Mach. Learn. Res. 2021 [paper](https://arxiv.org/abs/2102.00554) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Hoefler2021Sparsity.md)

    *Torsten Hoefler, Dan Alistarh, Tal Ben-Nun, Nikoli Dryden, Alexandra Peste*

37. **Survey of Expressivity in Deep Neural Networks.** NIPS 2016 [paper](https://arxiv.org/abs/1611.08083) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Raghu2016Survey.md)

    *Maithra Raghu, Ben Poole, Jon Kleinberg, Surya Ganguli, Jascha Sohl-Dickstein*

38. **Survey of reasoning using Neural networks.** arXiv 2017 [paper](https://arxiv.org/abs/1702.06186) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Sahu2017Survey.md)

    *Amit Sahu*

39. **The Deep Learning Compiler: A Comprehensive Survey.** IEEE Trans. Parallel Distributed Syst. 2021 [paper](https://arxiv.org/abs/2002.03794) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Li2021The.md)

    *Mingzhen Li, Yi Liu, Xiaoyan Liu, Qingxiao Sun, Xin You, Hailong Yang, Zhongzhi Luan, Lin Gan, Guangwen Yang, Depei Qian*

40. **The Modern Mathematics of Deep Learning.** arXiv 2021 [paper](https://arxiv.org/pdf/2105.04026.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Berner2021The.md)

    *Julius Berner, Philipp Grohs, Gitta Kutyniok, Philipp Petersen*

41. **Time Series Data Imputation: A Survey on Deep Learning Approaches.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.11347.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Fang2020Time.md)

    *Chenguang Fang, Chen Wang*

42. **Time-series forecasting with deep learning: a survey.** Philosophical Transactions of the Royal Society A 2021 [paper](https://royalsocietypublishing.org/doi/10.1098/rsta.2020.0209) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Lim2021Time-series.md)

    *Bryan Lim, Stefan Zohren*

43. **Tutorial on Variational Autoencoders.** arXiv 2016 [paper](https://arxiv.org/pdf/1606.05908.pdf) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Doersch2016Tutorial.md)

    *Carl Doersch*

44. **网络表示学习算法综述.** 计算机科学 2020 [paper](http://www.jsjkx.com/CN/10.11896/jsjkx.190300004) [bib](/bib/Machine-Learning/Deep-Learning-General-Methods/Ding2020Survey.md)

    *丁钰, 魏浩, 潘志松, 刘鑫*

#### [Deep Reinforcement Learning](#content)

1. **A Short Survey On Memory Based Reinforcement Learning.** arXiv 2019 [paper](https://arxiv.org/abs/1904.06736) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Ramani2019A.md)

    *Dhruv Ramani*

2. **A Short Survey on Probabilistic Reinforcement Learning.** arXiv 2019 [paper](https://arxiv.org/abs/1901.07010) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Russel2019A.md)

    *Reazul Hasan Russel*

3. **A survey of benchmarking frameworks for reinforcement learning.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.13577.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Stapelberg2020A.md)

    *Belinda Stapelberg, Katherine M. Malan*

4. **A Survey of Exploration Strategies in Reinforcement Learning.** McGill University 2003 [paper](https://www.semanticscholar.org/paper/A-Survey-of-Exploration-Strategies-in-Reinforcement-McFarlane/02761533d794ed9ed5dfd0295f2577e1e98c4fe2?p2df) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/McFarlane2003A.md)

    *R. McFarlane*

5. **A Survey of Inverse Reinforcement Learning: Challenges, Methods and Progress.** Artif. Intell. 2021 [paper](https://arxiv.org/abs/1806.06877) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Arora2021A.md)

    *Saurabh Arora, Prashant Doshi*

6. **A Survey of Reinforcement Learning Algorithms for Dynamically Varying Environments.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2005.10619) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Padakandla2021A.md)

    *Sindhu Padakandla*

7. **A Survey of Reinforcement Learning Informed by Natural Language.** IJCAI 2019 [paper](https://arxiv.org/abs/1906.03926) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Luketina2019A.md)

    *Jelena Luketina, Nantas Nardelli, Gregory Farquhar, Jakob N. Foerster, Jacob Andreas, Edward Grefenstette, Shimon Whiteson, Tim Rocktäschel*

8. **A Survey of Reinforcement Learning Techniques: Strategies, Recent Development, and Future Directions.** arXiv 2020 [paper](https://arxiv.org/abs/2001.06921) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Mondal2020A.md)

    *Amit Kumar Mondal*

9. **A Survey on Deep Reinforcement Learning for Audio-Based Applications.** arXiv 2021 [paper](http://arxiv.org/pdf/2101.00240.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Latif2021A.md)

    *Siddique Latif, Heriberto Cuayáhuitl, Farrukh Pervez, Fahad Shamshad, Hafiz Shehbaz Ali, Erik Cambria*

10. **A Survey on Deep Reinforcement Learning for Data Processing and Analytics.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.04526.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Cai2021A.md)

    *Qingpeng Cai, Can Cui, Yiyuan Xiong, Wei Wang, Zhongle Xie, Meihui Zhang*

11. **A survey on intrinsic motivation in reinforcement learning.** arXiv 2019 [paper](https://arxiv.org/abs/1908.06976) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Aubret2019A.md)

    *Arthur Aubret, Laëtitia Matignon, Salima Hassas*

12. **A Survey on Reinforcement Learning for Combinatorial Optimization.** arXiv 2020 [paper](https://arxiv.org/pdf/2008.12248.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Yang2020A.md)

    *Yunhao Yang, Andrew B. Whinston*

13. **A Survey on Reproducibility by Evaluating Deep Reinforcement Learning Algorithms on Real-World Robots.** CoRL 2019 [paper](https://arxiv.org/abs/1909.03772) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Lynnerup2019A.md)

    *Nicolai A. Lynnerup, Laura Nolling, Rasmus Hasle, John Hallam*

14. **Adapting Behaviour via Intrinsic Reward: A Survey and Empirical Study.** arXiv 2019 [paper](https://arxiv.org/pdf/1906.07865.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Linke2019Adapting.md)

    *Cam Linke, Nadia M. Ady, Martha White, Thomas Degris, Adam White*

15. **Comprehensive Review of Deep Reinforcement Learning Methods and Applications in Economics.** Mathematics 2020 [paper](https://www.mdpi.com/2227-7390/8/10/1640) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Mosavi2020Comprehensive.md)

    *Amirhosein Mosavi, Yaser Faghan, Pedram Ghamisi, Puhong Duan, Sina Faizollahzadeh Ardabili, Ely Salwana, Shahab S. Band*

16. **Curriculum Learning for Reinforcement Learning Domains: A Framework and Survey.** J. Mach. Learn. Res. 2020 [paper](https://arxiv.org/pdf/2003.04960.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Narvekar2020Curriculum.md)

    *Sanmit Narvekar, Bei Peng, Matteo Leonetti, Jivko Sinapov, Matthew E. Taylor, Peter Stone*

17. **Deep Model-Based Reinforcement Learning for High-Dimensional Problems, a Survey.** arXiv 2020 [paper](http://arxiv.org/pdf/2008.05598.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Plaat2020Deep.md)

    *Aske Plaat, Walter Kosters, Mike Preuss*

18. **Deep Reinforcement Learning for Clinical Decision Support: A Brief Survey.** arXiv 2019 [paper](https://arxiv.org/pdf/1907.09475.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Liu2019Deep.md)

    *Siqi Liu, Kee Yuan Ngiam, Mengling Feng*

19. **Deep Reinforcement Learning for Demand Driven Services in Logistics and Transportation Systems: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.04462.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Zong2021Deep.md)

    *Zefang Zong, Tao Feng, Tong Xia, Depeng Jin, Yong Li*

20. **Deep Reinforcement Learning for Intelligent Transportation Systems: A Survey.** IEEE Trans. Intell. Transp. Syst. 2022 [paper](https://arxiv.org/pdf/2005.00935.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Haydari2022Deep.md)

    *Ammar Haydari, Yasin Yilmaz*

21. **Deep Reinforcement Learning in Quantitative Algorithmic Trading: A Review.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.00123.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Pricope2021Deep.md)

    *Tidor-Vlad Pricope*

22. **Deep Reinforcement Learning: A Brief Survey.** IEEE Signal Process. Mag. 2017 [paper](https://ieeexplore.ieee.org/document/8103164) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Arulkumaran2017Deep.md)

    *Kai Arulkumaran, Marc Peter Deisenroth, Miles Brundage, Anil Anthony Bharath*

23. **Deep Reinforcement Learning: An Overview.** arXiv 2017 [paper](https://arxiv.org/abs/1701.07274) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Li2017Deep.md)

    *Yuxi Li*

24. **Derivative-Free Reinforcement Learning: A Review.** Frontiers Comput. Sci. 2021 [paper](https://arxiv.org/abs/2102.05710) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Qian2021Derivative-Free.md)

    *Hong Qian, Yang Yu*

25. **Explainable Reinforcement Learning for Broad-XAI: A Conceptual Framework and Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.09003.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Dazeley2021Explainable.md)

    *Richard Dazeley, Peter Vamplew, Francisco Cruz*

26. **Feature-Based Aggregation and Deep Reinforcement Learning: A Survey and Some New Implementations.** IEEE CAA J. Autom. Sinica 2019 [paper](https://arxiv.org/abs/1804.04577) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Bertsekas2019Feature-Based.md)

    *Dimitri P. Bertsekas*

27. **Model-based Reinforcement Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2006.16712) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Moerland2020Model-based.md)

    *Thomas M. Moerland, Joost Broekens, Catholijn M. Jonker*

28. **Reinforcement Learning for Combinatorial Optimization: A Survey.** Comput. Oper. Res. 2021 [paper](https://arxiv.org/abs/2003.03600) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Mazyavkina2021Reinforcement.md)

    *Nina Mazyavkina, Sergey Sviridov, Sergei Ivanov, Evgeny Burnaev*

29. **Reinforcement Learning in Healthcare: A Survey.** arXiv 2019 [paper](https://arxiv.org/pdf/1908.08796.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Yu2019Reinforcement.md)

    *Chao Yu, Jiming Liu, Shamim Nemati*

30. **Sim-to-Real Transfer in Deep Reinforcement Learning for Robotics: a Survey.** SSCI 2020 [paper](https://arxiv.org/pdf/2009.13303.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Zhao2020Sim-to-Real.md)

    *Wenshuai Zhao, Jorge Peña Queralta, Tomi Westerlund*

31. **Survey on reinforcement learning for language processing.** arXiv 2021 [paper](https://arxiv.org/abs/2104.05565) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Uc-Cetina2021Survey.md)

    *Víctor Uc-Cetina, Nicolás Navarro-Guerrero, Anabel Martín-González, Cornelius Weber, Stefan Wermter*

32. **Tutorial and Survey on Probabilistic Graphical Model and Variational Inference in Deep Reinforcement Learning.** SSCI 2019 [paper](https://arxiv.org/pdf/1908.09381.pdf) [bib](/bib/Machine-Learning/Deep-Reinforcement-Learning/Sun2019Tutorial.md)

    *Xudong Sun, Bernd Bischl*

#### [Federated Learning](#content)

1. **A Survey on Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection.** arXiv 2019 [paper](http://arxiv.org/pdf/1907.09693.pdf) [bib](/bib/Machine-Learning/Federated-Learning/Li2019A.md)

    *Qinbin Li, Zeyi Wen, Zhaomin Wu, Sixu Hu, Naibo Wang, Xu Liu, Bingsheng He*

2. **Achieving Security and Privacy in Federated Learning Systems: Survey, Research Challenges and Future Directions.** Eng. Appl. Artif. Intell. 2021 [paper](http://arxiv.org/pdf/2012.06810.pdf) [bib](/bib/Machine-Learning/Federated-Learning/Blanco-Justicia2021Achieving.md)

    *Alberto Blanco-Justicia, Josep Domingo-Ferrer, Sergio Martínez, David Sánchez, Adrian Flanagan, Kuan Eeik Tan*

3. **Advances and Open Problems in Federated Learning.** Found. Trends Mach. Learn. 2021 [paper](https://arxiv.org/abs/1912.04977) [bib](/bib/Machine-Learning/Federated-Learning/Kairouz2021Advances.md)

    *Peter Kairouz, H. Brendan McMahan, Brendan Avent, Aurélien Bellet, Mehdi Bennis, Arjun Nitin Bhagoji, Kallista A. Bonawitz, Zachary Charles, Graham Cormode, Rachel Cummings, Rafael G. L. D'Oliveira, Hubert Eichner, Salim El Rouayheb, David Evans, Josh Gardner, Zachary Garrett, Adrià Gascón, Badih Ghazi, Phillip B. Gibbons, Marco Gruteser, Zaïd Harchaoui, Chaoyang He, Lie He, Zhouyuan Huo, Ben Hutchinson, Justin Hsu, Martin Jaggi, Tara Javidi, Gauri Joshi, Mikhail Khodak, Jakub Konecný, Aleksandra Korolova, Farinaz Koushanfar, Sanmi Koyejo, Tancrède Lepoint, Yang Liu, Prateek Mittal, Mehryar Mohri, Richard Nock, Ayfer Özgür, Rasmus Pagh, Hang Qi, Daniel Ramage, Ramesh Raskar, Mariana Raykova, Dawn Song, Weikang Song, Sebastian U. Stich, Ziteng Sun, Ananda Theertha Suresh, Florian Tramèr, Praneeth Vepakomma, Jianyu Wang, Li Xiong, Zheng Xu, Qiang Yang, Felix X. Yu, Han Yu, Sen Zhao*

4. **Fusion of Federated Learning and Industrial Internet of Things: A Survey.** arXiv 2021 [paper](http://arxiv.org/pdf/2101.00798.pdf) [bib](/bib/Machine-Learning/Federated-Learning/Parimala2021Fusion.md)

    *Parimala M., R. M. Swarna Priya, Quoc-Viet Pham, Kapal Dev, Praveen Kumar Reddy Maddikunta, Thippa Reddy Gadekallu, Thien Huynh-The*

5. **Privacy and Robustness in Federated Learning: Attacks and Defenses.** arXiv 2020 [paper](https://arxiv.org/abs/2012.06337) [bib](/bib/Machine-Learning/Federated-Learning/Lyu2020Privacy.md)

    *Lingjuan Lyu, Han Yu, Xingjun Ma, Lichao Sun, Jun Zhao, Qiang Yang, Philip S. Yu*

6. **Threats to Federated Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2003.02133) [bib](/bib/Machine-Learning/Federated-Learning/Lyu2020Threats.md)

    *Lingjuan Lyu, Han Yu, Qiang Yang*

7. **Towards Utilizing Unlabeled Data in Federated Learning: A Survey and Prospective.** arXiv 2020 [paper](https://arxiv.org/abs/2002.11545) [bib](/bib/Machine-Learning/Federated-Learning/Jin2020Towards.md)

    *Yilun Jin, Xiguang Wei, Yang Liu, Qiang Yang*

#### [Few-Shot and Zero-Shot Learning](#content)

1. **A Survey of Zero-Shot Learning: Settings, Methods, and Applications.** ACM Trans. Intell. Syst. Technol. 2019 [paper](https://dl.acm.org/doi/10.1145/3293318) [bib](/bib/Machine-Learning/Few-Shot-and-Zero-Shot-Learning/Wang2019A.md)

    *Wei Wang, Vincent W. Zheng, Han Yu, Chunyan Miao*

2. **Generalizing from a Few Examples: A Survey on Few-Shot Learning.** ACM Comput. Surv. 2020 [paper](https://arxiv.org/abs/1904.05046) [bib](/bib/Machine-Learning/Few-Shot-and-Zero-Shot-Learning/Wang2020Generalizing.md)

    *Yaqing Wang, Quanming Yao, James T. Kwok, Lionel M. Ni*

3. **Learning from Few Samples: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2007.15484) [bib](/bib/Machine-Learning/Few-Shot-and-Zero-Shot-Learning/Bendre2020Learning.md)

    *Nihar Bendre, Hugo Terashima-Marín, Peyman Najafirad*

4. **Learning from Very Few Samples: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2009.02653) [bib](/bib/Machine-Learning/Few-Shot-and-Zero-Shot-Learning/Lu2020Learning.md)

    *Jiang Lu, Pinghua Gong, Jieping Ye, Changshui Zhang*

#### [General Machine Learning](#content)

1. **A Comprehensive Survey on Outlying Aspect Mining Methods.** arXiv 2020 [paper](https://arxiv.org/pdf/2005.02637.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Samariya2020A.md)

    *Durgesh Samariya, Jiangang Ma, Sunil Aryal*

2. **A Survey of Adaptive Resonance Theory Neural Network Models for Engineering Applications.** Neural Networks 2019 [paper](https://arxiv.org/abs/1905.11437) [bib](/bib/Machine-Learning/General-Machine-Learning/Silva2019A.md)

    *Leonardo Enzo Brito da Silva, Islam Elnabarawy, Donald C. Wunsch II*

3. **A survey of dimensionality reduction techniques.** arXiv 2014 [paper](https://arxiv.org/abs/1403.2877) [bib](/bib/Machine-Learning/General-Machine-Learning/Sorzano2014A.md)

    *Carlos Oscar Sánchez Sorzano, Javier Vargas, Alberto Domingo Pascual-Montano*

4. **A Survey of Human-in-the-loop for Machine Learning.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.00941) [bib](/bib/Machine-Learning/General-Machine-Learning/Wu2021A.md)

    *Xingjiao Wu, Luwei Xiao, Yixuan Sun, Junhang Zhang, Tianlong Ma, Liang He*

5. **A Survey of Learning Causality with Data: Problems and Methods.** ACM Comput. Surv. 2020 [paper](https://arxiv.org/pdf/1809.09337.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Guo2020A.md)

    *Ruocheng Guo, Lu Cheng, Jundong Li, P. Richard Hahn, Huan Liu*

6. **A Survey of Predictive Modelling under Imbalanced Distributions.** arXiv 2015 [paper](https://arxiv.org/abs/1505.01658) [bib](/bib/Machine-Learning/General-Machine-Learning/Branco2015A.md)

    *Paula Branco, Luís Torgo, Rita P. Ribeiro*

7. **A Survey On (Stochastic Fractal Search) Algorithm.** arXiv 2021 [paper](https://arxiv.org/abs/2102.01503) [bib](/bib/Machine-Learning/General-Machine-Learning/ElKomy2021A.md)

    *Mohammed ElKomy*

8. **A Survey on Data Collection for Machine Learning: a Big Data - AI Integration Perspective.** IEEE Trans. Knowl. Data Eng. 2021 [paper](https://arxiv.org/abs/1811.03402) [bib](/bib/Machine-Learning/General-Machine-Learning/Roh2021A.md)

    *Yuji Roh, Geon Heo, Steven Euijong Whang*

9. **A Survey on Distributed Machine Learning.** ACM Comput. Surv. 2020 [paper](https://arxiv.org/abs/1912.09789) [bib](/bib/Machine-Learning/General-Machine-Learning/Verbraeken2020A.md)

    *Joost Verbraeken, Matthijs Wolting, Jonathan Katzy, Jeroen Kloppenburg, Tim Verbelen, Jan S. Rellermeyer*

10. **A survey on feature weighting based K-Means algorithms.** J. Classif. 2016 [paper](https://arxiv.org/abs/1601.03483) [bib](/bib/Machine-Learning/General-Machine-Learning/Amorim2016A.md)

    *Renato Cordeiro de Amorim*

11. **A survey on graph kernels.** Appl. Netw. Sci. 2020 [paper](https://appliednetsci.springeropen.com/articles/10.1007/s41109-019-0195-3) [bib](/bib/Machine-Learning/General-Machine-Learning/Kriege2020A.md)

    *Nils M. Kriege, Fredrik D. Johansson, Christopher Morris*

12. **A Survey on Large-scale Machine Learning.** arXiv 2020 [paper](https://arxiv.org/abs/2008.03911) [bib](/bib/Machine-Learning/General-Machine-Learning/Wang2020A.md)

    *Meng Wang, Weijie Fu, Xiangnan He, Shijie Hao, Xindong Wu*

13. **A Survey on Optimal Transport for Machine Learning: Theory and Applications.** arXiv 2021 [paper](https://arxiv.org/abs/2106.01963) [bib](/bib/Machine-Learning/General-Machine-Learning/Torres2021A.md)

    *Luis Caicedo Torres, Luiz Manella Pereira, M. Hadi Amini*

14. **A Survey on Resilient Machine Learning.** arXiv 2017 [paper](https://arxiv.org/abs/1707.03184) [bib](/bib/Machine-Learning/General-Machine-Learning/Kumar2017A.md)

    *Atul Kumar, Sameep Mehta*

15. **A Survey on Surrogate Approaches to Non-negative Matrix Factorization.** Vietnam journal of mathematics 2018 [paper](https://link.springer.com/content/pdf/10.1007/s10013-018-0315-x.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Fernsel2018A.md)

    *Pascal Fernsel, Peter Maass*

16. **Adversarial Examples in Modern Machine Learning: A Review.** arXiv 2019 [paper](https://arxiv.org/abs/1911.05268) [bib](/bib/Machine-Learning/General-Machine-Learning/Wiyatno2019Adversarial.md)

    *Rey Reza Wiyatno, Anqi Xu, Ousmane Dia, Archy de Berker*

17. **Algorithms Inspired by Nature: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1903.01893) [bib](/bib/Machine-Learning/General-Machine-Learning/Gupta2019Algorithms.md)

    *Pranshu Gupta*

18. **An Overview of Privacy in Machine Learning.** arXiv 2020 [paper](https://arxiv.org/pdf/2005.08679.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Cristofaro2020An.md)

    *Emiliano De Cristofaro*

19. **Are deep learning models superior for missing data imputation in large surveys? Evidence from an empirical comparison.** arXiv 2021 [paper](https://arxiv.org/abs/2103.09316) [bib](/bib/Machine-Learning/General-Machine-Learning/Wang2021Are.md)

    *Zhenhua Wang, Olanrewaju Akande, Jason Poulos, Fan Li*

20. **Certification of embedded systems based on Machine Learning: A survey.** arXiv 2021 [paper](https://arxiv.org/abs/2106.07221) [bib](/bib/Machine-Learning/General-Machine-Learning/Vidot2021Certification.md)

    *Guillaume Vidot, Christophe Gabreau, Ileana Ober, Iulian Ober*

21. **Class-incremental learning: survey and performance evaluation.** arXiv 2020 [paper](https://arxiv.org/pdf/2010.15277.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Masana2020Class-incremental.md)

    *Marc Masana, Xialei Liu, Bartlomiej Twardowski, Mikel Menta, Andrew D. Bagdanov, Joost van de Weijer*

22. **Data and its (dis)contents: A survey of dataset development and use in machine learning research.** Patterns 2021 [paper](https://arxiv.org/pdf/2012.05345.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Paullada2021Data.md)

    *Amandalynne Paullada, Inioluwa Deborah Raji, Emily M. Bender, Emily Denton, Alex Hanna*

23. **Generating Artificial Outliers in the Absence of Genuine Ones - a Survey.** ACM Trans. Knowl. Discov. Data 2021 [paper](https://arxiv.org/pdf/2006.03646.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Steinbuss2021Generating.md)

    *Georg Steinbuss, Klemens Böhm*

24. **Hierarchical Mixtures-of-Experts for Exponential Family Regression Models with Generalized Linear Mean Functions: A Survey of Approximation and Consistency Results.** UAI 1998 [paper](https://arxiv.org/abs/1301.7390) [bib](/bib/Machine-Learning/General-Machine-Learning/Jiang1998Hierarchical.md)

    *Wenxin Jiang, Martin A. Tanner*

25. **Hyperbox-based machine learning algorithms: A comprehensive survey.** Soft Comput. 2021 [paper](https://arxiv.org/abs/1901.11303) [bib](/bib/Machine-Learning/General-Machine-Learning/Khuat2021Hyperbox-based.md)

    *Thanh Tung Khuat, Dymitr Ruta, Bogdan Gabrys*

26. **Introduction to Core-sets: an Updated Survey.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.09384.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Feldman2020Introduction.md)

    *Dan Feldman*

27. **Laplacian-Based Dimensionality Reduction Including Spectral Clustering, Laplacian Eigenmap, Locality Preserving Projection, Graph Embedding, and Diffusion Map: Tutorial and Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2106.02154) [bib](/bib/Machine-Learning/General-Machine-Learning/Ghojogh2021Laplacian-Based.md)

    *Benyamin Ghojogh, Ali Ghodsi, Fakhri Karray, Mark Crowley*

28. **Logic Locking at the Frontiers of Machine Learning: A Survey on Developments and Opportunities.** VLSI-SoC 2021 [paper](https://arxiv.org/abs/2107.01915) [bib](/bib/Machine-Learning/General-Machine-Learning/Sisejkovic2021Logic.md)

    *Dominik Sisejkovic, Lennart M. Reimann, Elmira Moussavi, Farhad Merchant, Rainer Leupers*

29. **Machine Learning at the Network Edge: A Survey.** ACM Comput. Surv. 2022 [paper](https://arxiv.org/abs/1908.00080) [bib](/bib/Machine-Learning/General-Machine-Learning/Murshed2022Machine.md)

    *M. G. Sarwar Murshed, Christopher Murphy, Daqing Hou, Nazar Khan, Ganesh Ananthanarayanan, Faraz Hussain*

30. **Machine Learning for Spatiotemporal Sequence Forecasting: A Survey.** arXiv 2018 [paper](https://arxiv.org/abs/1808.06865) [bib](/bib/Machine-Learning/General-Machine-Learning/Shi2018Machine.md)

    *Xingjian Shi, Dit-Yan Yeung*

31. **Machine Learning in Network Centrality Measures: Tutorial and Outlook.** ACM Comput. Surv. 2019 [paper](https://dl.acm.org/doi/10.1145/3237192) [bib](/bib/Machine-Learning/General-Machine-Learning/Grando2019Machine.md)

    *Felipe Grando, Lisandro Zambenedetti Granville, Luís C. Lamb*

32. **Machine Learning Testing: Survey, Landscapes and Horizons.** IEEE Trans. Software Eng. 2022 [paper](https://arxiv.org/abs/1906.10742) [bib](/bib/Machine-Learning/General-Machine-Learning/Zhang2022Machine.md)

    *Jie M. Zhang, Mark Harman, Lei Ma, Yang Liu*

33. **Machine Learning that Matters.** ICML 2012 [paper](https://arxiv.org/abs/1206.4656) [bib](/bib/Machine-Learning/General-Machine-Learning/Wagstaff2012Machine.md)

    *Kiri Wagstaff*

34. **Machine Learning with World Knowledge: The Position and Survey.** arXiv 2017 [paper](https://arxiv.org/abs/1705.02908) [bib](/bib/Machine-Learning/General-Machine-Learning/Song2017Machine.md)

    *Yangqiu Song, Dan Roth*

35. **Mean-Field Learning: a Survey.** arXiv 2012 [paper](https://arxiv.org/abs/1210.4657) [bib](/bib/Machine-Learning/General-Machine-Learning/Tembine2012Mean-Field.md)

    *Hamidou Tembine, Raúl Tempone, Pedro Vilanova*

36. **Multidimensional Scaling, Sammon Mapping, and Isomap: Tutorial and Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2009.08136) [bib](/bib/Machine-Learning/General-Machine-Learning/Ghojogh2020Multidimensional.md)

    *Benyamin Ghojogh, Ali Ghodsi, Fakhri Karray, Mark Crowley*

37. **Multimodal Machine Learning: A Survey and Taxonomy.** IEEE Trans. Pattern Anal. Mach. Intell. 2019 [paper](https://arxiv.org/abs/1705.09406) [bib](/bib/Machine-Learning/General-Machine-Learning/Baltrusaitis2019Multimodal.md)

    *Tadas Baltrusaitis, Chaitanya Ahuja, Louis-Philippe Morency*

38. **Multi-Objective Multi-Agent Decision Making: A Utility-based Analysis and Survey.** AAMAS 2020 [paper](https://link.springer.com/content/pdf/10.1007/s10458-019-09433-x.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Radulescu2020Multi-Objective.md)

    *Roxana Radulescu, Patrick Mannion, Diederik M. Roijers, Ann Nowé*

39. **Rational Kernels: A survey.** arXiv 2019 [paper](https://arxiv.org/pdf/1910.13800.pdf) [bib](/bib/Machine-Learning/General-Machine-Learning/Ghose2019Rational.md)

    *Abhishek Ghose*

40. **Statistical Queries and Statistical Algorithms: Foundations and Applications.** arXiv 2020 [paper](https://arxiv.org/abs/2004.00557) [bib](/bib/Machine-Learning/General-Machine-Learning/Reyzin2020Statistical.md)

    *Lev Reyzin*

41. **Structure Learning of Probabilistic Graphical Models: A Comprehensive Survey.** arXiv 2011 [paper](https://arxiv.org/abs/1111.6925) [bib](/bib/Machine-Learning/General-Machine-Learning/Zhou2011Structure.md)

    *Yang Zhou*

42. **Survey & Experiment: Towards the Learning Accuracy.** arXiv 2010 [paper](https://arxiv.org/abs/1012.4051) [bib](/bib/Machine-Learning/General-Machine-Learning/Zhu2010Survey.md)

    *Zeyuan Allen Zhu*

43. **Survey on Feature Selection.** arXiv 2015 [paper](https://arxiv.org/abs/1510.02892) [bib](/bib/Machine-Learning/General-Machine-Learning/Abdallah2015Survey.md)

    *Tarek Amr Abdallah, Beatriz de la Iglesia*

44. **Survey on Multi-output Learning.** IEEE Trans. Neural Networks Learn. Syst. 2020 [paper](https://arxiv.org/abs/1901.00248) [bib](/bib/Machine-Learning/General-Machine-Learning/Xu2020Survey.md)

    *Donna Xu, Yaxin Shi, Ivor W. Tsang, Yew-Soon Ong, Chen Gong, Xiaobo Shen*

45. **Survey: Machine Learning in Production Rendering.** arXiv 2020 [paper](https://arxiv.org/abs/2005.12518) [bib](/bib/Machine-Learning/General-Machine-Learning/Zhu2020Survey.md)

    *Shilin Zhu*

46. **The Benefits of Population Diversity in Evolutionary Algorithms: A Survey of Rigorous Runtime Analyses.** arXiv 2018 [paper](https://arxiv.org/abs/1801.10087) [bib](/bib/Machine-Learning/General-Machine-Learning/Sudholt2018The.md)

    *Dirk Sudholt*

47. **Towards Causal Representation Learning.** arXiv 2021 [paper](https://arxiv.org/abs/2102.11107) [bib](/bib/Machine-Learning/General-Machine-Learning/Schölkopf2021Towards.md)

    *Bernhard Schölkopf, Francesco Locatello, Stefan Bauer, Nan Rosemary Ke, Nal Kalchbrenner, Anirudh Goyal, Yoshua Bengio*

48. **Verification for Machine Learning, Autonomy, and Neural Networks Survey.** arXiv 2018 [paper](https://arxiv.org/abs/1810.01989) [bib](/bib/Machine-Learning/General-Machine-Learning/Xiang2018Verification.md)

    *Weiming Xiang, Patrick Musau, Ayana A. Wild, Diego Manzanas Lopez, Nathaniel Hamilton, Xiaodong Yang, Joel A. Rosenfeld, Taylor T. Johnson*

49. **What Can Knowledge Bring to Machine Learning? - A Survey of Low-shot Learning for Structured Data.** arXiv 2021 [paper](https://arxiv.org/abs/2106.06410) [bib](/bib/Machine-Learning/General-Machine-Learning/Hu2021What.md)

    *Yang Hu, Adriane Chapman, Guihua Wen, Wendy Hall*

50. **机器学习的五大类别及其主要算法综述.** 软件导刊 2019 [paper](http://www.rjdk.org/thesisDetails#10.11907/rjdk.182932&lang=zh) [bib](/bib/Machine-Learning/General-Machine-Learning/Li2019Survey.md)

    *李旭然, 丁晓红*

#### [Generative Adversarial Networks](#content)

1. **A Review of Generative Adversarial Networks in Cancer Imaging: New Applications, New Solutions.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.09543.pdf) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Osuala2021A.md)

    *Richard Osuala, Kaisar Kushibar, Lidia Garrucho, Akis Linardos, Zuzanna Szafranowska, Stefan Klein, Ben Glocker, Oliver Díaz, Karim Lekadir*

2. **A Review on Generative Adversarial Networks: Algorithms, Theory, and Applications.** arXiv 2020 [paper](https://arxiv.org/abs/2001.06937) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Gui2020A.md)

    *Jie Gui, Zhenan Sun, Yonggang Wen, Dacheng Tao, Jieping Ye*

3. **A Survey on Generative Adversarial Networks: Variants, Applications, and Training.** ACM Comput. Surv. 2022 [paper](https://arxiv.org/abs/2006.05132) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Jabbar2022A.md)

    *Abdul Jabbar, Xi Li, Bourahla Omar*

4. **Deep Generative Modelling: A Comparative Review of VAEs, GANs, Normalizing Flows, Energy-Based and Autoregressive Models.** arXiv 2021 [paper](https://arxiv.org/abs/2103.04922) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Bond-Taylor2021Deep.md)

    *Sam Bond-Taylor, Adam Leach, Yang Long, Chris G. Willcocks*

5. **GAN Computers Generate Arts? A Survey on Visual Arts, Music, and Literary Text Generation using Generative Adversarial Network.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.03857.pdf) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Shahriar2021GAN.md)

    *Sakib Shahriar*

6. **GAN Inversion: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2101.05278.pdf) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Xia2021GAN.md)

    *Weihao Xia, Yulun Zhang, Yujiu Yang, Jing-Hao Xue, Bolei Zhou, Ming-Hsuan Yang*

7. **Generative Adversarial Networks in Computer Vision: A Survey and Taxonomy.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/1906.01529) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Wang2021Generative.md)

    *Zhengwei Wang, Qi She, Tomás E. Ward*

8. **Generative Adversarial Networks in Human Emotion Synthesis: A Review.** IEEE Access 2020 [paper](https://ieeexplore.ieee.org/document/9279199) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Hajarolasvadi2020Generative.md)

    *Noushin Hajarolasvadi, Miguel Arjona Ramírez, Wesley Beccaro, Hasan Demirel*

9. **Generative Adversarial Networks: A Survey Towards Private and Secure Applications.** arXiv 2021 [paper](https://arxiv.org/abs/2106.03785) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Cai2021Generative.md)

    *Zhipeng Cai, Zuobin Xiong, Honghui Xu, Peng Wang, Wei Li, Yi Pan*

10. **Generative Adversarial Networks: An Overview.** IEEE Signal Process. Mag. 2018 [paper](https://arxiv.org/abs/1710.07035) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Creswell2018Generative.md)

    *Antonia Creswell, Tom White, Vincent Dumoulin, Kai Arulkumaran, Biswa Sengupta, Anil A. Bharath*

11. **How Generative Adversarial Networks and Their Variants Work: An Overview.** ACM Comput. Surv. 2019 [paper](https://arxiv.org/abs/1711.05914) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Hong2019How.md)

    *Yongjun Hong, Uiwon Hwang, Jaeyoon Yoo, Sungroh Yoon*

12. **Stabilizing Generative Adversarial Networks: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1910.00927) [bib](/bib/Machine-Learning/Generative-Adversarial-Networks/Wiatrak2019Stabilizing.md)

    *Maciej Wiatrak, Stefano V. Albrecht, Andrew Nystrom*

#### [Graph Neural Networks](#content)

1. **A Comprehensive Survey of Graph Embedding: Problems, Techniques, and Applications.** IEEE Trans. Knowl. Data Eng. 2018 [paper](https://ieeexplore.ieee.org/abstract/document/8294302) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Cai2018A.md)

    *Hongyun Cai, Vincent W. Zheng, Kevin Chen-Chuan Chang*

2. **A Comprehensive Survey on Graph Neural Networks.** IEEE Trans. Neural Networks Learn. Syst. 2021 [paper](https://arxiv.org/abs/1901.00596) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Wu2021A.md)

    *Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu*

3. **A Survey on Graph Neural Networks for Knowledge Graph Completion.** arXiv 2020 [paper](http://arxiv.org/pdf/2007.12374.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Arora2020A.md)

    *Siddhant Arora*

4. **A Survey on Graph Structure Learning: Progress and Opportunities.** arXiv 2021 [paper](https://arxiv.org/abs/2103.03036) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Zhu2021A.md)

    *Yanqiao Zhu, Weizhi Xu, Jinghao Zhang, Yuanqi Du, Jieyu Zhang, Qiang Liu, Carl Yang, Shu Wu*

5. **A Survey on Heterogeneous Graph Embedding: Methods, Techniques, Applications and Sources.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.14867.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Wang2020A.md)

    *Xiao Wang, Deyu Bo, Chuan Shi, Shaohua Fan, Yanfang Ye, Philip S. Yu*

6. **A Survey on The Expressive Power of Graph Neural Networks.** arXiv 2020 [paper](https://arxiv.org/abs/2003.04078) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Sato2020A.md)

    *Ryoma Sato*

7. **A Systematic Survey on Deep Generative Models for Graph Generation.** arXiv 2020 [paper](https://arxiv.org/pdf/2007.06686.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Guo2020A.md)

    *Xiaojie Guo, Liang Zhao*

8. **Adversarial Attack and Defense on Graph Data: A Survey.** arXiv 2018 [paper](https://arxiv.org/abs/1812.10528) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Sun2018Adversarial.md)

    *Lichao Sun, Ji Wang, Philip S. Yu, Bo Li*

9. **Bridging the Gap between Spatial and Spectral Domains: A Survey on Graph Neural Networks.** arXiv 2020 [paper](https://arxiv.org/abs/2002.11867) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Chen2020Bridging.md)

    *Zhiqian Chen, Fanglan Chen, Lei Zhang, Taoran Ji, Kaiqun Fu, Liang Zhao, Feng Chen, Chang-Tien Lu*

10. **Computing Graph Neural Networks: A Survey from Algorithms to Accelerators.** ACM Comput. Surv. 2022 [paper](http://arxiv.org/pdf/2010.00130.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Abadal2022Computing.md)

    *Sergi Abadal, Akshay Jain, Robert Guirado, Jorge López-Alonso, Eduard Alarcón*

11. **Deep Graph Similarity Learning: A Survey.** Data Min. Knowl. Discov. 2021 [paper](https://arxiv.org/pdf/1912.11615.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Ma2021Deep.md)

    *Guixiang Ma, Nesreen K. Ahmed, Theodore L. Willke, Philip S. Yu*

12. **Deep Learning on Graphs: A Survey.** IEEE Trans. Knowl. Data Eng. 2022 [paper](https://arxiv.org/abs/1812.04202) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Zhang2022Deep.md)

    *Ziwei Zhang, Peng Cui, Wenwu Zhu*

13. **Explainability in Graph Neural Networks: A Taxonomic Survey.** arXiv 2020 [paper](http://arxiv.org/pdf/2012.15445.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Yuan2020Explainability.md)

    *Hao Yuan, Haiyang Yu, Shurui Gui, Shuiwang Ji*

14. **Foundations and modelling of dynamic networks using Dynamic Graph Neural Networks: A survey.** arXiv 2020 [paper](https://arxiv.org/abs/2005.07496) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Skarding2020Foundations.md)

    *Joakim Skarding, Bogdan Gabrys, Katarzyna Musial*

15. **Graph Embedding Techniques, Applications, and Performance: A Survey.** Knowl. Based Syst. 2018 [paper](https://arxiv.org/abs/1705.02801) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Goyal2018Graph.md)

    *Palash Goyal, Emilio Ferrara*

16. **Graph Learning for Combinatorial Optimization: A Survey of State-of-the-Art.** Data Sci. Eng. 2021 [paper](https://arxiv.org/pdf/2008.12646.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Peng2021Graph.md)

    *Yun Peng, Byron Choi, Jianliang Xu*

17. **Graph Learning: A Survey.** IEEE Trans. Artif. Intell. 2021 [paper](https://arxiv.org/pdf/2105.00696.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Xia2021Graph.md)

    *Feng Xia, Ke Sun, Shuo Yu, Abdul Aziz, Liangtian Wan, Shirui Pan, Huan Liu*

18. **Graph Neural Network for Traffic Forecasting: A Survey.** arXiv 2021 [paper](http://arxiv.org/pdf/2101.11174.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Jiang2021Graph.md)

    *Weiwei Jiang, Jiayun Luo*

19. **Graph Neural Networks for Natural Language Processing: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.06090.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Wu2021Graph.md)

    *Lingfei Wu, Yu Chen, Kai Shen, Xiaojie Guo, Hanning Gao, Shucheng Li, Jian Pei, Bo Long*

20. **Graph Neural Networks Meet Neural-Symbolic Computing: A Survey and Perspective.** IJCAI 2020 [paper](https://arxiv.org/abs/2003.00330) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Lamb2020Graph.md)

    *Luís C. Lamb, Artur S. d'Avila Garcez, Marco Gori, Marcelo O. R. Prates, Pedro H. C. Avelar, Moshe Y. Vardi*

21. **Graph Neural Networks: A Review of Methods and Applications.** AI Open 2020 [paper](https://arxiv.org/abs/1812.08434) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Zhou2020Graph1.md)

    *Jie Zhou, Ganqu Cui, Shengding Hu, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Lifeng Wang, Changcheng Li, Maosong Sun*

22. **Graph Neural Networks: Methods, Applications, and Opportunities.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.10733.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Waikhom2021Graph.md)

    *Lilapati Waikhom, Ripon Patgiri*

23. **Graph Neural Networks: Taxonomy, Advances and Trends.** arXiv 2020 [paper](https://arxiv.org/pdf/2012.08752.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Zhou2020Graph.md)

    *Yu Zhou, Haixia Zheng, Xin Huang*

24. **Graph Representation Learning: A Survey.** APSIPA Transactions on Signal and Information Processing 2020 [paper](https://arxiv.org/abs/1909.00958) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Chen2020Graph.md)

    *Fenxiao Chen, Yuncheng Wang, Bin Wang, C.-C. Jay Kuo*

25. **Graph Self-Supervised Learning: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2103.00111) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Liu2021Graph.md)

    *Yixin Liu, Shirui Pan, Ming Jin, Chuan Zhou, Feng Xia, Philip S. Yu*

26. **Graph-Based Deep Learning for Medical Diagnosis and Analysis: Past, Present and Future.** Sensors 2021 [paper](https://arxiv.org/pdf/2105.13137.pdf) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Ahmedt-Aristizabal2021Graph-Based.md)

    *David Ahmedt-Aristizabal, Mohammad Ali Armin, Simon Denman, Clinton Fookes, Lars Petersson*

27. **Introduction to Graph Neural Networks.** Synthesis Lectures on Artificial Intelligence and Machine Learning 2020 [paper](https://ieeexplore.ieee.org/document/9048171) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Liu2020Introduction.md)

    *Zhiyuan Liu, Jie Zhou*

28. **Learning Representations of Graph Data - A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1906.02989) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Kinderkhedia2019Learning.md)

    *Mital Kinderkhedia*

29. **Meta-Learning with Graph Neural Networks: Methods and Applications.** arXiv 2021 [paper](https://arxiv.org/abs/2103.00137) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Mandal2021Meta-Learning.md)

    *Debmalya Mandal, Sourav Medya, Brian Uzzi, Charu Aggarwal*

30. **Representation Learning for Dynamic Graphs: A Survey.** J. Mach. Learn. Res. 2020 [paper](https://arxiv.org/abs/1905.11485) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Kazemi2020Representation.md)

    *Seyed Mehran Kazemi, Rishab Goel, Kshitij Jain, Ivan Kobyzev, Akshay Sethi, Peter Forsyth, Pascal Poupart*

31. **Robustness of deep learning models on graphs: A survey.** AI Open 2021 [paper](https://www.sciencedirect.com/science/article/pii/S2666651021000139) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Xu2021Robustness.md)

    *Jiarong Xu, Junru Chen, Siqi You, Zhiqing Xiao, Yang Yang, Jiangang Lu*

32. **Self-Supervised Learning of Graph Neural Networks: A Unified Review.** arXiv 2021 [paper](https://arxiv.org/abs/2102.10757) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Xie2021Self-Supervised.md)

    *Yaochen Xie, Zhao Xu, Zhengyang Wang, Shuiwang Ji*

33. **Survey of Image Based Graph Neural Networks.** arXiv 2021 [paper](https://arxiv.org/abs/2106.06307) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Nazir2021Survey.md)

    *Usman Nazir, He Wang, Murtaza Taj*

34. **Tackling Graphical NLP problems with Graph Recurrent Networks.** arXiv 2019 [paper](https://arxiv.org/abs/1907.06142) [bib](/bib/Machine-Learning/Graph-Neural-Networks/Song2019Tackling.md)

    *Linfeng Song*

#### [Interpretability and Analysis](#content)

1. **A brief survey of visualization methods for deep learning models from the perspective of Explainable AI.** macs.hw.ac.uk 2018 [paper](http://www.macs.hw.ac.uk/~ic14/IoannisChalkiadakis_RRR.pdf) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Chalkiadakis2018A.md)

    *Ioannis Chalkiadakis*

2. **A Survey of Methods for Explaining Black Box Models.** ACM Comput. Surv. 2019 [paper](https://dl.acm.org/doi/10.1145/3236009) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Guidotti2019A.md)

    *Riccardo Guidotti, Anna Monreale, Salvatore Ruggieri, Franco Turini, Fosca Giannotti, Dino Pedreschi*

3. **A Survey on Explainable Artificial Intelligence (XAI): Toward Medical XAI.** IEEE Trans. Neural Networks Learn. Syst. 2021 [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9233366) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Tjoa2021A.md)

    *Erico Tjoa, Cuntai Guan*

4. **A Survey on Knowledge integration techniques with Artificial Neural Networks for seq-2-seq/time series models.** arXiv 2020 [paper](https://arxiv.org/pdf/2008.05972.pdf) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Vadiraja2020A.md)

    *Pramod Vadiraja, Muhammad Ali Chattha*

5. **A Survey on Neural Network Interpretability.** IEEE Trans. Emerg. Top. Comput. Intell. 2021 [paper](https://arxiv.org/pdf/2012.14261.pdf) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Zhang2021A.md)

    *Yu Zhang, Peter Tiño, Ales Leonardis, Ke Tang*

6. **A Survey on the Explainability of Supervised Machine Learning.** J. Artif. Intell. Res. 2021 [paper](https://arxiv.org/abs/2011.07876) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Burkart2021A.md)

    *Nadia Burkart, Marco F. Huber*

7. **A Survey on Understanding, Visualizations, and Explanation of Deep Neural Networks.** arXiv 2021 [paper](https://arxiv.org/abs/2102.01792) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Shahroudnejad2021A.md)

    *Atefeh Shahroudnejad*

8. **Benchmarking and Survey of Explanation Methods for Black Box Models.** arXiv 2021 [paper](https://arxiv.org/pdf/2102.13076.pdf) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Bodria2021Benchmarking.md)

    *Francesco Bodria, Fosca Giannotti, Riccardo Guidotti, Francesca Naretto, Dino Pedreschi, Salvatore Rinzivillo*

9. **Causal Interpretability for Machine Learning - Problems, Methods and Evaluation.** SIGKDD Explor. 2020 [paper](https://arxiv.org/abs/2003.03934) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Moraffah2020Causal.md)

    *Raha Moraffah, Mansooreh Karami, Ruocheng Guo, Adrienne Raglin, Huan Liu*

10. **Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities and Challenges toward Responsible AI.** Inf. Fusion 2020 [paper](https://arxiv.org/abs/1910.10045) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Arrieta2020Explainable.md)

    *Alejandro Barredo Arrieta, Natalia Díaz Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador García, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera*

11. **Explainable Artificial Intelligence Approaches: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2101.09429) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Islam2021Explainable.md)

    *Sheikh Rabiul Islam, William Eberle, Sheikh Khaled Ghafoor, Mohiuddin Ahmed*

12. **Explainable artificial intelligence: A survey.** MIPRO 2018 [paper](https://ieeexplore.ieee.org/document/8400040) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Dosilovic2018Explainable.md)

    *Filip Karlo Dosilovic, Mario Brcic, Nikica Hlupic*

13. **Explainable Automated Fact-Checking: A Survey.** COLING 2020 [paper](https://arxiv.org/pdf/2011.03870.pdf) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Kotonya2020Explainable.md)

    *Neema Kotonya, Francesca Toni*

14. **Explainable Reinforcement Learning: A Survey.** CD-MAKE 2020 [paper](https://arxiv.org/abs/2005.06247) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Puiutta2020Explainable.md)

    *Erika Puiutta, Eric M. S. P. Veith*

15. **Foundations of Explainable Knowledge-Enabled Systems.** Knowledge Graphs for eXplainable Artificial Intelligence 2020 [paper](https://arxiv.org/abs/2003.07520) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Chari2020Foundations.md)

    *Shruthi Chari, Daniel M. Gruen, Oshani Seneviratne, Deborah L. McGuinness*

16. **How convolutional neural networks see the world - A survey of convolutional neural network visualization methods.** Math. Found. Comput. 2018 [paper](https://arxiv.org/abs/1804.11191) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Qin2018How.md)

    *Zhuwei Qin, Fuxun Yu, Chenchen Liu, Xiang Chen*

17. **Interpretable Machine Learning - A Brief History, State-of-the-Art and Challenges.** PKDD/ECML Workshops 2020 [paper](https://arxiv.org/abs/2010.09337) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Molnar2020Interpretable.md)

    *Christoph Molnar, Giuseppe Casalicchio, Bernd Bischl*

18. **Machine Learning Interpretability: A Survey on Methods and Metrics.** Electronics 2019 [paper](http://www.socolar.com/Article/Index?aid=100018215892&jid=100000022108) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Carvalho2019Machine.md)

    *Diogo V. Carvalho, Eduardo M. Pereira, Jaime S. Cardoso*

19. **On Interpretability of Artificial Neural Networks: A Survey.** IEEE Transactions on Radiation and Plasma Medical Sciences 2021 [paper](https://arxiv.org/pdf/2001.02522) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Fan2021On.md)

    *Feng-Lei Fan, Jinjun Xiong, Mengzhou Li, Ge Wang*

20. **On the computation of counterfactual explanations - A survey.** arXiv 2019 [paper](https://arxiv.org/pdf/1911.07749.pdf) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Artelt2019On.md)

    *André Artelt, Barbara Hammer*

21. **Opportunities and Challenges in Explainable Artificial Intelligence (XAI): A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2006.11371) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Das2020Opportunities.md)

    *Arun Das, Paul Rad*

22. **Peeking Inside the Black-Box: A Survey on Explainable Artificial Intelligence (XAI).** IEEE Access 2018 [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8466590) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Adadi2018Peeking.md)

    *Amina Adadi, Mohammed Berrada*

23. **Survey of explainable machine learning with visual and granular methods beyond quasi-explanations.** arXiv 2020 [paper](https://arxiv.org/abs/2009.10221) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Kovalerchuk2020Survey.md)

    *Boris Kovalerchuk, Muhammad Aurangzeb Ahmad, Ankur Teredesai*

24. **Understanding Neural Networks via Feature Visualization: A survey.** Explainable AI 2019 [paper](https://arxiv.org/abs/1904.08939) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Nguyen2019Understanding.md)

    *Anh Nguyen, Jason Yosinski, Jeff Clune*

25. **Visual Analytics in Deep Learning: An Interrogative Survey for the Next Frontiers.** IEEE Trans. Vis. Comput. Graph. 2019 [paper](https://arxiv.org/abs/1801.06889) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Hohman2019Visual.md)

    *Fred Hohman, Minsuk Kahng, Robert Pienta, Duen Horng Chau*

26. **Visual Interpretability for Deep Learning: a Survey.** Frontiers Inf. Technol. Electron. Eng. 2018 [paper](https://arxiv.org/abs/1802.00614) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Zhang2018Visual.md)

    *Quanshi Zhang, Song-Chun Zhu*

27. **Visualisation of Pareto Front Approximation: A Short Survey and Empirical Comparisons.** CEC 2019 [paper](https://arxiv.org/abs/1903.01768) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Gao2019Visualisation.md)

    *Huiru Gao, Haifeng Nie, Ke Li*

28. **When will the mist clear? On the Interpretability of Machine Learning for Medical Applications: a survey.** arXiv 2020 [paper](https://arxiv.org/abs/2010.00353) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Banegas-Luna2020When.md)

    *Antonio-Jesús Banegas-Luna, Jorge Peña-García, Adrian Iftene, Fiorella Guadagni, Patrizia Ferroni, Noemi Scarpato, Fabio Massimo Zanzotto, Andrés Bueno-Crespo, Horacio Pérez Sánchez*

29. **XAI Methods for Neural Time Series Classification: A Brief Review.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.08009.pdf) [bib](/bib/Machine-Learning/Interpretability-and-Analysis/Simic2021XAI.md)

    *Ilija Simic, Vedran Sabol, Eduardo E. Veas*

#### [Knowledge Distillation](#content)

1. **A Selective Survey on Versatile Knowledge Distillation Paradigm for Neural Network Models.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.14554.pdf) [bib](/bib/Machine-Learning/Knowledge-Distillation/Ku2020A.md)

    *Jeong-Hoe Ku, Jihun Oh, Young-Yoon Lee, Gaurav Pooniwala, SangJeong Lee*

2. **Knowledge Distillation: A Survey.** Int. J. Comput. Vis. 2021 [paper](https://arxiv.org/abs/2006.05525) [bib](/bib/Machine-Learning/Knowledge-Distillation/Gou2021Knowledge.md)

    *Jianping Gou, Baosheng Yu, Stephen J. Maybank, Dacheng Tao*

#### [Meta Learning](#content)

1. **A Comprehensive Overview and Survey of Recent Advances in Meta-Learning.** arXiv 2020 [paper](https://arxiv.org/abs/2004.11149) [bib](/bib/Machine-Learning/Meta-Learning/Peng2020A.md)

    *Huimin Peng*

2. **A Survey of Deep Meta-Learning.** Artif. Intell. Rev. 2021 [paper](https://arxiv.org/pdf/2010.03522.pdf) [bib](/bib/Machine-Learning/Meta-Learning/Huisman2021A.md)

    *Mike Huisman, Jan N. van Rijn, Aske Plaat*

3. **Meta-learning for Few-shot Natural Language Processing: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2007.09604) [bib](/bib/Machine-Learning/Meta-Learning/Yin2020Meta-learning.md)

    *Wenpeng Yin*

4. **Meta-Learning in Neural Networks: A Survey.** TPAMI 2021 [paper](https://arxiv.org/abs/2004.05439) [bib](/bib/Machine-Learning/Meta-Learning/Hospedales2021Meta-Learning.md)

    *Timothy Hospedales, Antreas Antoniou, Paul Micaelli, Amos Storkey*

5. **Meta-Learning: A Survey.** arXiv 2018 [paper](https://arxiv.org/abs/1810.03548) [bib](/bib/Machine-Learning/Meta-Learning/Vanschoren2018Meta-Learning.md)

    *Joaquin Vanschoren*

#### [Metric Learning](#content)

1. **A Survey on Metric Learning for Feature Vectors and Structured Data.** arXiv 2013 [paper](https://arxiv.org/abs/1306.6709) [bib](/bib/Machine-Learning/Metric-Learning/Bellet2013A.md)

    *Aurélien Bellet, Amaury Habrard, Marc Sebban*

2. **A Tutorial on Distance Metric Learning: Mathematical Foundations, Algorithms, Experimental Analysis, Prospects and Challenges.** Neurocomputing 2021 [paper](https://arxiv.org/abs/1812.05944) [bib](/bib/Machine-Learning/Metric-Learning/Suárez2021A.md)

    *Juan-Luis Suárez, Salvador García, Francisco Herrera*

#### [ML and DL Applications](#content)

1. **A Comprehensive Survey on Deep Music Generation: Multi-level Representations, Algorithms, Evaluations, and Future Directions.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.06801.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Ji2020A.md)

    *Shulei Ji, Jing Luo, Xinyu Yang*

2. **A Comprehensive Survey on Graph Anomaly Detection with Deep Learning.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.07178.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Ma2021A.md)

    *Xiaoxiao Ma, Jia Wu, Shan Xue, Jian Yang, Quan Z. Sheng, Hui Xiong*

3. **A Comprehensive Survey on Machine Learning Techniques and User Authentication Approaches for Credit Card Fraud Detection.** arXiv 2019 [paper](https://arxiv.org/pdf/1912.02629.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Yousefi2019A.md)

    *Niloofar Yousefi, Marie Alaghband, Ivan Garibay*

4. **A guide to deep learning in healthcare.** Nature Medicine 2019 [paper](https://www.nature.com/articles/s41591-018-0316-z) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Esteva2019A.md)

    *Andre Esteva, Alexandre Robicquet, Bharath Ramsundar, Volodymyr Kuleshov, Mark DePristo, Katherine Chou, Claire Cui, Greg Corrado, Sebastian Thrun, Jeff Dean*

5. **A Survey of Deep Learning Applications to Autonomous Vehicle Control.** IEEE Trans. Intell. Transp. Syst. 2021 [paper](https://arxiv.org/pdf/1912.10773.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Kuutti2021A.md)

    *Sampo Kuutti, Richard Bowden, Yaochu Jin, Phil Barber, Saber Fallah*

6. **A Survey of Deep Learning Techniques for Autonomous Driving.** J. Field Robotics 2020 [paper](https://arxiv.org/pdf/1910.07738.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Grigorescu2020A.md)

    *Sorin Mihai Grigorescu, Bogdan Trasnea, Tiberiu T. Cocias, Gigel Macesanu*

7. **A Survey of Machine Learning for Computer Architecture and Systems.** arXiv 2021 [paper](https://arxiv.org/abs/2102.07952) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Wu2021A.md)

    *Nan Wu, Yuan Xie*

8. **A Survey of Machine Learning Techniques for Detecting and Diagnosing COVID-19 from Imaging.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.04344.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Panday2021A.md)

    *Aishwarza Panday, Muhammad Ashad Kabir, Nihad Karim Chowdhury*

9. **A Survey on Anomaly Detection for Technical Systems using LSTM Networks.** Comput. Ind. 2021 [paper](https://arxiv.org/abs/2105.13810) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Lindemann2021A.md)

    *Benjamin Lindemann, Benjamin Maschler, Nada Sahlab, Michael Weyrich*

10. **A Survey on Deep Learning-based Non-Invasive Brain Signals:Recent Advances and New Frontiers.** Journal of Neural Engineering 2021 [paper](https://arxiv.org/abs/1905.04149) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Zhang2021A.md)

    *Xiang Zhang, Lina Yao, Xianzhi Wang, Jessica Monaghan, David McAlpine, Yu Zhang*

11. **A Survey on Machine Learning Applied to Dynamic Physical Systems.** arXiv 2020 [paper](https://arxiv.org/pdf/2009.09719.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Verma2020A.md)

    *Sagar Verma*

12. **A Survey on Practical Applications of Multi-Armed and Contextual Bandits.** arXiv 2019 [paper](https://arxiv.org/pdf/1904.10040.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Bouneffouf2019A.md)

    *Djallel Bouneffouf, Irina Rish*

13. **A Survey on Spatial and Spatiotemporal Prediction Methods.** arXiv 2020 [paper](https://arxiv.org/pdf/2012.13384.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Jiang2020A.md)

    *Zhe Jiang*

14. **A Survey on the Use of AI and ML for Fighting the COVID-19 Pandemic.** arXiv 2020 [paper](https://arxiv.org/pdf/2008.07449.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Islam2020A.md)

    *Muhammad Nazrul Islam, Toki Tahmid Inan, Suzzana Rafi, Syeda Sabrina Akter, Iqbal H. Sarker, A. K. M. Najmul Islam*

15. **A Survey on Traffic Signal Control Methods.** arXiv 2019 [paper](https://arxiv.org/pdf/1904.08117.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Wei2019A.md)

    *Hua Wei, Guanjie Zheng, Vikash V. Gayah, Zhenhui Li*

16. **Aesthetics, Personalization and Recommendation: A survey on Deep Learning in Fashion.** arXiv 2021 [paper](https://arxiv.org/abs/2101.08301) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Gong2021Aesthetics.md)

    *Wei Gong, Laila Khalid*

17. **Artificial Neural Networks-Based Machine Learning for Wireless Networks: A Tutorial.** IEEE Commun. Surv. Tutorials 2019 [paper](https://ieeexplore.ieee.org/document/8755300) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Chen2019Artificial.md)

    *Mingzhe Chen, Ursula Challita, Walid Saad, Changchuan Yin, Mérouane Debbah*

18. **Classification of Pathological and Normal Gait: A Survey.** arXiv 2020 [paper](https://arxiv.org/pdf/2012.14465.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Saxe2020Classification.md)

    *Ryan C. Saxe, Samantha Kappagoda, David K. A. Mordecai*

19. **Classification supporting COVID-19 diagnostics based on patient survey data.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.12247.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Henzel2020Classification.md)

    *Joanna Henzel, Joanna Tobiasz, Michal Kozielski, Malgorzata Bach, Pawel Foszner, Aleksandra Gruca, Mateusz Kania, Justyna Mika, Anna Papiez, Aleksandra Werner, Joanna Zyla, Jerzy Jaroszewicz, Joanna Polanska, Marek Sikora*

20. **Credit card fraud detection using machine learning: A survey.** arXiv 2020 [paper](https://arxiv.org/pdf/2010.06479.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Lucas2020Credit.md)

    *Yvan Lucas, Johannes Jurgovsky*

21. **Deep Learning for Click-Through Rate Estimation.** IJCAI 2021 [paper](https://arxiv.org/pdf/2104.10584.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Zhang2021Deep.md)

    *Weinan Zhang, Jiarui Qin, Wei Guo, Ruiming Tang, Xiuqiang He*

22. **Deep Learning for Spatio-Temporal Data Mining: A Survey.** arXiv 2019 [paper](https://arxiv.org/pdf/1906.04928.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Wang2019Deep.md)

    *Senzhang Wang, Jiannong Cao, Philip S. Yu*

23. **Deep learning models for predictive maintenance: a survey, comparison, challenges and prospect.** arXiv 2020 [paper](https://arxiv.org/pdf/2010.03207.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Serradilla2020Deep.md)

    *Oscar Serradilla, Ekhi Zugasti, Urko Zurutuza*

24. **Deep Learning-based Spacecraft Relative Navigation Methods: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.08876.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Song2021Deep.md)

    *Jianing Song, Duarte Rondao, Nabil Aouf*

25. **DL-Traff: Survey and Benchmark of Deep Learning Models for Urban Traffic Prediction.** CIKM 2021 [paper](https://arxiv.org/pdf/2108.09091.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Jiang2021DL-Traff.md)

    *Renhe Jiang, Du Yin, Zhaonan Wang, Yizhuo Wang, Jiewen Deng, Hangchen Liu, Zekun Cai, Jinliang Deng, Xuan Song, Ryosuke Shibasaki*

26. **Event Prediction in the Big Data Era: A Systematic Survey.** ACM Comput. Surv. 2021 [paper](https://dl.acm.org/doi/10.1145/3450287) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Zhao2021Event.md)

    *Liang Zhao*

27. **Fashion Meets Computer Vision: A Survey.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2003.13988) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Cheng2021Fashion.md)

    *Wen-Huang Cheng, Sijie Song, Chieh-Yun Chen, Shintami Chusnul Hidayati, Jiaying Liu*

28. **Going Deeper Into Face Detection: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2103.14983) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Minaee2021Going.md)

    *Shervin Minaee, Ping Luo, Zhe Lin, Kevin W. Bowyer*

29. **Graph Representation Learning in Biomedicine.** arXiv 2021 [paper](http://arxiv.org/abs/2104.04883) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Li2021Graph.md)

    *Michelle M. Li, Kexin Huang, Marinka Zitnik*

30. **Graph-based Deep Learning for Communication Networks: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2106.02533) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Jiang2021Graph-based.md)

    *Weiwei Jiang*

31. **How Developers Iterate on Machine Learning Workflows - A Survey of the Applied Machine Learning Literature.** arXiv 2018 [paper](https://arxiv.org/abs/1803.10311) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Xin2018How.md)

    *Doris Xin, Litian Ma, Shuchen Song, Aditya G. Parameswaran*

32. **Known Operator Learning and Hybrid Machine Learning in Medical Imaging - A Review of the Past, the Present, and the Future.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.04543.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Maier2021Known.md)

    *Andreas Maier, Harald Köstler, Marco Heisig, Patrick Krauss, Seung Hee Yang*

33. **Machine Learning Aided Static Malware Analysis: A Survey and Tutorial.** arXiv 2018 [paper](https://arxiv.org/abs/1808.01201) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Shalaginov2018Machine.md)

    *Andrii Shalaginov, Sergii Banin, Ali Dehghantanha, Katrin Franke*

34. **Machine Learning for Cataract Classification and Grading on Ophthalmic Imaging Modalities: A Survey.** arXiv 2020 [paper](http://arxiv.org/pdf/2012.04830.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Zhang2020Machine.md)

    *Xiaoqing Zhang, Jiansheng Fang, Yan Hu, Yanwu Xu, Risa Higashita, Jiang Liu*

35. **Machine Learning for Electronic Design Automation: A Survey.** ACM Trans. Design Autom. Electr. Syst. 2021 [paper](https://arxiv.org/abs/2102.03357) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Huang2021Machine.md)

    *Guyue Huang, Jingbo Hu, Yifan He, Jialong Liu, Mingyuan Ma, Zhaoyang Shen, Juejian Wu, Yuanfan Xu, Hengrui Zhang, Kai Zhong, Xuefei Ning, Yuzhe Ma, Haoyu Yang, Bei Yu, Huazhong Yang, Yu Wang*

36. **Machine Learning for Survival Analysis: A Survey.** ACM Comput. Surv. 2019 [paper](https://arxiv.org/abs/1708.04649) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Wang2019Machine.md)

    *Ping Wang, Yan Li, Chandan K. Reddy*

37. **Medical Image Segmentation using 3D Convolutional Neural Networks: A Review.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.08467.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Niyas2021Medical.md)

    *S. Niyas, S. J. Pawan, M. Anand Kumar, Jeny Rajan*

38. **Physics-Guided Deep Learning for Dynamical Systems: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2107.01272) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Wang2021Physics-Guided.md)

    *Rui Wang*

39. **Predicting the Future from First Person (Egocentric) Vision: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2107.13411.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Rodin2021Predicting.md)

    *Ivan Rodin, Antonino Furnari, Dimitrios Mavroedis, Giovanni Maria Farinella*

40. **Prediction of neonatal mortality in Sub-Saharan African countries using data-level linkage of multiple surveys.** arXiv 2020 [paper](https://arxiv.org/pdf/2011.12707.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Tadesse2020Prediction.md)

    *Girmaw Abebe Tadesse, Celia Cintas, Skyler Speakman, Komminist Weldemariam*

41. **Requirement Engineering Challenges for AI-intense Systems Development.** WAIN@ICSE 2021 [paper](https://arxiv.org/pdf/2103.10270.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Heyn2021Requirement.md)

    *Hans-Martin Heyn, Eric Knauss, Amna Pir Muhammad, Olof Eriksson, Jennifer Linder, Padmini Subbiah, Shameer Kumar Pradhan, Sagar Tungal*

42. **Short-term Traffic Prediction with Deep Neural Networks: A Survey.** IEEE Access 2021 [paper](https://arxiv.org/abs/2009.00712) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Lee2021Short-term.md)

    *Kyungeun Lee, Moonjung Eo, Euna Jung, Yoonjin Yoon, Wonjong Rhee*

43. **Should I Raise The Red Flag? A comprehensive survey of anomaly scoring methods toward mitigating false alarms.** arXiv 2019 [paper](https://arxiv.org/pdf/1904.06646.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Zohrevand2019Should.md)

    *Zahra Zohrevand, Uwe Glässer*

44. **The Threat of Adversarial Attacks on Machine Learning in Network Security - A Survey.** arXiv 2019 [paper](https://arxiv.org/pdf/1911.02621.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Ibitoye2019The.md)

    *Olakunle Ibitoye, Rana Abou Khamis, Ashraf Matrawy, M. Omair Shafiq*

45. **Threat of Adversarial Attacks on Deep Learning in Computer Vision: A Survey.** IEEE Access 2018 [paper](https://ieeexplore.ieee.org/abstract/document/8294186) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Akhtar2018Threat.md)

    *Naveed Akhtar, Ajmal S. Mian*

46. **Understanding racial bias in health using the Medical Expenditure Panel Survey data.** arXiv 2019 [paper](https://arxiv.org/pdf/1911.01509.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Singh2019Understanding.md)

    *Moninder Singh, Karthikeyan Natesan Ramamurthy*

47. **Urban flows prediction from spatial-temporal data using machine learning: A survey.** arXiv 2019 [paper](https://arxiv.org/pdf/1908.10218.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Xie2019Urban.md)

    *Peng Xie, Tianrui Li, Jia Liu, Shengdong Du, Xin Yang, Junbo Zhang*

48. **Using Deep Learning for Visual Decoding and Reconstruction from Brain Activity: A Review.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.04169.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Horn2021Using.md)

    *Madison Van Horn*

49. **Utilising Graph Machine Learning within Drug Discovery and Development.** arXiv 2020 [paper](https://arxiv.org/pdf/2012.05716.pdf) [bib](/bib/Machine-Learning/ML-and-DL-Applications/Gaudelet2020Utilising.md)

    *Thomas Gaudelet, Ben Day, Arian R. Jamasb, Jyothish Soman, Cristian Regep, Gertrude Liu, Jeremy B. R. Hayter, Richard Vickers, Charles Roberts, Jian Tang, David Roblin, Tom L. Blundell, Michael M. Bronstein, Jake P. Taylor-King*

#### [Model Compression and Acceleration](#content)

1. **A Survey of Model Compression and Acceleration for Deep Neural Networks.** arXiv 2017 [paper](https://arxiv.org/abs/1710.09282) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Cheng2017A.md)

    *Yu Cheng, Duo Wang, Pan Zhou, Tao Zhang*

2. **A Survey of Quantization Methods for Efficient Neural Network Inference.** arXiv 2021 [paper](https://arxiv.org/pdf/2103.13630.pdf) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Gholami2021A.md)

    *Amir Gholami, Sehoon Kim, Zhen Dong, Zhewei Yao, Michael W. Mahoney, Kurt Keutzer*

3. **A Survey on Deep Neural Network Compression: Challenges, Overview, and Solutions.** arXiv 2020 [paper](https://arxiv.org/pdf/2010.03954.pdf) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Mishra2020A.md)

    *Rahul Mishra, Hari Prabhat Gupta, Tanima Dutta*

4. **A Survey on GAN Acceleration Using Memory Compression Technique.** arXiv 2021 [paper](https://arxiv.org/pdf/2108.06626.pdf) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Tantawy2021A.md)

    *Dina Tantawy, Mohamed Zahran, Amr Wassal*

5. **A Survey on Methods and Theories of Quantized Neural Networks.** arXiv 2018 [paper](https://arxiv.org/abs/1808.04752) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Guo2018A.md)

    *Yunhui Guo*

6. **An Overview of Neural Network Compression.** arXiv 2020 [paper](https://arxiv.org/abs/2006.03669) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Neill2020An.md)

    *James O'Neill*

7. **Compression of Deep Learning Models for Text: A Survey.** ACM Trans. Knowl. Discov. Data 2022 [paper](https://arxiv.org/abs/2008.05221) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Gupta2022Compression.md)

    *Manish Gupta, Puneet Agrawal*

8. **Efficient Deep Learning: A Survey on Making Deep Learning Models Smaller, Faster, and Better.** arXiv 2021 [paper](https://arxiv.org/pdf/2106.08962.pdf) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Menghani2021Efficient.md)

    *Gaurav Menghani*

9. **Pruning Algorithms to Accelerate Convolutional Neural Networks for Edge Applications: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2005.04275) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Liu2020Pruning.md)

    *Jiayi Liu, Samarth Tripathi, Unmesh Kurup, Mohak Shah*

10. **Pruning and Quantization for Deep Neural Network Acceleration: A Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2101.09671) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Liang2021Pruning.md)

    *Tailin Liang, John Glossner, Lei Wang, Shaobo Shi*

11. **Survey of Machine Learning Accelerators.** HPEC 2020 [paper](http://arxiv.org/pdf/2009.00993.pdf) [bib](/bib/Machine-Learning/Model-Compression-and-Acceleration/Reuther2020Survey.md)

    *Albert Reuther, Peter Michaleas, Michael Jones, Vijay Gadepally, Siddharth Samsi, Jeremy Kepner*

#### [Multi-Label Learning](#content)

1. **A Review on Multi-Label Learning Algorithms.** IEEE Trans. Knowl. Data Eng. 2014 [paper](https://ieeexplore.ieee.org/abstract/document/6471714) [bib](/bib/Machine-Learning/Multi-Label-Learning/Zhang2014A.md)

    *Min-Ling Zhang, Zhi-Hua Zhou*

2. **Multi-Label Classification: An Overview.** Int. J. Data Warehous. Min. 2007 [paper](https://www.igi-global.com/article/multi-label-classification/1786) [bib](/bib/Machine-Learning/Multi-Label-Learning/Tsoumakas2007Multi-Label.md)

    *Grigorios Tsoumakas, Ioannis Katakis*

3. **Multi-label learning: a review of the state of the art and ongoing research.** WIREs Data Mining Knowl. Discov. 2014 [paper](https://wires.onlinelibrary.wiley.com/doi/abs/10.1002/widm.1139) [bib](/bib/Machine-Learning/Multi-Label-Learning/Galindo2014Multi-label.md)

    *Eva Lucrecia Gibaja Galindo, Sebastián Ventura*

4. **The Emerging Trends of Multi-Label Learning.** arXiv 2020 [paper](https://arxiv.org/abs/2011.11197) [bib](/bib/Machine-Learning/Multi-Label-Learning/Liu2020The.md)

    *Weiwei Liu, Xiaobo Shen, Haobo Wang, Ivor W. Tsang*

#### [Multi-Task and Multi-View Learning](#content)

1. **A brief review on multi-task learning.** Multim. Tools Appl. 2018 [paper](https://link.springer.com/article/10.1007/s11042-018-6463-x) [bib](/bib/Machine-Learning/Multi-Task-and-Multi-View-Learning/Thung2018A.md)

    *Kim-Han Thung, Chong-Yaw Wee*

2. **A Survey on Multi-Task Learning.** IEEE Trans. Knowl. Data Eng. 2021 [paper](https://arxiv.org/abs/1707.08114) [bib](/bib/Machine-Learning/Multi-Task-and-Multi-View-Learning/Zhang2021A.md)

    *Yu Zhang, Qiang Yang*

3. **A Survey on Multi-view Learning.** arXiv 2013 [paper](https://arxiv.org/abs/1304.5634) [bib](/bib/Machine-Learning/Multi-Task-and-Multi-View-Learning/Xu2013A.md)

    *Chang Xu, Dacheng Tao, Chao Xu*

4. **An overview of multi-task learning.** National Science Review 2017 [paper](https://academic.oup.com/nsr/article/5/1/30/4101432) [bib](/bib/Machine-Learning/Multi-Task-and-Multi-View-Learning/Zhang2017An.md)

    *Yu Zhang, Qiang Yang*

5. **An Overview of Multi-Task Learning in Deep Neural Networks.** arXiv 2017 [paper](https://arxiv.org/abs/1706.05098) [bib](/bib/Machine-Learning/Multi-Task-and-Multi-View-Learning/Ruder2017An.md)

    *Sebastian Ruder*

6. **Multi-Task Learning for Dense Prediction Tasks: A Survey.** TPAMI 2021 [paper](https://arxiv.org/pdf/2004.13379.pdf) [bib](/bib/Machine-Learning/Multi-Task-and-Multi-View-Learning/Vandenhende2021Multi-Task.md)

    *Simon Vandenhende, Stamatios Georgoulis, Wouter Van Gansbeke, Marc Proesmans, Dengxin Dai, Luc Van Gool*

7. **Multi-task learning for natural language processing in the 2020s: where are we going?.** Pattern Recognit. Lett. 2020 [paper](https://arxiv.org/pdf/2007.16008) [bib](/bib/Machine-Learning/Multi-Task-and-Multi-View-Learning/Worsham2020Multi-task.md)

    *Joseph Worsham, Jugal Kalita*

8. **Multi-Task Learning with Deep Neural Networks: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2009.09796) [bib](/bib/Machine-Learning/Multi-Task-and-Multi-View-Learning/Crawshaw2020Multi-Task.md)

    *Michael Crawshaw*

#### [Online Learning](#content)

1. **A Survey of Algorithms and Analysis for Adaptive Online Learning.** J. Mach. Learn. Res. 2017 [paper](https://arxiv.org/abs/1403.3465) [bib](/bib/Machine-Learning/Online-Learning/McMahan2017A.md)

    *H. Brendan McMahan*

2. **Online Continual Learning in Image Classification: An Empirical Survey.** Neurocomputing 2022 [paper](http://arxiv.org/pdf/2101.10423.pdf) [bib](/bib/Machine-Learning/Online-Learning/Mai2022Online.md)

    *Zheda Mai, Ruiwen Li, Jihwan Jeong, David Quispe, Hyunwoo Kim, Scott Sanner*

3. **Online Learning: A Comprehensive Survey.** Neurocomputing 2021 [paper](https://arxiv.org/abs/1802.02871) [bib](/bib/Machine-Learning/Online-Learning/Hoi2021Online.md)

    *Steven C. H. Hoi, Doyen Sahoo, Jing Lu, Peilin Zhao*

4. **Preference-based Online Learning with Dueling Bandits: A Survey.** J. Mach. Learn. Res. 2021 [paper](https://jmlr.org/papers/v22/18-546.html) [bib](/bib/Machine-Learning/Online-Learning/Bengs2021Preference-based.md)

    *Viktor Bengs, Róbert Busa-Fekete, Adil El Mesaoudi-Paul, Eyke Hüllermeier*

#### [Optimization](#content)

1. **A Survey of Optimization Methods from a Machine Learning Perspective.** IEEE Trans. Cybern. 2020 [paper](https://arxiv.org/abs/1906.06821) [bib](/bib/Machine-Learning/Optimization/Sun2020A.md)

    *Shiliang Sun, Zehui Cao, Han Zhu, Jing Zhao*

2. **A Systematic and Meta-analysis Survey of Whale Optimization Algorithm.** Comput. Intell. Neurosci. 2019 [paper](https://arxiv.org/abs/1903.08763) [bib](/bib/Machine-Learning/Optimization/Mohammed2019A.md)

    *Hardi M. Mohammed, Shahla U. Umar, Tarik A. Rashid*

3. **An overview of gradient descent optimization algorithms.** arXiv 2016 [paper](https://arxiv.org/abs/1609.04747) [bib](/bib/Machine-Learning/Optimization/Ruder2016An.md)

    *Sebastian Ruder*

4. **Convex Optimization Overview.** citeseerx 2008 [paper](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.142.6470) [bib](/bib/Machine-Learning/Optimization/Kolter2008Convex.md)

    *Zico Kolter, Honglak Lee*

5. **Evolutionary Multitask Optimization: a Methodological Overview, Challenges and Future Research Directions.** arXiv 2021 [paper](https://arxiv.org/abs/2102.02558) [bib](/bib/Machine-Learning/Optimization/Osaba2021Evolutionary.md)

    *Eneko Osaba, Aritz D. Martinez, Javier Del Ser*

6. **Gradient Boosting Machine: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1908.06951) [bib](/bib/Machine-Learning/Optimization/He2019Gradient.md)

    *Zhiyuan He, Danchen Lin, Thomas Lau, Mike Wu*

7. **Investigating Bi-Level Optimization for Learning and Vision from a Unified Perspective: A Survey and Beyond.** arXiv 2021 [paper](https://arxiv.org/abs/2101.11517) [bib](/bib/Machine-Learning/Optimization/Liu2021Investigating.md)

    *Risheng Liu, Jiaxin Gao, Jin Zhang, Deyu Meng, Zhouchen Lin*

8. **Learning Combinatorial Optimization on Graphs: A Survey with Applications to Networking.** IEEE Access 2020 [paper](https://arxiv.org/pdf/2005.11081.pdf) [bib](/bib/Machine-Learning/Optimization/Vesselinova2020Learning.md)

    *Natalia Vesselinova, Rebecca Steinert, Daniel F. Perez-Ramirez, Magnus Boman*

9. **Nature-Inspired Optimization Algorithms: Research Direction and Survey.** arXiv 2021 [paper](https://arxiv.org/abs/2102.04013) [bib](/bib/Machine-Learning/Optimization/Sachan2021Nature-Inspired.md)

    *Rohit Kumar Sachan, Dharmender Singh Kushwaha*

10. **Optimization for deep learning: theory and algorithms.** arXiv 2019 [paper](https://arxiv.org/abs/1912.08957) [bib](/bib/Machine-Learning/Optimization/Sun2019Optimization.md)

    *Ruoyu Sun*

11. **Optimization Problems for Machine Learning: A Survey.** Eur. J. Oper. Res. 2021 [paper](https://arxiv.org/abs/1901.05331) [bib](/bib/Machine-Learning/Optimization/Gambella2021Optimization.md)

    *Claudio Gambella, Bissan Ghaddar, Joe Naoum-Sawaya*

12. **Particle Swarm Optimization: A survey of historical and recent developments with hybridization perspectives.** Mach. Learn. Knowl. Extr. 2019 [paper](https://arxiv.org/abs/1804.05319) [bib](/bib/Machine-Learning/Optimization/Sengupta2019Particle.md)

    *Saptarshi Sengupta, Sanchita Basak, Richard A. Peters*

13. **Why Do Local Methods Solve Nonconvex Problems?.** Beyond the Worst-Case Analysis of Algorithms 2020 [paper](https://arxiv.org/pdf/2103.13462.pdf) [bib](/bib/Machine-Learning/Optimization/Ma2020Why.md)

    *Tengyu Ma*

#### [Semi-Supervised, Weakly-Supervised and Unsupervised Learning](#content)

1. **A brief introduction to weakly supervised learning.** National Science Review 2017 [paper](https://cs.nju.edu.cn/_upload/tpl/01/0b/267/template267/zhouzh.files/publication/nsr18.pdf) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Zhou2017A.md)

    *Zhi-Hua Zhou*

2. **A Survey of Unsupervised Dependency Parsing.** COLING 2020 [paper](https://arxiv.org/pdf/2010.01535.pdf) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Han2020A.md)

    *Wenjuan Han, Yong Jiang, Hwee Tou Ng, Kewei Tu*

3. **A Survey on Deep Semi-supervised Learning.** arXiv 2021 [paper](https://arxiv.org/abs/2103.00550) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Yang2021A.md)

    *Xiangli Yang, Zixing Song, Irwin King, Zenglin Xu*

4. **A survey on Semi-, Self- and Unsupervised Learning for Image Classification.** IEEE Access 2021 [paper](https://arxiv.org/abs/2002.08721) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Schmarje2021A.md)

    *Lars Schmarje, Monty Santarossa, Simon-Martin Schröder, Reinhard Koch*

5. **A Survey on Semi-Supervised Learning Techniques.** IJCTT 2014 [paper](https://arxiv.org/abs/1402.4645) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Prakash2014A.md)

    *V. Jothi Prakash, Dr. L.M. Nithya*

6. **Deep Learning for Weakly-Supervised Object Detection and Object Localization: A Survey.** arXiv 2021 [paper](https://arxiv.org/pdf/2105.12694.pdf) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Shao2021Deep.md)

    *Feifei Shao, Long Chen, Jian Shao, Wei Ji, Shaoning Xiao, Lu Ye, Yueting Zhuang, Jun Xiao*

7. **Graph-based Semi-supervised Learning: A Comprehensive Review.** arXiv 2021 [paper](https://arxiv.org/abs/2102.13303) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Song2021Graph-based.md)

    *Zixing Song, Xiangli Yang, Zenglin Xu, Irwin King*

8. **Improvability Through Semi-Supervised Learning: A Survey of Theoretical Results.** arXiv 2019 [paper](https://arxiv.org/abs/1908.09574) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Mey2019Improvability.md)

    *Alexander Mey, Marco Loog*

9. **Learning from positive and unlabeled data: a survey.** Mach. Learn. 2020 [paper](https://arxiv.org/abs/1811.04820) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Bekker2020Learning.md)

    *Jessa Bekker, Jesse Davis*

10. **Unsupervised Cross-Lingual Representation Learning.** ACL 2019 [paper](https://www.aclweb.org/anthology/P19-4007.pdf) [bib](/bib/Machine-Learning/Semi-Supervised,-Weakly-Supervised-and-Unsupervised-Learning/Ruder2019Unsupervised.md)

    *Sebastian Ruder, Anders Søgaard, Ivan Vulic*

#### [Transfer Learning](#content)

1. **A Comprehensive Survey on Transfer Learning.** Proc. IEEE 2021 [paper](https://arxiv.org/abs/1911.02685) [bib](/bib/Machine-Learning/Transfer-Learning/Zhuang2021A.md)

    *Fuzhen Zhuang, Zhiyuan Qi, Keyu Duan, Dongbo Xi, Yongchun Zhu, Hengshu Zhu, Hui Xiong, Qing He*

2. **A Survey of Unsupervised Deep Domain Adaptation.** ACM Trans. Intell. Syst. Technol. 2020 [paper](https://arxiv.org/abs/1812.02849) [bib](/bib/Machine-Learning/Transfer-Learning/Wilson2020A.md)

    *Garrett Wilson, Diane J. Cook*

3. **A Survey on Deep Transfer Learning.** ICANN 2018 [paper](https://arxiv.org/abs/1808.01974) [bib](/bib/Machine-Learning/Transfer-Learning/Tan2018A.md)

    *Chuanqi Tan, Fuchun Sun, Tao Kong, Wenchang Zhang, Chao Yang, Chunfang Liu*

4. **A survey on domain adaptation theory: learning bounds and theoretical guarantees.** arXiv 2020 [paper](https://arxiv.org/abs/2004.11829) [bib](/bib/Machine-Learning/Transfer-Learning/Redko2020A.md)

    *Ievgen Redko, Emilie Morvant, Amaury Habrard, Marc Sebban, Younès Bennani*

5. **A Survey on Negative Transfer.** arXiv 2020 [paper](http://arxiv.org/pdf/2009.00909.pdf) [bib](/bib/Machine-Learning/Transfer-Learning/Zhang2020A.md)

    *Wen Zhang, Lingfei Deng, Lei Zhang, Dongrui Wu*

6. **A Survey on Transfer Learning.** IEEE Trans. Knowl. Data Eng. 2010 [paper](https://ieeexplore.ieee.org/abstract/document/5288526) [bib](/bib/Machine-Learning/Transfer-Learning/Pan2010A.md)

    *Sinno Jialin Pan, Qiang Yang*

7. **A Survey on Transfer Learning in Natural Language Processing.** arXiv 2020 [paper](https://arxiv.org/abs/2007.04239) [bib](/bib/Machine-Learning/Transfer-Learning/Alyafeai2020A.md)

    *Zaid Alyafeai, Maged Saeed AlShaibani, Irfan Ahmad*

8. **Evolution of transfer learning in natural language processing.** arXiv 2019 [paper](https://arxiv.org/abs/1910.07370) [bib](/bib/Machine-Learning/Transfer-Learning/Malte2019Evolution.md)

    *Aditya Malte, Pratik Ratadiya*

9. **Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer.** J. Mach. Learn. Res. 2020 [paper](https://arxiv.org/pdf/1910.10683.pdf) [bib](/bib/Machine-Learning/Transfer-Learning/Raffel2020Exploring.md)

    *Colin Raffel, Noam Shazeer, Adam Roberts, Katherine Lee, Sharan Narang, Michael Matena, Yanqi Zhou, Wei Li, Peter J. Liu*

10. **Neural Unsupervised Domain Adaptation in NLP - A Survey.** COLING 2020 [paper](https://arxiv.org/abs/2006.00632) [bib](/bib/Machine-Learning/Transfer-Learning/Ramponi2020Neural.md)

    *Alan Ramponi, Barbara Plank*

11. **Transfer Adaptation Learning: A Decade Survey.** arXiv 2019 [paper](https://arxiv.org/pdf/1903.04687.pdf) [bib](/bib/Machine-Learning/Transfer-Learning/Zhang2019Transfer.md)

    *Lei Zhang, Xinbo Gao*

12. **Transfer Learning for Reinforcement Learning Domains: A Survey.** J. Mach. Learn. Res. 2009 [paper](https://jmlr.csail.mit.edu/papers/v10/taylor09a.html#:~:text=Transfer%20Learning%20for%20Reinforcement%20Learning%20Domains%3A%20A%20Survey,as%20is%20common%20in%20other%20machine%20learning%20contexts.) [bib](/bib/Machine-Learning/Transfer-Learning/Taylor2009Transfer.md)

    *Matthew E. Taylor, Peter Stone*

13. **Transfer Learning in Deep Reinforcement Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2009.07888) [bib](/bib/Machine-Learning/Transfer-Learning/Zhu2020Transfer.md)

    *Zhuangdi Zhu, Kaixiang Lin, Jiayu Zhou*

#### [Trustworthy Machine Learning](#content)

1. **A Survey of Privacy Attacks in Machine Learning.** arXiv 2020 [paper](https://arxiv.org/pdf/2007.07646) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Rigaki2020A.md)

    *Maria Rigaki, Sebastian Garcia*

2. **A survey of safety and trustworthiness of deep neural networks: Verification, testing, adversarial attack and defence, and interpretability.** Comput. Sci. Rev. 2020 [paper](https://www.sciencedirect.com/science/article/abs/pii/S1574013719302527?via%3Dihub) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Huang2020A.md)

    *Xiaowei Huang, Daniel Kroening, Wenjie Ruan, James Sharp, Youcheng Sun, Emese Thamo, Min Wu, Xinping Yi*

3. **A Survey on Bias and Fairness in Machine Learning.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/1908.09635) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Mehrabi2021A.md)

    *Ninareh Mehrabi, Fred Morstatter, Nripsuta Saxena, Kristina Lerman, Aram Galstyan*

4. **Backdoor Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2007.08745) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Li2020Backdoor.md)

    *Yiming Li, Baoyuan Wu, Yong Jiang, Zhifeng Li, Shu-Tao Xia*

5. **Differential Privacy and Machine Learning: a Survey and Review.** arXiv 2014 [paper](https://arxiv.org/abs/1412.7584) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Ji2014Differential.md)

    *Zhanglong Ji, Zachary Chase Lipton, Charles Elkan*

6. **Fairness in Machine Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/pdf/2010.04053.pdf) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Caton2020Fairness.md)

    *Simon Caton, Christian Haas*

7. **Local Differential Privacy and Its Applications: A Comprehensive Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2008.03686) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Yang2020Local.md)

    *Mengmeng Yang, Lingjuan Lyu, Jun Zhao, Tianqing Zhu, Kwok-Yan Lam*

8. **Practical Machine Learning Safety: A Survey and Primer.** arXiv 2021 [paper](https://arxiv.org/abs/2106.04823) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Mohseni2021Practical.md)

    *Sina Mohseni, Haotao Wang, Zhiding Yu, Chaowei Xiao, Zhangyang Wang, Jay Yadawa*

9. **Privacy in Deep Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2004.12254) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Mireshghallah2020Privacy.md)

    *Fatemehsadat Mireshghallah, Mohammadkazem Taram, Praneeth Vepakomma, Abhishek Singh, Ramesh Raskar, Hadi Esmaeilzadeh*

10. **Technology Readiness Levels for Machine Learning Systems.** arXiv 2021 [paper](https://arxiv.org/pdf/2101.03989.pdf) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Lavin2021Technology.md)

    *Alexander Lavin, Ciarán M. Gilligan-Lee, Alessya Visnjic, Siddha Ganju, Dava Newman, Sujoy Ganguly, Danny Lange, Atilim Günes Baydin, Amit Sharma, Adam Gibson, Yarin Gal, Eric P. Xing, Chris Mattmann, James Parr*

11. **The Creation and Detection of Deepfakes: A Survey.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/abs/2004.11138) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Mirsky2021The.md)

    *Yisroel Mirsky, Wenke Lee*

12. **Tutorial: Safe and Reliable Machine Learning.** arXiv 2019 [paper](https://arxiv.org/abs/1904.07204) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Saria2019Tutorial.md)

    *Suchi Saria, Adarsh Subbaswamy*

13. **When Machine Learning Meets Privacy: A Survey and Outlook.** ACM Comput. Surv. 2021 [paper](https://arxiv.org/pdf/2011.11819.pdf) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Liu2021When.md)

    *Bo Liu, Ming Ding, Sina Shaham, Wenny Rahayu, Farhad Farokhi, Zihuai Lin*

14. **机器学习模型安全与隐私研究综述.** 软件学报 2021 [paper](http://www.jos.org.cn/jos/ch/reader/view_abstract.aspx?file_no=6131&flag=1) [bib](/bib/Machine-Learning/Trustworthy-Machine-Learning/Ji2021Security.md)

    *纪守领, 杜天宇, 李进锋, 沈超, 李博*

## Team Members

The project is maintained by 

*Ziyang Wang, Shuhan Zhou, Nuo Xu, Bei Li, Yinqiao Li, Quan Du, Tong Xiao, and Jingbo Zhu*

*Natural Language Processing Lab., School of Computer Science and Engineering, Northeastern University*

*NiuTrans Research*

Please feel free to contact us if you have any questions (wangziyang [at] stumail.neu.edu.cn or libei_neu [at] outlook.com).

## Acknowledge

We would like to thank the people who have contributed to this project. They are

*Xin Zeng, Laohu Wang, Chenglong Wang, Xiaoqian Liu, Xuanjun Zhou, Jingnan Zhang, Yongyu Mu, Zefan Zhou, Yanhong Jiang, Xinyang Zhu, Xingyu Liu, Dong Bi, Ping Xu, Zijian Li, Fengning Tian, Hui Liu, Kai Feng, Yuhao Zhang, Chi Hu, Di Yang, Lei Zheng, Hexuan Chen, Zeyang Wang, Tengbo Liu, Xia Meng, Weiqiao Shan, Tao Zhou, Runzhe Cao, Yingfeng Luo, Binghao Wei, Wandi Xu, Yan Zhang, Yichao Wang, Mengyu Ma, Zihao Liu*

