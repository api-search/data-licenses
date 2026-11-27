---
api_specs:
- filename: graphiql
  format: yaml
  label: SanAPI
  slug: sanapi
  spec_type: OpenAPI
  url: https://api.santiment.net/graphiql
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Nothing in these T&C gives You the right to make copies of the Services or of any portion thereof.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: In case that You wish to resell Santiment’s Data to third parties, a corporate subscription is required.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Santiment
output_license: custom
provenance_date: '2026-11-10'
provider_name: Santiment
provider_slug: santiment
slug: santiment-data-license
source_date: '2026-11-10'
source_filename: santiment-data-license.yml
source_heading: Data License
source_page: https://santiment.net/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Santiment\naid: santiment\nurl: https://santiment.net/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: In case that You wish to resell Santiment’s Data to third parties, a corporate subscription is required.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Nothing in these T&C gives You the right to make copies of the Services or of any portion thereof.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/santiment/data-license/santiment-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Santiment's own page on 2026-11-10.
synthetic: false
tags:
- Cryptocurrency
- Blockchain
- Market Intelligence
- On-Chain Metrics
- Social Sentiment
- Developer Activity
- Analytics
- GraphQL
---
