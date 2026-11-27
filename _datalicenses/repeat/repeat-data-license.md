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
    text: You will only use the Services for your own internal, non-commercial use, and not on behalf of or for the benefit of any third party
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Repeat may use, sell, and share de-identified and aggregated data that is derived from the End Customer Data (“Derived Data”) without compensation to you for Repeat’s own business purposes.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Repeat
output_license: custom
provenance_date: '2026-11-10'
provider_name: Repeat
provider_slug: repeat
slug: repeat-data-license
source_date: '2026-11-10'
source_filename: repeat-data-license.yml
source_heading: Data License
source_page: https://getrepeat.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Repeat\naid: repeat\nurl: https://getrepeat.io/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Repeat may use, sell, and share de-identified and aggregated data that is derived from the End Customer\n    Data (“Derived Data”) without compensation to you for Repeat’s own business purposes.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You will only use the Services for your own internal, non-commercial use, and not on behalf of or for the\n    benefit of any third party\nattribution:\n  required: null\n  text: null\n\
  interface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/repeat/data-license/repeat-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Repeat's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Lifecycle Marketing
- Retention
- E-Commerce
- Customer Data
- Shopify
- Consumer Packaged Goods
---
