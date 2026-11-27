---
api_specs:
- filename: carstat-app-recalls-api-openapi.yml
  format: yaml
  label: carstat-app Recalls API
  slug: carstat-app-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carstat-app/openapi/carstat-app-recalls-api-openapi.yml
- filename: carstat-app-safety-ratings-api-openapi.yml
  format: yaml
  label: carstat-app Safety Ratings API
  slug: carstat-app-safety-ratings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carstat-app/openapi/carstat-app-safety-ratings-api-openapi.yml
- filename: carstat-app-vehicle-specifications-api-openapi.yml
  format: yaml
  label: carstat-app Vehicle Specifications API
  slug: carstat-app-vehicle-specifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carstat-app/openapi/carstat-app-vehicle-specifications-api-openapi.yml
- filename: carstat-app-vin-decoding-api-openapi.yml
  format: yaml
  label: carstat-app VIN Decoding API
  slug: carstat-app-vin-decoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carstat-app/openapi/carstat-app-vin-decoding-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: must appear within the same page module as the displayed data, legible without requiring user interaction to reveal it, and linked to carstat.app.
  data:
    license: custom
    stance_commercial: conditional
    text: You are granted a non-exclusive, non-transferable, revocable, and limited license to use the data.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Using the Carstat API to power a publicly accessible vehicle lookup tool, decoder, or report product offered to the general public requires a separate written commercial licence.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: carstat-app
output_license: custom
provenance_date: '2026-11-09'
provider_name: carstat-app
provider_slug: carstat-app
slug: carstat-app-data-license
source_date: '2026-11-09'
source_filename: carstat-app-data-license.yml
source_heading: Data License
source_page: https://carstat.app/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: carstat-app\naid: carstat-app\nurl: https://carstat.app/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Using the Carstat API to power a publicly accessible vehicle lookup tool, decoder, or report product offered\n    to the general public requires a separate written commercial licence.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: You are granted a non-exclusive, non-transferable, revocable, and limited license to use the data.\nattribution:\n  required: true\n  text: must appear within the same page module as the displayed\
  \ data, legible without requiring user interaction\n    to reveal it, and linked to carstat.app.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/carstat-app/data-license/carstat-app-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from carstat-app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Data
- Vehicles
---
