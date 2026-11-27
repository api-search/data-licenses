---
api_specs:
- filename: allmodels-account-api-openapi.yml
  format: yaml
  label: Allmodels Account API
  slug: allmodels-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-account-api-openapi.yml
- filename: allmodels-allmodels-api-api-openapi.yml
  format: yaml
  label: Allmodels Allmodels API
  slug: allmodels-allmodels-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-allmodels-api-api-openapi.yml
- filename: allmodels-custom-voices-api-openapi.yml
  format: yaml
  label: Allmodels Custom Voices API
  slug: allmodels-custom-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-custom-voices-api-openapi.yml
- filename: allmodels-el-api-openapi.yml
  format: yaml
  label: Allmodels El API
  slug: allmodels-el-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-el-api-openapi.yml
- filename: allmodels-health-api-openapi.yml
  format: yaml
  label: Allmodels Health API
  slug: allmodels-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-health-api-openapi.yml
- filename: allmodels-oai-api-openapi.yml
  format: yaml
  label: Allmodels Oai API
  slug: allmodels-oai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-oai-api-openapi.yml
- filename: allmodels-realtime-api-openapi.yml
  format: yaml
  label: Allmodels Realtime API
  slug: allmodels-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-realtime-api-openapi.yml
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
    text: You may use the audio and transcripts you generate, and voices you clone from recordings you have the rights to, subject to the terms of the provider that serves your request.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Allmodels
output_license: custom
provenance_date: '2026-11-09'
provider_name: Allmodels
provider_slug: allmodels
slug: allmodels-data-license
source_date: '2026-11-09'
source_filename: allmodels-data-license.yml
source_heading: Data License
source_page: https://allmodels.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Allmodels\naid: allmodels\nurl: https://allmodels.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You may use the audio and transcripts you generate, and voices you clone from recordings you have the rights\n    to, subject to the terms of the provider that serves your request.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/allmodels/data-license/allmodels-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from Allmodels's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice AI
- Text-to-Speech
- Speech-to-Text
- Real-Time
---
