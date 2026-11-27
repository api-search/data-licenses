---
api_specs:
- filename: appmanai-com-app-metadata-api-openapi.yml
  format: yaml
  label: AppManAi App Metadata API
  slug: appmanai-com-app-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appmanai-com/openapi/appmanai-com-app-metadata-api-openapi.yml
- filename: appmanai-com-app-metrics-api-openapi.yml
  format: yaml
  label: AppManAi App Metrics API
  slug: appmanai-com-app-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appmanai-com/openapi/appmanai-com-app-metrics-api-openapi.yml
- filename: appmanai-com-app-reviews-api-openapi.yml
  format: yaml
  label: AppManAi App Reviews API
  slug: appmanai-com-app-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appmanai-com/openapi/appmanai-com-app-reviews-api-openapi.yml
- filename: appmanai-com-app-search-api-openapi.yml
  format: yaml
  label: AppManAi App Search API
  slug: appmanai-com-app-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appmanai-com/openapi/appmanai-com-app-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Resell, redistribute, or make the raw data available as a competing bulk-data or API product.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Subject to these Terms and your payment of applicable fees, we grant you a limited, non-exclusive, non-transferable, revocable license to access the Service and use the data internally in your own products and workflows.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AppManAi
output_license: custom
provenance_date: '2026-11-09'
provider_name: AppManAi
provider_slug: appmanai-com
slug: appmanai-com-data-license
source_date: '2026-11-09'
source_filename: appmanai-com-data-license.yml
source_heading: Data License
source_page: https://appmanai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AppManAi\naid: appmanai-com\nurl: https://appmanai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Subject to these Terms and your payment of applicable fees, we grant you a limited, non-exclusive, non-transferable,\n    revocable license to access the Service and use the data internally in your own products and workflows.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Resell, redistribute, or make the raw data available as a competing bulk-data or API product.\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/appmanai-com/data-license/appmanai-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from AppManAi's own page on 2026-11-09.
synthetic: false
tags:
- App Store Data
- Google Play Data
- ASO
- Data API
- App Intelligence
---
