<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"bindings": ["public"],
	"created_at": "2025-01-22T10:07:27Z",
	"description": "sample cloud endpoint",
	"domain": {
		"id": "rd_2rynzDPiOz4VYEiRPiEoXVSPtiD",
		"uri": "https://api.ngrok.com/reserved_domains/rd_2rynzDPiOz4VYEiRPiEoXVSPtiD"
	},
	"hostport": "endpoint-example2.com:443",
	"id": "ep_2rynzooucO3mxmy1vN22X945DRU",
	"metadata": "{\"environment\": \"staging\"}",
	"pooling_enabled": false,
	"proto": "https",
	"public_url": "https://endpoint-example2.com",
	"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
	"type": "cloud",
	"updated_at": "2025-01-22T10:07:27Z",
	"uri": "https://api.ngrok.com/endpoints/ep_2rynzooucO3mxmy1vN22X945DRU",
	"url": "https://endpoint-example2.com"
}
```
