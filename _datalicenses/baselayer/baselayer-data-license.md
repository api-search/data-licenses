---
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Customer may not resell, share, disclose, modify or create derivative works from Baselayer Data
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Customer may summarize it and include it in Customer’s own internal work product, such as memos, reports and decision records. This is still limited to Customer’s internal business purposes
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Baselayer
output_license: custom
provenance_date: '2026-11-09'
provider_name: Baselayer
provider_slug: baselayer
slug: baselayer-data-license
source_date: '2026-11-09'
source_filename: baselayer-data-license.yml
source_heading: Data License
source_page: https://baselayer.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Baselayer\naid: baselayer\nurl: https://baselayer.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Customer may summarize it and include it in Customer’s own internal work product, such as memos, reports\n    and decision records. This is still limited to Customer’s internal business purposes\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Customer may not resell, share, disclose, modify or create derivative works from Baselayer Data\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/baselayer/data-license/baselayer-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Baselayer's own page on 2026-11-09.
synthetic: false
tags:
- Business
- Identity Verification
- Risk Management
- Fintech
---
