# data-512-a1

The goal of this project was to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2021. This assignment was the data curation stage and involves the collection and preprocessing of the data from various sources.

Source data license: 

Link to the Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

Link to all relevant API documentation:

Legacy pagecounts: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts

Pageviews: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews


Values in final data file:
-year: year of page view count
- month: month of page view count
- pagecount_all_views: number of views in timeframe from pagecount source
- pagecount_desktop_views: number of desktop views in timeframe from pagecount source
- pagecount_mobile_views: number of mobile views in timeframe from pagecount source
pageview_all_views: number of views in timeframe from pageview source
pageview_desktop_views: number of desktop views in timeframe from pageview source
pageview_mobile_views: number of mobile views in timeframe from pageview source


Data from the Pageview API excludes spiders/crawlers, while data from the Pagecounts API does not.
