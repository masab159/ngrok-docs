<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-12-28T10:06:14Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2qqBlOGyeVp9PImclxZACEMUDx4",
					"uri": "https://api.ngrok.com/event_destinations/ed_2qqBlOGyeVp9PImclxZACEMUDx4"
				}
			],
			"id": "esb_2qqBlLYSEcRi7vqKhIM5dhs7svl",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2qqBlLYSEcRi7vqKhIM5dhs7svl/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2qqBlLYSEcRi7vqKhIM5dhs7svl"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
