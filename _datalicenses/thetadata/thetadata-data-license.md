---
api_specs:
- filename: thetadata-streaming-asyncapi.yml
  format: yaml
  label: ThetaData Streaming WebSocket API
  slug: thetadata-streaming-websocket-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/thetadata/asyncapi/thetadata-streaming-asyncapi.yml
- filename: thetadata-calendar-api-openapi.yml
  format: yaml
  label: ThetaData Calendar API
  slug: thetadata-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-calendar-api-openapi.yml
- filename: thetadata-index-api-openapi.yml
  format: yaml
  label: ThetaData Index API
  slug: thetadata-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-index-api-openapi.yml
- filename: thetadata-interest-rate-api-openapi.yml
  format: yaml
  label: ThetaData Interest Rate API
  slug: thetadata-interest-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-interest-rate-api-openapi.yml
- filename: thetadata-option-api-openapi.yml
  format: yaml
  label: ThetaData Option API
  slug: thetadata-option-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-option-api-openapi.yml
- filename: thetadata-stock-api-openapi.yml
  format: yaml
  label: ThetaData Stock API
  slug: thetadata-stock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-stock-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: 'shall not: (i) archive, download, reproduce, distribute, modify, display, perform, publish, license, create derivative works of, or offer for sale the Services or any Content or information contained in or obtained from or through the Services'
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: In any case, you shall not use the Services Data in connection with any trade, business, professional or other commercial activities.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: ThetaData
output_license: custom
provenance_date: '2026-11-10'
provider_name: ThetaData
provider_slug: thetadata
slug: thetadata-data-license
source_date: '2026-11-10'
source_filename: thetadata-data-license.yml
source_heading: Data License
source_page: https://thetadata.net/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: ThetaData\naid: thetadata\nurl: https://thetadata.net/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: In any case, you shall not use the Services Data in connection with any trade, business, professional or\n    other commercial activities.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: 'shall not: (i) archive, download, reproduce, distribute, modify, display, perform, publish, license, create\n    derivative works of, or offer for sale the Services or any Content or information contained in or obtained from\n    or through\
  \ the Services'\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/thetadata/data-license/thetadata-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from ThetaData's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Market Data
- Options
- Stocks
- Indices
- Real-Time
- Historical Data
- Trading
---
