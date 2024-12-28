<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-28T10:06:09Z",
			"hostport": "35477e56ec14.ngrok.paid:443",
			"id": "ep_2qqBkkNTcOWWEG85wMFu1pMUucD",
			"name": "command_line",
			"principal": {
				"id": "usr_2qqBiFxlCOXt9kLGGVLOLQc1R9r",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://35477e56ec14.ngrok.paid",
			"tunnel": {
				"id": "tn_2qqBkkNTcOWWEG85wMFu1pMUucD",
				"uri": "https://api.ngrok.com/tunnels/tn_2qqBkkNTcOWWEG85wMFu1pMUucD"
			},
			"tunnel_session": {
				"id": "ts_2qqBkk27HLlTcEn5gpWRq9WDO5l",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qqBkk27HLlTcEn5gpWRq9WDO5l"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-28T10:06:09Z",
			"upstream_url": "http://localhost:80",
			"url": "https://35477e56ec14.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-28T10:06:07Z",
			"domain": {
				"id": "rd_2qqBkIFmHMZXu2QgW64XgidYH1m",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2qqBkIFmHMZXu2QgW64XgidYH1m"
			},
			"edge": {
				"id": "edgtls_2qqBkIDDkwd57Q9OTJW2STfPBmc",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2qqBkIDDkwd57Q9OTJW2STfPBmc"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2qqBkHAVCX8SVxakTPvz3nUELxV",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-28T10:06:07Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
