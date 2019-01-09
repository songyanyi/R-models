# adaboost方法是用下一个模型来拟合上一个模型的残差
# resnet模型是x = x+残差 ，用残差模块来拟合残差
# 能否用残差模块来不断拟合y = x的残差

#########R##########
非参数核方法聚类 
https://cran.r-project.org/web/packages/pdfCluster/pdfCluster.pdf 

R-RerF（又名Randomer Forest（RerF）或随机投影森林）
https://cran.r-project.org/web/packages/rerf/index.html

条件广义线性模型
https://cran.r-project.org/web/packages/cglm/index.html

glmc：拟合受约束条件约束的广义线性模型
适合广义线性模型，其中参数受线性约束。通过给出线性预测器的符号描述，误差分布的描述以及参数的约束矩阵来指定模型。
https://cran.r-project.org/web/packages/glmc/index.html


Curve Linear Regression via Dimension Reduction
https://cran.r-project.org/web/packages/clr/clr.pdf

CopCTS Copula-Based Semiparametric Analysis for Time Series Data with
Detection Limits 时间序列数据的半参数Copula分析

DIMORA：扩散模型R分析
https://cran.r-project.org/web/packages/DIMORA/DIMORA.pdf


Dose Response Data Analysis using the 4 Parameter Logistic (4pl) Model
https://cran.r-project.org/web/packages/dr4pl/vignettes/usage_examples_HA.html

惩罚似然法在广义线性混合模型（GLMM）中执行联合选择
Performs joint selection in Generalized Linear Mixed Models (GLMMs) using penalized
likelihood methods. Specifically, the Penalized QuasiLikelihood 惩罚准似然函数
(PQL) is used as a loss function,
https://cran.r-project.org/web/packages/rpql/rpql.pdf


可视化
https://cran.r-project.org/web/packages/visNetwork/vignettes/Introduction-to-visNetwork.html


Estimate parameters of logistic regression with missing data and perform model selection, using algorithm Stochastic Approximation EM. 缺失数据的logistic回归--随机逼近EM算法
https://cran.r-project.org/web/packages/misaem/index.html

Nonparametric Estimation and Inference Procedures using Partitioning-Based Least Squares Regression 非参数估计和推理，使用分区的最小二乘回归
https://cran.r-project.org/web/packages/lspartition/lspartition.pdf


Estimates Rasch models and mixture Rasch models
https://cran.r-project.org/web/packages/mixRasch/mixRasch.pdf
https://cran.r-project.org/web/packages/mixRaschTools/index.html

mlergm：多级指数族随机图模型
https://cran.r-project.org/web/packages/mlergm/vignettes/mlergm_tutorial.html


Parallel Bayesian Optimization of Hyperparameters
https://cran.r-project.org/web/packages/ParBayesianOptimization/index.html

npExact：精确的非参数假设检验：均值，方差和随机不等式
https://cran.r-project.org/web/packages/npExact/npExact.pdf

Structural Equation Multidimensional Scaling 多尺度结构方程
https://cran.r-project.org/web/packages/semds/index.html


R用于估计和执行几个马尔可夫状态切换和混合二元copula模型的拟合度检验。拟合优度检验基于Cramer von Mises统计量，并使用Rosenblatt变换和参数自举来估计p值。copula参数的估计基于使用伪观察定义为归一化秩的伪最大似然法。
https://cran.r-project.org/web/packages/HMMcopula/index.html


empirical: Probability Distributions as Models of Data
计算连续(非步进)经验(和非参数)概率密度、累积分布和分位数函数。支持单变量、多变量和条件概率分布，一些核平滑特征和加权数据(可能有用的混合模糊聚类)。能够计算多元概率和条件概率。还可以计算条件中位数、分位数和模
https://cran.r-project.org/web/packages/empirical/index.html

snfa：平滑的非参数前沿分析
拟合非参数生产前沿用于效率分析。提供了数据包络分析（DEA）的平滑模拟和随机前沿分析（SFA）的非参数模拟的方法。如Racine等人所述，使用约束内核平滑为多个输入和单个输出构造前沿。（2009），允许对估计的边界强加单调性和凹度约束。
https://cran.r-project.org/web/packages/snfa/index.html


Bayesian Additive Regression Trees 贝叶斯加性回归树
https://cran.r-project.org/web/packages/BART/index.html

lg: Locally Gaussian Distributions: Estimation and Methods 局部高斯密度估计
https://cran.r-project.org/web/packages/lg/index.html

cubature：超立方体上的自适应多元积分
R包围Steven G. Johnson的Cubature C库，用于在超立方体上进行自适应多变量积分，以及Thomas Hahn的Cuba C库用于确定性和蒙特卡罗积分。提供了用于Cubature和Cuba例程的标量和向量接口; 强烈建议使用矢量接口，如包装插图中所示。
https://cran.r-project.org/web/packages/cubature/index.html


basicMCMCplots
https://cran.r-project.org/web/packages/basicMCMCplots/basicMCMCplots.pdf

聚类
Distance measures (GDM1, GDM2,	Sokal-Michener, Bray-Curtis, for symbolic interval-valued data), cluster quality indices (Calinski-Harabasz, Baker-Hubert, Hubert-Levine, Silhouette, Krzanowski-Lai, Hartigan, Gap,	Davies-Bouldin),	data normalization formulas (metric data, interval-valued symbolic data), data generation (typical and non-typical data), HINoV method,	replication analysis, linear ordering methods, spectral clustering, agreement indices between two partitions, plot functions (for categorical and symbolic interval-valued data). (MILLIGAN, G.W., COOPER, M.C. (1985) <doi:10.1007/BF02294245>, HUBERT, L., ARABIE, P. (1985) <doi:10.1007%2FBF01908075>, RAND, W.M. (1971) <doi:10.1080/01621459.1971.10482356>, JAJUGA, K., WALESIAK, M. (2000) <doi:10.1007/978-3-642-57280-7_11>, MILLIGAN, G.W., COOPER, M.C. (1988) <doi:10.1007/BF01897163>, JAJUGA, K., WALESIAK, M., BAK, A. (2003) <doi:10.1007/978-3-642-55721-7_12>, DAVIES, D.L., BOULDIN, D.W. (1979) <doi:10.1109/TPAMI.1979.4766909>, CALINSKI, T., HARABASZ, J. (1974) <doi:10.1080/03610927408827101>, HUBERT, L. (1974) <doi:10.1080/01621459.1974.10480191>, TIBSHIRANI, R., WALTHER, G., HASTIE, T. (2001) <doi:10.1111/1467-9868.00293>, BRECKENRIDGE, J.N. (2000) <doi:10.1207/S15327906MBR3502_5>, WALESIAK, M., DUDEK, A. (2008) <doi:10.1007/978-3-540-78246-9_11>).
https://cran.r-project.org/web/packages/clusterSim/index.html


extremefit: Estimation of Extreme Conditional Quantiles and Probabilities 极值条件分位数和概率密度
https://cran.r-project.org/web/packages/extremefit/index.html


广义对数线性模型
通过EM和Fisher评分方法，对不完整列联表的对数线性模型（包括一些潜在类模型）的例程。允许自举。有关一般方法，请参见Espeland和Hui（1987）< doi：10.2307 / 2531553 >。
https://cran.r-project.org/web/packages/gllm/index.html

lasso2：L1约束估计又名'套索'
根据Osborne等人的算法，在对估计施加L1约束的同时解决回归问题的例程和文档。（1998）
https://cran.r-project.org/web/packages/lasso2/vignettes/Manual-vignette.pdf

mixKernel

grf：广义随机森林（Beta）
用于基于森林的统计估计和推理的可插入包。GRF目前提供非参数最小二乘回归，分位数回归和治疗效果估计（可选地使用工具变量）的方法。该软件包目前处于测试阶段，我们希望不断改进其性能和可用性。
https://cran.r-project.org/web/packages/grf/index.html

The Variance Gamma Distribution
https://cran.r-project.org/web/packages/VarianceGamma/VarianceGamma.pdf


