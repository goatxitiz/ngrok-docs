<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
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
		},
		{
			"bindings": ["public"],
			"created_at": "2025-01-22T10:07:26Z",
			"hostport": "dfc0febeef05.ngrok.paid:443",
			"id": "ep_2rynzlldNGDrEaSDlJ5RTdHPQXS",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2rynxDNYTCzMTYCYucBalrNchTp",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://dfc0febeef05.ngrok.paid",
			"tunnel": {
				"id": "tn_2rynzlldNGDrEaSDlJ5RTdHPQXS",
				"uri": "https://api.ngrok.com/tunnels/tn_2rynzlldNGDrEaSDlJ5RTdHPQXS"
			},
			"tunnel_session": {
				"id": "ts_2rynzmlC0VCdGFbeCNEYTDE1gAh",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2rynzmlC0VCdGFbeCNEYTDE1gAh"
			},
			"type": "ephemeral",
			"updated_at": "2025-01-22T10:07:26Z",
			"upstream_url": "http://localhost:80",
			"url": "https://dfc0febeef05.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-01-22T10:07:23Z",
			"domain": {
				"id": "rd_2rynzDPiOz4VYEiRPiEoXVSPtiD",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2rynzDPiOz4VYEiRPiEoXVSPtiD"
			},
			"edge": {
				"id": "edgtls_2rynzIekL8cVWxy9IfNhpWTrriy",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2rynzIekL8cVWxy9IfNhpWTrriy"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2rynzEhCjJ9xbDkVJqhoGQQl2dz",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-01-22T10:07:23Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
