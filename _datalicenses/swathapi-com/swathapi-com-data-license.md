---
api_specs:
- filename: swathapi-com-billing-api-openapi.yml
  format: yaml
  label: swathapi-com Billing API
  slug: swathapi-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-billing-api-openapi.yml
- filename: swathapi-com-monitors-api-openapi.yml
  format: yaml
  label: swathapi-com Monitors API
  slug: swathapi-com-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-monitors-api-openapi.yml
- filename: swathapi-com-property-api-openapi.yml
  format: yaml
  label: swathapi-com Property API
  slug: swathapi-com-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-property-api-openapi.yml
- filename: swathapi-com-signup-api-openapi.yml
  format: yaml
  label: swathapi-com Signup API
  slug: swathapi-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-signup-api-openapi.yml
- filename: swathapi-com-storms-api-openapi.yml
  format: yaml
  label: swathapi-com Storms API
  slug: swathapi-com-storms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-storms-api-openapi.yml
- filename: swathapi-com-swaths-api-openapi.yml
  format: yaml
  label: swathapi-com Swaths API
  slug: swathapi-com-swaths-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-swaths-api-openapi.yml
- filename: swathapi-com-usage-api-openapi.yml
  format: yaml
  label: swathapi-com Usage API
  slug: swathapi-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swathapi-com/openapi/swathapi-com-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Storm detection outputs derived from NOAA MRMS (event timing, severity, swath geometry) may be displayed publicly with attribution to Swath.
  data:
    license: custom
    stance_commercial: conditional
    text: You may not resell, redistribute, or sublicense raw parcel or property records obtained from the Service as a standalone dataset, or use them to build or seed a competing property-data product.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You receive a non-exclusive, non-transferable license to use data returned by the Service inside your own applications and workflows, including white-label products where the data is materially transformed or combined with your own.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: swathapi-com
output_license: custom
provenance_date: '2026-11-10'
provider_name: swathapi-com
provider_slug: swathapi-com
slug: swathapi-com-data-license
source_date: '2026-11-10'
source_filename: swathapi-com-data-license.yml
source_heading: Data License
source_page: https://swathapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: swathapi-com\naid: swathapi-com\nurl: https://swathapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You receive a non-exclusive, non-transferable license to use data returned by the Service inside your own\n    applications and workflows, including white-label products where the data is materially transformed or combined\n    with your own.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: You may not resell, redistribute, or sublicense raw parcel or property records obtained from the Service\n    as a standalone dataset, or use\
  \ them to build or seed a competing property-data product.\nattribution:\n  required: true\n  text: Storm detection outputs derived from NOAA MRMS (event timing, severity, swath geometry) may be displayed\n    publicly with attribution to Swath.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/swathapi-com/data-license/swathapi-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from swathapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Weather
- Storm
- Artificial Intelligence
- NOAA
---
