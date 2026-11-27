---
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: provided that Licensee conspicuously attributes Chainalysis as the source within the same medium of such conclusions.
  data:
    license: custom
    stance_commercial: conditional
    text: export Chainalysis Data in bulk, or extract or otherwise use data from the Services except as made available as part of the Services’ normal functions
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Deliverables may only be used by Licensee in connection with its investigation of illicit activities.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Chainalysis
output_license: custom
provenance_date: '2026-11-09'
provider_name: Chainalysis
provider_slug: chainalysis
slug: chainalysis-data-license
source_date: '2026-11-09'
source_filename: chainalysis-data-license.yml
source_heading: Data License
source_page: https://www.chainalysis.com/msa1023/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Chainalysis\naid: chainalysis\nurl: https://www.chainalysis.com/msa1023/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Deliverables may only be used by Licensee in connection with its investigation of illicit activities.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: export Chainalysis Data in bulk, or extract or otherwise use data from the Services except as made available\n    as part of the Services’ normal functions\nattribution:\n  required: true\n  text: provided that Licensee conspicuously attributes Chainalysis as the source within\
  \ the same medium of such\n    conclusions.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/chainalysis/data-license/chainalysis-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Chainalysis's own page on 2026-11-09.
synthetic: false
tags:
- Compliance
- AML
- Transaction Monitoring
- Sanctions
- Investigations
- Blockchain Analytics
- Risk Management
- Cryptocurrency
---
