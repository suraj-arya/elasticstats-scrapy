# elasticstats-scrapy 


A scrapy extension to send crawl stats to elasticsearch index.

## how to install

```bash

$ pip install elasticstats-scrapy

```

## how to use

In order to use this extension, add following settings in settings.py

* `ELASTICSTATS_ENABLED`
* `ELASTICSEARCH_AUTH`
* `ELASTICSEARCH_SERVERS`
* `ELASTICSEARCH_USE_SSL`
* `ELASTICSEARCH_USERNAME`
* `ELASTICSEARCH_PASSWORD`

* `ELASTICSTATS_INDEX`
* `ELASTICSTATS_TYPE` 

Note: this extension by default sends custom stats you will be collecting under `custom_stats` or `ELASTICSTATS_KEY`. To send all the scrapy stats, set `ELASTICSTATS_ALL` in your settings to `True`. 


## Features

* TODO
  - update readme



* Free software: MIT license
