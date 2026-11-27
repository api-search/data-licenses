---
api_specs:
- filename: finnhub-default-api-openapi.yml
  format: yaml
  label: Finnhub Default API
  slug: finnhub-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finnhub/openapi/finnhub-default-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: All data must be deleted should your subscription to that data ends.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: All plan listed on Finnhub website is strictly for personal use unless explicitly stated otherwise.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Finnhub
output_license: null
provenance_date: '2026-11-09'
provider_name: Finnhub
provider_slug: finnhub
slug: finnhub-data-license
source_date: '2026-11-09'
source_filename: finnhub-data-license.yml
source_heading: Data License
source_page: https://finnhub.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Finnhub\naid: finnhub\nurl: https://finnhub.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: All plan listed on Finnhub website is strictly for personal use unless explicitly stated otherwise.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: All data must be deleted should your subscription to that data ends.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/finnhub/data-license/finnhub-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Finnhub's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Stocks
- Foreign Exchange
- Cryptocurrency
- Fundamentals
- News
- WebSocket
- Real-Time
- Financial Data
---
