---
api_specs:
- filename: allspice-io-repos-api-openapi.yml
  format: yaml
  label: AllSpice.io Repos API
  slug: allspice-io-repos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allspice-io/openapi/allspice-io-repos-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Customer grants AllSpice a limited license during each Subscription Period to use Customer Data as provided for in this Section 5(a)
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Customer owns and retains all right, title, and interest in and to the Customer Data and AI Output.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AllSpice.io
output_license: custom
provenance_date: '2026-11-09'
provider_name: AllSpice.io
provider_slug: allspice-io
slug: allspice-io-data-license
source_date: '2026-11-09'
source_filename: allspice-io-data-license.yml
source_heading: Data License
source_page: https://allspice.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AllSpice.io\naid: allspice-io\nurl: https://allspice.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Customer owns and retains all right, title, and interest in and to the Customer Data and AI Output.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Customer grants AllSpice a limited license during each Subscription Period to use Customer Data as provided\n    for in this Section 5(a)\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/allspice-io/data-license/allspice-io-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from AllSpice.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hardware
- Collaboration
- Artificial Intelligence
- Design
---
