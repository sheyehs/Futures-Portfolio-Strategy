单品种因子分析
原始数据在别处整理成规范的形式，即纵轴为时间，横轴为因子名称。有些简单的因子可以拿来直接跑模型，有些则要在多种因子间做进一步加工以形成新的因子，这些复杂因子的构造程序保存在factor_construct中(以后应该整理成一个文件夹)。不需做进一步生成因子的数据则可以直接跑入factor_examine中。

收盘价与预测差异置于同一张图

再细分流程：
	train: fit models
	test: select model, best estimate
	validate: predict, difference analysis