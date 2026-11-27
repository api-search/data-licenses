---
api_specs:
- filename: invokely-openapi-generated.yml
  format: yaml
  label: Invokely API
  slug: invokely-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invokely/openapi/_ae-authored/invokely-openapi-generated.yml
- filename: invokely-rank-api-openapi.yml
  format: yaml
  label: Invokely Rank API
  slug: invokely-rank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invokely/openapi/invokely-rank-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: The citation in each response carries that attribution and any notice the publisher asks for.
  data:
    license: null
    stance_commercial: conditional
    text: The statistics themselves remain under their publishers' licenses.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: You may use the figures you receive in your own products, agents, analyses and publications, including commercial ones, as long as you respect the source licenses and these terms.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Invokely
output_license: custom
provenance_date: '2026-11-09'
provider_name: Invokely
provider_slug: invokely
slug: invokely-data-license
source_date: '2026-11-09'
source_filename: invokely-data-license.yml
source_heading: Data License
source_page: https://invokely.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Invokely\naid: invokely\nurl: https://invokely.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: You may use the figures you receive in your own products, agents, analyses and publications, including commercial\n    ones, as long as you respect the source licenses and these terms.\ndata:\n  license: null\n  stance_commercial: conditional\n  text: The statistics themselves remain under their publishers' licenses.\nattribution:\n  required: true\n  text: The citation in each response carries that attribution and any notice the publisher asks for.\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/invokely/data-license/invokely-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Invokely's own page on 2026-11-09.
synthetic: false
tags:
- Statistics
- Economic Data
- Public Data
- Data API
---
