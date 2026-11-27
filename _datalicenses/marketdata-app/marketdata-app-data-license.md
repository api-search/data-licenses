---
api_specs:
- filename: marketdata-app-indices-api-openapi.yml
  format: yaml
  label: Market Data Indices API
  slug: marketdata-app-indices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketdata-app/openapi/marketdata-app-indices-api-openapi.yml
- filename: marketdata-app-markets-api-openapi.yml
  format: yaml
  label: Market Data Markets API
  slug: marketdata-app-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketdata-app/openapi/marketdata-app-markets-api-openapi.yml
- filename: marketdata-app-options-api-openapi.yml
  format: yaml
  label: Market Data Options API
  slug: marketdata-app-options-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketdata-app/openapi/marketdata-app-options-api-openapi.yml
- filename: marketdata-app-stocks-api-openapi.yml
  format: yaml
  label: Market Data Stocks API
  slug: marketdata-app-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketdata-app/openapi/marketdata-app-stocks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Market Data grants you a limited, non-exclusive, non-transferrable, non-sublicensable license to access and use our data on an unlimited number of computers and mobile devices that you own or control for your own personal non-professional use.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: You may not sell, resell, retransmit, or redistribute or make our data or any third-party data available to anyone.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Market Data
output_license: custom
provenance_date: '2026-11-10'
provider_name: Market Data
provider_slug: marketdata-app
slug: marketdata-app-data-license
source_date: '2026-11-10'
source_filename: marketdata-app-data-license.yml
source_heading: Data License
source_page: https://www.marketdata.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Market Data\naid: marketdata-app\nurl: https://www.marketdata.app/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: You may not sell, resell, retransmit, or redistribute or make our data or any third-party data available\n    to anyone.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Market Data grants you a limited, non-exclusive, non-transferrable, non-sublicensable license to access\n    and use our data on an unlimited number of computers and mobile devices that you own or control for your own\n    personal non-professional use.\n\
  attribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/marketdata-app/data-license/marketdata-app-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Market Data's own page on 2026-11-10.
synthetic: false
tags:
- Market Data
- Financial Data
- Stocks
- Options
- Indices
- Real-Time Data
- Historical Data
- Quotes
---
