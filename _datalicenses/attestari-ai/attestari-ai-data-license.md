---
api_specs:
- filename: attestari-ai-health-api-openapi.yml
  format: yaml
  label: Attestari Health API
  slug: attestari-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-health-api-openapi.yml
- filename: attestari-ai-manifest-api-openapi.yml
  format: yaml
  label: Attestari Manifest API
  slug: attestari-ai-manifest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-manifest-api-openapi.yml
- filename: attestari-ai-remote-api-openapi.yml
  format: yaml
  label: Attestari Remote API
  slug: attestari-ai-remote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-remote-api-openapi.yml
- filename: attestari-ai-verdict-api-openapi.yml
  format: yaml
  label: Attestari Verdict API
  slug: attestari-ai-verdict-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-verdict-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You may display a grade in your own product with the words "Rated by Attestari" and a link to attestari.ai.
  data:
    license: custom
    stance_commercial: prohibited
    text: The engine, the reports, the index and the site are ours, and these terms give you no rights in them beyond using Attestari as described.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You may use verdicts inside your own products and workflows.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Attestari
output_license: custom
provenance_date: '2026-11-09'
provider_name: Attestari
provider_slug: attestari-ai
slug: attestari-ai-data-license
source_date: '2026-11-09'
source_filename: attestari-ai-data-license.yml
source_heading: Data License
source_page: https://attestari.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Attestari\naid: attestari-ai\nurl: https://attestari.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You may use verdicts inside your own products and workflows.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: The engine, the reports, the index and the site are ours, and these terms give you no rights in them beyond\n    using Attestari as described.\nattribution:\n  required: true\n  text: You may display a grade in your own product with the words \"Rated by Attestari\" and a link to attestari.ai.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/attestari-ai/data-license/attestari-ai-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Attestari's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Security
- Compliance
- Open Source
---
