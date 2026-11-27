---
api_specs:
- filename: siftingio-asyncapi.yaml
  format: yaml
  label: SiftingIO Live Stream
  slug: siftingio-live-stream
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/siftingio/asyncapi/siftingio-asyncapi.yaml
- filename: siftingio-commodities-api-openapi.yml
  format: yaml
  label: SiftingIO Commodities API
  slug: siftingio-commodities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-commodities-api-openapi.yml
- filename: siftingio-convert-api-openapi.yml
  format: yaml
  label: SiftingIO Convert API
  slug: siftingio-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-convert-api-openapi.yml
- filename: siftingio-crypto-api-openapi.yml
  format: yaml
  label: SiftingIO Crypto API
  slug: siftingio-crypto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-crypto-api-openapi.yml
- filename: siftingio-dex-api-openapi.yml
  format: yaml
  label: SiftingIO DEX API
  slug: siftingio-dex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-dex-api-openapi.yml
- filename: siftingio-filers-api-openapi.yml
  format: yaml
  label: SiftingIO Filers API
  slug: siftingio-filers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-filers-api-openapi.yml
- filename: siftingio-forex-api-openapi.yml
  format: yaml
  label: SiftingIO Forex API
  slug: siftingio-forex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-forex-api-openapi.yml
- filename: siftingio-live-api-openapi.yml
  format: yaml
  label: SiftingIO Live API
  slug: siftingio-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-live-api-openapi.yml
- filename: siftingio-markets-api-openapi.yml
  format: yaml
  label: SiftingIO Markets API
  slug: siftingio-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-markets-api-openapi.yml
- filename: siftingio-signals-api-openapi.yml
  format: yaml
  label: SiftingIO Signals API
  slug: siftingio-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-signals-api-openapi.yml
- filename: siftingio-stocks-api-openapi.yml
  format: yaml
  label: SiftingIO Stocks API
  slug: siftingio-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-stocks-api-openapi.yml
- filename: siftingio-economic-calendar-api-openapi.yml
  format: yaml
  label: SiftingIO Economic Calendar API
  slug: siftingio-economic-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-economic-calendar-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: remove, alter, or obscure any attribution, source identifier, or disclaimer that the Service or the Agreement requires you to display.
  data:
    license: custom
    stance_commercial: conditional
    text: Any rights not expressly granted are reserved by SaltingIO and its Data Sources.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: to access the Service and to use the data delivered through it (the “Data”) solely for your internal business purposes and within the scope of your active plan tier.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SiftingIO
output_license: custom
provenance_date: '2026-11-10'
provider_name: SiftingIO
provider_slug: siftingio
slug: siftingio-data-license
source_date: '2026-11-10'
source_filename: siftingio-data-license.yml
source_heading: Data License
source_page: https://sifting.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SiftingIO\naid: siftingio\nurl: https://sifting.io/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://github.com/SiftingIO/siftingio-mcp/blob/main/LICENSE\n  - https://sifting.io/legal/terms-of-use\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: to access the Service and to use the data delivered through it (the “Data”) solely for your internal business\n    purposes and within the scope of your active plan tier.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Any rights not expressly granted are reserved by SaltingIO and its Data Sources.\nattribution:\n\
  \  required: true\n  text: remove, alter, or obscure any attribution, source identifier, or disclaimer that the Service or the Agreement\n    requires you to display.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/siftingio/data-license/siftingio-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from SiftingIO's own page on 2026-11-10.
synthetic: false
tags:
- Financial market data
- Stocks/equities
- Foreign Exchange
- Cryptocurrency
- DeFi/on-chain
- Commodities
- SEC Filings
- XBRL
- Fundamentals
- Fintech
- Quant/trading infrastructure
- Real-Time Streaming
- WebSocket
- FIX
- Financial Data
- Market Data
- Stocks
- DeFi
- Real-Time
- REST API
- MCP Server
- Agent-Native
---
