---
api_specs:
- filename: nationalize-nationality-api-openapi.yml
  format: yaml
  label: Nationalize.io Nationality API
  slug: nationalize-nationality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nationalize/openapi/nationalize-nationality-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Demografix owns all rights in the Services, including the APIs, the underlying datasets, the statistical models, and all associated documentation and content.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: API responses are licensed to you for use in accordance with your subscription and these Terms. This license is non-exclusive, worldwide, and valid for as long as your subscription is active.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Nationalize.io
output_license: custom
provenance_date: '2026-11-10'
provider_name: Nationalize.io
provider_slug: nationalize
slug: nationalize-data-license
source_date: '2026-11-10'
source_filename: nationalize-data-license.yml
source_heading: Data License
source_page: https://nationalize.io/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Nationalize.io\naid: nationalize\nurl: https://nationalize.io/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: API responses are licensed to you for use in accordance with your subscription and these Terms. This license\n    is non-exclusive, worldwide, and valid for as long as your subscription is active.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Demografix owns all rights in the Services, including the APIs, the underlying datasets, the statistical\n    models, and all associated documentation and content.\n\
  attribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/nationalize/data-license/nationalize-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Nationalize.io's own page on 2026-11-10.
synthetic: false
tags:
- Nationality
- Name Prediction
- Demographics
- Probabilistic Models
- People
---
