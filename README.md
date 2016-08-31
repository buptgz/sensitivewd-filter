# sensitivewd-filter
具体通过实现DFA算法实现对敏感词、广告词的过滤功能：
 1、匹配大小写过滤
 2、匹配全角半角过滤
 3、匹配过滤停顿词过滤。
 
其中resources资源目录中：
stopwd.txt ：停顿词，匹配时间直接过滤。
wd.txt：敏感词库。


WordFilter为敏感词过滤类，有如下方法：

isContains() ：是否包含敏感词
doFilter()：过滤敏感词

测试结果：

解析文字：法@@!轮!　　功
解析字数 : 9
加载时间 : 12953998ns
加载时间 : 12ms 
解析时间 : 15584375ns 
解析时间 : 15ms 
*********


是否包含敏感词： true 
解析时间 : 92783ns 
解析时间 : 0ms 

博文地址：http://blog.csdn.net/fengshizty/article/details/52373005
