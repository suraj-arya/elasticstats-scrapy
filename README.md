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

After updating these settings, add the following line in you settings.py extensions setting like this

```python

EXTENSIONS = {
    'elasticstats.ElasticStatsSender': 900
}

```

## Features

* TODO
  - update readme



* Free software: MIT license
