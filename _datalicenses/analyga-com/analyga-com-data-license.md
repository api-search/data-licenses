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
    text: You grant us a limited licence to host, process, and transmit Your Data solely to provide the Service.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: You retain all rights to the analytics data you collect through the Service ("Your Data").
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: analyga
output_license: custom
provenance_date: '2026-11-09'
provider_name: analyga
provider_slug: analyga-com
slug: analyga-com-data-license
source_date: '2026-11-09'
source_filename: analyga-com-data-license.yml
source_heading: Data License
source_page: https://analyga.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: analyga\naid: analyga-com\nurl: https://analyga.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: You retain all rights to the analytics data you collect through the Service (\"Your Data\").\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You grant us a limited licence to host, process, and transmit Your Data solely to provide the Service.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/analyga-com/data-license/analyga-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from analyga's own page on 2026-11-09.
synthetic: false
tags:
- AI-native
- Software-as-a-Service
- Revenue Analytics
- Dashboards
- MCP
---
