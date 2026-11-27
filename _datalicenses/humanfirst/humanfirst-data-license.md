---
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Customer must quote or attribute Licensed Data and other information provided to Customer by ICON in Customer's external publications
  data:
    license: custom
    stance_commercial: prohibited
    text: ICON shall retain all right, title, and interest in and to the Licensed Data, HumanFirst Platform and Solutions
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: (j) use the Licensed Data or HumanFirst Platform (or any portion thereof) for commercial time-sharing or service-bureau use, to create similar or competitive products or services, or for any purpose other than its own internal use
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: HumanFirst
output_license: custom
provenance_date: '2026-11-09'
provider_name: HumanFirst
provider_slug: humanfirst
slug: humanfirst-data-license
source_date: '2026-11-09'
source_filename: humanfirst-data-license.yml
source_heading: Data License
source_page: https://www.gohumanfirst.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: HumanFirst\naid: humanfirst\nurl: https://www.gohumanfirst.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: (j) use the Licensed Data or HumanFirst Platform (or any portion thereof) for commercial time-sharing or\n    service-bureau use, to create similar or competitive products or services, or for any purpose other than its\n    own internal use\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: ICON shall retain all right, title, and interest in and to the Licensed Data, HumanFirst Platform and Solutions\nattribution:\n\
  \  required: true\n  text: Customer must quote or attribute Licensed Data and other information provided to Customer by ICON in Customer's\n    external publications\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/humanfirst/data-license/humanfirst-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from HumanFirst's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Clinical Research
- Digital Health
- Digital Biomarkers
- Wearables
- Clinical Trials
- Real-World Evidence
---
