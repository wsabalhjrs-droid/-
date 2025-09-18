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
          "started_at": "2025-07-15T17:26:39Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.54wjyeeiaa5hviebw.local-ngrok-cname.com",
      "created_at": "2025-07-15T17:26:39Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2zv8tN4quOlyVW4R2uojOyHQ2ed",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2zv8tN4quOlyVW4R2uojOyHQ2ed"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2zv8tMBpxMRxebfR6wBGgjXmUhn",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2zv8tMBpxMRxebfR6wBGgjXmUhn"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.54wjyeeiaa5hviebw.local-ngrok-cname.com",
      "created_at": "2025-07-15T17:26:39Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2zv8tLeqt9Cp3ATwZefRt4hfEhW",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2zv8tLeqt9Cp3ATwZefRt4hfEhW"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-07-15T17:26:09Z",
      "description": "Your dev domain",
      "domain": "fresh-firstly-pony.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2zv8pYyxyNMLJ2rMu9fhIartAxJ",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2zv8pYyxyNMLJ2rMu9fhIartAxJ"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
