---
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
    stance_commercial: unstated
    text: You may use returned comparison results in your workflows.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: PayloadPier
output_license: custom
provenance_date: '2026-11-10'
provider_name: PayloadPier
provider_slug: payloadpier
slug: payloadpier-data-license
source_date: '2026-11-10'
source_filename: payloadpier-data-license.yml
source_heading: Data License
source_page: https://payloadpier.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: PayloadPier\naid: payloadpier\nurl: https://payloadpier.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: You may use returned comparison results in your workflows.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/payloadpier/data-license/payloadpier-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from PayloadPier's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pricing
- SupplierComparison
- Data Processing
---
