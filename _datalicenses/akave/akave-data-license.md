---
api_specs:
- filename: akave-buckets-api-openapi.yml
  format: yaml
  label: Akave Buckets API
  slug: akave-buckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akave/openapi/akave-buckets-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: You hereby grant to Akave a nonexclusive, worldwide, transferable, sublicensable, irrevocable, royalty-free, fully paid-up license to process, display, copy, store, transmit, and otherwise access and use the Data for purposes of providing the Data Storage Service to Subscriber and its Authorized Users.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: null
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Akave
output_license: null
provenance_date: '2026-11-09'
provider_name: Akave
provider_slug: akave
slug: akave-data-license
source_date: '2026-11-09'
source_filename: akave-data-license.yml
source_heading: Data License
source_page: https://akave.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Akave\naid: akave\nurl: https://akave.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: You hereby grant to Akave a nonexclusive, worldwide, transferable, sublicensable, irrevocable, royalty-free,\n    fully paid-up license to process, display, copy, store, transmit, and otherwise access and use the Data for\n    purposes of providing the Data Storage Service to Subscriber and its Authorized Users.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/akave/data-license/akave-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Akave's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Object Storage
- S3 Compatible
- Decentralized Storage
- Cloud Storage
- gRPC
- MCP
---
