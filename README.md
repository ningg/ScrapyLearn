# ScrapyLearn
学习 Scrapy 的 demo

## 例子说明

### 简单 demo

几个零散的 demo

#### Scrapinghub blog 文章爬取

执行命令:

```
scrapy runspider ./top/ningg/scrapy/scrapinghub_spider.py
```

#### quotes 爬取

执行命令:

```
scrapy runspider ./top/ningg/scrapy/quotes_spider.py

# 指定输出文件
scrapy runspider ./top/ningg/scrapy/quotes_spider.py -o quotes.json
```

### 完整 scrapy 工程

完整的 scrapy 工程.

创建工程, 执行命令:

```
# 当前目录,创建 tutorial 目录, 并增加 scrapy 工程模板
scrapy startproject tutorial
```

启动工程, 执行命令:

```
cd tutorial/output

scrapy crawl quotes
```

## 参考资料

* [Scrapy documentation](https://docs.scrapy.org/en/latest/)
* [Scrapy Tutorial](https://docs.scrapy.org/en/latest/intro/tutorial.html)


