---
api_specs:
- filename: artifacta-io-openapi.json
  format: json
  label: Artifacta API
  slug: artifacta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifacta-io/openapi/artifacta-io-openapi.json
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: You grant us a limited license to host, store, transmit, and display your artifacts solely to operate the service for you
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: You own your artifacts. Anything you upload — code, models, documents, outputs — remains yours.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Artifacta
output_license: custom
provenance_date: '2026-11-09'
provider_name: Artifacta
provider_slug: artifacta-io
slug: artifacta-io-data-license
source_date: '2026-11-09'
source_filename: artifacta-io-data-license.yml
source_heading: Data License
source_page: https://artifacta.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Artifacta\naid: artifacta-io\nurl: https://artifacta.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: You own your artifacts. Anything you upload — code, models, documents, outputs — remains yours.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: You grant us a limited license to host, store, transmit, and display your artifacts solely to operate the\n    service for you\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/artifacta-io/data-license/artifacta-io-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Artifacta's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Storage
- Artifact
- MCP
- Open Source
---
