# -融360“天机”金融风控大数据竞赛-
本队决赛第11名，比赛由融360公司举办，构建模型用于预测用户是否会二次贷款。

比赛简介：融360“天机”金融风控大数据竞赛是由中国领先的金融服务平台融360主办，统计之都、CDA数据分析研究院协办，中国工业统计教学研究会、中山大学华南统计科学研究中心承办，以解决实际线上金融服务问题为目标开展的数据竞赛。
本次竞赛基于融360平台积累的真实的用户数据，向全球大数据金融人才征集更有效的算法、模型，利用数据挖掘用户价值，为用户提供更好的金融服务。

比赛程序说明：数据清洗+特征工程+train与test的分布探索+模型构建！！

1、数据清洗程序涉及四张表：user_info、consumption、rong_tag、relation；

2、对清洗后的四张表同步进行特征工程；

3、可视化对比train和test的分布【从数据缺失角度思考分布】；

4、构建RF+XGBoost，并进行多模型的ensemble以及auc的rank融合。
