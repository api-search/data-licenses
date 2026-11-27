---
api_specs:
- filename: arvx-ai-readings-api-openapi.yml
  format: yaml
  label: ARVX Readings API
  slug: arvx-ai-readings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arvx-ai/openapi/arvx-ai-readings-api-openapi.yml
- filename: arvx-ai-records-api-openapi.yml
  format: yaml
  label: ARVX Records API
  slug: arvx-ai-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arvx-ai/openapi/arvx-ai-records-api-openapi.yml
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
    text: you receive a non-exclusive license to use Readings inside Your Product and to store Sealed Records and send them back to the Service.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: ARVX
output_license: custom
provenance_date: '2026-11-09'
provider_name: ARVX
provider_slug: arvx-ai
slug: arvx-ai-data-license
source_date: '2026-11-09'
source_filename: arvx-ai-data-license.yml
source_heading: Data License
source_page: https://developer.arvx.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: ARVX\naid: arvx-ai\nurl: https://developer.arvx.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: you receive a non-exclusive license to use Readings inside Your Product and to store Sealed Records and\n    send them back to the Service.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/arvx-ai/data-license/arvx-ai-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from ARVX's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
