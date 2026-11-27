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
    text: All data and individual entries made on the Solution by each User remain the property of this User.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Apart from the Scorecard, the other Assessment Results are not included in the aforementioned license and may only be used for internal purposes by the Assessed company.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: CyberVadis
output_license: custom
provenance_date: '2026-11-09'
provider_name: CyberVadis
provider_slug: cybervadis
slug: cybervadis-data-license
source_date: '2026-11-09'
source_filename: cybervadis-data-license.yml
source_heading: Data License
source_page: https://app.cybervadis.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: CyberVadis\naid: cybervadis\nurl: https://app.cybervadis.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Apart from the Scorecard, the other Assessment Results are not included in the aforementioned license and\n    may only be used for internal purposes by the Assessed company.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: All data and individual entries made on the Solution by each User remain the property of this User.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/cybervadis/data-license/cybervadis-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from CyberVadis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Third-Party Risk Management
- Security Ratings
- Governance Risk Compliance
- Infrastructure Saas
---
