---
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: keep the attribution text of every Source the Data came from, of every Dataset you use
  data:
    license: custom
    stance_commercial: conditional
    text: Subject to these terms, the Source licences and the licences of the Datasets, we grant you a non-exclusive, non-transferable licence to use the Data and the Datasets you receive through the Service
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: we grant you a non-exclusive, non-transferable licence to use the Data and the Datasets you receive through the Service, including in your own products and services and for commercial purposes.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AIS Trail
output_license: custom
provenance_date: '2026-11-09'
provider_name: AIS Trail
provider_slug: aistrail-com
slug: aistrail-com-data-license
source_date: '2026-11-09'
source_filename: aistrail-com-data-license.yml
source_heading: Data License
source_page: https://aistrail.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AIS Trail\naid: aistrail-com\nurl: https://aistrail.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: we grant you a non-exclusive, non-transferable licence to use the Data and the Datasets you receive through\n    the Service, including in your own products and services and for commercial purposes.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Subject to these terms, the Source licences and the licences of the Datasets, we grant you a non-exclusive,\n    non-transferable licence to use the Data and the Datasets you receive\
  \ through the Service\nattribution:\n  required: true\n  text: keep the attribution text of every Source the Data came from, of every Dataset you use\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/aistrail-com/data-license/aistrail-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from AIS Trail's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Maritime
- AIS
- Data
- Real-Time
---
