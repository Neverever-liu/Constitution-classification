# Constitution-classification
## 基于人体检的无监督聚类
由于一开始的数据不能直接作为训练数据，要经过归一化处理。普通的归一化不能使数据出现良好的结果，所以采用了各种特殊归一化来找出最好的数据转化方式。
聚类方法有：Kmeans，AgglomerativeClustering，MiniBatchKMeans，SpectralClustering，DBSCAN聚类
使用的指标：轮廓系数(Silhouette Coefficient)，戴维斯-博尔丁指数(Davies-Bouldin index)，卡林斯基-哈拉巴兹指数(Calinski-Harabaz Index)，SSE，标准化互信息（NMI），调整互信息（AMI）	
由于是无监督聚类，对于不同的聚类数目，不同的归一化的数据最终聚类结果都需要进行比较
（人的体测数据为保密数据，不公开）
