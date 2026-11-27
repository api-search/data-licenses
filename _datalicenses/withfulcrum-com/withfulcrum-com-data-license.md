---
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Customer grants Fulcrum a non-exclusive, worldwide, royalty-free license to access, use, host, copy, process, transmit, display, and create technical or operational derivatives of Customer Data as necessary to provide, secure, support, maintain, and improve the Services
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: Customer shall not resell, redistribute, publish, share, or provide access to Output Data to any third party except as expressly permitted in the Agreement or with Fulcrum’s prior written consent.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Fulcrum
output_license: custom
provenance_date: '2026-11-10'
provider_name: Fulcrum
provider_slug: withfulcrum-com
slug: withfulcrum-com-data-license
source_date: '2026-11-10'
source_filename: withfulcrum-com-data-license.yml
source_heading: Data License
source_page: https://www.withfulcrum.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Fulcrum\naid: withfulcrum-com\nurl: https://www.withfulcrum.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: Customer shall not resell, redistribute, publish, share, or provide access to Output Data to any third party\n    except as expressly permitted in the Agreement or with Fulcrum’s prior written consent.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Customer grants Fulcrum a non-exclusive, worldwide, royalty-free license to access, use, host, copy, process,\n    transmit, display, and create technical or operational\
  \ derivatives of Customer Data as necessary to provide,\n    secure, support, maintain, and improve the Services\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/withfulcrum-com/data-license/withfulcrum-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Fulcrum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Integration
- Platform
---
