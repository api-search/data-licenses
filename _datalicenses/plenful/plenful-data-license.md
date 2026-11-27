---
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Customer will continue to retain its ownership rights to all Service Data processed under the terms of this MSA and Plenful will own all Usage Data.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Plenful may use Service Data, including any protected health information included in Service Data (“PHI”), to generate outputs, recommendations, classifications, extractions, workflow actions and other features and functionality for Customer and Authorized Users within the Services.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Plenful
output_license: custom
provenance_date: '2026-11-10'
provider_name: Plenful
provider_slug: plenful
slug: plenful-data-license
source_date: '2026-11-10'
source_filename: plenful-data-license.yml
source_heading: Data License
source_page: https://www.plenful.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Plenful\naid: plenful\nurl: https://www.plenful.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Plenful may use Service Data, including any protected health information included in Service Data (“PHI”),\n    to generate outputs, recommendations, classifications, extractions, workflow actions and other features and\n    functionality for Customer and Authorized Users within the Services.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Customer will continue to retain its ownership rights to all Service Data processed under the terms\
  \ of this\n    MSA and Plenful will own all Usage Data.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/plenful/data-license/plenful-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Plenful's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Artificial Intelligence
- Workflow Automation
- Machine Learning
- 340B
- Prior Authorization
---
