<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-15T17:27:06Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2zv8wmEMCvBAEZSt70bGnEVXf0R",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2zv8wmEMCvBAEZSt70bGnEVXf0R"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2zv8vPfk3PitLcbfVczbhlPKqwQ",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2zv8vPfk3PitLcbfVczbhlPKqwQ"
        },
        "enabled": true
      },
      "created_at": "2025-07-15T17:26:55Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2zv8vMlh6V6JnAbU6S8EWY7JnMG",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2zv8vMlh6V6JnAbU6S8EWY7JnMG"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
