---
api_specs:
- filename: concentrate-decisions-api-openapi.yml
  format: yaml
  label: Concentrate Decisions API
  slug: concentrate-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-decisions-api-openapi.yml
- filename: concentrate-messages-api-openapi.yml
  format: yaml
  label: Concentrate Messages API
  slug: concentrate-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-messages-api-openapi.yml
- filename: concentrate-models-api-openapi.yml
  format: yaml
  label: Concentrate Models API
  slug: concentrate-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-models-api-openapi.yml
- filename: concentrate-responses-api-openapi.yml
  format: yaml
  label: Concentrate Responses API
  slug: concentrate-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-responses-api-openapi.yml
- filename: concentrate-systemone-api-openapi.yml
  format: yaml
  label: Concentrate Systemone API
  slug: concentrate-systemone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-systemone-api-openapi.yml
- filename: concentrate-chat-completions-api-openapi.yml
  format: yaml
  label: Concentrate Chat Completions API
  slug: concentrate-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-chat-completions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Customer retains ownership of Customer Data.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: As between Concentrate and Customer, Customer owns all right, title, and interest in and to Outputs generated in response to Customer Data, to the extent permitted by applicable Model Provider and Third-Party Product terms
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Concentrate
output_license: custom
provenance_date: '2026-11-09'
provider_name: Concentrate
provider_slug: concentrate
slug: concentrate-data-license
source_date: '2026-11-09'
source_filename: concentrate-data-license.yml
source_heading: Data License
source_page: https://concentrate.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Concentrate\naid: concentrate\nurl: https://concentrate.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: As between Concentrate and Customer, Customer owns all right, title, and interest in and to Outputs generated\n    in response to Customer Data, to the extent permitted by applicable Model Provider and Third-Party Product terms\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Customer retains ownership of Customer Data.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/concentrate/data-license/concentrate-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Concentrate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Gateways
- Platform
---
