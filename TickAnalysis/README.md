# 基于CTP平台FTD协议的tick数据分析

CTP是通用交易平台，FTD协议是期货交易数据交换协议，这个tick数据其实不是book order每变化一次的通知，而是1秒钟两次的快照数据，所以其实里面的分析方法得出的结果是不太准确的，该代码仅供学习

该项目是基于vnpy框架的，把文件放在如下目录即可运行

\vnpy\vn.ctp\vnctpmd\test\tickAnalysis.py

分析文章请见：
[]()