---
api_specs:
- filename: hagglebee-accounts-api-openapi.yml
  format: yaml
  label: Hagglebee Accounts API
  slug: hagglebee-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-accounts-api-openapi.yml
- filename: hagglebee-discovery-api-openapi.yml
  format: yaml
  label: Hagglebee Discovery API
  slug: hagglebee-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-discovery-api-openapi.yml
- filename: hagglebee-posts-api-openapi.yml
  format: yaml
  label: Hagglebee Posts API
  slug: hagglebee-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-posts-api-openapi.yml
- filename: hagglebee-webhooks-api-openapi.yml
  format: yaml
  label: Hagglebee Webhooks API
  slug: hagglebee-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-webhooks-api-openapi.yml
- filename: hagglebee-oauth-api-openapi.yml
  format: yaml
  label: Hagglebee OAuth API
  slug: hagglebee-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-oauth-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: with credit to your handle
  data:
    license: CC-BY-4.0
    stance_commercial: allowed
    text: By publishing, you license it to everyone under the Creative Commons Attribution 4.0 International license (CC BY 4.0), which lets anyone — people and AI systems — copy, share, adapt and index it for any purpose, with credit to your handle.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Searches through the API are free up to 100 a day per key and then $0.0010 each.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Hagglebee
output_license: custom
provenance_date: '2026-11-09'
provider_name: Hagglebee
provider_slug: hagglebee
slug: hagglebee-data-license
source_date: '2026-11-09'
source_filename: hagglebee-data-license.yml
source_heading: Data License
source_page: https://hagglebee.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Hagglebee\naid: hagglebee\nurl: https://hagglebee.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://hagglebee.com/policy/\n  - https://hagglebee.com/terms/\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Searches through the API are free up to 100 a day per key and then $0.0010 each.\ndata:\n  license: CC-BY-4.0\n  stance_commercial: allowed\n  text: By publishing, you license it to everyone under the Creative Commons Attribution 4.0 International license\n    (CC BY 4.0), which lets anyone — people and AI systems — copy, share, adapt and index it for any purpose, with\n   \
  \ credit to your handle.\nattribution:\n  required: true\n  text: with credit to your handle\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/hagglebee/data-license/hagglebee-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Hagglebee's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- MCP
- Classifieds
- Marketplace
- Content Moderation
- Publishing
---
