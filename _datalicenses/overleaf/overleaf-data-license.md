---
api_specs:
- filename: overleaf-openapi-generated.yml
  format: yaml
  label: Overleaf API
  slug: overleaf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overleaf/openapi/_ae-authored/overleaf-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Unless otherwise agreed in a Contract, the Service is provided for your own non-commercial, internal and personal use
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: as between you and us, you retain ownership of the Inputs and shall own Outputs, to the extent permitted by applicable law.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Overleaf
output_license: custom
provenance_date: '2026-11-10'
provider_name: Overleaf
provider_slug: overleaf
slug: overleaf-data-license
source_date: '2026-11-10'
source_filename: overleaf-data-license.yml
source_heading: Data License
source_page: https://www.overleaf.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Overleaf\naid: overleaf\nurl: https://www.overleaf.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: as between you and us, you retain ownership of the Inputs and shall own Outputs, to the extent permitted\n    by applicable law.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Unless otherwise agreed in a Contract, the Service is provided for your own non-commercial, internal and\n    personal use\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/overleaf/data-license/overleaf-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Overleaf's own page on 2026-11-10.
synthetic: false
tags:
- Collaboration
- LaTeX
- Cloud
- Academic
- Writing
- Company
---
