---
api_specs:
- filename: secondfactor-openapi-generated.yml
  format: yaml
  label: SecondFactor API
  slug: secondfactor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secondfactor/openapi/_ae-authored/secondfactor-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: You retain all rights to your own Customer Application, your own data, and the content you transmit through it. You grant us a limited license to process the data you submit (including End User Data) solely to provide the Services to you, as described in our Privacy Policy.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Use of the Services requires a positive credit balance.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SecondFactor
output_license: custom
provenance_date: '2026-11-10'
provider_name: SecondFactor
provider_slug: secondfactor
slug: secondfactor-data-license
source_date: '2026-11-10'
source_filename: secondfactor-data-license.yml
source_heading: Data License
source_page: https://secondfactor.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SecondFactor\naid: secondfactor\nurl: https://secondfactor.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Use of the Services requires a positive credit balance.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: You retain all rights to your own Customer Application, your own data, and the content you transmit through\n    it. You grant us a limited license to process the data you submit (including End User Data) solely to provide\n    the Services to you, as described in our Privacy Policy.\nattribution:\n  required: null\n  text:\
  \ null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/secondfactor/data-license/secondfactor-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from SecondFactor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- OTP
- Authentication
- Multi-Channel
- Messaging
---
