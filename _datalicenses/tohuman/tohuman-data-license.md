---
api_specs:
- filename: tohuman-humanizations-api-openapi.yml
  format: yaml
  label: ToHuman Humanizations API
  slug: tohuman-humanizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tohuman/openapi/tohuman-humanizations-api-openapi.yml
- filename: tohuman-humanize-api-openapi.yml
  format: yaml
  label: ToHuman Humanize API
  slug: tohuman-humanize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tohuman/openapi/tohuman-humanize-api-openapi.yml
- filename: tohuman-submit-api-openapi.yml
  format: yaml
  label: ToHuman Submit API
  slug: tohuman-submit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tohuman/openapi/tohuman-submit-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: We do not claim any rights to your content.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: You retain full ownership of all text you submit to the Service and all humanized output.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: ToHuman
output_license: null
provenance_date: '2026-11-10'
provider_name: ToHuman
provider_slug: tohuman
slug: tohuman-data-license
source_date: '2026-11-10'
source_filename: tohuman-data-license.yml
source_heading: Data License
source_page: https://tohuman.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: ToHuman\naid: tohuman\nurl: https://tohuman.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: You retain full ownership of all text you submit to the Service and all humanized output.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: We do not claim any rights to your content.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tohuman/data-license/tohuman-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from ToHuman's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Text-Humanization
- Content Generation
- Marketing
- Software-as-a-Service
---
