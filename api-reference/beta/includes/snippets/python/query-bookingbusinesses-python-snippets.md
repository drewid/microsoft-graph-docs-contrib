---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

query_params = BookingBusinessesRequestBuilder.BookingBusinessesRequestBuilderGetQueryParameters(
		query = "Adventure",
)

request_configuration = BookingBusinessesRequestBuilder.BookingBusinessesRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.booking_businesses.get(request_configuration = request_configuration)


```