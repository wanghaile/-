
# -中文分词器分析
老板心血来潮突然要做个搜索，苦逼的IT狗疯狂加班，终于明白了开源Lucene,Solr,ES这些搜索引擎框架及服务紧接着某度一下，
一堆的分词器插件顿时蒙B了。。。。于是苦逼的小狗，又开始对市场开源分词器开始调查，
终于用了三天时间测试各个分词器后完成这篇分析报告，不足之处大家一定忍着别吐呀。。。
那我就按照自己测试F1值排序写吧。。。


1、AnsJ分词器

相关链接:https://github.com/NLPchina/ansj_seg
相关文档：http://nlpchina.github.io/ansj_seg/
文档是否完善:是
测评结果:
分词类型	         耗时(字符/毫秒)    精度(Precision)   召回率(Recall) 	 F值(F-mesure)	   错误率(Error Rate)

nlp分词-NlpAnalysis	    122.37	         92.58%	         92.90%	           92.74%	           7.44%
精准分词-ToAnalysis	    257.12		       92.57%		        92.93%		        92.75%	         7.45%
基本分词-BaseAnalysis	  60.33		         82.89%		       90.03%		          86.31%	         18.58%
面向索引的分词		        185.47		       40.98%		        97.16%	           57.65%	         50.10%



2、THULAC	
清华大学开发;java、c++版本，
相关链接:http://nlp.csai.tsinghua.edu.cn/site2/index.php/zh/the-news/238-thulac-thutag	
文档是否完善:文档不完善，java版本	
测评结果:
分词类型	      耗时(字符/毫秒)	 精度(Precision)	召回率(Recall)	 F值(F-mesure)	 错误率(Error Rate)
CBTaggingD分词	    	33.65		       86.70%		       89.27%	        87.97%	         13.70%


3、HanLP分词器
相关链接:https://github.com/hankcs/HanLP
文档是否完善:是
测评结果:
分词类型	      耗时(字符/毫秒)	 精度(Precision)	 召回率(Recall)	 F值(F-mesure)	 错误率(Error Rate)
N-最短路径分词	    44.52	          86.81%	        84.75%	         85.77%	         12.88%
最短路径分词	      171.02	        85.73%	        84.73%	         85.22%	         14.11%
极速词典分词	      1631.5	        80.80%	        86.50%	         83.55%	         20.56%
标准分词	          78.92	          87.76%	        83.13%	         85.38%	         11.60%
NLP分词	          110.52	        87.86%	        82.63%	         85.17%	         11.42%
CRF分词	          18.38	          88.32%	        82.53%	         85.33%	         10.91%
索引分词						316.77					75.38%					90.92%					 82.43%					 29.69%


4、Jcseg	
相关链接:https://github.com/lionsoul2014/jcseg	
文档是否完善:完善	
测评结果:
分词类型	   耗时(字符/毫秒)	 精度(Precision)	 召回率(Recall)	 F值(F-mesure)	 错误率(Error Rate)
复杂模式				165.49						84.55%					83.05%					83.80%					15.18%
简易模式				306.76						83.23%					82.15%					82.69%					16.55%


5、Fudannlp	
相关链接:https://github.com/joeywen/fudannlp	
文档是否完善:完善	
测评结果:
分词类型	      耗时(字符/毫秒)	 精度(Precision)	 召回率(Recall)	 F值(F-mesure)	 错误率(Error Rate)
CWSTagger分词  	55.93	             81.16%					85.76%						83.40%					19.91%


6、Jieba	
相关链接:https://github.com/yanyiwu/cppjieba;	
文档是否完善:java版不完善
测评结果:
分词类型	   耗时(字符/毫秒)	 精度(Precision)	 召回率(Recall)	 F值(F-mesure)	 错误率(Error Rate)
SEARCH分词	    509.28						83.93%						80.56%				82.21%						15.42%
INDEX分词			232.48						76.06%						87.81%				81.52%						27.63%


7、MMSeg4j 	
相关链接:https://github.com/chenlb/mmseg4j-solr;
https://github.com/chenlb/mmseg4j-core;
相关文档:http://blog.chenlb.com/category/mmseg4j	
文档是否完善:欠缺,主要针对solr,lucene索引	
测评结果:
分词类型	      耗时(字符/毫秒)	 精度(Precision)	 召回率(Recall)	 F值(F-mesure)	 错误率(Error Rate)
ComplexSeg分词	    433.78						74.76%				61.81%					67.67%						20.87%
SimpleSeg分词			629.21						73.85%				61.14%					66.90%						21.65%
MaxWordSeg分词			372.44						68.86%				64.86%					66.80%						29.34%


8、IKAnalyzer	
相关链接:https://github.com/yozhao/IKAnalyzer	
文档是否完善:完善	
测评结果:
分词类型	      耗时(字符/毫秒)	 精度(Precision)	 召回率(Recall)	 F值(F-mesure)	 错误率(Error Rate)
细粒度切分分词			29.88						74.67%					59.70%					66.35%						20.25%
智能切分分词				57.11						59.71%					73.23%					65.78%						49.41%

以下几个分词器能力有限有的不是java版本，有的配置复杂，有的长期不再维护。。
希望大牛们再更新提炼吧。。。。
9、Paoding 	
相关链接:http://git.oschina.net/zhzhenqin/paoding-analysis	
文档简单。维护差	


10、Stanford	
相关链接:http://nlp.stanford.edu/software/segmenter.shtml	
文档复杂，调用复杂。	


11、PanGu
相关链接：http://pangusegment.codeplex.com/	
完善、C#版本	

12、NLPIR	
相关链接：https://github.com/NLPIR-team/NLPIR	
完善，衍生出AnsJ分词	

13、LTP	哈工大分词器
相关链接：https://github.com/HIT-SCIR/ltp	
提供云服务，C++版本	

					
PS：		
1、本次调查对象针对java版本分词器进行，基本主流分词都有java版本实现，规避跨语言造成的影响			
2、本次测试使用国际自然语言组织发布的资源集http://www.sighan.org/bakeoff2005/			
3、综合各个指标看，从文档及配置程度及最终综合测评结果看选择中科院的JAVA版本改写的ANJ或者清华大学版本，
个人建议选择ANJ.	
