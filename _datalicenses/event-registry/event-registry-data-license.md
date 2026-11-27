---
api_specs:
- filename: event-registry-articles-api-openapi.yml
  format: yaml
  label: Event Registry Articles API
  slug: event-registry-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-articles-api-openapi.yml
- filename: event-registry-events-api-openapi.yml
  format: yaml
  label: Event Registry Events API
  slug: event-registry-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-events-api-openapi.yml
- filename: event-registry-suggest-api-openapi.yml
  format: yaml
  label: Event Registry Suggest API
  slug: event-registry-suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-suggest-api-openapi.yml
- filename: event-registry-topic-pages-api-openapi.yml
  format: yaml
  label: Event Registry Topic Pages API
  slug: event-registry-topic-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-topic-pages-api-openapi.yml
- filename: event-registry-usage-api-openapi.yml
  format: yaml
  label: Event Registry Usage API
  slug: event-registry-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: false
    text: Attribution to Event Registry is not required.
  data:
    license: custom
    stance_commercial: conditional
    text: By subscribing to a paid plan, you are granted a limited, non-exclusive, non-transferable, and revocable license to access and use Event Registry data for commercial purposes, provided that all use complies with third-party copyright and intellectual property laws.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: What you create from the data (labels, statistics, summaries, models, reports) is yours.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Event Registry
output_license: custom
provenance_date: '2026-11-09'
provider_name: Event Registry
provider_slug: event-registry
slug: event-registry-data-license
source_date: '2026-11-09'
source_filename: event-registry-data-license.yml
source_heading: Data License
source_page: https://newsapi.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Event Registry\naid: event-registry\nurl: https://newsapi.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://github.com/EventRegistry/newsapi-mcp/blob/main/LICENSE\n  - https://newsapi.ai/terms\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: What you create from the data (labels, statistics, summaries, models, reports) is yours.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: By subscribing to a paid plan, you are granted a limited, non-exclusive, non-transferable, and revocable\n    license to access and use Event Registry data for commercial purposes, provided\
  \ that all use complies with third-party\n    copyright and intellectual property laws.\nattribution:\n  required: false\n  text: Attribution to Event Registry is not required.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/event-registry/data-license/event-registry-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Event Registry's own page on 2026-11-09.
synthetic: false
tags:
- News
- Media Monitoring
- News Intelligence
- Event Detection
- Named Entity Recognition
- Sentiment Analysis
- Media Analytics
- News API
---
