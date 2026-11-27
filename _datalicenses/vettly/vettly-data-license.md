---
api_specs:
- filename: vettly-moderation-api-openapi.yml
  format: yaml
  label: Vettly Moderation API
  slug: vettly-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vettly/openapi/vettly-moderation-api-openapi.yml
- filename: vettly-system-api-openapi.yml
  format: yaml
  label: Vettly System API
  slug: vettly-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vettly/openapi/vettly-system-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: 'you grant us a worldwide, non-exclusive, royalty-free license to: Process, store, transmit, and analyze Customer Data solely to provide the Services'
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: null
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Vettly
output_license: null
provenance_date: '2026-11-10'
provider_name: Vettly
provider_slug: vettly
slug: vettly-data-license
source_date: '2026-11-10'
source_filename: vettly-data-license.yml
source_heading: Data License
source_page: https://vettly.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Vettly\naid: vettly\nurl: https://vettly.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: 'you grant us a worldwide, non-exclusive, royalty-free license to: Process, store, transmit, and analyze\n    Customer Data solely to provide the Services'\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/vettly/data-license/vettly-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Vettly's own page on 2026-11-10.
synthetic: false
tags:
- Content Moderation
- Trust and Safety
- Security
- Text Analysis
- Image Moderation
- video-moderation
- UGC
- Compliance
- agent-guardrails
- MCP
---
