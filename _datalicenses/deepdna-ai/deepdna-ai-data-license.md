---
api_specs:
- filename: deepdna-ai-knowledge-api-openapi.yml
  format: yaml
  label: deepdna-ai Knowledge API
  slug: deepdna-ai-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdna-ai/openapi/deepdna-ai-knowledge-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: keeping the cited sources and the disclaimer that comes with them
  data:
    license: custom
    stance_commercial: prohibited
    text: Resell or republish the knowledge base as a whole, or a substantial part of it, as your own dataset
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Call the knowledge endpoints and the MCP server, directly or through an AI assistant, and show or quote their responses, keeping the cited sources and the disclaimer that comes with them
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: deepdna-ai
output_license: custom
provenance_date: '2026-11-09'
provider_name: deepdna-ai
provider_slug: deepdna-ai
slug: deepdna-ai-data-license
source_date: '2026-11-09'
source_filename: deepdna-ai-data-license.yml
source_heading: Data License
source_page: https://deepdna.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: deepdna-ai\naid: deepdna-ai\nurl: https://deepdna.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Call the knowledge endpoints and the MCP server, directly or through an AI assistant, and show or quote\n    their responses, keeping the cited sources and the disclaimer that comes with them\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Resell or republish the knowledge base as a whole, or a substantial part of it, as your own dataset\nattribution:\n  required: true\n  text: keeping the cited sources and the disclaimer that comes\
  \ with them\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/deepdna-ai/data-license/deepdna-ai-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from deepdna-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmacogenomics
- MCP
- AI Agents
- Genomics
- Healthcare
---
