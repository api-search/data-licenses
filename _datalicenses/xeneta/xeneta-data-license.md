---
api_specs:
- filename: xeneta-air-api-openapi.yml
  format: yaml
  label: Xeneta Air API
  slug: xeneta-air-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xeneta/openapi/xeneta-air-api-openapi.yml
- filename: xeneta-ocean-api-openapi.yml
  format: yaml
  label: Xeneta Ocean API
  slug: xeneta-ocean-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xeneta/openapi/xeneta-ocean-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: clearly referencing Xeneta as the source
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Limit the use of Information to its own business operation. If the Customer wishes to make any other use of Xeneta's Information, the Customer must obtain prior written permission from Xeneta;
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Xeneta
output_license: custom
provenance_date: '2026-11-10'
provider_name: Xeneta
provider_slug: xeneta
slug: xeneta-data-license
source_date: '2026-11-10'
source_filename: xeneta-data-license.yml
source_heading: Data License
source_page: https://www.xeneta.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Xeneta\naid: xeneta\nurl: https://www.xeneta.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Limit the use of Information to its own business operation. If the Customer wishes to make any other use\n    of Xeneta's Information, the Customer must obtain prior written permission from Xeneta;\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: true\n  text: clearly referencing Xeneta as the source\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/xeneta/data-license/xeneta-data-license.yml
stated_fields:
- outputs
- attribution
summary_line: 2 quoted statements, read from Xeneta's own page on 2026-11-10.
synthetic: false
tags:
- Freight
- Shipping
- Logistics
- Ocean Freight
- Air Freight
- Benchmarking
- Market Data
- Supply Chain
- Rates
- Emissions
---
