---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = Contact(
	parent_folder_id = "parentFolderId-value",
	birthday = "datetime-value",
	file_as = "fileAs-value",
	display_name = "displayName-value",
	given_name = "givenName-value",
	initials = "initials-value",
)

result = await graph_client.me.contact_folders.by_contact_folder_id('contactFolder-id').contacts.post(request_body = request_body)


```