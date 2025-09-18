<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-15T17:27:00Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2zv8vINmADThXQswnRRUAv6vEu2",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2zv8vINmADThXQswnRRUAv6vEu2"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2zv8w0IJ7OvnJ5CZv2WvLt9VyTn",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-15T17:27:00Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2zv8w0IJ7OvnJ5CZv2WvLt9VyTn",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-15T17:26:58Z",
      "hostport": "f49403589cba.ngrok.paid:443",
      "id": "ep_2zv8vkAp44vyLdmgUpRlS9wzl1i",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2zv8pW7jpicXNRYZ002vKHKKCOZ",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://f49403589cba.ngrok.paid",
      "tunnel": {
        "id": "tn_2zv8vkAp44vyLdmgUpRlS9wzl1i",
        "uri": "https://api.ngrok.com/tunnels/tn_2zv8vkAp44vyLdmgUpRlS9wzl1i"
      },
      "tunnel_session": {
        "id": "ts_2zv8vijHluz8uWYkh8CxhJzYNi8",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2zv8vijHluz8uWYkh8CxhJzYNi8"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-15T17:26:58Z",
      "upstream_url": "http://localhost:80",
      "url": "https://f49403589cba.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-15T17:26:55Z",
      "domain": {
        "id": "rd_2zv8vINmADThXQswnRRUAv6vEu2",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2zv8vINmADThXQswnRRUAv6vEu2"
      },
      "edge": {
        "id": "edgtls_2zv8vMlh6V6JnAbU6S8EWY7JnMG",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2zv8vMlh6V6JnAbU6S8EWY7JnMG"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2zv8vMRcOHGecbkFyr1L44wS2uZ",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-15T17:26:55Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
