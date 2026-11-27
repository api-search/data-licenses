---
api_specs:
- filename: bifrost-health-api-openapi.yml
  format: yaml
  label: Bifrost Health API
  slug: bifrost-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bifrost/openapi/bifrost-health-api-openapi.yml
- filename: bifrost-chat-completions-api-openapi.yml
  format: yaml
  label: Bifrost Chat Completions API
  slug: bifrost-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bifrost/openapi/bifrost-chat-completions-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You must retain, in the Source form of any Derivative Works that You distribute, all copyright, patent, trademark, and attribution notices from the Source form of the Work
  data:
    license: Apache-2.0
    stance_commercial: conditional
    text: 'provided that You meet the following conditions:'
  interface_license:
    url: null
  outputs:
    license: custom
    source: https://www.getmaxim.ai/terms-of-service
    stance_commercial: unstated
    text: As between you and Maxim, all Customer Data, Outputs, and any Customer Confidential Information are and will remain owned exclusively by you or your licensors, as applicable.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Bifrost
output_license: custom
provenance_date: '2026-11-09'
provider_name: Bifrost
provider_slug: bifrost
slug: bifrost-data-license
source_date: '2026-11-09'
source_filename: bifrost-data-license.yml
source_heading: Data License
source_page: https://github.com/maximhq/bifrost/blob/dev/LICENSE
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Bifrost\naid: bifrost\nurl: https://github.com/maximhq/bifrost/blob/dev/LICENSE\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://github.com/maximhq/bifrost/blob/dev/LICENSE\n  - https://www.getmaxim.ai/terms-of-service\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: As between you and Maxim, all Customer Data, Outputs, and any Customer Confidential Information are and\n    will remain owned exclusively by you or your licensors, as applicable.\n  source: https://www.getmaxim.ai/terms-of-service\ndata:\n  license: Apache-2.0\n  stance_commercial: conditional\n  text: 'provided that You\
  \ meet the following conditions:'\nattribution:\n  required: true\n  text: You must retain, in the Source form of any Derivative Works that You distribute, all copyright, patent,\n    trademark, and attribution notices from the Source form of the Work\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/bifrost/data-license/bifrost-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Bifrost's own page on 2026-11-09.
synthetic: false
tags:
- AI Gateway
- LLM
- Load Balancing
- Open Source
- OpenAI-Compatible
- MCP
---
