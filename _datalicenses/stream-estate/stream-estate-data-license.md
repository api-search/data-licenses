---
api_specs:
- filename: stream-estate-indicators-api-openapi.yml
  format: yaml
  label: stream-estate Indicators API
  slug: stream-estate-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stream-estate/openapi/stream-estate-indicators-api-openapi.yml
- filename: stream-estate-properties-api-openapi.yml
  format: yaml
  label: stream-estate Properties API
  slug: stream-estate-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stream-estate/openapi/stream-estate-properties-api-openapi.yml
- filename: stream-estate-searches-api-openapi.yml
  format: yaml
  label: stream-estate Searches API
  slug: stream-estate-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stream-estate/openapi/stream-estate-searches-api-openapi.yml
- filename: stream-estate-webhooks-api-openapi.yml
  format: yaml
  label: stream-estate Webhooks API
  slug: stream-estate-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stream-estate/openapi/stream-estate-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Resell or sublicense the data made available through the Service as such, republish the data feed in bulk in a substantially unmodified form, or use the Service or its data to provide a competing data API or data product.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: display data obtained through the Service in your own applications and products to your direct users; create analyses, statistics, and other derived insights from the data
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: stream-estate
output_license: custom
provenance_date: '2026-11-10'
provider_name: stream-estate
provider_slug: stream-estate
slug: stream-estate-data-license
source_date: '2026-11-10'
source_filename: stream-estate-data-license.yml
source_heading: Data License
source_page: https://stream.estate/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: stream-estate\naid: stream-estate\nurl: https://stream.estate/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: display data obtained through the Service in your own applications and products to your direct users; create\n    analyses, statistics, and other derived insights from the data\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Resell or sublicense the data made available through the Service as such, republish the data feed in bulk\n    in a substantially unmodified form, or use the Service or its data to provide a competing data\
  \ API or data product.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/stream-estate/data-license/stream-estate-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from stream-estate's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- PropTech
- Data API
- Market Analytics
- Valuation
---
