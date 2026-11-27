---
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Your Applications made available to end users must prominently display “Powered by Runway” and link to runway.com on applicable user interfaces
  data:
    license: custom
    stance_commercial: prohibited
    text: you shall not license, sell, rent, lease, transfer, assign, reproduce, distribute, host, or similarly exploit any Services except as permitted through the APIs
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Subject to your compliance with the Agreement, the Company does not restrict your commercial use of your Outputs.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Runway Financial
output_license: custom
provenance_date: '2026-11-10'
provider_name: Runway Financial
provider_slug: runway-com
slug: runway-com-data-license
source_date: '2026-11-10'
source_filename: runway-com-data-license.yml
source_heading: Data License
source_page: https://runway.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Runway Financial\naid: runway-com\nurl: https://runway.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Subject to your compliance with the Agreement, the Company does not restrict your commercial use of your\n    Outputs.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: you shall not license, sell, rent, lease, transfer, assign, reproduce, distribute, host, or similarly exploit\n    any Services except as permitted through the APIs\nattribution:\n  required: true\n  text: Your Applications made available to\
  \ end users must prominently display “Powered by Runway” and link to runway.com\n    on applicable user interfaces\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/runway-com/data-license/runway-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Runway Financial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Payments
---
