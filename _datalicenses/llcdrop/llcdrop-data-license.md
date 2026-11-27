---
api_specs:
- filename: llcdrop-account-api-openapi.yml
  format: yaml
  label: LLCDrop Account API
  slug: llcdrop-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-account-api-openapi.yml
- filename: llcdrop-businesses-api-openapi.yml
  format: yaml
  label: LLCDrop Businesses API
  slug: llcdrop-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-businesses-api-openapi.yml
- filename: llcdrop-counties-and-stats-api-openapi.yml
  format: yaml
  label: LLCDrop Counties and stats API
  slug: llcdrop-counties-and-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-counties-and-stats-api-openapi.yml
- filename: llcdrop-datasets-api-openapi.yml
  format: yaml
  label: LLCDrop Datasets API
  slug: llcdrop-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-datasets-api-openapi.yml
- filename: llcdrop-filings-api-openapi.yml
  format: yaml
  label: LLCDrop Filings API
  slug: llcdrop-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-filings-api-openapi.yml
- filename: llcdrop-parcels-api-openapi.yml
  format: yaml
  label: LLCDrop Parcels API
  slug: llcdrop-parcels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-parcels-api-openapi.yml
- filename: llcdrop-reference-lists-api-openapi.yml
  format: yaml
  label: LLCDrop Reference lists API
  slug: llcdrop-reference-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-reference-lists-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: sell, resell, rent, license, publish, redistribute or otherwise make Lead Data available to others, except as a signed Data Reseller License allows;
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: solely to identify and contact prospective business customers for your own business.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: LLCDrop
output_license: custom
provenance_date: '2026-11-09'
provider_name: LLCDrop
provider_slug: llcdrop
slug: llcdrop-data-license
source_date: '2026-11-09'
source_filename: llcdrop-data-license.yml
source_heading: Data License
source_page: https://llcdrop.com/marketing/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: LLCDrop\naid: llcdrop\nurl: https://llcdrop.com/marketing/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: solely to identify and contact prospective business customers for your own business.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: sell, resell, rent, license, publish, redistribute or otherwise make Lead Data available to others, except\n    as a signed Data Reseller License allows;\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/llcdrop/data-license/llcdrop-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from LLCDrop's own page on 2026-11-09.
synthetic: false
tags:
- Lead Generation
- Business Data
- Marketing
- Real Estate
---
