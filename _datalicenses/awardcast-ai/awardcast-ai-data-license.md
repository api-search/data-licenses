---
api_specs:
- filename: awardcast-ai-mcp.json
  format: json
  label: AwardCast AI MCP
  slug: awardcast-ai-mcp
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardcast-ai/openapi/awardcast-ai-mcp.json
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: Underlying government records are public.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: The service, its content, and its forecasts are owned by AwardCast AI or its licensors.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AwardCast AI
output_license: custom
provenance_date: '2026-11-09'
provider_name: AwardCast AI
provider_slug: awardcast-ai
slug: awardcast-ai-data-license
source_date: '2026-11-09'
source_filename: awardcast-ai-data-license.yml
source_heading: Data License
source_page: https://awardcast.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AwardCast AI\naid: awardcast-ai\nurl: https://awardcast.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: The service, its content, and its forecasts are owned by AwardCast AI or its licensors.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Underlying government records are public.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/awardcast-ai/data-license/awardcast-ai-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from AwardCast AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Forecasting
- Government
- Contracts
- Pricing
---
