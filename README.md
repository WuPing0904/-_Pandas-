# KnowledgePlanet_Pandas
跟着知识星球学Python之Pandas

(一)数据分析之文件读取、数据合并（拼接、关联）、保存。
1.读取
读取 pd.read_csv()
读取前两行 x.head(2)
读取倒数5条数据 x.tail()

2.合并
合并数据 x.append(y,ignore_index=True)
内联合并数据 x.merge(y,how='inner',on='xId')

3.查看
维度x.shape 
去重后的数据条数 len(x.xId.unique())
x和y交集去重后的数据条数 len(np.intersectld(x.xId.unique(),y.xId.unique()))

4.保存
保存数据 to.csv
