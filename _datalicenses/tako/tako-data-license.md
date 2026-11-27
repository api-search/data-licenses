---
api_specs:
- filename: tako-agent-api-openapi.yml
  format: yaml
  label: Tako Agent API
  slug: tako-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tako/openapi/tako-agent-api-openapi.yml
- filename: tako-tako-api-openapi.yml
  format: yaml
  label: Tako API
  slug: tako-tako-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tako/openapi/tako-tako-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You must clearly attribute the underlying data sources identified by Tako whenever displaying, distributing, or otherwise using Content, including in any outputs derived from Content
  data:
    license: custom
    stance_commercial: prohibited
    text: 'You shall not: (a) sublicense, resell, rent, lease, transfer, assign, time-share, or otherwise commercially exploit the Service'
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: You must clearly attribute the underlying data sources identified by Tako whenever displaying, distributing, or otherwise using Content, including in any outputs derived from Content
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Tako
output_license: null
provenance_date: '2026-11-10'
provider_name: Tako
provider_slug: tako
slug: tako-data-license
source_date: '2026-11-10'
source_filename: tako-data-license.yml
source_heading: Data License
source_page: https://tako.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Tako\naid: tako\nurl: https://tako.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: You must clearly attribute the underlying data sources identified by Tako whenever displaying, distributing,\n    or otherwise using Content, including in any outputs derived from Content\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: 'You shall not: (a) sublicense, resell, rent, lease, transfer, assign, time-share, or otherwise commercially\n    exploit the Service'\nattribution:\n  required: true\n  text: You must clearly attribute the underlying\
  \ data sources identified by Tako whenever displaying, distributing,\n    or otherwise using Content, including in any outputs derived from Content\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tako/data-license/tako-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Tako's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data
- Search
- Answer Engine
- Financial Data
- Knowledge Graph
- Agents
- MCP
- Data Visualization
---
