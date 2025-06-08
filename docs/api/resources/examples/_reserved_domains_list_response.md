<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2yDlp7gLNsLrXe6UGC4zShBiwc6",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2yDlp7gLNsLrXe6UGC4zShBiwc6"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.4npjptqapowetfdnk.local-ngrok-cname.com",
      "created_at": "2025-06-08T10:06:44Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2yDlpCH0BLDCWqYDh5GZzucUyJm",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2yDlpCH0BLDCWqYDh5GZzucUyJm"
    },
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
          "started_at": "2025-06-08T10:06:44Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.4npjptqapowetfdnk.local-ngrok-cname.com",
      "created_at": "2025-06-08T10:06:44Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2yDlpBG1kSXLf1IVkjBUhF8rysj",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2yDlpBG1kSXLf1IVkjBUhF8rysj"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
