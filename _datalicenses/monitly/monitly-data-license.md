---
api_specs:
- filename: monitly-charts-api-openapi.yml
  format: yaml
  label: Monitly Charts API
  slug: monitly-charts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monitly/openapi/monitly-charts-api-openapi.yml
- filename: monitly-datasets-api-openapi.yml
  format: yaml
  label: Monitly Datasets API
  slug: monitly-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monitly/openapi/monitly-datasets-api-openapi.yml
- filename: monitly-mcp-api-openapi.yml
  format: yaml
  label: Monitly MCP API
  slug: monitly-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monitly/openapi/monitly-mcp-api-openapi.yml
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
    text: Users retain ownership of charts and visualizations they create using our service.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Monitly
output_license: custom
provenance_date: '2026-11-10'
provider_name: Monitly
provider_slug: monitly
slug: monitly-data-license
source_date: '2026-11-10'
source_filename: monitly-data-license.yml
source_heading: Data License
source_page: https://monit.ly/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Monitly\naid: monitly\nurl: https://monit.ly/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Users retain ownership of charts and visualizations they create using our service.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/monitly/data-license/monitly-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from Monitly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Statistics
- Dashboards
---