mcmcr：操纵MCMC样本
用于存储，操作和汇总蒙特卡罗马尔可夫链（MCMC）样本的函数和类
https://cran.r-project.org/web/packages/mcmcr/index.html


平稳时间序列的贝叶斯谱推断beyondWhittle：固定时间序列的贝叶斯谱推断
用于单变量和多变量时间序列的贝叶斯参数，非参数和半参数程序的实现。该方案基于C. Kirch等（2018）< doi：10.1214 / 18-BA1126 >和A. Meier（2018）< https://opendata.uni-halle.de//handle/1981185920中介绍的方法。 / 13470 >。它得到了DFG拨款KI 1443 / 3-1的支持。
https://cran.r-project.org/web/packages/beyondWhittle/index.html

Delaporte分布的统计函数，为Delaporte分布提供概率质量，分布，分位数，随机变量生成和矩量法参数估计函数。Delaporte是离散概率分布，可以认为是具有泊松分布的负二项分布的卷积。或者，可以将其视为具有泊松和负二项分量的计数分布。它在精算学中被研究为频率分布，其具有比泊松更多的可变性，但小于负二项式
https://cran.r-project.org/web/packages/Delaporte/index.html

SemiMarkov：多态半马尔可夫模型
用于将多状态半马尔可夫模型拟合到纵向数据的函数。考虑了适用于处理指数，威布尔和指数威布尔分布的参数最大似然估计方法。可以考虑右删失，并且可以使用Cox比例模型来包括常数和时变协变量。参考：A。Krol和P. Saint-Pierre（2015）< doi：10.18637 / jss.v066.i06 >。
https://cran.r-project.org/web/packages/SemiMarkov/index.html


EpiModel：传染病动力学的数学建模
用于模拟传染病动态数学模型的工具。流行病模型类包括确定性区室模型，随机个体接触模型和随机网络模型。网络模型使用来自R中软件包的Statnet套件的指数族随机图模型（ERGM）的稳健统计方法。用于流行病建模的标准模板包括SI，SIR和SIS疾病类型。EpiModel具有扩展这些模板的API，以满足新的科学研究目标。
http://www.epimodel.org/

结构贝叶斯矢量自回归模型
BHSBVAR：结构贝叶斯矢量自回归模型
使用Baumeister和Hamilton（2015）< doi：10.3982 / ECTA12356 >，Baumeister和Hamilton（2017）< doi：10.3386 / w24167 >以及Baumeister和Hamilton（2018）开发的方法提供运行结构贝叶斯矢量自回归模型的函数。< doi：10.1016 / j.jmoneco.2018.06.005 >。还提供了用于绘制模型参数的脉冲响应，历史分解和后验分布的函数。
https://cran.r-project.org/web/packages/BHSBVAR/index.html


Continuous Time Structural Equation Modelling
https://cran.r-project.org/web/packages/ctsem/ctsem.pdf

Graphical Least Square Estimation
Graph <- GLSE(x,y,parallel=FALSE)$Graph
results <- BootSE(Graph,x,y,n.boot=150,sig.level =.3,centering = TRUE)

MUS的kmeans
https://cran.r-project.org/web/packages/pivmet/vignettes/K-means_clustering_using_the_MUS_algorithm.html
https://cran.r-project.org/web/packages/pivmet/index.html


library(kernlab)

广义线性模型非凸惩罚估计的统一算法
一种有效的统一非凸惩罚估计算法，用于高斯（线性），二项Logit（逻辑），泊松，多项Logit和Cox比例风险回归模型。统一算法基于凸凹程序实现，该算法可应用于大多数现有的非凸处罚。该算法还支持凸罚：最小绝对收缩和选择算子（LASSO）。支持的非凸处罚包括平滑限幅绝对偏差（SCAD），极小极大凹处罚（MCP），截断LASSO罚分（TLP），削波LASSO（CLASSO），稀疏脊（SRIDGE），修改桥（MBRIDGE）和修改日志（MLOG）。对于高维数据（包含许多变量的数据集），该算法选择产生简约回归模型的相关变量。Kim，D.，Lee，S。和Kwon，S。（2018）<arXiv：1811.05061 >，Lee，S.，Kwon，S。和Kim，Y。（2016）< doi：10.1016 / j.csda.2015.08.019 >，Kwon，S.，Lee，S。和Kim，Y。 （2015）< doi：10.1016 / j.csda.2015.07.001 >。（本研究由Pepperdine Graziadio商学院和韩国国家研究基金会应用研究中心的Julian Virtue教授资助。）
https://cran.r-project.org/web/packages/ncpen/index.html

辅助变量回归 instruments: Estimate Regression Models with Instrumental Variables
https://cran.r-project.org/web/packages/instruments/index.html

randcorr	生成随机pxp相关矩阵



nproc：Neyman-Pearson（NP）分类算法和NP接收器操作特性（NP-ROC）曲线
在许多二元分类应用中，例如疾病诊断和垃圾邮件检测，从业者通常面临限制I类错误（即，将0级观察错误分类为类1的条件概率）的需要，使得其保持低于期望阈值。为了满足这一需求，Neyman-Pearson（NP）分类范式是一种自然选择; 它最小化了类型II错误（即，将类1观察错误分类为类0的条件概率），同时对类型I错误强制执行上限α。尽管NP范式在假设检验中具有长达一个世纪的历史，但在分类方案中尚未得到很好的认可和实施。直接将经验类型I错误限制为不超过alpha的常见做法不满足I类错误控制目标，因为生成的分类器仍然可能具有远大于alpha的I类错误。因此，NP范式在实践中尚未针对许多分类方案正确实施。在这项工作中，我们开发了第一个伞形算法，该算法实现了所有评分类型分类方法的NP范例，包括常用方法，如逻辑回归，支持向量机和随机森林。在这种伞算法的支持下，我们提出了一种新的NP分类方法图形工具：NP接收器工作特性（NP-ROC）频带，受流行的接收器工作特性（ROC）曲线驱动
https://cran.r-project.org/web/packages/nproc/index.html


Rdimtools：降维和估算方法
我们提供线性和非线性降维技术。还提供了用于探索性分析的内在维度估计方法。有关维数技术的更多详细信息，请参阅Ma和Zhu（2013）< doi：10.1111 / j.1751-5823.2012.00182.x >的文章，如果您对统计方法感兴趣，或者Engel，Huttenberger和Hamann（2012） < doi：10.4230 / OASIcs.VLUDS.2011.135 >进行更广泛的多学科概述。
https://cran.r-project.org/web/packages/Rdimtools/index.html

rrcov: Scalable Robust Estimators with High Breakdown Point
Robust Location and Scatter Estimation and Robust Multivariate Analysis with High Breakdown Point.
https://cran.r-project.org/web/packages/rrcov/index.html


分类结果评估
https://cran.r-project.org/web/packages/mltest/mltest.pdf


AutoStepwiseGLM：通过训练和测试方法构建逐步GLM
随机将数据拆分为测试和训练集。然后，使用逐步选择在训练数据上拟合多个多元回归模型，并在测试数据上进行测试。对于每个模型返回的是比较模型Akaike信息准则（AIC），预测值与实际值之间的Pearson相关系数（r），平均绝对误差（MAE）和模型之间的R-Squared的图。通过模型评估度量（即，AIC，r，MAE和R-Squared）将每个模型相对于其他模型进行排序，并且返回模型评估度量中具有最佳平均排名的模型。AIC，r，MAE和R-Squared的模型评估度量权重分别作为参数aic_wt，r_wt，mae_wt和r_squ_wt。
https://cran.r-project.org/web/packages/AutoStepwiseGLM/index.html


tidyposterior: Bayesian Analysis to Compare Models using Resampling Statistics
Bayesian analysis used here to answer the question: "when looking at resampling results, are the differences between models 'real'?" To answer this, a model can be created were the performance statistic is the resampling statistics (e.g. accuracy or RMSE). These values are explained by the model types. In doing this, we can get parameter estimates for each model's affect on performance and make statistical (and practical) comparisons between models. The methods included here are similar to Benavoli et al (2017) <http://jmlr.org/papers/v18/16-305.html>.
https://cran.r-project.org/web/packages/tidyposterior/index.html


