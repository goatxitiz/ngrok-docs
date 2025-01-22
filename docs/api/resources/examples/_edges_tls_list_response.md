<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-01-22T10:07:33Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2ryo0fbDSaZViWHk5q4dfWPqUnt",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2ryo0fbDSaZViWHk5q4dfWPqUnt"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2rynzDL2twrlL7jaOUOUKbDRud7",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2rynzDL2twrlL7jaOUOUKbDRud7"
				},
				"enabled": true
			},
			"created_at": "2025-01-22T10:07:22Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2rynzIekL8cVWxy9IfNhpWTrriy",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2rynzIekL8cVWxy9IfNhpWTrriy"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
