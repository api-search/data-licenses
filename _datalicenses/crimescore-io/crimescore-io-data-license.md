---
api_specs:
- filename: crimescore-io-geocode-api-openapi.yml
  format: yaml
  label: crimescore-io Geocode API
  slug: crimescore-io-geocode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimescore-io/openapi/crimescore-io-geocode-api-openapi.yml
- filename: crimescore-io-incidents-api-openapi.yml
  format: yaml
  label: crimescore-io Incidents API
  slug: crimescore-io-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimescore-io/openapi/crimescore-io-incidents-api-openapi.yml
- filename: crimescore-io-score-api-openapi.yml
  format: yaml
  label: crimescore-io Score API
  slug: crimescore-io-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimescore-io/openapi/crimescore-io-score-api-openapi.yml
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
    stance_commercial: conditional
    text: The Safety Scores, grades, component scores, contributor details, recent-incident summaries, and map outputs returned by the Service are provided to you under a non-exclusive, non-transferable license to use within your applications.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: crimescore-io
output_license: custom
provenance_date: '2026-11-09'
provider_name: crimescore-io
provider_slug: crimescore-io
slug: crimescore-io-data-license
source_date: '2026-11-09'
source_filename: crimescore-io-data-license.yml
source_heading: Data License
source_page: https://crimescore.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: crimescore-io\naid: crimescore-io\nurl: https://crimescore.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: The Safety Scores, grades, component scores, contributor details, recent-incident summaries, and map outputs\n    returned by the Service are provided to you under a non-exclusive, non-transferable license to use within your\n    applications.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/crimescore-io/data-license/crimescore-io-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from crimescore-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Safety
- Real Estate
- Data
- Mapping
---
