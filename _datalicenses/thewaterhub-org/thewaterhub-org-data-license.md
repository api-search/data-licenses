---
api_specs:
- filename: openapi.json
  format: json
  label: The Water Hub API
  slug: thewaterhub-api
  spec_type: OpenAPI
  url: https://thewaterhub.org/openapi.json
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: Quote figures with the brand name, the date shown, and a link back to the page you took them from.
  data:
    license: custom
    stance_commercial: conditional
    text: The Water Hub System Pricing Index is free to reuse with citation.
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
name: thewaterhub-org
output_license: null
provenance_date: '2026-11-10'
provider_name: thewaterhub-org
provider_slug: thewaterhub-org
slug: thewaterhub-org-data-license
source_date: '2026-11-10'
source_filename: thewaterhub-org-data-license.yml
source_heading: Data License
source_page: https://thewaterhub.org/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: thewaterhub-org\naid: thewaterhub-org\nurl: https://thewaterhub.org/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: The Water Hub System Pricing Index is free to reuse with citation.\nattribution:\n  required: true\n  text: Quote figures with the brand name, the date shown, and a link back to the page you took them from.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/thewaterhub-org/data-license/thewaterhub-org-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from thewaterhub-org's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Water
- Pricing
- Datasets
---