GJRM：广义联合回归建模 Generalised Joint Regression Modelling
在存在方程的误差关联，内生性，非随机样本选择或部分可观察性的情况下，用于拟合具有几种类型的协变量效应的各种关节（和单变量）回归模型的例程。
https://cran.r-project.org/web/packages/GJRM/index.html


gllvm: Generalized Linear Latent Variable Models
Analysis of multivariate data using generalized linear latent variable models (gllvm). Estimation is performed using either Laplace approximation method or variational approximation method implemented via TMB (Kristensen et al., (2016), <doi:10.18637/jss.v070.i05>). Details for gllvm, see Hui et al. (2015) <doi:10.1111/2041-210X.12236> and (2017) <doi:10.1080/10618600.2016.1164708> and Niku et al. (2017) <doi:10.1007/s13253-017-0304-7>.
https://cran.r-project.org/web/packages/gllvm/index.html

项目反应理论 -- 心理学统计
LNIRT: LogNormal Response Time Item Response Theory Models
Allows the simultaneous analysis of responses and response times in an Item Response Theory (IRT) modelling framework. Supports covariates for item and person (random) parameters. Parameter estimation is done with a MCMC algorithm. LNIRT replaces the package CIRT, which was written by Rinke Klein Entink. For reference, see the paper by Fox, Klein Entink and Van der Linden (2007), "Modeling of Responses and Response Times with the Package cirt", Journal of Statistical Software, <doi:10.18637/jss.v020.i07>.
https://cran.r-project.org/web/packages/LNIRT/index.html



Gaussian Process Modeling of Multi-Response Datasets
https://cran.r-project.org/web/packages/GPM/GPM.pdf


LVGP：具有定性和定量输入变量的潜变量高斯过程建模
使用潜变量高斯过程建模拟合数据集的响应曲面，预测新输入的响应，并在潜在空间（仅1D或2D）中绘制潜在变量位置。数据集的输入变量可以是定量的，定性的/分类的或混合的。数据集的输出变量是标量（定量）。使用类似于另一个GP建模包“GPM”的逐次逼近/松弛算法来完成似然函数的优化。该建模方法发表在Yichi Zhang，Siyu Tao，Wei Chen和Daniel W. Apley（2018）< arXiv：1806.07504 >的“具有定性和定量因子的高斯过程建模的潜变量方法”中。该软件包是在西北大学的IDEAL开发的
https://cran.r-project.org/web/packages/LVGP/index.html


mixsqp：序列二次规划用于混合比例的快速最大似然估计
提供基于顺序二次规划（SQP）的优化算法，用于在已知组分密度的有限混合模型中混合比例的最大似然估计。预计这些算法将获得至少与最先进的MOSEK内点求解器一样精确的解决方案（在“REBayes”软件包中称为“KWDual”功能），并且它们有望达到解决方案在大型数据集中更快。该算法描述于Y.Kim，P.Parbonetto，M.Stephens＆M.Anitescu（2012）< arXiv：1806.01412 >中。
https://cran.r-project.org/web/packages/mixsqp/index.html


deming：Deming，Theil-Sen，Passing-Bablock和Total Least Squares回归
广义Deming回归，Theil-Sen回归和Passing-Bablock回归函数。
https://cran.r-project.org/web/packages/deming/index.html


SolveRationalMatrixEquation：求解有理矩阵方程
给定对称正定矩阵Q和非奇异矩阵L，找到对称正定解X，使得X = Q + L（X inv）L ^ T. 参考文献：Benner，P.，Faßbender，H。关于有理矩阵方程的解。Benner，Faßbender（2007）< doi：10.1155 / 2007/21850 >。
https://cran.r-project.org/web/packages/SolveRationalMatrixEquation/index.html



降维
https://cran.r-project.org/web/packages/SolveRationalMatrixEquation/index.html


MIAmaxent：最大熵分布建模的模块化集成方法
用于训练，选择和评估最大熵（和标准逻辑回归）分布模型的工具。该软件包提供了用户控制的解释变量转换，通过嵌套模型比较选择变量以及灵活的模型评估和投影的工具。它遵循基于最大熵建模的最大似然解释的原则，并使用无限加权逻辑回归进行模型拟合。
https://cran.r-project.org/web/packages/MIAmaxent/index.html

pgbart：使用粒子吉布斯采样器和吉布斯/ Metropolis-Hastings采样器的贝叶斯加性回归树
实施Particle Gibbs采样器和Gibbs / Metropolis-Hastings采样器以拟合贝叶斯加性回归树模型。可以分离模型（训练）的构建和新数据集（测试）的预测。我们的参考文献是：Lakshminarayanan B，Roy D，Teh Y W. Particle Gibbs for Bayesian additive regression trees [C]，Artificial Intelligence and Statistics。2015：553-561，< http://proceedings.mlr.press/v38/lakshminarayanan15.pdf >和Chipman，H.，George，E。和McCulloch R.（2010）Bayesian Additive Regression Trees。The Annals of Applied Statistics，4,1,266-298，< doi：10.1214 / 09-aoas285 >。
https://cran.r-project.org/web/packages/pgbart/index.html


lslx：通过惩罚似然的半确定结构方程模型
通过LASSO或minimax凹惩罚（MCP）的惩罚似然（PL）拟合半确认结构方程模型（SEM）
https://cran.r-project.org/web/packages/lslx/index.html


lme4: Linear Mixed-Effects Models using 'Eigen' and S4
Fit linear and generalized linear mixed-effects models. The models and their components are represented using S4 classes and methods. The core computational algorithms are implemented using the 'Eigen' C++ library for numerical linear algebra and 'RcppEigen' "glue".
https://cran.r-project.org/web/packages/lme4/index.html


BGLR：贝叶斯广义线性回归
贝叶斯广义线性回归。
https://cran.r-project.org/web/packages/BGLR/index.html


修复：使用潜在仪器变量使用内生回归器拟合线性模型
使用潜在的工具变量方法拟合具有内生回归量的线性模型。包中包含的方法是Lewbel（1997）< doi：10.2307 / 2171884 >高阶矩方法以及Lewbel（2012）< doi：10.1080 / 07350015.2012.643126 >异方差方法，Park和Gupta（2012）< doi：10.1287 /mksc.1120.0718 >使用Gaussian copula和Kim and Frees的联合估计方法（2007）< doi：10.1007 / s11336-007-9008-1>多级广义矩方法，用于处理多级设置中的内生性。这些是解决内生性问题的统计技术，不需要外部工具变量。请注意，对于2.0.0版本，引入了大量更改，这些更改大大提高了功能性和可用性，但却打破了向后兼容性。
https://cran.r-project.org/web/packages/REndo/index.html

rstanarm：通过Stan的贝叶斯应用回归建模
使用'rstan'软件包估计以前编译的回归模型，该软件包为Stan C ++库提供R接口以进行贝叶斯估计。用户通过惯用的R语法使用公式和data.frame以及先验的一些其他参数来指定模型。
https://cran.r-project.org/web/packages/rstanarm/index.html
https://cran.r-project.org/web/packages/rstanarm/vignettes/continuous.html

spTimer：时空贝叶斯建模
利用[1]贝叶斯高斯过程（GP）模型，[2]贝叶斯自回归（AR）模型和基于贝叶斯高斯预测过程（GPP）的贝叶斯高斯预测过程（GPP），拟合，空间预测和时间预测大量的时空数据用于时空大问题的AR模型。Bakar和Sahu（2015）< doi：10.18637 / jss.v063.i15 >。
https://cran.r-project.org/web/packages/spTimer/index.html

bayesdfa：贝叶斯动态因子分析（DFA）与'斯坦'
用'Stan'实现贝叶斯动态因子分析。动态因子分析是多变量时间序列的降维工具。'bayesdfa'以多种方式扩展了传统的动态因子模型。首先，通过使用student-t分布建模过程错误，可以在潜在趋势中估计极端事件。其次，可以任选地包括自回归和移动平均分量。第三，可以使用隐马尔可夫模型分析估计的动态因子，以评估对潜在制度的支持
https://cran.r-project.org/web/packages/bayesdfa/index.html

