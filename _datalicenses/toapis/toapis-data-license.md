---
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Content you generate through the API belongs to you, subject to your responsibility to ensure that its use is lawful and compliant.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: ToAPIs
output_license: custom
provenance_date: '2026-11-10'
provider_name: ToAPIs
provider_slug: toapis
slug: toapis-data-license
source_date: '2026-11-10'
source_filename: toapis-data-license.yml
source_heading: Data License
source_page: https://toapis.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: ToAPIs\naid: toapis\nurl: https://toapis.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Content you generate through the API belongs to you, subject to your responsibility to ensure that its use\n    is lawful and compliant.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/toapis/data-license/toapis-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from ToAPIs's own page on 2026-11-10.
synthetic: false
tags:
- AI API
- LLM/AI gateway
- model aggregation
- OpenAI-Compatible
- Model Routing
- provider failover
- Text Generation
- Image Generation
- Video Generation
- Developer Tools
- A2A
---
