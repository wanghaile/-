# -���ķִ�������
�ϰ���Ѫ����ͻȻҪ������������Ƶ�IT�����Ӱ࣬���������˿�ԴLucene,Solr,ES��Щ���������ܼ�����
������ĳ��һ�£�һ�ѵķִ��������ʱ��B�ˡ����������ǿ�Ƶ�С�����ֿ�ʼ���г���Դ�ִ�����ʼ���飬
������������ʱ����Ը����ִ����������ƪ�������棬����֮�����һ�����ű���ѽ������
���ҾͰ����Լ�����F1ֵ����д�ɡ�����


1��AnsJ�ִ���
�������:https://github.com/NLPchina/ansj_seg
����ĵ���http://nlpchina.github.io/ansj_seg/
�ĵ��Ƿ�����:��
�������:
�ִ�����	            ��ʱ(�ַ�/����)	 ����(Precision)	 �ٻ���(Recall)	 Fֵ(F-mesure)	 ������(Error Rate)
nlp�ִ�-NlpAnalysis	    122.37	        92.58%	         92.90%	        92.74%	         7.44%
��׼�ִ�-ToAnalysis			257.12					92.57%					 92.93%					92.75%	         7.45%
�����ִ�-BaseAnalysis	  60.33						82.89%					 90.03%					86.31%					 18.58%
���������ķִ�						185.47					40.98%					  97.16%	      57.65%	          50.10%


2��THULAC	
�廪��ѧ����;java��c++�汾��
�������:http://nlp.csai.tsinghua.edu.cn/site2/index.php/zh/the-news/238-thulac-thutag	
�ĵ��Ƿ�����:�ĵ������ƣ�java�汾	
�������:
�ִ�����	      ��ʱ(�ַ�/����)	 ����(Precision)	 �ٻ���(Recall)	 Fֵ(F-mesure)	 ������(Error Rate)
CBTaggingD�ִ�	    33.65						86.70%					89.27%						87.97%					13.70%


3��HanLP�ִ���
�������:https://github.com/hankcs/HanLP
�ĵ��Ƿ�����:��
�������:
�ִ�����	      ��ʱ(�ַ�/����)	 ����(Precision)	 �ٻ���(Recall)	 Fֵ(F-mesure)	 ������(Error Rate)
N-���·���ִ�	    44.52	          86.81%	        84.75%	         85.77%	         12.88%
���·���ִ�	      171.02	        85.73%	        84.73%	         85.22%	         14.11%
���ٴʵ�ִ�	      1631.5	        80.80%	        86.50%	         83.55%	         20.56%
��׼�ִ�	          78.92	          87.76%	        83.13%	         85.38%	         11.60%
NLP�ִ�	          110.52	        87.86%	        82.63%	         85.17%	         11.42%
CRF�ִ�	          18.38	          88.32%	        82.53%	         85.33%	         10.91%
�����ִ�						316.77					75.38%					90.92%					 82.43%					 29.69%


4��Jcseg	
�������:https://github.com/lionsoul2014/jcseg	
�ĵ��Ƿ�����:����	
�������:
�ִ�����	   ��ʱ(�ַ�/����)	 ����(Precision)	 �ٻ���(Recall)	 Fֵ(F-mesure)	 ������(Error Rate)
����ģʽ				165.49						84.55%					83.05%					83.80%					15.18%
����ģʽ				306.76						83.23%					82.15%					82.69%					16.55%


5��Fudannlp	
�������:https://github.com/joeywen/fudannlp	
�ĵ��Ƿ�����:����	
�������:
�ִ�����	      ��ʱ(�ַ�/����)	 ����(Precision)	 �ٻ���(Recall)	 Fֵ(F-mesure)	 ������(Error Rate)
CWSTagger�ִ�  	55.93	             81.16%					85.76%						83.40%					19.91%


6��Jieba	
�������:https://github.com/yanyiwu/cppjieba;	
�ĵ��Ƿ�����:java�治����
�������:
�ִ�����	   ��ʱ(�ַ�/����)	 ����(Precision)	 �ٻ���(Recall)	 Fֵ(F-mesure)	 ������(Error Rate)
SEARCH�ִ�	    509.28						83.93%						80.56%				82.21%						15.42%
INDEX�ִ�			232.48						76.06%						87.81%				81.52%						27.63%


7��MMSeg4j 	
�������:https://github.com/chenlb/mmseg4j-solr;
https://github.com/chenlb/mmseg4j-core;
����ĵ�:http://blog.chenlb.com/category/mmseg4j	
�ĵ��Ƿ�����:Ƿȱ,��Ҫ���solr,lucene����	
�������:
�ִ�����	      ��ʱ(�ַ�/����)	 ����(Precision)	 �ٻ���(Recall)	 Fֵ(F-mesure)	 ������(Error Rate)
ComplexSeg�ִ�	    433.78						74.76%				61.81%					67.67%						20.87%
SimpleSeg�ִ�			629.21						73.85%				61.14%					66.90%						21.65%
MaxWordSeg�ִ�			372.44						68.86%				64.86%					66.80%						29.34%


8��IKAnalyzer	
�������:https://github.com/yozhao/IKAnalyzer	
�ĵ��Ƿ�����:����	
�������:
�ִ�����	      ��ʱ(�ַ�/����)	 ����(Precision)	 �ٻ���(Recall)	 Fֵ(F-mesure)	 ������(Error Rate)
ϸ�����зִַ�			29.88						74.67%					59.70%					66.35%						20.25%
�����зִַ�				57.11						59.71%					73.23%					65.78%						49.41%

���¼����ִ������������еĲ���java�汾���е����ø��ӣ��еĳ��ڲ���ά������
ϣ����ţ���ٸ��������ɡ�������
9��Paoding 	
�������:http://git.oschina.net/zhzhenqin/paoding-analysis	
�ĵ��򵥡�ά����	


10��Stanford	
�������:http://nlp.stanford.edu/software/segmenter.shtml	
�ĵ����ӣ����ø��ӡ�	


11��PanGu
������ӣ�http://pangusegment.codeplex.com/	
���ơ�C#�汾	

12��NLPIR	
������ӣ�https://github.com/NLPIR-team/NLPIR	
���ƣ�������AnsJ�ִ�	

13��LTP	������ִ���
������ӣ�https://github.com/HIT-SCIR/ltp	
�ṩ�Ʒ���C++�汾	

					
PS��		
1�����ε���������java�汾�ִ������У����������ִʶ���java�汾ʵ�֣���ܿ�������ɵ�Ӱ��			
2�����β���ʹ�ù�����Ȼ������֯��������Դ��http://www.sighan.org/bakeoff2005/			
3���ۺϸ���ָ�꿴�����ĵ������ó̶ȼ������ۺϲ��������ѡ���п�Ժ��JAVA�汾��д��ANJ�����廪��ѧ�汾��
���˽���ѡ��ANJ.	