walker：具有时变系数的贝叶斯回归
贝叶斯动态回归模型，其中回归系数随着时间的推移随着随机行走而变化。支持高斯，泊松和二项式观测。马尔可夫链蒙特卡罗计算是使用Stan提供的哈密顿蒙特卡罗计算的，使用模型的状态空间表示，以便在系数上边缘化以进行有效采样。对于非高斯模型，Walker使用基于近似边际MCMC的重要性抽样类型估计器，如Vihola，Helske，Franks（2017，< arXiv：1609.02541 >）
https://cran.r-project.org/web/packages/walker/index.html



modesto：随机系统的建模与分析
当我们考虑连续观察的随机系统时，计算重要的数量。如，成本模型，限制分布，转移矩阵，过渡分布和占用矩阵。该方法描述于例如Ross S.（2014），Introduction to Probability Models。十一版。学术出版社。
https://cran.r-project.org/web/packages/modesto/index.html



cgam：约束广义加法模型
通过cgam例程拟合约束广义加性模型。给定一组预测器，每个预测器可具有形状或顺序限制，使用迭代重新加权的锥投影算法找到约束广义加性模型的最大似然估计。ShapeSelect例程选择预测变量的子集，并描述与响应的组件关系。对于每个预测变量，用户只需指定一组可能的形状或顺序限制。模型选择方法选择关系的形状和顺序以及变量。锥信息准则（CIC）用于选择变量和形状的最佳组合。当可能模型的集合很大时，可以使用遗传算法。此外，cgam例程使用翘曲平面样条实现二维等渗回归，没有可加性假设。它还可以适合具有三角样条的凸或凹回归曲面，而无需加性假设。见Mary C. Meyer（2013）<doi：10.1080 / 10485252.2013.797577 >了解更多详情。
https://cran.r-project.org/web/packages/cgam/index.html


集合：高性能容器数据类型
提供高性能容器数据类型，例如Queue，Stack，Deque，Dict和OrderedDict。基准< https://randy3k.github.io/collections/articles/benchmark.html >表明这些容器比其他包提供的容器渐进式效率更高
https://cran.r-project.org/web/packages/collections/index.html

econet：参数依赖网络中心度量的估计
提供使用线性 - 均值模型估计依赖于参数的网络中心度量的方法。实现了非线性最小二乘和最大似然估计。该方法允许网络效应中的链路和节点异构性，内生网络形成以及未连接节点的存在。例程还比较了依赖于参数的网络中心度量的解释力与网络中心性的标准度量的解释力。使用Battaglini和Patacchini（2018）的数据来说明“econet”一揽子计划的好处和特征，该数据研究了当立法者关心与他们有社会联系的其他立法者的行为时美国竞选捐款的决定因素。有关其他详细信息，请参阅插图
https://cran.r-project.org/web/packages/econet/index.html


sn：Skew-Normal和相关分布，如Skew-t
构建和操纵偏斜正常族和一些相关族的概率分布，特别是偏斜族，并在单变量和多变量情况下提供数据拟合和模型诊断的相关统计方法
https://cran.r-project.org/web/packages/sn/index.html

RXshrink：通过广义脊或最小角回归的最大似然收缩
识别并显示特定收缩路径的TRACE，并在正态分布理论下确定收缩程度，以便在回归（β）系数估算中产生MSE风险的最佳降低。当病态（几乎多线性）模型产生具有“错误”数字符号的OLS估计时，也提供了替代估计。
https://cran.r-project.org/web/packages/RXshrink/index.html


gmnl：具有随机参数的多项Logit模型
用随机系数估计多项Logit模型的最大模拟似然方法。具体而言，它允许估计具有连续异质性的模型，例如混合多项logit和广义多项logit。它还允许估计具有离散异质性的模型，例如潜类和混合混合多项logit模型。
https://cran.r-project.org/web/packages/gmnl/index.html

rsvd：随机奇异值分解
低秩矩阵分解是基本工具，广泛用于数据分析，降维和数据压缩。传统上，高精度的确定性矩阵算法用于此任务。然而，大规模数据的出现严重挑战了我们分析大数据的计算能力。随机性的概念已经被证明是一种有效的策略，可以快速生成熟悉问题的近似答案，例如奇异值分解（SVD）。rsvd软件包提供了几种随机矩阵算法，如随机奇异值分解（rsvd），随机主成分分析（rpca），随机鲁棒主成分分析（rrpca），随机内插分解（rid）和随机CUR分解（rcur）。 ）。此外，还提供了几种绘图功能。Erichson等人详细讨论了这些方法。（2016）<arXiv：1608.02148 >。
https://cran.r-project.org/web/packages/rsvd/index.html

Rchoice：具有随机参数的离散选择（二元，泊松和有序）模型
用于横截面和纵向数据的随机参数的二元（Probit和Logit），有序（Probit和Logit）和Poisson模型的估计的模拟最大似然法的实现。
https://cran.r-project.org/web/packages/Rchoice/index.html


GLMMadaptive：使用自适应高斯求积的广义线性混合模型
使用自适应高斯求积法则拟合最大似然下的单个分组因子的广义线性混合模型近似随机效应的积分; Jose C. Pinheiro和Douglas M. Bates（1995）< doi：10.1080 / 10618600.1995.10474663 >。
https://cran.r-project.org/web/packages/GLMMadaptive/index.html


ipc 进程间通信
https://cran.r-project.org/web/packages/ipc/vignettes/shinymp.html

lsmeans：最小二乘意味着
获得线性，广义线性和混合模型的最小二乘平均值。计算最小二乘平均值的对比或线性函数，以及斜率的比较。情节和紧凑的字母显示。最小二乘法是在Harvey，W（1960）“具有不等子类数的数据的最小二乘分析”，技术报告ARS-20-8，美国农业部国家农业图书馆中提出的，并在Searle，Speed和Milliken中进一步讨论（ 1980）“线性模型中的人口边际均值：最小二乘法的替代方法”，美国统计学家34（4），216-221 < doi：10.1080 / 00031305.1980.10483031 >。注意：lsmeans现在主要依赖于'emmeans'包中的代码。'lsmeans'将在不久的将来存档。
https://cran.r-project.org/web/packages/lsmeans/index.html

arfima：分数ARIMA（和其他长记忆）时间序列建模
模拟，拟合和预测长记忆和反持久时间序列，可能与ARMA，回归，传递函数组件混合。使用精确方法（MLE，预测，模拟）。错误报告应该通过GitHub（在< https://github.com/JQVeenstra/arfima >）完成，该软件包的开发版本存在; 它可以使用devtools安装。
https://cran.r-project.org/web/packages/arfima/index.html


blavaan：贝叶斯潜变量分析
拟合各种贝叶斯潜变量模型，包括验证性因子分析，结构方程模型和潜在增长曲线模型。
https://cran.r-project.org/web/packages/blavaan/index.html

bfsl：最合适的直线
提供来自York（1968）< doi：10.1016 / S0012-821X（68）80059-7 > 的解决方案，用于将直线拟合到具有两个坐标中的误差的双变量数据。它给出了对x和y两者中具有（可能相关的）正态分布误差的独立点的最佳拟合直线的截距，斜率和标准误差的无偏估计。其他常用的变量误差方法，如正交距离回归，几何平均回归或Deming回归，都是约克解的特例。
https://cran.r-project.org/web/packages/bfsl/index.html



通过convexjlr进行凸优化
https://cran.r-project.org/web/packages/convexjlr/vignettes/my-vignette.html

GMCM：高斯混合Copula模型的快速估计
使用高斯混合Copula模型的无监督聚类和元分析
https://cran.r-project.org/web/packages/GMCM/index.html

球：通过球统计的统计推断和确定的独立筛选
基于球统计的假设检验和确定独立筛选（SIS）程序，包括球发散< doi：10.1214 / 17-AOS1579 >，球协方差和球相关< doi：10.1080 / 01621459.2018.1462709 >，用于分析复杂数据。基于球发散和球协方差的无分布测试被实施以检测度量空间中的分布差异和关联< arXiv：1811.03750 >。此外，实现了基于球相关性及其所有变体的通用非参数SIS程序，以应对超高维数据环境中的挑战。
https://cran.r-project.org/web/packages/Ball/vignettes/Ball.html




