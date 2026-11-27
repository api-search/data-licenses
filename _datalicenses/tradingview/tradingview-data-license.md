---
api_specs:
- filename: tradingview-account-api-openapi.yml
  format: yaml
  label: TradingView Account API
  slug: tradingview-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-account-api-openapi.yml
- filename: tradingview-authorization-api-openapi.yml
  format: yaml
  label: TradingView Authorization API
  slug: tradingview-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-authorization-api-openapi.yml
- filename: tradingview-broker-configuration-api-openapi.yml
  format: yaml
  label: TradingView Broker Configuration API
  slug: tradingview-broker-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-broker-configuration-api-openapi.yml
- filename: tradingview-data-integration-api-openapi.yml
  format: yaml
  label: TradingView Data Integration API
  slug: tradingview-data-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-data-integration-api-openapi.yml
- filename: tradingview-data-permissions-api-openapi.yml
  format: yaml
  label: TradingView Data Permissions API
  slug: tradingview-data-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-data-permissions-api-openapi.yml
- filename: tradingview-market-data-api-openapi.yml
  format: yaml
  label: TradingView Market Data API
  slug: tradingview-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-market-data-api-openapi.yml
- filename: tradingview-trading-api-openapi.yml
  format: yaml
  label: TradingView Trading API
  slug: tradingview-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-trading-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: on the condition that TradingView attribution is clearly visible at all times when such charts and products are used.
  data:
    license: custom
    stance_commercial: prohibited
    text: Except as otherwise expressly permitted, our agreements with Data Providers strictly forbid the sublicensing, assigning, transferring, selling, loaning, or any distribution of TradingView content, including market data, for any form of compensation.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: The display-only license and the non-display restrictions in this Section 3 apply in full to the MCP Server and to any AI Client connected to it, subject only to the limited personal exception in Section 27.4.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: TradingView
output_license: custom
provenance_date: '2026-11-10'
provider_name: TradingView
provider_slug: tradingview
slug: tradingview-data-license
source_date: '2026-11-10'
source_filename: tradingview-data-license.yml
source_heading: Data License
source_page: https://www.tradingview.com/policies/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: TradingView\naid: tradingview\nurl: https://www.tradingview.com/policies/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://github.com/tradingview/lightweight-charts/blob/master/LICENSE\n  - https://www.tradingview.com/policies/\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: The display-only license and the non-display restrictions in this Section 3 apply in full to the MCP Server\n    and to any AI Client connected to it, subject only to the limited personal exception in Section 27.4.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Except as otherwise\
  \ expressly permitted, our agreements with Data Providers strictly forbid the sublicensing,\n    assigning, transferring, selling, loaning, or any distribution of TradingView content, including market data,\n    for any form of compensation.\nattribution:\n  required: true\n  text: on the condition that TradingView attribution is clearly visible at all times when such charts and products\n    are used.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tradingview/data-license/tradingview-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from TradingView's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Charts
- Charting Library
- Financial Data
- Market Data
- Widgets
- Trading
- Fintech
- Embeddable Components
---
