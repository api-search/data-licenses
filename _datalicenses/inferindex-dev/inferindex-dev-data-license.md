---
api_specs:
- filename: inferindex-dev-mcp.json
  format: json
  label: InferIndex API
  slug: inferindex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inferindex-dev/openapi/inferindex-dev-mcp.json
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Prices and conditions are collected from providers' public information and may be incomplete, outdated or wrong
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You may use the responses in your own tools, products and analyses. Don't present InferIndex data as official information from a provider, and don't resell raw access to the API as your own service.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: inferindex-dev
output_license: custom
provenance_date: '2026-11-09'
provider_name: inferindex-dev
provider_slug: inferindex-dev
slug: inferindex-dev-data-license
source_date: '2026-11-09'
source_filename: inferindex-dev-data-license.yml
source_heading: Data License
source_page: https://inferindex.dev/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: inferindex-dev\naid: inferindex-dev\nurl: https://inferindex.dev/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You may use the responses in your own tools, products and analyses. Don't present InferIndex data as official\n    information from a provider, and don't resell raw access to the API as your own service.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Prices and conditions are collected from providers' public information and may be incomplete, outdated or\n    wrong\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/inferindex-dev/data-license/inferindex-dev-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from inferindex-dev's own page on 2026-11-09.
synthetic: false
tags:
- LLM
- Pricing
- Index
- Data
---
