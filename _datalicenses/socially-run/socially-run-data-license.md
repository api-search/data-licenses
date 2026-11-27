---
api_specs:
- filename: socially-run-attributions-api-openapi.yml
  format: yaml
  label: socially-run Attributions API
  slug: socially-run-attributions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-attributions-api-openapi.yml
- filename: socially-run-dossiers-api-openapi.yml
  format: yaml
  label: socially-run Dossiers API
  slug: socially-run-dossiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-dossiers-api-openapi.yml
- filename: socially-run-emails-api-openapi.yml
  format: yaml
  label: socially-run Emails API
  slug: socially-run-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-emails-api-openapi.yml
- filename: socially-run-jobs-api-openapi.yml
  format: yaml
  label: socially-run Jobs API
  slug: socially-run-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-jobs-api-openapi.yml
- filename: socially-run-platforms-api-openapi.yml
  format: yaml
  label: socially-run Platforms API
  slug: socially-run-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-platforms-api-openapi.yml
- filename: socially-run-posts-api-openapi.yml
  format: yaml
  label: socially-run Posts API
  slug: socially-run-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-posts-api-openapi.yml
- filename: socially-run-profiles-api-openapi.yml
  format: yaml
  label: socially-run Profiles API
  slug: socially-run-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-profiles-api-openapi.yml
- filename: socially-run-resolve-api-openapi.yml
  format: yaml
  label: socially-run Resolve API
  slug: socially-run-resolve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-resolve-api-openapi.yml
- filename: socially-run-search-api-openapi.yml
  format: yaml
  label: socially-run Search API
  slug: socially-run-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-search-api-openapi.yml
- filename: socially-run-trending-api-openapi.yml
  format: yaml
  label: socially-run Trending API
  slug: socially-run-trending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-trending-api-openapi.yml
- filename: socially-run-usage-api-openapi.yml
  format: yaml
  label: socially-run Usage API
  slug: socially-run-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-usage-api-openapi.yml
- filename: socially-run-usernames-api-openapi.yml
  format: yaml
  label: socially-run Usernames API
  slug: socially-run-usernames-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-usernames-api-openapi.yml
- filename: socially-run-web-api-openapi.yml
  format: yaml
  label: socially-run Web API
  slug: socially-run-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-web-api-openapi.yml
- filename: socially-run-webhooks-api-openapi.yml
  format: yaml
  label: socially-run Webhooks API
  slug: socially-run-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: null
    text: The username database is built from open-source projects credited at /v1/attributions and on our data and retention page
  data:
    license: custom
    stance_commercial: unstated
    text: the parts under CC BY-SA 4.0 stay under that license.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: The results are yours to use within the acceptable use policy; the public data inside them belongs to the people who published it.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: socially-run
output_license: custom
provenance_date: '2026-11-10'
provider_name: socially-run
provider_slug: socially-run
slug: socially-run-data-license
source_date: '2026-11-10'
source_filename: socially-run-data-license.yml
source_heading: Data License
source_page: https://socially.run/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: socially-run\naid: socially-run\nurl: https://socially.run/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: The results are yours to use within the acceptable use policy; the public data inside them belongs to the\n    people who published it.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: the parts under CC BY-SA 4.0 stay under that license.\nattribution:\n  required: null\n  text: The username database is built from open-source projects credited at /v1/attributions and on our data and\n    retention page\ninterface_license:\n  url:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/socially-run/data-license/socially-run-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from socially-run's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Data API
- JSON
- MCP
- AI Agents
---
