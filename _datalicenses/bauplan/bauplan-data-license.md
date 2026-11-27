---
api_specs:
- filename: bauplan-bauplanlabs-api-openapi.yml
  format: yaml
  label: Bauplan Bauplanlabs API
  slug: bauplan-bauplanlabs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bauplan/openapi/bauplan-bauplanlabs-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: use the Sandbox, the Bauplan Platform and Content for commercial, production, or client workloads
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: You further agree that you will not rely on any output generated through the Sandbox, for any purpose.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Bauplan
output_license: null
provenance_date: '2026-11-09'
provider_name: Bauplan
provider_slug: bauplan
slug: bauplan-data-license
source_date: '2026-11-09'
source_filename: bauplan-data-license.yml
source_heading: Data License
source_page: https://bauplanlabs.com/terms-and-conditions-sandbox
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Bauplan\naid: bauplan\nurl: https://bauplanlabs.com/terms-and-conditions-sandbox\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: You further agree that you will not rely on any output generated through the Sandbox, for any purpose.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: use the Sandbox, the Bauplan Platform and Content for commercial, production, or client workloads\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/bauplan/data-license/bauplan-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Bauplan's own page on 2026-11-09.
synthetic: false
tags:
- Data Engineering
- AI Agents
- Serverless Platform
- Data Pipeline
- Data Integration
- Isolation and Rollback
---
