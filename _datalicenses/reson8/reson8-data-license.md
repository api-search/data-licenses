---
api_specs:
- filename: reson8-auth-api-openapi.yml
  format: yaml
  label: Reson8 Auth API
  slug: reson8-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reson8/openapi/reson8-auth-api-openapi.yml
- filename: reson8-custom-models-api-openapi.yml
  format: yaml
  label: Reson8 Custom Models API
  slug: reson8-custom-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reson8/openapi/reson8-custom-models-api-openapi.yml
- filename: reson8-speech-to-text-api-openapi.yml
  format: yaml
  label: Reson8 Speech to Text API
  slug: reson8-speech-to-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reson8/openapi/reson8-speech-to-text-api-openapi.yml
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
    text: The Customer retains all Intellectual Property Rights in its Audio Data, Terminology Lists, and Output.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Reson8
output_license: custom
provenance_date: '2026-11-10'
provider_name: Reson8
provider_slug: reson8
slug: reson8-data-license
source_date: '2026-11-10'
source_filename: reson8-data-license.yml
source_heading: Data License
source_page: https://www.reson8.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Reson8\naid: reson8\nurl: https://www.reson8.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: The Customer retains all Intellectual Property Rights in its Audio Data, Terminology Lists, and Output.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/reson8/data-license/reson8-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from Reson8's own page on 2026-11-10.
synthetic: false
tags:
- Speech Recognition
- Speech-to-Text
- Voice AI
- Transcription
- Diarization
- Machine Learning
- Developers
---
