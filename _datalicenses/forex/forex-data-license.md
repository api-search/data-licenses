---
api_specs:
- filename: forex-account-api-openapi.yml
  format: yaml
  label: Forex Account API
  slug: forex-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forex/openapi/forex-account-api-openapi.yml
- filename: forex-rates-api-openapi.yml
  format: yaml
  label: Forex Rates API
  slug: forex-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forex/openapi/forex-rates-api-openapi.yml
- filename: forex-reference-api-openapi.yml
  format: yaml
  label: Forex Reference API
  slug: forex-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forex/openapi/forex-reference-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: this license does not permit re-distribution of our data.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: ExchangeRate-API data may only be used for your end purposes and not in any product or service that offers programmatic or automatic access to exchange rate data.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Forex
output_license: custom
provenance_date: '2026-11-09'
provider_name: Forex
provider_slug: forex
slug: forex-data-license
source_date: '2026-11-09'
source_filename: forex-data-license.yml
source_heading: Data License
source_page: https://www.exchangerate-api.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Forex\naid: forex\nurl: https://www.exchangerate-api.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: ExchangeRate-API data may only be used for your end purposes and not in any product or service that offers\n    programmatic or automatic access to exchange rate data.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: this license does not permit re-distribution of our data.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/forex/data-license/forex-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Forex's own page on 2026-11-09.
synthetic: false
tags:
- Currency
- Exchange Rates
- Financial Data
- Foreign Exchange
- Trading
---
