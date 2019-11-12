
### 安装新的包

在 Anaconda 环境下离线安装新包:
打开 Anaconda Powershell Prompt 命令框
输入 比如： conda install --use-local C:\Users\z0042fpf\Downloads\tsfresh-0.12.0-py_0.tar.bz2
等待后便可安装成功
参考 <https://blog.csdn.net/qq_33039859/article/details/80785535> 

直接打开 Anaconda Navigator, search libraries, 安装


安装特定版本第三方库
pip install catboost==0.16.5

修改 Dataframe 列名
http://sofasofa.io/forum_main_post.php?postid=1000532


在 Dataframe 里插入一个新列
http://sofasofa.io/forum_main_post.php?postid=1000562


### 时间序列分类相关方法

	• 使用 tsfresh 库，从数据中计算、提取特征、进行训练
	• 使用 LSTM, Neural Network 训练
	• 使用 pyts 把一维时间序列转换成二维图片

相关参考：
tsfresh
https://tsfresh.readthedocs.io/en/latest/text/sklearn_transformers.html
https://tsfresh.readthedocs.io/en/latest/text/tsfresh_on_a_cluster.html?highlight=download
https://blog.csdn.net/takethevow/article/details/80171440
https://blog.csdn.net/qq_23144435/article/details/81100977

pyts
https://blog.csdn.net/weixin_39679367/article/details/88653018

在使用sklearn时如何选择合适的分类器

基于xgboost+GridSearchCV的波士顿房价预测 (回归）



### 其它

分类器:
from xgboost import XGBClassifier
from lightgbm import LGBMClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import AdaBoostClassifier    [https://bit.ly/2TtwinG]

数据集:
sklearn.datasets  [https://sklearn.apachecn.org/docs/0.21.3/47.html] 
                           
数据预处理:
from sklearn.preprocessing import StandardScaler, MinMaxScaler, MaxAbsScaler
from sklearn.pipeline import Pipeline, FeatureUnion

sklearn 数据预处理: 归一化、标准化、正则化 https://www.cnblogs.com/hudongni1/articles/5499307.html
5.3 预处理数据 sklearn中文文档 https://sklearn.apachecn.org/docs/0.21.3/40.html


### 用 scikit-learn pipeline 搜索模型和参数

提问:  
https://stackoverflow.com/questions/23045318/scikit-grid-search-over-multiple-classifiers
Hyperparameter optimization across multiple models in scikit-learn
https://github.com/davidsbatista/machine-learning-notebooks/blob/master/hyperparameter-across-models.ipynb
https://github.com/bmurauer/pipelinehelper/blob/master/example.py


### 过采样

Imbalanced Classes: Part 2
https://towardsdatascience.com/imbalanced-class-sizes-and-classification-models-a-cautionary-tale-part-2-cf371500d1b3



### Pipeline

A Simple Guide to Scikit-learn Pipelines
From <https://medium.com/vickdata/a-simple-guide-to-scikit-learn-pipelines-4ac0d974bdcf> 

Scikit-Learn Pipeline Examples
From <http://queirozf.com/entries/scikit-learn-pipeline-examples> 




