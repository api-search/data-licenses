---
api_specs:
- filename: searchapi-search-api-openapi.yml
  format: yaml
  label: SearchApi SERP API
  slug: searchapi-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-search-api-openapi.yml
- filename: searchapi-account-api-openapi.yml
  format: yaml
  label: SearchApi Account & Analytics API
  slug: searchapi-account-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-account-api-openapi.yml
- filename: searchapi-analytics-api-openapi.yml
  format: yaml
  label: SearchApi Analytics API
  slug: searchapi-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-analytics-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: null
    text: Falsify or delete any author attributions, legal notices, or other labels that indicate the origin or source of the material.
  data:
    license: null
    stance_commercial: unstated
    text: SearchApi gathers and generates specific Data by aggregating information from publicly available web pages using SearchApi’s proprietary technology.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: 'Unless required by law or explicitly allowed by the owner, you must not, and must not allow your end-users or others acting on your behalf, to engage in the following activities with the Data obtained from the API:'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SearchApi
output_license: null
provenance_date: '2026-11-10'
provider_name: SearchApi
provider_slug: searchapi
slug: searchapi-data-license
source_date: '2026-11-10'
source_filename: searchapi-data-license.yml
source_heading: Data License
source_page: https://www.searchapi.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SearchApi\naid: searchapi\nurl: https://www.searchapi.io/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: 'Unless required by law or explicitly allowed by the owner, you must not, and must not allow your end-users\n    or others acting on your behalf, to engage in the following activities with the Data obtained from the API:'\ndata:\n  license: null\n  stance_commercial: unstated\n  text: SearchApi gathers and generates specific Data by aggregating information from publicly available web pages\n    using SearchApi’s proprietary technology.\nattribution:\n\
  \  required: null\n  text: Falsify or delete any author attributions, legal notices, or other labels that indicate the origin or source\n    of the material.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/searchapi/data-license/searchapi-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from SearchApi's own page on 2026-11-10.
synthetic: false
tags:
- Search
- SERP
- Google Search
- Web Scraping
- Search data
- Market Intelligence
- SEO
- MCP
- Agent-Native
---
