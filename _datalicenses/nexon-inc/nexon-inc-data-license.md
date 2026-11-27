---
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You shall clearly and conspicuously identify Nexon in Your Application as the source of the Nexon Game Data
  data:
    license: custom
    stance_commercial: prohibited
    text: The Nexon Game Data is for Your personal use to enhance the experience of the players of Nexon’s games and you are not allowed to sell, license or otherwise transfer the Nexon Game Data to any third party.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: Without Nexon’s prior written agreement, use of the Nexon API Services for commercial purposes is not permitted, whether compensated or not.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Nexon
output_license: custom
provenance_date: '2026-11-10'
provider_name: Nexon
provider_slug: nexon-inc
slug: nexon-inc-data-license
source_date: '2026-11-10'
source_filename: nexon-inc-data-license.yml
source_heading: Data License
source_page: https://openapi.nexon.com/support/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Nexon\naid: nexon-inc\nurl: https://openapi.nexon.com/support/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: Without Nexon’s prior written agreement, use of the Nexon API Services for commercial purposes is not permitted,\n    whether compensated or not.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: The Nexon Game Data is for Your personal use to enhance the experience of the players of Nexon’s games and\n    you are not allowed to sell, license or otherwise transfer the Nexon Game Data to any third party.\nattribution:\n  required:\
  \ true\n  text: You shall clearly and conspicuously identify Nexon in Your Application as the source of the Nexon Game Data\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/nexon-inc/data-license/nexon-inc-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Nexon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Gaming
- Video Games
- Game Data
- Developer API
- OpenAPI
---
