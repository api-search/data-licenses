---
api_specs:
- filename: scavio-openapi-generated.yml
  format: yaml
  label: Scavio API
  slug: scavio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scavio/openapi/_ae-authored/scavio-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: You retain ownership of your Customer Data.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: Search results returned by the API originate from third-party platforms. You are responsible for complying with those platforms' terms of service when using the data.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Scavio
output_license: null
provenance_date: '2026-11-10'
provider_name: Scavio
provider_slug: scavio
slug: scavio-data-license
source_date: '2026-11-10'
source_filename: scavio-data-license.yml
source_heading: Data License
source_page: https://scavio.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Scavio\naid: scavio\nurl: https://scavio.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: Search results returned by the API originate from third-party platforms. You are responsible for complying\n    with those platforms' terms of service when using the data.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: You retain ownership of your Customer Data.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/scavio/data-license/scavio-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Scavio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data
- Artificial Intelligence
---
