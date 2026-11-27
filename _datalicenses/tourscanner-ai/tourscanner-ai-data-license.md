---
api_specs:
- filename: tourscanner-ai-tourscanner-api-openapi.yml
  format: yaml
  label: TourScanner API
  slug: tourscanner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourscanner-ai/openapi/tourscanner-ai-tourscanner-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: prohibited
    text: Do not copy the catalog in bulk, resell raw data, or build a competing dataset from it.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: While your access is active, you may display catalog content in your product as the documentation allows.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: TourScanner AI
output_license: custom
provenance_date: '2026-11-10'
provider_name: TourScanner AI
provider_slug: tourscanner-ai
slug: tourscanner-ai-data-license
source_date: '2026-11-10'
source_filename: tourscanner-ai-data-license.yml
source_heading: Data License
source_page: https://tourscanner.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: TourScanner AI\naid: tourscanner-ai\nurl: https://tourscanner.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: While your access is active, you may display catalog content in your product as the documentation allows.\ndata:\n  license: null\n  stance_commercial: prohibited\n  text: Do not copy the catalog in bulk, resell raw data, or build a competing dataset from it.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tourscanner-ai/data-license/tourscanner-ai-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from TourScanner AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tours
- Activities
- Booking
---