logistic 标准步骤
https://cran.r-project.org/web/packages/blorr/vignettes/introduction.html

minerva: Maximal Information-Based Nonparametric Exploration for Variable Analysis
Wrapper for 'minepy' implementation of Maximal Information-based Nonparametric Exploration statistics (MIC and MINE family). Detailed information of the ANSI C implementation of 'minepy' can be found at <http://minepy.readthedocs.io/en/latest>.
https://cran.r-project.org/web/packages/minerva/index.html


msaenet：稀疏回归的多步自适应估计方法
用于高维回归特征选择的多步自适应弹性网（MSAENet）算法在Xiao和Xu（2015）< doi：10.1080 / 00949655.2015.1016944 >中提出，支持多步自适应MCP-net（MSAMNet）和多步自适应SCAD-net（MSASNet）方法。
https://cran.r-project.org/web/packages/msaenet/index.html

pgmm: Parsimonious Gaussian Mixture Models
Carries out model-based clustering or classification using parsimonious Gaussian mixture models. McNicholas and Murphy (2008) <doi:10.1007/s11222-008-9056-0>, McNicholas (2010) <doi:10.1016/j.jspi.2009.11.006>, McNicholas and Murphy (2010) <doi:10.1093/bioinformatics/btq498>, McNicholas et al. (2010) <doi:10.1016/j.csda.2009.02.011>.


emmeans：估计边际均值，即最小二乘均值
获得许多线性，广义线性和混合模型的估计边际均值（EMM）。计算EMM的对比或线性函数，趋势和斜率的比较。情节和紧凑的字母显示。讨论了最小二乘法，并在Searle，Speed和Milliken（1980）中提出了“估计边际均值”一词。线性模型中的人口边际均值：最小二乘法的替代方法，美国统计学家34（4） ，216-221 < doi：10.1080 / 00031305.1980.10483031 >。
https://cran.r-project.org/web/packages/emmeans/index.html

HCmodelSets：具有大量潜在解释变量的回归
用于执行Cox，DR和Battey，HS（2017）< doi：10.1073 / pnas.1703764114 > 提出的程序的简化，探索和模型选择阶段的软件，用于当潜在解释变量的数量远远超过样本量时的稀疏回归。该软件支持线性回归，基于概率的广义线性回归模型拟合和由部分似然拟合的比例风险模型。
https://cran.r-project.org/web/packages/HCmodelSets/index.html

libcoin：置换推断的线性检验统计量
Strasser和Weber（1999）< http://epub.wu.ac.at/102/ > 框架下的线性测试统计和置换推断的基本基础设施。最终用户不得使用此包。CRAN包'coin'实现了所有用户界面，可供任何人使用。
https://cran.r-project.org/web/packages/libcoin/index.html



blavaan：贝叶斯潜变量分析
拟合各种贝叶斯潜变量模型，包括验证性因子分析，结构方程模型和潜在增长曲线模型。
https://cran.r-project.org/web/packages/blavaan/index.html

logisticRR：Logistic回归调整后的相对风险
可以通过逻辑回归直接获得以潜在混杂因素为条件的调整后的比值比。然而，这些调整后的比值比被广泛错误地解释为相对风险。由于相对风险通常对公共健康感兴趣，我们提供了一个简单的代码，用于从潜在混杂因素下的逻辑回归模型中返回调整后的相对风险。
https://cran.r-project.org/web/packages/logisticRR/index.html

mvord：多元有序回归模型
一种灵活的框架，用于使用复合似然法拟合多元序数回归模型。
https://cran.r-project.org/web/packages/mvord/index.html


restriktor：线性模型的限制统计估计和推断
允许在（广义）线性统计模型中进行易于使用的测试或评估关于参数和效应的线性相等和不等式限制。
https://cran.r-project.org/web/packages/restriktor/index.html


BAS：使用贝叶斯自适应采样的贝叶斯变量选择和模型平均
用于线性模型和广义线性模型的贝叶斯变量选择和模型平均的包，使用随机或确定性采样而无需从后验分布替换。系数的先前分布来自Zellner的g-prior或对应于Zellner-Siow Cauchy Priors的g- priors的混合物或来自Liang等人（2008）< doi：10.1198 / 016214507000001337 > 的g- priors的混合物，用于线性模型或混合物Li和Clyde（2018）的GLM中的g-priors的结构< arXiv：1503.06913>。其他模型选择标准包括AIC，BIC和经验贝叶斯估计g。可以使用采样w / out替换基于采样模型更新采样概率，或者使用BAS树结构作为有效哈希表的有效MCMC算法采样模型。允许所有模型上的均匀先验或模型大小的β二项式先验分布，并且可以使用模型空间上的大p截断先验。用户可以强制始终包含变量。采样算法背后的细节在Clyde，Ghosh和Littman（2010）< doi：10.1198 / jcgs.2010.09049中提供。>。该材料基于国家科学基金会资助DMS-1106891的工作。本材料中表达的任何观点，发现，结论或建议均为作者的观点，不一定反映国家科学基金会的观点。
https://cran.r-project.org/web/packages/BAS/index.html


chngpt：阈值回归的估计和假设检验
阈值回归模型也称为两阶段回归，破坏回归，分裂点回归，结构变化模型和回归扭结模型。包括连续和不连续阈值模型的方法，但对前者的支持要大得多。该方案描述于Fong，Huang，Gilbert和Permar（2017）chngpt：阈值回归模型估计和推论，BMC Bioinformatics，in press，< doi：10.1186 / s12859-017-1863-x >。
https://cran.r-project.org/web/packages/chngpt/index.html

GHS：使用数据增强块Gibbs采样器的图形马蹄形MCMC采样器
绘制后验样本以估计多元高斯数据的精度矩阵。样本的后验是由Li，Bhadra和Craig（2017）< arXiv：1707.06661 >进行的图形马蹄估计。该函数使用Wang（2012）< doi：10.1214 / 12-BA729 > 的贝叶斯图形套索的矩阵分解和变量变换，以及Makalic和Schmidt先生在马蹄下采样的变量增量（2016）< arXiv：1508.03884 > 。图形马蹄形功能的结构受到使用阻塞采样的贝叶斯图形套索功能的启发，由Wang（2012）< doi：10.1214 / 12-BA729 > 撰写。
https://cran.r-project.org/web/packages/GHS/index.html


lass0：（高维）线性回归的Lasso-Zero
使用Lasso-Zero进行（可能是高维）线性回归模型的模型选择，Lasso-Zero是一种依赖于重复使用噪声词典的基于L1的方法，如Descloux，P。和Sardy，S。（2018）所描述的< arXiv： 1805.05133 >。
https://cran.r-project.org/web/packages/lass0/index.html

matrixNormal：矩阵正态分布
计算Matrix Normal的密度，概率和随机偏差（Iranmanesh et.al.（2010）< doi：10.7508 / ijmsi.2010.02.004 >）。还包括简单但有用的矩阵函数。有关更多信息，请参阅R包帮助文件。
https://cran.r-project.org/web/packages/matrixNormal/index.html


oem：正交化EM：对高大数据的惩罚回归
使用Xiong等人的正交化EM算法解决了大高数据的惩罚最小二乘问题。（2016）< doi：10.1080 / 00401706.2015.1054436 >。主拟合函数是oem（），函数cv.oem（）和xval.oem（）用于交叉验证，后者是线性模型的加速交叉验证函数。big.oem（）函数允许内存不合适。
https://cran.r-project.org/web/packages/oem/index.html


QDComparison：用于双样本分位数和分布比较的现代非参数工具
允许从业者确定（i）两个单变量分布（可以是连续的，离散的，甚至是混合的）是否相等，（ii）两个分布如何不同（形状差异，例如位置，比例等），以及（iii） ）两个分布不同（分位数），都使用非参数LP统计。主要参考文献是Jungreis，D。和Mukhopadhyay，S。（2018，技术报告）。https://cran.r-project.org/web/packages/QDComparison/index.html


