---
api_specs:
- filename: zillapi-account-api-openapi.yml
  format: yaml
  label: Zillapi Account API
  slug: zillapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-account-api-openapi.yml
- filename: zillapi-buildings-api-openapi.yml
  format: yaml
  label: Zillapi Buildings API
  slug: zillapi-buildings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-buildings-api-openapi.yml
- filename: zillapi-jobs-api-openapi.yml
  format: yaml
  label: Zillapi Jobs API
  slug: zillapi-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-jobs-api-openapi.yml
- filename: zillapi-listings-api-openapi.yml
  format: yaml
  label: Zillapi Listings API
  slug: zillapi-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-listings-api-openapi.yml
- filename: zillapi-properties-api-openapi.yml
  format: yaml
  label: Zillapi Properties API
  slug: zillapi-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-properties-api-openapi.yml
- filename: zillapi-search-api-openapi.yml
  format: yaml
  label: Zillapi Search API
  slug: zillapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-search-api-openapi.yml
- filename: zillapi-webhooks-api-openapi.yml
  format: yaml
  label: Zillapi Webhooks API
  slug: zillapi-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Underlying property data is sourced from publicly available pages on zillow.com and is owned by its respective rights holders.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Subject to your compliance with these Terms and timely payment of fees, Zillapi grants you a non-exclusive, non-transferable, revocable license to call the Service and use the responses inside your application during the term of your subscription.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Zillapi
output_license: custom
provenance_date: '2026-11-10'
provider_name: Zillapi
provider_slug: zillapi
slug: zillapi-data-license
source_date: '2026-11-10'
source_filename: zillapi-data-license.yml
source_heading: Data License
source_page: https://zillapi.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Zillapi\naid: zillapi\nurl: https://zillapi.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Subject to your compliance with these Terms and timely payment of fees, Zillapi grants you a non-exclusive,\n    non-transferable, revocable license to call the Service and use the responses inside your application during\n    the term of your subscription.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Underlying property data is sourced from publicly available pages on zillow.com and is owned by its respective\n    rights holders.\n\
  attribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/zillapi/data-license/zillapi-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Zillapi's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- PropTech
- Property Data
- Zillow
- Zestimate
- Valuation
- AVM
- Listings
- MCP
- AI Agents
- REST API
---
