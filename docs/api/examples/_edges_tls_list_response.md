<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-28T10:06:18Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2qqBlmWosG7nuC0Ofaj7cReMmff",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qqBlmWosG7nuC0Ofaj7cReMmff"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2qqBkIv4eYDaPqNfveznWVwUxbl",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2qqBkIv4eYDaPqNfveznWVwUxbl"
				},
				"enabled": true
			},
			"created_at": "2024-12-28T10:06:06Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2qqBkIDDkwd57Q9OTJW2STfPBmc",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qqBkIDDkwd57Q9OTJW2STfPBmc"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
