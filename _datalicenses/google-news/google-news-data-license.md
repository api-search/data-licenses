---
api_specs:
- filename: google-news-headlines-api-openapi.yml
  format: yaml
  label: Google News RSS Headlines API
  slug: google-news-headlines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-news/openapi/google-news-headlines-api-openapi.yml
- filename: google-news-search-api-openapi.yml
  format: yaml
  label: Google News RSS Search API
  slug: google-news-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-news/openapi/google-news-search-api-openapi.yml
- filename: google-news-topics-api-openapi.yml
  format: yaml
  label: Google News RSS Topics API
  slug: google-news-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-news/openapi/google-news-topics-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: You may use Google’s content as allowed by these terms and any service-specific additional terms , but we retain any intellectual property rights that we have in our content.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: null
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Google News RSS
output_license: null
provenance_date: '2026-11-09'
provider_name: Google News RSS
provider_slug: google-news
slug: google-news-data-license
source_date: '2026-11-09'
source_filename: google-news-data-license.yml
source_heading: Data License
source_page: https://policies.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Google News RSS\naid: google-news\nurl: https://policies.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: You may use Google’s content as allowed by these terms and any service-specific additional terms , but we\n    retain any intellectual property rights that we have in our content.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/google-news/data-license/google-news-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Google News RSS's own page on 2026-11-09.
synthetic: false
tags:
- Aggregation
- Google News
- Headlines
- Media
- News
- RSS
---
