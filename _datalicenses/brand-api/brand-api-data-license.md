---
api_specs:
- filename: brand-api-brands-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Brands API
  slug: brand-api-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-brands-api-openapi.yml
- filename: brand-api-context-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Context API
  slug: brand-api-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-context-api-openapi.yml
- filename: brand-api-search-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Search API
  slug: brand-api-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-search-api-openapi.yml
- filename: brand-api-viewer-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Viewer API
  slug: brand-api-viewer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-viewer-api-openapi.yml
- filename: brand-api-agents-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Agents API
  slug: brand-api-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-agents-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Brandfetch grants the Customer a limited, non-exclusive, non-transferable, non-sublicensable license to the Services and the Content.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Customer shall use the Services through its own employees, agents and/or duly authorised representatives only and for its own business purposes
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Brand API (Brandfetch)
output_license: custom
provenance_date: '2026-11-09'
provider_name: Brand API (Brandfetch)
provider_slug: brand-api
slug: brand-api-data-license
source_date: '2026-11-09'
source_filename: brand-api-data-license.yml
source_heading: Data License
source_page: https://brandfetch.com/terms?mode=dev
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Brand API (Brandfetch)\naid: brand-api\nurl: https://brandfetch.com/terms?mode=dev\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Customer shall use the Services through its own employees, agents and/or duly authorised representatives\n    only and for its own business purposes\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Brandfetch grants the Customer a limited, non-exclusive, non-transferable, non-sublicensable license to\n    the Services and the Content.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/brand-api/data-license/brand-api-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Brand API (Brandfetch)'s own page on 2026-11-09.
synthetic: false
tags:
- Brands
- Logo
- Brand Assets
- Company Data
- Firmographics
- Brand Context
- Merchant Enrichment
- Agent Tools
- A2A
---
