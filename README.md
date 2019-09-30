### elasticsearch-dsl-py
---
https://github.com/elastic/elasticsearch-dsl-py

```py
// test_elasticsearch_dsl/test_result.py

@fixture
def agg_response(aggs_search, aggs_data):
  return response.Respnse(aggs_search, aggs_data)

def test_agg_response_is_pickleable(agg_response):

def test_response_is_pickleable(dummy_response):

def test_hit_is_pickleable(dummy_response):




```

```
```

```
```
