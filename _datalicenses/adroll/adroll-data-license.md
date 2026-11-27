---
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: NextRoll owns or controls all right, title and interest in and to the Services, Service Data, Performance Reports, and NextRoll Materials
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: Customer is permitted to use Performance Reports for its own internal business purposes, including after expiration or termination of this Agreement.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AdRoll
output_license: custom
provenance_date: '2026-11-09'
provider_name: AdRoll
provider_slug: adroll
slug: adroll-data-license
source_date: '2026-11-09'
source_filename: adroll-data-license.yml
source_heading: Data License
source_page: https://www.nextroll.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AdRoll\naid: adroll\nurl: https://www.nextroll.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.nextroll.com/terms\n  - https://www.nextroll.com/terms/api\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: Customer is permitted to use Performance Reports for its own internal business purposes, including after\n    expiration or termination of this Agreement.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: NextRoll owns or controls all right, title and interest in and to the Services, Service Data, Performance\n    Reports, and NextRoll Materials\nattribution:\n\
  \  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/adroll/data-license/adroll-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from AdRoll's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Display Advertising
- Retargeting
- Marketing
- AdTech
- Programmatic
---
