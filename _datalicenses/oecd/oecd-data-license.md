---
api_specs:
- filename: oecd-data-api-openapi.yml
  format: yaml
  label: OECD Data API
  slug: oecd-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oecd/openapi/oecd-data-api-openapi.yml
- filename: oecd-structure-api-openapi.yml
  format: yaml
  label: OECD Structure API
  slug: oecd-structure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oecd/openapi/oecd-structure-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: The OECD makes data (the “Data”) available for use and consultation by the public.
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
name: OECD
output_license: null
provenance_date: '2026-11-10'
provider_name: OECD
provider_slug: oecd
slug: oecd-data-license
source_date: '2026-11-10'
source_filename: oecd-data-license.yml
source_heading: Data License
source_page: https://www.oecd.org/en/about/terms-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: OECD\naid: oecd\nurl: https://www.oecd.org/en/about/terms-conditions.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: The OECD makes data (the “Data”) available for use and consultation by the public.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/oecd/data-license/oecd-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from OECD's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Statistics
- Economics
- SDMX
---
