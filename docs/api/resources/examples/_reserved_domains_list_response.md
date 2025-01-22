<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-01-22T10:07:07Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.2ebbm53nu5ebcbpx.local-ngrok-cname.com",
			"created_at": "2025-01-22T10:07:07Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2rynxKnXtLgp66KCJZjGEjYZKLa",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2rynxKnXtLgp66KCJZjGEjYZKLa"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2rynxBJBq2HBn7Gn6boSIuMrcYs",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2rynxBJBq2HBn7Gn6boSIuMrcYs"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.2ebbm53nu5ebcbpx.local-ngrok-cname.com",
			"created_at": "2025-01-22T10:07:06Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2rynxDxlvnhm8QosYb1QqfQGNHB",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2rynxDxlvnhm8QosYb1QqfQGNHB"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
