---
api_specs:
- filename: serpresult-com-account-api-openapi.yml
  format: yaml
  label: SerpResult Account API
  slug: serpresult-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-account-api-openapi.yml
- filename: serpresult-com-api-keys-api-openapi.yml
  format: yaml
  label: SerpResult API keys API
  slug: serpresult-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-api-keys-api-openapi.yml
- filename: serpresult-com-billing-api-openapi.yml
  format: yaml
  label: SerpResult Billing API
  slug: serpresult-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-billing-api-openapi.yml
- filename: serpresult-com-meta-api-openapi.yml
  format: yaml
  label: SerpResult Meta API
  slug: serpresult-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-meta-api-openapi.yml
- filename: serpresult-com-search-api-openapi.yml
  format: yaml
  label: SerpResult Search API
  slug: serpresult-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-search-api-openapi.yml
- filename: serpresult-com-usage-api-openapi.yml
  format: yaml
  label: SerpResult Usage API
  slug: serpresult-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: Results come from third-party search engines. Their content belongs to whoever published it
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: resell raw responses as a competing search results API
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SerpResult
output_license: null
provenance_date: '2026-11-10'
provider_name: SerpResult
provider_slug: serpresult-com
slug: serpresult-com-data-license
source_date: '2026-11-10'
source_filename: serpresult-com-data-license.yml
source_heading: Data License
source_page: https://www.serpresult.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SerpResult\naid: serpresult-com\nurl: https://www.serpresult.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: resell raw responses as a competing search results API\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Results come from third-party search engines. Their content belongs to whoever published it\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/serpresult-com/data-license/serpresult-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from SerpResult's own page on 2026-11-10.
synthetic: false
tags:
- Search
- SERP
- Data
- JSON
- Cloud
---
