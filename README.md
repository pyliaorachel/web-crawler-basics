## Libraries

* [Scrapy](https://scrapy.org/)

## Usage

- Twitter Follower Crawler: crawling your Twitter followers' followers' followers'...followers
	1. `pip install scrapy`
	2. Create `config.py` under the same directory as `twitter-spider.py` with your twitter account info:
		```
		TWITTER_USERNAME = 'your-username'
		TWITTER_PASSWORD = 'your-password'
		```
	3. Run `scrapy runspider twitter-spider.py`
	4. You may change the `level` variable in `twitter-spider.py` to crawl more levels of followers


