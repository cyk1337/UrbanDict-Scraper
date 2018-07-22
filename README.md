Scraping Urban Dict through website and API
-------------

We only crawled the word entry whose token number < 2, i.e. single token. If you need to scrape the whole word entries including phrase entries, please remove the filter restriction in the file `UD_spider/spiders/<spider_name.py>`.

* Scraping data from webpage: http://urbandictionary.com/
```diff
+ scrapy crawl UD
```

* Scrapying data via API:
```diff
+ scrapy crawl UD_API
```
