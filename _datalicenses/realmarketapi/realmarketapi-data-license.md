---
api_specs:
- filename: realmarketapi-market-data-api-openapi.yml
  format: yaml
  label: RealMarketAPI Market Data API
  slug: realmarketapi-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/realmarketapi/openapi/realmarketapi-market-data-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Market data is provided on an "as is" and "as available" basis sourced from professional broker feeds.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: null
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: RealMarketAPI
output_license: null
provenance_date: '2026-11-10'
provider_name: RealMarketAPI
provider_slug: realmarketapi
slug: realmarketapi-data-license
source_date: '2026-11-10'
source_filename: realmarketapi-data-license.yml
source_heading: Data License
source_page: https://realmarketapi.com/en-US/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: RealMarketAPI\naid: realmarketapi\nurl: https://realmarketapi.com/en-US/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Market data is provided on an \"as is\" and \"as available\" basis sourced from professional broker feeds.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/realmarketapi/data-license/realmarketapi-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from RealMarketAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Market Data
- Real-Time
---
