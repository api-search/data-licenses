---
api_specs:
- filename: rainbow-ai-nowcast-api-openapi.yml
  format: yaml
  label: Rainbow.AI Nowcast API
  slug: rainbow-ai-nowcast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow-ai/openapi/rainbow-ai-nowcast-api-openapi.yml
- filename: rainbow-ai-radar-api-openapi.yml
  format: yaml
  label: Rainbow.AI Radar API
  slug: rainbow-ai-radar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow-ai/openapi/rainbow-ai-radar-api-openapi.yml
- filename: rainbow-ai-snapshots-api-openapi.yml
  format: yaml
  label: Rainbow.AI Snapshots API
  slug: rainbow-ai-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow-ai/openapi/rainbow-ai-snapshots-api-openapi.yml
- filename: rainbow-ai-tiles-api-openapi.yml
  format: yaml
  label: Rainbow.AI Tiles API
  slug: rainbow-ai-tiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow-ai/openapi/rainbow-ai-tiles-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Attribution is required whenever API Data or insights derived from it are shown to end users or the public.
  data:
    license: custom
    stance_commercial: conditional
    text: All rights, title, and interest in and to the Rainbow.ai API and API Data remain with the Company and its licensors. No ownership of any intellectual property is transferred to you
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: You may use the API and API Data in both personal and commercial projects. This includes internal business use and incorporation of API Data into products or services that you offer to end users or customers.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Rainbow.AI
output_license: custom
provenance_date: '2026-11-10'
provider_name: Rainbow.AI
provider_slug: rainbow-ai
slug: rainbow-ai-data-license
source_date: '2026-11-10'
source_filename: rainbow-ai-data-license.yml
source_heading: Data License
source_page: https://developer.rainbow.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Rainbow.AI\naid: rainbow-ai\nurl: https://developer.rainbow.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: You may use the API and API Data in both personal and commercial projects. This includes internal business\n    use and incorporation of API Data into products or services that you offer to end users or customers.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: All rights, title, and interest in and to the Rainbow.ai API and API Data remain with the Company and its\n    licensors. No ownership of any intellectual property\
  \ is transferred to you\nattribution:\n  required: true\n  text: Attribution is required whenever API Data or insights derived from it are shown to end users or the public.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/rainbow-ai/data-license/rainbow-ai-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Rainbow.AI's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Precipitation
- Forecasting
- Nowcast
- Radar
- Tiles
- Geospatial
---
