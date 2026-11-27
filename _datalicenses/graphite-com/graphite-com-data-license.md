---
api_specs:
- filename: graphite-com-authentication-api-openapi.yml
  format: yaml
  label: Graphite Authentication API
  slug: graphite-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/graphite-com/openapi/graphite-com-authentication-api-openapi.yml
- filename: graphite-com-github-app-api-openapi.yml
  format: yaml
  label: Graphite GitHub App API
  slug: graphite-com-github-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/graphite-com/openapi/graphite-com-github-app-api-openapi.yml
- filename: graphite-com-merge-queue-api-openapi.yml
  format: yaml
  label: Graphite Merge Queue API
  slug: graphite-com-merge-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/graphite-com/openapi/graphite-com-merge-queue-api-openapi.yml
- filename: graphite-com-stacks-api-openapi.yml
  format: yaml
  label: Graphite Stacks API
  slug: graphite-com-stacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/graphite-com/openapi/graphite-com-stacks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Graphite owns all right, title, and interest in and to (a) the Services (including the Graphite CLI and the Graphite Platform, including the design and layout of its dashboard), (b) the Usage Data, and (c) the Documentation
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Customer retains all ownership rights in Input and Customer owns all Output, and Graphite hereby assigns to Customer all of Graphite’s right, title, and interest, if any, in and to Output.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Graphite
output_license: custom
provenance_date: '2026-11-09'
provider_name: Graphite
provider_slug: graphite-com
slug: graphite-com-data-license
source_date: '2026-11-09'
source_filename: graphite-com-data-license.yml
source_heading: Data License
source_page: https://graphite.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Graphite\naid: graphite-com\nurl: https://graphite.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Customer retains all ownership rights in Input and Customer owns all Output, and Graphite hereby assigns\n    to Customer all of Graphite’s right, title, and interest, if any, in and to Output.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Graphite owns all right, title, and interest in and to (a) the Services (including the Graphite CLI and\n    the Graphite Platform, including the design and layout of\
  \ its dashboard), (b) the Usage Data, and (c) the Documentation\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/graphite-com/data-license/graphite-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Graphite's own page on 2026-11-09.
synthetic: false
tags:
- Code Review
- Stacked PRs
- merge-queue
- AI Code Review
- Developer Tools
- GitHub
---
