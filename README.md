# sinaFinanceSpider
# 爬取新浪财经网http://finance.sina.com.cn/stock/
# 各股票公司每日公告（爬取股票分析所需语料）
ps.需要requests、lxml、threading、datetime等py模块
  运行：python  crawlCompanyAnnouncement.py     
  其实日期和结束日期可以在main方法中修改，[begin,end]  首尾都包括，若结束日期大于当前日期，取当前日期为结束日期。
