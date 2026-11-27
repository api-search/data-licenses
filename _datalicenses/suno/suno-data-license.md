---
api_specs:
- filename: suno-lyrics-api-openapi.yml
  format: yaml
  label: Suno Lyrics API
  slug: suno-lyrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suno/openapi/suno-lyrics-api-openapi.yml
- filename: suno-music-api-openapi.yml
  format: yaml
  label: Suno Music API
  slug: suno-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suno/openapi/suno-music-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: you agree not to modify, copy, frame, scrape, rent, lease, loan, sell, distribute, or create derivative works based on the Service or the Service Content
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You may commercially exploit Output solely to the extent it adheres to Suno's Conditions of Access and Use as outlined above provided you have obtained a permitted download of that Output in accordance with the download allocations for your applicable service tier
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Suno
output_license: custom
provenance_date: '2026-11-10'
provider_name: Suno
provider_slug: suno
slug: suno-data-license
source_date: '2026-11-10'
source_filename: suno-data-license.yml
source_heading: Data License
source_page: https://suno.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Suno\naid: suno\nurl: https://suno.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You may commercially exploit Output solely to the extent it adheres to Suno's Conditions of Access and Use\n    as outlined above provided you have obtained a permitted download of that Output in accordance with the download\n    allocations for your applicable service tier\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: you agree not to modify, copy, frame, scrape, rent, lease, loan, sell, distribute, or create derivative\n   \
  \ works based on the Service or the Service Content\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/suno/data-license/suno-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Suno's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Music Generation
- Audio
- Generative
- Text-to-Speech
- Music
---
