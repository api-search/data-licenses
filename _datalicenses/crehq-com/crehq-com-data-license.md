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
    text: Resell, redistribute, or sublicense CREHQ data to third parties without our written consent
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Export data as permitted by your subscription tier for your internal business use
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: CREHQ
output_license: custom
provenance_date: '2026-11-09'
provider_name: CREHQ
provider_slug: crehq-com
slug: crehq-com-data-license
source_date: '2026-11-09'
source_filename: crehq-com-data-license.yml
source_heading: Data License
source_page: https://crehq.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: CREHQ\naid: crehq-com\nurl: https://crehq.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://crehq.com/license-terms/\n  - https://crehq.com/terms/\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Export data as permitted by your subscription tier for your internal business use\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Resell, redistribute, or sublicense CREHQ data to third parties without our written consent\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/crehq-com/data-license/crehq-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from CREHQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commercial Real Estate
- Location Intelligence
- Location Data
- Datasets
- Franchise Data
- Site Selection
- MCP
- Data Licensing
---
