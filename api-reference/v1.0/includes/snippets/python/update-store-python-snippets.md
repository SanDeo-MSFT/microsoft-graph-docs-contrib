---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = Store(
	default_language_tag = "en-US",
)

result = await graph_client.sites.by_site_id('site-id').term_store.patch(request_body = request_body)


```