CountsEPPM：计数数据的均值和方差建模
使用扩展泊松过程模型（EPPM）对欠分散和过分散计数数据建模，如文章Faddy和Smith（2011）< doi：10.18637 / jss.v069.i06 >。
https://cran.r-project.org/web/packages/CountsEPPM/index.html

kza：Kolmogorov-Zurbenko自适应滤波器
时间序列分析包括断裂检测，光谱分析，KZ傅立叶变换。
https://cran.r-project.org/web/packages/kza/index.html


rhmc：哈密尔顿蒙特卡洛
在R中实现简单的哈密顿蒙特卡罗例程，用于从任何期望的连续且平滑的目标分布中进行采样。有关哈密​​尔顿蒙特卡洛的详细信息，请参阅Neal（2017）< arXiv：1701.02434 >。不支持自动参数选择。
https://cran.r-project.org/web/packages/rhmc/index.html


palasso：配对的套索回归
使用成对的协变量实现稀疏回归（Rauschenberger等人）。
https://cran.r-project.org/web/packages/palasso/index.html
https://cran.r-project.org/web/packages/palasso/vignettes/vignette.html


docopulae：Copula模型的最优设计
基于Fisher信息的Copula模型优化设计的直接方法。提供灵活的功能，用于构建联合PDF，评估Fisher信息和寻找最佳设计。它包括一个可扩展的求和和积分解决方案，称为'nint'，用于转换，绘图和比较设计的函数，以及一组用于常见低级任务的工具。
https://cran.r-project.org/web/packages/docopulae/index.html


RWeightedKmeans：加权对象k-均值算法
k-means算法的加权对象版本，对异常值数据具有鲁棒性。
https://cran.r-project.org/web/packages/RWeightedKmeans/index.html


SAMCpack：随机逼近蒙特卡罗（SAMC）采样器和方法
随机逼近蒙特卡罗（SAMC）是着名的马尔可夫链蒙特卡罗（MCMC）算法之一。众所周知，它能够从多模态或双重难处理的分布中进行采样。我们为连续分发提供通用SAMC采样器。支持用户指定的R和C ++密度。我们还为利用SAMC计算的特定问题提供函数。参见Liang等人（2010）< doi：10.1002 / 9780470669723 >以完整地介绍该方法。
https://cran.r-project.org/web/packages/SAMCpack/index.html


dhglm：双层次广义线性模型
实现双层次广义线性模型，其中随机效应方差的均值，色散参数和残差方差（过度离散）可以进一步建模为随机效应模型。
https://cran.r-project.org/web/packages/dhglm/index.html

mvLSW：多变量局部平稳小波过程估计
用小波分析多变量时间序列的工具。这包括：从多变量进化小波谱（mvEWS）模拟多变量局部平稳小波（mvLSW）过程; 估计mvEWS，局部相干性和局部部分相干性。有关详细信息，请参阅Park，Eckley和Ombao（2014）< doi：10.1109 / TSP.2014.2343937 >。
https://cran.r-project.org/web/packages/mvLSW/index.html

mmpf：预测函数的蒙特卡罗方法
使用蒙特卡罗积分将预测函数边缘化并计算置换重要性。

NetworkInference：推断潜在扩散网络
这是netinf算法的R实现（Gomez Rodriguez，Leskovec和Krause，2010）< doi：10.1145 / 1835804.1835933 >。给定一组在一组节点之间传播的事件，该算法推断出最可能的稳定扩散网络，该网络是扩散过程的基础。
https://cran.r-project.org/web/packages/NetworkInference/index.html

nipals：使用NIPALS和Gram-Schmidt正交化的主成分分析
主成分分析矩阵使用非线性迭代偏最小二乘与Gram-Schmidt正交化的得分和负荷。优化速度。见Andrecut（2009）< doi：10.1089 / cmb.2008.0221 >。
https://cran.r-project.org/web/packages/nipals/index.html


sparcl：执行稀疏层次聚类和稀疏K均值聚类
实现Witten和Tibshirani（2010）的稀疏聚类方法：“聚类中的特征选择框架”; 发表于Journal of the American Statistical Association 105（490）：713-726。

lolog：潜在订单Logistic图模型
网络潜序逻辑（LOLOG）模型的估计。LOLOG是一种灵活且完全通用的统计图模型。该软件包提供了执行MOM，GMM和变分推理的功能。提供视觉诊断和拟合度度量。有关方法的详细说明，请参见研究员（2018）< arXiv：1804.04583 >。
https://cran.r-project.org/web/packages/lolog/index.html

pkmon：离散函数k-单调约束下的最小二乘估计
我们使用基于Groeneboom等人（2008）< doi：10.1111 / j.1467-9469.2007.00588.x > 的支持约简算法的方法，在k-单调约束下实现两个最小二乘估计。第一个是关于k-单调离散函数集的投影估计器。第二个是对k-单调离散概率集的投影。该软件包提供了从Lefevre和Loisel（2013）< doi：10.1239 / jap / 1378401239 >以及样条混合中基于样条生成样本的函数。
https://cran.r-project.org/web/packages/pkmon/index.html


reReg：周期性事件回归
循环事件过程和失败时间数据的回归模型的集合。可用的方法包括Xu等人的这些方法。（2017）< doi：10.1080 / 01621459.2016.1173557 >，Lin等。（2000）< doi：10.1111 / 1467-9868.00259 >，Wang等。（2001）< doi：10.1198 / 016214501753209031 >，Ghosh和Lin（2003）< doi：10.1111 / j.0006-341X.2003.00102.x >，以及Huang和Wang（2004）< doi：10.1198 / 016214504000001033 >。
https://cran.r-project.org/web/packages/reReg/index.html

tidybayes：整洁数据和贝叶斯模型的'Geoms'
以整洁的数据格式为贝叶斯模型（'JAGS'，'Stan'，'rstanarm'，'brms'，'MCMCglmm'，'coda'......）编制和提取，操纵和可视化后抽取数据。提供的功能有助于从贝叶斯模型中提取抽取的整洁数据帧，并以整齐的格式生成点汇总和间隔。此外，'ggplot2''geoms'和'stats'是为常见的可视化基元提供的，例如具有多个不确定区间的点，眼图（区间加上密度），以及具有多个任意不确定带的拟合曲线。
https://cran.r-project.org/web/packages/tidybayes/index.html

boral：贝叶斯排序和回归AnaLysis
用于分析生态学中多元数据的贝叶斯方法。使用马尔可夫链蒙特卡罗（MCMC）方法通过Three进行估计。可以拟合JAGS类型的模型：1）仅使用解释变量，boral将独立列广义线性模型（GLM）拟合到响应矩阵的每列; 2）仅使用潜在变量，boral适用于基于模型的无约束排序的纯潜变量模型; 3）利用解释和潜在变量，boral拟合将列GLM与潜在变量相关联，以说明响应矩阵的列之间的任何残差相关性。
https://cran.r-project.org/web/packages/boral/index.html

stplanr：可持续交通规划
用于运输规划的功能和数据访问工具，包括起始 - 目的地分析，路线分配和建模旅行模式。
https://cran.r-project.org/web/packages/stplanr/vignettes/stplanr-paper.html


bayesm：贝叶斯推理营销/微观计量经济学
涵盖了营销和微观计量经济学应用中使用的许多重要模型。该软件包包括：贝叶斯回归（单变量或多变量变量），贝叶斯看似无关回归（SUR），二进制和序数Probit，多项Logit（MNL）和多项式Probit（MNP），多变量Probit，负二项（泊松）回归，多变量法线的混合（包括聚类），具有正常基的Dirichlet过程先验密度估计，具有正态先验和协变量的分层线性模型，具有法线先验和协变量的混合的分层线性模型，具有法线先验和协变量的混合的分层多项式Lo​​gits，具有Dirichlet过程先验和协变量的分层多项式Lo​​gits，分层负二项式回归模型，
https://cran.r-project.org/web/packages/bayesm/index.html


