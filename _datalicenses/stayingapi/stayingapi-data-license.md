---
api_specs:
- filename: stayingapi-account-api-openapi.yml
  format: yaml
  label: StayingAPI Account API
  slug: stayingapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stayingapi/openapi/stayingapi-account-api-openapi.yml
- filename: stayingapi-data-api-openapi.yml
  format: yaml
  label: StayingAPI Data API
  slug: stayingapi-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stayingapi/openapi/stayingapi-data-api-openapi.yml
- filename: stayingapi-jobs-api-openapi.yml
  format: yaml
  label: StayingAPI Jobs API
  slug: stayingapi-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stayingapi/openapi/stayingapi-jobs-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Every normalized record carries the source platform and a canonical source url so the original listing can be attributed and linked.
  data:
    license: null
    stance_commercial: unstated
    text: Underlying listing content, reviews and photographs remain the property of their respective owners or the source platforms; nothing here transfers ownership of that content to you.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: we grant you a limited, non-exclusive, non-transferable, revocable license to use the Service and its outputs to build and operate your own application.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: StayingAPI
output_license: custom
provenance_date: '2026-11-10'
provider_name: StayingAPI
provider_slug: stayingapi
slug: stayingapi-data-license
source_date: '2026-11-10'
source_filename: stayingapi-data-license.yml
source_heading: Data License
source_page: https://stayingapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: StayingAPI\naid: stayingapi\nurl: https://stayingapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: we grant you a limited, non-exclusive, non-transferable, revocable license to use the Service and its outputs\n    to build and operate your own application.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Underlying listing content, reviews and photographs remain the property of their respective owners or the\n    source platforms; nothing here transfers ownership of that content to you.\nattribution:\n  required: true\n  text: Every\
  \ normalized record carries the source platform and a canonical source url so the original listing can\n    be attributed and linked.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/stayingapi/data-license/stayingapi-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from StayingAPI's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Hospitality
- accommodation-data
- hotel-api
- Vacation Rentals
- Short-Term Rental
- Airbnb
- Booking.com
- Vrbo
- google-hotels
- cross-ota-price-comparison
- Availability
- Reviews
- REST
- MCP
- Agent-Native
- OpenAPI
---
