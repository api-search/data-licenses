---
api_specs:
- filename: modal-labs-modal-web-endpoints-representative-api-openapi.yml
  format: yaml
  label: Modal Web Endpoints (Representative) API
  slug: modal-labs-modal-web-endpoints-representative-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modal-labs/openapi/modal-labs-modal-web-endpoints-representative-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Customer hereby grants to Modal a limited license to use Customer Data as necessary to provide the Service to Customer.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Input and Output shall be considered Customer Data.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Modal
output_license: custom
provenance_date: '2026-11-10'
provider_name: Modal
provider_slug: modal-labs
slug: modal-labs-data-license
source_date: '2026-11-10'
source_filename: modal-labs-data-license.yml
source_heading: Data License
source_page: https://modal.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Modal\naid: modal-labs\nurl: https://modal.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Input and Output shall be considered Customer Data.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Customer hereby grants to Modal a limited license to use Customer Data as necessary to provide the Service\n    to Customer.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/modal-labs/data-license/modal-labs-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Modal's own page on 2026-11-10.
synthetic: false
tags:
- Serverless
- Compute
- GPU
- AI Infrastructure
- Sandbox
- Infrastructure as Code
---
