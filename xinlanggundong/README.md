# 这个是新浪滚动新闻爬取的scrapy 爬虫测试
2019-05-01  
已经可以准确的爬取前一天的所有新闻了（设置成这样，方便第二天1点把昨天的所有新闻爬下来），这个是增量爬虫



# todo
待做到事情。
+ 设置UA  (👌)
+ 代理 (👌)类似ua  
+ 设置请求延迟 (👌)  
    + settings 中 DOWNLOAD_DELAY  
+ 可以把爬取下前一天的所有新闻的文字版本了  
    + 大部分可以爬下来的属于同一种的页面布局  (👌)
    + 发现了另一种布局，数量不算多，可增加解析或者丢弃 
+ 重写请求，使用 selenuim + chrome 无头模式组合来使用做动态爬取
+ 提取下一页后继续爬取
+ 下载媒体的图片
+ 链接把数据写入mongdb