tsxtreme：时间序列中极值依赖的贝叶斯模型
表征时间序列的极值依赖结构，避免预处理和过滤，通常采用峰值超阈值方法。它使用了Heffernan和Tawn（2004）< doi：10.1111 / j.1467-9868.2004.02050.x > 的条件方法，这种方法在极值和渐近依赖结构方面非常灵活，贝叶斯方法提高了效率并允许导出度量不确定性。例如，可以估计与时间上的簇的大小相关的极值指数，并且从其后验分布获得样本。
https://cran.r-project.org/web/packages/tsxtreme/index.html

mirtjml：高维项目因子分析的联合极大似然估计
基于多维项目响应理论模型，为项目因子分析（IFA）提供约束联合最大似然估计算法。到目前为止，我们基于二维响应数据的多维双参数逻辑（M2PL）模型提供探索性和确认性IFA的功能。与传统的IFA估算方法相比，此方案中实施的方法可以更好地扩展到包含大量受访者，项目和潜在因素的数据。多处理'OpenMP'API有助于计算。有关更多信息，请参阅：1。Chen，Y.，Li，X。和Zhang，S。（2018）。高维探索项因子分析的联合极大似然估计。Psychometrika，1-23。< doi：10.1007 / s11336-018-9646-5>; 2. Chen，Y.，Li，X。和Zhang，S。（2017）。大规模数据的结构潜在因子分析：可识别性，可估计性及其影响。arXiv preprint < arXiv：1712.08966 >。
https://cran.r-project.org/web/packages/mirtjml/index.html

SGL：将GLM（或Cox模型）与Lasso和Group Lasso正则化相结合
通过惩罚最大似然拟合一个正则化的广义线性模型。该模型适合惩罚参数的值的路径。适合线性，逻辑和Cox模型。
https://cran.r-project.org/web/packages/SGL/index.html


ragt2ridges：向量自回归（VAR）过程的岭估计
ragt2ridges-package提供向量自回归过程的岭最大似然估计：VAR（1），VAR（2）和VARX（1）模型（更多要添加）。可以通过以下方式将先验知识结合到估计中：a）在时间序列链图中被认为不存在的边缘的规范，以及b）对于大的惩罚参数值，参数估计被收缩的收缩目标。估计功能伴随着惩罚参数选择的方法。此外，该软件包还提供了用于开发估计模型的支持功能。其中，i）实现推断非稀疏岭估计（以及由此的时间序列链图）的支持的过程，ii）节点网络汇总统计表，iii）互信息分析，iv）脉冲响应分析。参看 Miok等人。（2017）<doi：10.1002 / bimj.201500269 >和Miok等人。（2018）< doi：10.1002 / bimj.201700195 >有关实施方法的详细信息。
https://cran.r-project.org/web/packages/ragt2ridges/index.html


MGLM：多变量响应广义线性模型
提供（1）拟合多变量离散分布，（2）从多变量离散分布生成随机数，以及（3）对多变量分类响应数据进行回归和惩罚回归的函数。实现的模型包括：多项logit模型，Dirichlet多项式模型，广义Dirichlet多项式模型和负多项模型。充分利用次要化最大化（MM）算法和Newton-Raphson方法，我们推导并实现稳定有效的算法来找到最大似然估计。在多核机器上，支持多线程。
https://cran.r-project.org/web/packages/MGLM/index.html


rjags: Bayesian Graphical Models using MCMC
Interface to the JAGS MCMC library.
https://cran.r-project.org/web/packages/rjags/index.html

BMSC：约束条件下的贝叶斯模型选择
一个贝叶斯回归包，支持使用Stan的约束系数估计和变量选择。这包括马蹄形先验（< doi：10.1093 / biomet / asq017 >）的稳健变量选择算法，该算法在潜在参数约束下考虑主效应，相互作用以及给定变量的幂，找到最优模型。
https://cran.r-project.org/web/packages/BMSC/index.html


bsplinePsd：使用B样条Priors的贝叶斯非参数谱密度估计
实现Metropolis-in-Gibbs MCMC算法以灵活地估计静止时间序列的谱密度。该算法在使用Whittle似然产生伪后验样本之前更新非参数B样条，并且基于Edwards，MC，Meyer，R。和Christensen，N.，Statistics and Computing（2018）中提出的工作。<doi.org/10.1007/s11222-017-9796-9>。
https://cran.r-project.org/web/packages/bsplinePsd/index.html


sdpt3r：半定二次线性规划求解器
使用SDPT3的R实现来解决一般半定线性规划公式（KC Toh，MJ Todd和RH Tutuncu（1999）< doi：10.1080 / 10556789908805762 >）。这包括诸如最近相关矩阵问题（Higham（2002）< doi：10.1093 / imanum / 22.3.329 >），D-最佳实验设计（Smith（1918）< doi：10.2307 / 2331929 >），距离加权判别等问题（Marron和Todd（2012）< doi：10.1198 / 016214507000001120 >），以及包括最大割问题的图论问题。有关SDPT3的技术细节可以在RH Tutuncu，KC Toh和MJ Todd（2003）< doi：10.1007 / s10107-002-0347-5 >中找到。
https://cran.r-project.org/web/packages/sdpt3r/index.html

RSGHB：分层贝叶斯估计的函数：一种灵活的方法
使用分层贝叶斯（HB）框架估计模型的函数。灵活性允许用户直接指定似然函数而不是假设预定的模型结构。可以使用此代码估计的模型类型包括离散选择模型族（Multinomial Logit，Mixed Logit，嵌套Logit，Error Components Logit和Latent Class）以及有序的probit和ordered logit等有序响应模型。此外，该软件包允许灵活地将参数指定为固定的（跨个体不变）或随机分布的随机参数。支持的参数分布包括正常，正/负对数正态，正/负删失正态和约翰逊SB分布。肯尼斯火车' 用于进行分层贝叶斯估计的Matlab和Gauss代码已经成为该软件包中包含的一些功能的基础。这些Matlab / Gauss函数已被重写以在R中进行优化。添加了大量代码以增加代码库的灵活性和可用性。可以在这里找到Train的原始Gauss和Matlab代码：<http://elsa.berkeley.edu/Software/abstracts/train1006mxlhb.html >在此处查看关于HB in Discrete Choice with Simulation的章节：< http://elsa.berkeley.edu/books/choice2.html >; 以及他在这里使用HB与非正态分布的论文：< http://eml.berkeley.edu// ~train/trainsonnier.pdf >。作者还要感谢Stephane Hess和Choice Modeling Center的宝贵贡献：< https://cmc.leeds.ac.uk/ >。
https://cran.r-project.org/web/packages/RSGHB/index.html

logNormReg：log Normal Linear Regression
用于拟合具有对数正态误差和身份链接的简单线性回归模型的函数（以原始比例获取响应）。见Muggeo（2018）< doi：10.13140 / RG.2.2.18118.16965 >。
https://cran.r-project.org/web/packages/logNormReg/index.html


iprior：使用I-Priors进行回归建模
提供执行和分析I-prior回归模型的方法。通过直接优化对数似然或EM算法来进行估计。

bnlearn：贝叶斯网络结构学习，参数学习和推理
贝叶斯网络结构学习，参数学习和推理。该软件包实现了基于约束的（PC，GS，IAMB，Inter-IAMB，Fast-IAMB，MMPC，Hiton-PC），成对（ARACNE和Chow-Liu），基于分数（Hill-Climbing和禁忌搜索）和混合（MMHC和RSMAX2）离散，高斯和条件高斯网络的结构学习算法，以及许多得分函数和条件独立性测试。还实现了Naive Bayes和Tree-Augmented Naive Bayes（TAN）分类器。包括一些效用函数（模型比较和操作，随机数据生成，弧定向测试，简单和高级图），以及对参数估计（最大似然和贝叶斯）和推理，条件概率查询和交叉验证的支持。http://www.bnlearn.com >。
https://cran.r-project.org/web/packages/bnlearn/index.html

EZtune：调整AdaBoost，支持向量机和梯度增强机器
包含两个功能，旨在简化调校监督学习方法。eztune函数使用遗传算法或准Newton-Raphson优化器来找到最佳的调整参数集。用户可以选择优化器，学习方法，以及优化是否基于通过重新替换或交叉验证获得的准确性。函数eztune.cv将计算交叉验证的错误率。eztune.cv的目的是在重新替换用于优化时提供交叉验证的准确性，因为重新取代通常会产生过高的准确性。
https://cran.r-project.org/web/packages/EZtune/index.html

