---
api_specs:
- filename: crustapi-demo-api-openapi.yml
  format: yaml
  label: CrustAPI Demo API
  slug: crustapi-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-demo-api-openapi.yml
- filename: crustapi-search-api-openapi.yml
  format: yaml
  label: CrustAPI Search API
  slug: crustapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-search-api-openapi.yml
- filename: crustapi-account-api-openapi.yml
  format: yaml
  label: CrustAPI Account API
  slug: crustapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-account-api-openapi.yml
- filename: crustapi-linked-in-api-openapi.yml
  format: yaml
  label: CrustAPI Linked In API
  slug: crustapi-linked-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-linked-in-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: 'Unless we agree otherwise in writing, every Dataset comes with a standard license: a limited, non-exclusive, non-transferable right to use the Dataset for your own internal business purposes.'
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Do not resell or redistribute the raw data as a competing dataset or API without adding meaningful value.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: CrustAPI
output_license: custom
provenance_date: '2026-11-09'
provider_name: CrustAPI
provider_slug: crustapi
slug: crustapi-data-license
source_date: '2026-11-09'
source_filename: crustapi-data-license.yml
source_heading: Data License
source_page: https://crustapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: CrustAPI\naid: crustapi\nurl: https://crustapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Do not resell or redistribute the raw data as a competing dataset or API without adding meaningful value.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: 'Unless we agree otherwise in writing, every Dataset comes with a standard license: a limited, non-exclusive,\n    non-transferable right to use the Dataset for your own internal business purposes.'\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/crustapi/data-license/crustapi-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from CrustAPI's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Google Maps
- LinkedIn
- SERP / Web Scraping
- Business & Lead Data
- People / Recruiting Data
- Data Enrichment
- AI Agents / MCP
- RAG
- Data
---
