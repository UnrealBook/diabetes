# diabetes

竞赛题目
中国是世界上糖尿病患者最多的国家，病人达到1.1亿，每年有130万人死于糖尿病及其相关疾病。每年用于糖尿病的医疗费用占中国公共医疗卫生支出的比例超过13%，超过3000亿元。本次大赛旨在通过糖尿病人的临床数据和体检指标来预测人群的糖尿病程度，以血糖浓度为指标。参赛选手需要设计高精度，高效，且解释性强的算法来挑战糖尿病精准预测这一科学难题。

竞赛数据
大赛初赛数据共包含两个文件，训练文件d_train.csv和测试文件d_test.csv，每个文件第一行是字段名，之后每一行代表一个个体。文件共包含42个字段，包含数值型、字符型、日期型等众多数据类型，部分字段内容在部分人群中有缺失，其中第一列为个体ID号。训练文件的最后一列为标签列，既需要预测的目标血糖值。

大赛复赛数据共包含两个文件，训练文件g_train.csv和测试文件g_test.csv，每个文件第一行是字段名，之后每一行代表一个个体，部分字段名已经做脱敏处理。文件共包含85个字段，部分字段内容在部分人群中有缺失，其中第一列为个体ID号。训练文件的最后一列为标签列，既需要预测的是否有糖尿病的类别。

提交说明
参赛选手提交一个csv文件，文件共一列，内容为预测的血糖值。

评估指标
初赛期间，参赛选手需要提交对每个人的糖尿病血糖预测结果，以小数形式表示，保留小数点后三位。该结果将与个体实际检测到的血糖结果进行对比，以均方误差为评价指标，结果越小越好，均方误差计算公式如下：



其中m为总人数，y'i 为选手预测的第i个人的血糖值，yi 为第i个人的实际血糖检测值。

复赛期间，参赛选手需要提交对每个人是否患糖尿病的预测结果，以整数形式表示类别，取值范围0或者1。该结果将与个体实际检测到的糖尿病患病情况进行对比，以错误区分类别的总数为评价指标，结果越小越好。

决赛期间，选手要求提供特征因子的重要性排序，并提供分析思路与判断依据。该项内容将被用于评定最终名次的因素之一。


参考文献

Meta-analysis of the relationship between common type 2 diabetes risk gene variants with gestational diabetes mellitus. Mao H et al. PLoS One.
 2012;7(9):e45882. doi: 10.1371/journal.pone.0045882.

Meta-analysisof the relationship between common type 2 diabetes risk gene variants withgestational diabetes mellitus. Mao H et al. PLoS One. 2012;7(9):e45882.doi: 10.1371/journal.pone.0045882.

Inherited destiny? Genetics and gestational diabetes mellitus.Watanabe RM.Genome Med. 2011 Mar 25;3(3):18. doi: 10.1186/gm232.

Identification of HKDC1 and BACE2as Genes Inf luencing Glycemic Traits During Pregnancy Through Genome-WideAssociation Studies. M. Geoffrey Hayes et al. Diabetes. 62:3282–3291, 2013.

Genetics, genomics and metabolomics: new insights into maternal metabolism during pregnancy.Lowe WL Jret al. Diabet Med. 2014Mar;31(3):254-62. doi: 10.1111/dme.12352.

Genetics of GestationalDiabetes Mellitus and Maternal Metabolism. Lowe WL Jret al. Curr Diab Rep. 2016 Feb;16(2):15. doi: 10.1007/s11892-015-0709-z.

Genetic variants andthe risk of gestational diabetes mellitus: a systematic review. Zhang Cet al. Hum ReprodUpdate. 2013 Jul-Aug;19(4):376-90.doi: 10.1093/humupd/dmt013. Epub 2013 May 19.

Finding genetic riskfactors of gestational diabetes. Kwak SHet al. GenomicsInform. 2012 Dec;10(4):239-43. doi:10.5808/GI.2012.10.4.239. Epub 2012 Dec 31.

A genome-wide associationstudy of gestational diabetesmellitus in Korean women. Kwak SHet al. Diabetes. 2012Feb;61(2):531-41. doi: 10.2337/db11-1034. Epub 2012 Jan 10.
