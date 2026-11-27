---
api_specs:
- filename: databutler-dev-openapi-generated.yml
  format: yaml
  label: databutler-dev API
  slug: databutler-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databutler-dev/openapi/_ae-authored/databutler-dev-openapi-generated.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Quote and republish answers, with a link to the answer's cite.url or to databutler.dev.
  data:
    license: null
    stance_commercial: conditional
    text: Use the data commercially, subject to each figure's upstream licence, which every answer names (for example the Open Government Licence for gov.uk figures, Licence Ouverte for French data, MIT for endoflife.date).
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Use the data commercially, subject to each figure's upstream licence, which every answer names
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: databutler-dev
output_license: custom
provenance_date: '2026-11-09'
provider_name: databutler-dev
provider_slug: databutler-dev
slug: databutler-dev-data-license
source_date: '2026-11-09'
source_filename: databutler-dev-data-license.yml
source_heading: Data License
source_page: https://databutler.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: databutler-dev\naid: databutler-dev\nurl: https://databutler.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Use the data commercially, subject to each figure's upstream licence, which every answer names\ndata:\n  license: null\n  stance_commercial: conditional\n  text: Use the data commercially, subject to each figure's upstream licence, which every answer names (for example\n    the Open Government Licence for gov.uk figures, Licence Ouverte for French data, MIT for endoflife.date).\nattribution:\n  required: true\n  text: Quote and republish answers,\
  \ with a link to the answer's cite.url or to databutler.dev.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/databutler-dev/data-license/databutler-dev-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from databutler-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Tax
- Reference
---
