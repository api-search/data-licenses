---
api_specs:
- filename: parceled-ai-account-api-openapi.yml
  format: yaml
  label: parceled-ai Account API
  slug: parceled-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parceled-ai/openapi/parceled-ai-account-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Parceled asserts no ownership over the underlying public data.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You may use the data you retrieve, subject to Section 4 (Acceptable use) and Section 5 (Data use and compliance).
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: parceled-ai
output_license: custom
provenance_date: '2026-11-10'
provider_name: parceled-ai
provider_slug: parceled-ai
slug: parceled-ai-data-license
source_date: '2026-11-10'
source_filename: parceled-ai-data-license.yml
source_heading: Data License
source_page: https://www.parceled.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: parceled-ai\naid: parceled-ai\nurl: https://www.parceled.ai/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You may use the data you retrieve, subject to Section 4 (Acceptable use) and Section 5 (Data use and compliance).\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Parceled asserts no ownership over the underlying public data.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/parceled-ai/data-license/parceled-ai-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from parceled-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Data API
- Mapping
- Artificial Intelligence
---
