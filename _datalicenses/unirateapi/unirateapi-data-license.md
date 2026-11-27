---
api_specs:
- filename: unirateapi-commodity-api-openapi.yml
  format: yaml
  label: UniRate API Commodity API
  slug: unirateapi-commodity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unirateapi/openapi/unirateapi-commodity-api-openapi.yml
- filename: unirateapi-currency-api-openapi.yml
  format: yaml
  label: UniRate API Currency API
  slug: unirateapi-currency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unirateapi/openapi/unirateapi-currency-api-openapi.yml
- filename: unirateapi-historical-currency-api-openapi.yml
  format: yaml
  label: UniRate API Historical Currency API
  slug: unirateapi-historical-currency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unirateapi/openapi/unirateapi-historical-currency-api-openapi.yml
- filename: unirateapi-vat-rates-api-openapi.yml
  format: yaml
  label: UniRate API VAT Rates API
  slug: unirateapi-vat-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unirateapi/openapi/unirateapi-vat-rates-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You must include attribution on any pages or applications where you display exchange rates obtained from our service.
  data:
    license: custom
    stance_commercial: conditional
    text: redistribution or resale of our data to third parties is strictly prohibited.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: You are welcome to cache our response data and utilize it for both personal and commercial currency conversion applications.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: UniRate API
output_license: custom
provenance_date: '2026-11-10'
provider_name: UniRate API
provider_slug: unirateapi
slug: unirateapi-data-license
source_date: '2026-11-10'
source_filename: unirateapi-data-license.yml
source_heading: Data License
source_page: https://unirateapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: UniRate API\naid: unirateapi\nurl: https://unirateapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: You are welcome to cache our response data and utilize it for both personal and commercial currency conversion\n    applications.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: redistribution or resale of our data to third parties is strictly prohibited.\nattribution:\n  required: true\n  text: You must include attribution on any pages or applications where you display exchange rates obtained from\n    our service.\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/unirateapi/data-license/unirateapi-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from UniRate API's own page on 2026-11-10.
synthetic: false
tags:
- Currency
- Exchange Rates
- Foreign Exchange
- Currency Conversion
- VAT
- Finance
- Financial Data
---
