<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-06-08T10:07:10Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2yDlsRaVlZGwhnpXlsELd5QvvDy",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yDlsRaVlZGwhnpXlsELd5QvvDy"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2yDlr5li9RAWcaxMA683T4SJU0t",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2yDlr5li9RAWcaxMA683T4SJU0t"
        },
        "enabled": true
      },
      "created_at": "2025-06-08T10:07:00Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2yDlr5qSBZkix0I34tQncuNF8oD",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yDlr5qSBZkix0I34tQncuNF8oD"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
