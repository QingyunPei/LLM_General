# LLM_General
I created this gallery for the interesting project related to LLM and its extension that I have searched on GitHub and some Websites.

## Knowledge Graph
1. Bert In Relation Extraction

GitHub Link: https://github.com/Ricardokevins/Bert-In-Relation-Extraction/tree/main 

这个项目是基于Bert模型对于文本三元关系提取的一个实际运用，数据是使用的是百度发布的DUIE数据（https://aistudio.baidu.com/aistudio/datasetdetail/88472），包含了实体识别和关系抽取。整个项目主要有几个构成：数据的预处理【预设关系有48类+1类（未确定）】，模型的设定【直接使用Bert用于序列分类的（BertEncoder+Fc+CrossEntropy）】，预训练和预测
