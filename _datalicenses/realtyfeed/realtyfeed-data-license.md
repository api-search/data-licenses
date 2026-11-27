---
api_specs:
- filename: realtyfeed-mls-router-postman.json
  format: json
  label: MLS Router API
  slug: mls-router-api
  spec_type: Postman
  url: https://artifacts.apis.io/realtyfeed/postman/realtyfeed-mls-router-postman.json
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Users are granted a limited, revocable license to use the Services
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: prohibited
    text: 'Users may not : Resell, redistribute, or misuse data'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: RealtyFeed
output_license: null
provenance_date: '2026-11-10'
provider_name: RealtyFeed
provider_slug: realtyfeed
slug: realtyfeed-data-license
source_date: '2026-11-10'
source_filename: realtyfeed-data-license.yml
source_heading: Data License
source_page: https://realtyfeed.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: RealtyFeed\naid: realtyfeed\nurl: https://realtyfeed.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: prohibited\n  text: 'Users may not : Resell, redistribute, or misuse data'\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Users are granted a limited, revocable license to use the Services\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/realtyfeed/data-license/realtyfeed-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from RealtyFeed's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- MLS
- RESO Web API
- OData
- IDX
- Property Data
---
