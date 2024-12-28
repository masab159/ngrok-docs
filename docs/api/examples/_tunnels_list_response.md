<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tunnels": [
		{
			"endpoint": {
				"id": "ep_2qqBjTyaOL5vKC2JRQ44FXS08rN",
				"uri": "https://api.ngrok.com/endpoints/ep_2qqBjTyaOL5vKC2JRQ44FXS08rN"
			},
			"forwards_to": "http://localhost:80",
			"id": "tn_2qqBjTyaOL5vKC2JRQ44FXS08rN",
			"proto": "https",
			"public_url": "https://03f8c3ac7dbd.ngrok.paid",
			"region": "us",
			"started_at": "2024-12-28T10:05:59Z",
			"tunnel_session": {
				"id": "ts_2qqBjQ8vgUcab36nlIHoUkWVkBE",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qqBjQ8vgUcab36nlIHoUkWVkBE"
			}
		},
		{
			"forwards_to": "http://localhost:80",
			"id": "tn_2qqBiw1Bub1ZwSPbjz3ZRReo4zs",
			"labels": {
				"baz": "qux",
				"foo": "bar"
			},
			"region": "us",
			"started_at": "2024-12-28T10:05:55Z",
			"tunnel_session": {
				"id": "ts_2qqBiuw8WP8vAgN47wtM62w5C2B",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qqBiuw8WP8vAgN47wtM62w5C2B"
			}
		}
	],
	"uri": "https://api.ngrok.com/tunnels"
}
```
