---
api_specs:
- filename: spoken-md-transcripts-api-openapi.yml
  format: yaml
  label: Podcast Transcripts API
  slug: podcast-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spoken-md/openapi/spoken-md-transcripts-api-openapi.yml
- filename: spoken-md-well-known-openapi.json
  format: json
  label: Podcast Transcripts API .well-known API
  slug: podcast-transcripts-api-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spoken-md/openapi/_original/spoken-md-well-known-openapi.json
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Redistribute raw transcripts as a standalone dataset or corpus, resell API access or credits, or use transcripts fetched from Spoken to build or train a competing transcript or podcast-data API.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Search them, analyse them, summarise them, quote passages from them in what you build and show those to your own users, publish the work you produce from them, and automate all of it.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: spoken-md
output_license: custom
provenance_date: '2026-11-10'
provider_name: spoken-md
provider_slug: spoken-md
slug: spoken-md-data-license
source_date: '2026-11-10'
source_filename: spoken-md-data-license.yml
source_heading: Data License
source_page: https://spoken.md/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: spoken-md\naid: spoken-md\nurl: https://spoken.md/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Search them, analyse them, summarise them, quote passages from them in what you build and show those to\n    your own users, publish the work you produce from them, and automate all of it.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Redistribute raw transcripts as a standalone dataset or corpus, resell API access or credits, or use transcripts\n    fetched from Spoken to build or train a competing transcript or podcast-data API.\n\
  attribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/spoken-md/data-license/spoken-md-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from spoken-md's own page on 2026-11-10.
synthetic: false
tags:
- Podcasts
- Transcripts
- Markdown
- Artificial Intelligence
---
