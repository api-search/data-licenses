---
api_specs:
- filename: aikstockdata-data-api-openapi.yml
  format: yaml
  label: 한국주식데이터 (aikstockdata) Data API
  slug: aikstockdata-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aikstockdata/openapi/aikstockdata-data-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: 본 사이트가 공개하는 데이터(/data/public/*)는 출처를 표기하면 비영리 목적으로 인용·이용할 수 있습니다.
  data:
    license: custom
    stance_commercial: prohibited
    text: 상업적(영리) 목적의 재배포는 어떤 경우에도 허용하지 않습니다.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: 상업적(영리) 목적의 재배포는 어떤 경우에도 허용하지 않습니다.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: 한국주식데이터 (aikstockdata)
output_license: custom
provenance_date: '2026-11-09'
provider_name: 한국주식데이터 (aikstockdata)
provider_slug: aikstockdata
slug: aikstockdata-data-license
source_date: '2026-11-09'
source_filename: aikstockdata-data-license.yml
source_heading: Data License
source_page: https://aikstockdata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: 한국주식데이터 (aikstockdata)\naid: aikstockdata\nurl: https://aikstockdata.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: 상업적(영리) 목적의 재배포는 어떤 경우에도 허용하지 않습니다.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: 상업적(영리) 목적의 재배포는 어떤 경우에도 허용하지 않습니다.\nattribution:\n  required: true\n  text: 본 사이트가 공개하는 데이터(/data/public/*)는 출처를 표기하면 비영리 목적으로 인용·이용할 수 있습니다.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/aikstockdata/data-license/aikstockdata-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from 한국주식데이터 (aikstockdata)'s own page on 2026-11-09.
synthetic: false
tags:
- South Korea
- Stock Market
- Financial Data
- Open Data
- Dart
- kospi
- kosdaq
- konex
- Filings
- Stocks
- MCP
- Llms.txt
- OpenAPI
---
