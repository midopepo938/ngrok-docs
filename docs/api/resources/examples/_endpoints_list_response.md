<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-08T10:07:05Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2yDlr9MHRzrsA7Hl9Xhm1AugXs4",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yDlr9MHRzrsA7Hl9Xhm1AugXs4"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yDlrnOsVU5FDodpjht5ziOQWZd",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-06-08T10:07:05Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2yDlrnOsVU5FDodpjht5ziOQWZd",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-08T10:07:03Z",
      "hostport": "b9f5855aacf5.ngrok.paid:443",
      "id": "ep_2yDlrVStEdB4c4L39duXUGA58gH",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2yDlp13ZOgsVwr7UOXPmIZyYdnz",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://b9f5855aacf5.ngrok.paid",
      "tunnel": {
        "id": "tn_2yDlrVStEdB4c4L39duXUGA58gH",
        "uri": "https://api.ngrok.com/tunnels/tn_2yDlrVStEdB4c4L39duXUGA58gH"
      },
      "tunnel_session": {
        "id": "ts_2yDlrafFvgAp6VE47utN9X0tJTF",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2yDlrafFvgAp6VE47utN9X0tJTF"
      },
      "type": "ephemeral",
      "updated_at": "2025-06-08T10:07:03Z",
      "upstream_url": "http://localhost:80",
      "url": "https://b9f5855aacf5.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-08T10:07:00Z",
      "domain": {
        "id": "rd_2yDlr9MHRzrsA7Hl9Xhm1AugXs4",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yDlr9MHRzrsA7Hl9Xhm1AugXs4"
      },
      "edge": {
        "id": "edgtls_2yDlr5qSBZkix0I34tQncuNF8oD",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2yDlr5qSBZkix0I34tQncuNF8oD"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yDlrADs41bDvD8Z7WjRtP2n21b",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-06-08T10:07:00Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
