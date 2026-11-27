---
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: prohibited
    text: Customer may not access, use, download, modify, publish, transmit, participate in the transfer or sale of, reproduce, create new or derivative works from, distribute, perform, display (including framing and inline linking), communicate to the public or in any way exploit, any of the Service and Materials in whole or in part.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Customer retains all rights, title, and interest in and to the Customer Data. For the avoidance of doubt, as between Reforge and Customer, Customer will retain all right, title, and interest in all Customer Data and to all analyses created by Customer or Customer's authorized personnel using the Service.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Reforge
output_license: custom
provenance_date: '2026-11-10'
provider_name: Reforge
provider_slug: reforge
slug: reforge-data-license
source_date: '2026-11-10'
source_filename: reforge-data-license.yml
source_heading: Data License
source_page: https://www.reforge.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Reforge\naid: reforge\nurl: https://www.reforge.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Customer retains all rights, title, and interest in and to the Customer Data. For the avoidance of doubt,\n    as between Reforge and Customer, Customer will retain all right, title, and interest in all Customer Data and\n    to all analyses created by Customer or Customer's authorized personnel using the Service.\ndata:\n  license: null\n  stance_commercial: prohibited\n  text: Customer may not access, use, download, modify,\
  \ publish, transmit, participate in the transfer or sale of,\n    reproduce, create new or derivative works from, distribute, perform, display (including framing and inline linking),\n    communicate to the public or in any way exploit, any of the Service and Materials in whole or in part.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/reforge/data-license/reforge-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Reforge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Feature Flags
- Feature Management
- Dynamic Configuration
- Live Config
- Experimentation
- Developer Tools
- SDK
- Observability
---