移民：迭代Max-Min熵边际最大化与特征选择的交互术语
基于大边缘原理，该软件包执行特征选择方法：“IM4E”（最小 - 最小熵算法下的迭代裕度最大化）; “imIM4E”（Max-Min熵算法下的不平衡迭代裕度最大化）; “移民”（迭代最大 - 最小熵边界最大化与交互项算法）; “Simba”（基于迭代搜索边界的算法）; “LFE”（局部特征提取算法）。该包还对上述特征选择方法执行预测。
https://cran.r-project.org/web/packages/Immigrate/index.html


MLGL：多层组 - 套索
它在解释变量之间的冗余的上下文中实现了变量选择的新过程，其适用于高维数据（Grimonprez等人（2018）< https://hal.inria.fr/hal-01857242 >）
https://cran.r-project.org/web/packages/MLGL/index.html

nprotreg：球体 - 球体回归的非参数旋转
通过估计局部加权旋转来拟合球体 - 球体回归模型。根据非刚性旋转模型模拟球 - 球数据。提供在Newton-Raphson学习方案中应用迭代过程的偏差减少方法。利用交叉验证来选择平滑参数。参见Marco Di Marzio，Agnese Panzera和Charles C. Taylor（2018）< doi：10.1080 / 01621459.2017.1421542 >。
https://cran.r-project.org/web/packages/nprotreg/index.html

nvmix：多元正态方差混合（包括非整数自由度的学生t分布）
用于处理多元正态方差混合分布的函数，包括评估它们的分布函数，密度和随机数生成。
https://cran.r-project.org/web/packages/nvmix/index.html


vimp：非参数变量重要性
使用潜在回归函数的灵活估计，计算高维和低维中非参数变量重要性度量的点估计和有效置信区间。有关这些方法的更多信息，请参阅Williamson等。（2017）< https://biostats.bepress.com/uwbiostat/paper422/ >。
https://cran.r-project.org/web/packages/vimp/index.html


egoTERGM：通过期望最大化（EM）估计自我时间指数随机图模型
使用两阶段估计估计自我 - 时间指数随机图模型，包括通过时间指数随机图模型参数的k均值聚类和根据Campbell的EM（2018）< doi：10.7910 / DVN / TWHEZ9 >。
https://cran.r-project.org/web/packages/egoTERGM/vignettes/KnechtVignette.html


HARModel：异构自回归模型
使用Corsi（2009）< doi：10.1093 / jjfinec / nbp001 >中的HAR模型进行估算，模拟和预测。
https://academic.oup.com/jfec/article-abstract/7/2/174/856522?redirectedFrom=fulltext


nlts：非线性时间序列分析
R函数用于（非）线性时间序列分析，重点是非参数自回归和阶次估计，以及线性/可加性的测试。
https://cran.r-project.org/web/packages/nlts/index.html

saemix：随机逼近期望最大化（SAEM）算法
SAEMIX软件包实现了随机逼近EM算法，用于（非）线性混合效应模型中的参数估计。SAEM算法： - 使用随机逼近期望最大化（SAEM）算法计算总体参数的最大似然估计，而不使用模型的任何近似（线性化，正交近似等）， - 提供最大的标准误差似然估计器 - 使用Hastings-Metropolis算法估计条件模式，条件均值和各个参数的条件标准差。Monolix集团的成员（< http://group.monolix.org/ >）已经发表了SAEM在农学，动物育种和PKPD分析中的几种应用。
https://cran.r-project.org/web/packages/saemix/index.html

varbin：连续和分类变量的最佳分箱
用于简单有效地对连续和分类数据进行离散化的工具。该包计算给定解释变量相对于用户指定的目标变量的最佳分箱。目的是为每个计算的双点分配唯一的证据权重值，以便重新编码原始变量。该包允许用户对所得到的分箱上的功能形式施加某些限制，同时最大化原始数据中的整体信息值。该软件包非常适用于逻辑评分模型，其中输入变量可能受到例如监管机构的线性等限制。一个很好的来源，详细描述了记分卡的发展，证据权重编码在信用评分中的作用是（Siddiqi 2006，ISBN：978-0-471-75451-0）。该软件包利用决策树和等渗回归的离散特性来适应灵活的功能形式和最大信息值之间的权衡。

dglars：微分几何最小角度回归
拟稀疏广义线性模型的微分几何最小二乘回归方法。在该版本的包中，用户可以拟合指定高斯，泊松，二项式，伽马和逆高斯族的模型。此外，可以使用若干链接函数来模​​拟响应变量的条件期望值与线性预测值之间的关系。解决方案曲线可以使用有效的预测校正器或循环坐标下降算法来计算，如通过以下URL链接的论文中所述。
https://cran.r-project.org/web/packages/dglars/index.html


mfbvar：混合频率贝叶斯VAR模型
用明尼苏达或稳态先验估计混合频率贝叶斯矢量自回归（VAR）模型。该软件包实现了一个基于状态空间的VAR模型，可以处理数据的混合频率。使用马尔可夫链蒙特卡罗估计模型以数值逼近后验分布，其中先验可以是明尼苏达先验，如Schorfheide和Song（2015）< doi：10.1080 / 07350015.2014.954707 >所使用的，或稳态之前，正如Ankargren，Unosson和Yang（2018）所倡导的那样< http://uu.diva-portal.org/smash/get/diva2:1260262/FULLTEXT01.pdf >。
https://cran.r-project.org/web/packages/mfbvar/index.html

TreeSearch：使用自定义最优性标准的系统发生树搜索
使用用户定义的标准搜索最佳的系统发育树。实现Profile Parsimony（Faith和Trueman，2001）< doi：10.1080 / 10635150118627 >和连续近似（Farris，1969）< doi：10.2307 / 2412182 >。使用Brazeau，Guillerme和Smith（2019）< doi：10.1093 / sysbio / syy083 > 的算法处理不适用的数据。
https://cran.r-project.org/web/packages/TreeSearch/index.html


gllvm: Generalized Linear Latent Variable Models
Analysis of multivariate data using generalized linear latent variable models (gllvm). Estimation is performed using either Laplace approximation method or variational approximation method implemented via TMB (Kristensen et al., (2016), <doi:10.18637/jss.v070.i05>). Details for gllvm, see Hui et al. (2015) <doi:10.1111/2041-210X.12236> and (2017) <doi:10.1080/10618600.2016.1164708> and Niku et al. (2017) <doi:10.1007/s13253-017-0304-7>.
https://cran.r-project.org/web/packages/gllvm/index.html


kmed：基于距离的k-Medoids
基于距离的k-medoids聚类的算法：简单快速的k-medoids（Park and Jun，2009）< doi：10.1016 / j.eswa.2008.01.039 >，排名k-medoids（Zadegan等，2013）< doi：10.1016 / j.knosys.2012.10.012 >，和步骤k-medoids（Yu等，2018）< doi：10.1016 / j.eswa.2017.09.052 >。计算混合变量数据的距离，如Gower，Podani，Wishart（2003）< doi：10.1007 / 978-3-642-55721-7_23 >，Huang（1997）< http://citeseerx.ist.psu.edu/viewdoc /download?doi=10.1.1.94.9984&rep=rep1&type=pdf>,Harikumar和PV（2015）< doi：10.1016 / j.procs.2015.10.077 >，以及Ahmad和Dey（2007）< doi：10.1016 / j。 datak.2007.03.016>。群集验证应用引导程序生成具有灵活重新排序矩阵算法（例如完整，病区或平均链接）的热图。
https://cran.r-project.org/web/packages/kmed/index.html



regsem：正则化结构方程模型
使用脊和套索惩罚（和扩展）来惩罚结构方程模型中的特定参数。该软件包提供额外的成本函数，交叉验证以及传统结构方程模型之外的其他扩展。还包含执行探索性调解（XMed）的功能。
https://cran.r-project.org/web/packages/regsem/index.html










10.10 - 12/25






