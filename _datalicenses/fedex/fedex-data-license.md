---
api_specs:
- filename: fedex-authorization-api-openapi.yml
  format: yaml
  label: FedEx API Authorization
  slug: fedex-api-authorization
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-authorization-api-openapi.yml
- filename: fedex-rate-api-openapi.yml
  format: yaml
  label: FedEx Rates and Transit Times API
  slug: fedex-rates-and-transit-times-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-rate-api-openapi.yml
- filename: fedex-ship-api-openapi.yml
  format: yaml
  label: FedEx Ship API
  slug: fedex-ship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-ship-api-openapi.yml
- filename: fedex-pickup-api-openapi.yml
  format: yaml
  label: FedEx Pickup Request API
  slug: fedex-pickup-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-pickup-api-openapi.yml
- filename: fedex-track-api-openapi.yml
  format: yaml
  label: FedEx Basic Integrated Visibility
  slug: fedex-basic-integrated-visibility
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-track-api-openapi.yml
- filename: fedex-regulatory-api-openapi.yml
  format: yaml
  label: FedEx Regulatory API
  slug: fedex-regulatory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-regulatory-api-openapi.yml
- filename: fedex-address-api-openapi.yml
  format: yaml
  label: FedEx Address API
  slug: fedex-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-address-api-openapi.yml
- filename: fedex-availability-api-openapi.yml
  format: yaml
  label: FedEx Availability API
  slug: fedex-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-availability-api-openapi.yml
- filename: fedex-commodity-api-openapi.yml
  format: yaml
  label: FedEx Commodity API
  slug: fedex-commodity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-commodity-api-openapi.yml
- filename: fedex-country-api-openapi.yml
  format: yaml
  label: FedEx Country API
  slug: fedex-country-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-country-api-openapi.yml
- filename: fedex-documents-api-openapi.yml
  format: yaml
  label: FedEx Documents API
  slug: fedex-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-documents-api-openapi.yml
- filename: fedex-dutytax-api-openapi.yml
  format: yaml
  label: FedEx Dutytax API
  slug: fedex-dutytax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-dutytax-api-openapi.yml
- filename: fedex-globaltrade-api-openapi.yml
  format: yaml
  label: FedEx Globaltrade API
  slug: fedex-globaltrade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-globaltrade-api-openapi.yml
- filename: fedex-irc-api-openapi.yml
  format: yaml
  label: FedEx Irc API
  slug: fedex-irc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-irc-api-openapi.yml
- filename: fedex-location-api-openapi.yml
  format: yaml
  label: FedEx Location API
  slug: fedex-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-location-api-openapi.yml
- filename: fedex-webhook-api-openapi.yml
  format: yaml
  label: FedEx Webhook API
  slug: fedex-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-webhook-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: fedex.com and its Content are protected by United States and international copyright, trademark and other laws.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You may use the InSight Information for Your own internal business purposes, to facilitate delivery, customs clearance, or communication with a shipment's shipper, recipient, broker, third party payer or carrier
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: FedEx
output_license: custom
provenance_date: '2026-11-09'
provider_name: FedEx
provider_slug: fedex
slug: fedex-data-license
source_date: '2026-11-09'
source_filename: fedex-data-license.yml
source_heading: Data License
source_page: https://www.fedex.com/en-us/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: FedEx\naid: fedex\nurl: https://www.fedex.com/en-us/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You may use the InSight Information for Your own internal business purposes, to facilitate delivery, customs\n    clearance, or communication with a shipment's shipper, recipient, broker, third party payer or carrier\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: fedex.com and its Content are protected by United States and international copyright, trademark and other\n    laws.\nattribution:\n  required: null\n  text: null\n\
  interface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/fedex/data-license/fedex-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from FedEx's own page on 2026-11-09.
synthetic: false
tags:
- Address Validation
- Freight
- Logistics
- Pickup
- Ratings
- Shipping
- Tracking
- Webhook
- Fortune 100
---
