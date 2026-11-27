---
api_specs:
- filename: placer-account-info-api-openapi.yml
  format: yaml
  label: Placer Account Info API
  slug: placer-account-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-account-info-api-openapi.yml
- filename: placer-loyalty-reports-api-openapi.yml
  format: yaml
  label: Placer Loyalty Reports API
  slug: placer-loyalty-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-loyalty-reports-api-openapi.yml
- filename: placer-manage-pois-api-openapi.yml
  format: yaml
  label: Placer Manage POIs API
  slug: placer-manage-pois-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-manage-pois-api-openapi.yml
- filename: placer-ranking-reports-api-openapi.yml
  format: yaml
  label: Placer Ranking Reports API
  slug: placer-ranking-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-ranking-reports-api-openapi.yml
- filename: placer-retail-sales-reports-api-openapi.yml
  format: yaml
  label: Placer Retail Sales Reports API
  slug: placer-retail-sales-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-retail-sales-reports-api-openapi.yml
- filename: placer-trade-area-reports-api-openapi.yml
  format: yaml
  label: Placer Trade Area Reports API
  slug: placer-trade-area-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-trade-area-reports-api-openapi.yml
- filename: placer-visitor-journey-reports-api-openapi.yml
  format: yaml
  label: Placer Visitor Journey Reports API
  slug: placer-visitor-journey-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-visitor-journey-reports-api-openapi.yml
- filename: placer-visits-reports-api-openapi.yml
  format: yaml
  label: Placer Visits Reports API
  slug: placer-visits-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-visits-reports-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: you must include an attribution to Placer
  data:
    license: custom
    stance_commercial: prohibited
    text: You shall not distribute, sublicense, display, or otherwise provide to third parties any data provided by Placer
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: any data provided by Placer may be used solely for your internal business purposes.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Placer
output_license: custom
provenance_date: '2026-11-10'
provider_name: Placer
provider_slug: placer
slug: placer-data-license
source_date: '2026-11-10'
source_filename: placer-data-license.yml
source_heading: Data License
source_page: https://www.placer.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Placer\naid: placer\nurl: https://www.placer.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: any data provided by Placer may be used solely for your internal business purposes.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You shall not distribute, sublicense, display, or otherwise provide to third parties any data provided by\n    Placer\nattribution:\n  required: true\n  text: you must include an attribution to Placer\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/placer/data-license/placer-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Placer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Location Analytics
- Foot Traffic
- Geospatial
- Retail Analytics
- Real Estate
- Consumer Insights
- Data
---
