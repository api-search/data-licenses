---
api_specs:
- filename: tavily-crawl-api-openapi.yml
  format: yaml
  label: Tavily Crawl API
  slug: tavily-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-crawl-api-openapi.yml
- filename: tavily-extract-api-openapi.yml
  format: yaml
  label: Tavily Extract API
  slug: tavily-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-extract-api-openapi.yml
- filename: tavily-map-api-openapi.yml
  format: yaml
  label: Tavily Map API
  slug: tavily-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-map-api-openapi.yml
- filename: tavily-research-api-openapi.yml
  format: yaml
  label: Tavily Research API
  slug: tavily-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-research-api-openapi.yml
- filename: tavily-search-api-openapi.yml
  format: yaml
  label: Tavily Search API
  slug: tavily-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-search-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Tavily owns and will continue to own all rights, title, and interest, including any and all intellectual property rights, in and to the Services
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
name: Tavily
output_license: null
provenance_date: '2026-11-10'
provider_name: Tavily
provider_slug: tavily
slug: tavily-data-license
source_date: '2026-11-10'
source_filename: tavily-data-license.yml
source_heading: Data License
source_page: https://www.tavily.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Tavily\naid: tavily\nurl: https://www.tavily.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Tavily owns and will continue to own all rights, title, and interest, including any and all intellectual\n    property rights, in and to the Services\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tavily/data-license/tavily-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Tavily's own page on 2026-11-10.
synthetic: false
tags:
- Search
- Web Search
- AI Agents
- LLM
- Extract
- Crawl
- Sitemap
- Research
- REST
- LangChain
- LlamaIndex
- Real-Time
- A2A
---
