---
api_specs:
- filename: qfex-mds-asyncapi.yml
  format: yaml
  label: QFEX Market Data WebSocket (MDS)
  slug: qfex-market-data-websocket-mds
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/qfex/asyncapi/qfex-mds-asyncapi.yml
- filename: qfex-trade-asyncapi.yml
  format: yaml
  label: QFEX Trade WebSocket
  slug: qfex-trade-websocket
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/qfex/asyncapi/qfex-trade-asyncapi.yml
- filename: qfex-market-data-api-openapi.yml
  format: yaml
  label: Qfex Market Data API
  slug: qfex-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qfex/openapi/qfex-market-data-api-openapi.yml
- filename: qfex-pnl-api-openapi.yml
  format: yaml
  label: Qfex Pnl API
  slug: qfex-pnl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qfex/openapi/qfex-pnl-api-openapi.yml
- filename: qfex-user-api-openapi.yml
  format: yaml
  label: Qfex User API
  slug: qfex-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qfex/openapi/qfex-user-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: 'You must not reproduce, distribute, modify, create derivative works of, publicly display, publicly perform, republish, download, store, or transmit any of the material on our Services, except as follows:'
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
name: Qfex
output_license: null
provenance_date: '2026-11-10'
provider_name: Qfex
provider_slug: qfex
slug: qfex-data-license
source_date: '2026-11-10'
source_filename: qfex-data-license.yml
source_heading: Data License
source_page: https://docs.qfex.com/legal/client-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Qfex\naid: qfex\nurl: https://docs.qfex.com/legal/client-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: 'You must not reproduce, distribute, modify, create derivative works of, publicly display, publicly perform,\n    republish, download, store, or transmit any of the material on our Services, except as follows:'\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/qfex/data-license/qfex-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Qfex's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Trading
- Exchange
- Perpetual Futures
- Market Data
- WebSocket
- Foreign Exchange
- Commodities
- Stocks
- Financial Services
- CLI
- Fintech
- Real-Time
---
