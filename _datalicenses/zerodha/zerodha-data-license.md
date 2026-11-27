---
api_specs:
- filename: zerodha-alerts-api-openapi.yml
  format: yaml
  label: Zerodha Alerts API
  slug: zerodha-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-alerts-api-openapi.yml
- filename: zerodha-gtt-api-openapi.yml
  format: yaml
  label: Zerodha Gtt API
  slug: zerodha-gtt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-gtt-api-openapi.yml
- filename: zerodha-orders-api-openapi.yml
  format: yaml
  label: Zerodha Orders API
  slug: zerodha-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-orders-api-openapi.yml
- filename: zerodha-portfolio-api-openapi.yml
  format: yaml
  label: Zerodha Portfolio API
  slug: zerodha-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-portfolio-api-openapi.yml
- filename: zerodha-session-api-openapi.yml
  format: yaml
  label: Zerodha Session API
  slug: zerodha-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-session-api-openapi.yml
- filename: zerodha-trades-api-openapi.yml
  format: yaml
  label: Zerodha Trades API
  slug: zerodha-trades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-trades-api-openapi.yml
- filename: zerodha-user-api-openapi.yml
  format: yaml
  label: Zerodha User API
  slug: zerodha-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-user-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: By no means is any proprietary right or license in any intellectual property impliedly or expressly granted by Zerodha to the Client or any other user of the Platform
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: The Client agrees to use real-time price data shared with them via any of our platforms, only for the purpose of using the platform and activities that can be undertaken on our platforms.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Zerodha
output_license: custom
provenance_date: '2026-11-10'
provider_name: Zerodha
provider_slug: zerodha
slug: zerodha-data-license
source_date: '2026-11-10'
source_filename: zerodha-data-license.yml
source_heading: Data License
source_page: https://zerodha.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Zerodha\naid: zerodha\nurl: https://zerodha.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: The Client agrees to use real-time price data shared with them via any of our platforms, only for the purpose\n    of using the platform and activities that can be undertaken on our platforms.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: By no means is any proprietary right or license in any intellectual property impliedly or expressly granted\n    by Zerodha to the Client or any other user of the Platform\n\
  attribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/zerodha/data-license/zerodha-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Zerodha's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Trading
- Fintech
---
