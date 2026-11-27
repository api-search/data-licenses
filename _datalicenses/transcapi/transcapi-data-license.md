---
api_specs:
- filename: transcapi-airports-api-openapi.yml
  format: yaml
  label: TransCAPI Airports API
  slug: transcapi-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-airports-api-openapi.yml
- filename: transcapi-alerts-api-openapi.yml
  format: yaml
  label: TransCAPI Alerts API
  slug: transcapi-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-alerts-api-openapi.yml
- filename: transcapi-bus-api-openapi.yml
  format: yaml
  label: TransCAPI Bus API
  slug: transcapi-bus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-bus-api-openapi.yml
- filename: transcapi-disruptions-api-openapi.yml
  format: yaml
  label: TransCAPI Disruptions API
  slug: transcapi-disruptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-disruptions-api-openapi.yml
- filename: transcapi-journey-api-openapi.yml
  format: yaml
  label: TransCAPI Journey API
  slug: transcapi-journey-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-journey-api-openapi.yml
- filename: transcapi-places-api-openapi.yml
  format: yaml
  label: TransCAPI Places API
  slug: transcapi-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-places-api-openapi.yml
- filename: transcapi-rail-api-openapi.yml
  format: yaml
  label: TransCAPI Rail API
  slug: transcapi-rail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-rail-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: if you show the data to others, you must display the attribution described there
  data:
    license: custom
    stance_commercial: conditional
    text: TransCAPI's data comes from official open data, under the licences listed on our Data sources & attribution page.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: building your own product on top of the data is fine
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: TransCAPI
output_license: custom
provenance_date: '2026-11-10'
provider_name: TransCAPI
provider_slug: transcapi
slug: transcapi-data-license
source_date: '2026-11-10'
source_filename: transcapi-data-license.yml
source_heading: Data License
source_page: https://www.transcapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: TransCAPI\naid: transcapi\nurl: https://www.transcapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: building your own product on top of the data is fine\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: TransCAPI's data comes from official open data, under the licences listed on our Data sources & attribution\n    page.\nattribution:\n  required: true\n  text: if you show the data to others, you must display the attribution described there\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/transcapi/data-license/transcapi-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from TransCAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Transport
- United Kingdom
- Ireland
---
