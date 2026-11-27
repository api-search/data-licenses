---
api_specs:
- filename: pipehero-app-mcp-api-openapi.yml
  format: yaml
  label: pipehero-app MCP API
  slug: pipehero-app-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pipehero-app/openapi/pipehero-app-mcp-api-openapi.yml
- filename: pipehero-app-slack-api-openapi.yml
  format: yaml
  label: pipehero-app Slack API
  slug: pipehero-app-slack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pipehero-app/openapi/pipehero-app-slack-api-openapi.yml
- filename: pipehero-app-webhooks-api-openapi.yml
  format: yaml
  label: pipehero-app Webhooks API
  slug: pipehero-app-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pipehero-app/openapi/pipehero-app-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: You retain all rights to the data you tunnel and capture through the Service. You grant us a limited license to host and process it solely to provide the Service.
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
name: pipehero-app
output_license: null
provenance_date: '2026-11-10'
provider_name: pipehero-app
provider_slug: pipehero-app
slug: pipehero-app-data-license
source_date: '2026-11-10'
source_filename: pipehero-app-data-license.yml
source_heading: Data License
source_page: https://pipehero.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: pipehero-app\naid: pipehero-app\nurl: https://pipehero.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: You retain all rights to the data you tunnel and capture through the Service. You grant us a limited license\n    to host and process it solely to provide the Service.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/pipehero-app/data-license/pipehero-app-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from pipehero-app's own page on 2026-11-10.
synthetic: false
tags:
- Webhook
- API Workspace
- Developer Tools
- MCP
- Integration
---
