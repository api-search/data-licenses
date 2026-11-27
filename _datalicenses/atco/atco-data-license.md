---
api_specs:
- filename: atco-query-api-openapi.yml
  format: yaml
  label: ATCO Query API
  slug: atco-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atco/openapi/atco-query-api-openapi.yml
- filename: atco-service-api-openapi.yml
  format: yaml
  label: ATCO Service API
  slug: atco-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atco/openapi/atco-service-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: You are granted a limited license only to display and print information contained on the ATCO website for your own personal, non-commercial use.
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
name: ATCO
output_license: null
provenance_date: '2026-11-09'
provider_name: ATCO
provider_slug: atco
slug: atco-data-license
source_date: '2026-11-09'
source_filename: atco-data-license.yml
source_heading: Data License
source_page: https://www.atco.com/en-ca/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: ATCO\naid: atco\nurl: https://www.atco.com/en-ca/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You are granted a limited license only to display and print information contained on the ATCO website for\n    your own personal, non-commercial use.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/atco/data-license/atco-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from ATCO's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Canada
- Utilities
- Electricity
- Gas
- Grid
- Distribution
- Transmission
- DER
- Solar
- Renewables
- Open Data
- Geospatial
- Alberta
---
