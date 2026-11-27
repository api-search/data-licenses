---
api_specs:
- filename: bitculator-alarms-api-openapi.yml
  format: yaml
  label: Bitculator Alarms API
  slug: bitculator-alarms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-alarms-api-openapi.yml
- filename: bitculator-calculators-api-openapi.yml
  format: yaml
  label: Bitculator Calculators API
  slug: bitculator-calculators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-calculators-api-openapi.yml
- filename: bitculator-coins-api-openapi.yml
  format: yaml
  label: Bitculator Coins API
  slug: bitculator-coins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-coins-api-openapi.yml
- filename: bitculator-conversion-api-openapi.yml
  format: yaml
  label: Bitculator Conversion API
  slug: bitculator-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-conversion-api-openapi.yml
- filename: bitculator-editorial-api-openapi.yml
  format: yaml
  label: Bitculator Editorial API
  slug: bitculator-editorial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-editorial-api-openapi.yml
- filename: bitculator-exchanges-api-openapi.yml
  format: yaml
  label: Bitculator Exchanges API
  slug: bitculator-exchanges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-exchanges-api-openapi.yml
- filename: bitculator-global-market-api-openapi.yml
  format: yaml
  label: Bitculator Global Market API
  slug: bitculator-global-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-global-market-api-openapi.yml
- filename: bitculator-indicators-api-openapi.yml
  format: yaml
  label: Bitculator Indicators API
  slug: bitculator-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-indicators-api-openapi.yml
- filename: bitculator-liquidations-api-openapi.yml
  format: yaml
  label: Bitculator Liquidations API
  slug: bitculator-liquidations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-liquidations-api-openapi.yml
- filename: bitculator-markets-api-openapi.yml
  format: yaml
  label: Bitculator Markets API
  slug: bitculator-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-markets-api-openapi.yml
- filename: bitculator-meta-api-openapi.yml
  format: yaml
  label: Bitculator Meta API
  slug: bitculator-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-meta-api-openapi.yml
- filename: bitculator-prices-api-openapi.yml
  format: yaml
  label: Bitculator Prices API
  slug: bitculator-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-prices-api-openapi.yml
- filename: bitculator-sentiment-api-openapi.yml
  format: yaml
  label: Bitculator Sentiment API
  slug: bitculator-sentiment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-sentiment-api-openapi.yml
- filename: bitculator-wallets-api-openapi.yml
  format: yaml
  label: Bitculator Wallets API
  slug: bitculator-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-wallets-api-openapi.yml
- filename: bitculator-webhooks-api-openapi.yml
  format: yaml
  label: Bitculator Webhooks API
  slug: bitculator-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Widgets must keep the "Powered by Bitculator" link visible and unaltered, and must not be cropped, restyled to hide it, or presented as your own data or as an endorsement by us.
  data:
    license: custom
    stance_commercial: prohibited
    text: 'What you may not do with what you receive: resell it, redistribute it, publish it as a dataset, mirror it in bulk, or use it to build or feed a competing market-data product.'
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: The free tier of the data API and the MCP server is for personal, non-commercial use; commercial use of those needs a paid plan.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Bitculator
output_license: custom
provenance_date: '2026-11-09'
provider_name: Bitculator
provider_slug: bitculator
slug: bitculator-data-license
source_date: '2026-11-09'
source_filename: bitculator-data-license.yml
source_heading: Data License
source_page: https://bitculator.com/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Bitculator\naid: bitculator\nurl: https://bitculator.com/en/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: The free tier of the data API and the MCP server is for personal, non-commercial use; commercial use of\n    those needs a paid plan.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: 'What you may not do with what you receive: resell it, redistribute it, publish it as a dataset, mirror\n    it in bulk, or use it to build or feed a competing market-data product.'\nattribution:\n  required: true\n  text: Widgets must keep\
  \ the \"Powered by Bitculator\" link visible and unaltered, and must not be cropped, restyled\n    to hide it, or presented as your own data or as an endorsement by us.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/bitculator/data-license/bitculator-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Bitculator's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- crypto-market-data
- Blockchain
- Finance
- Fintech
- Web3
- Trading
- Exchange Data
- Wallets
- Sentiment
- Indicators
---
