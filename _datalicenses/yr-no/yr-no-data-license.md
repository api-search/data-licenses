---
api_specs:
- filename: yr-no-alerts-api-openapi.yml
  format: yaml
  label: Yr Alerts API
  slug: yr-no-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yr-no/openapi/yr-no-alerts-api-openapi.yml
- filename: yr-no-data-api-openapi.yml
  format: yaml
  label: Yr Data API
  slug: yr-no-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yr-no/openapi/yr-no-data-api-openapi.yml
- filename: yr-no-metadata-api-openapi.yml
  format: yaml
  label: Yr Metadata API
  slug: yr-no-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yr-no/openapi/yr-no-metadata-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: You must give appropriate credit, provide a link to the license, and indicate if changes were made.
  data:
    license: CC-BY-4.0
    stance_commercial: unstated
    text: All open data require attribution as specified in the CC BY 4.0 license
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
name: Yr
output_license: null
provenance_date: '2026-11-10'
provider_name: Yr
provider_slug: yr-no
slug: yr-no-data-license
source_date: '2026-11-10'
source_filename: yr-no-data-license.yml
source_heading: Data License
source_page: https://developer.yr.no/doc/TermsOfService/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Yr\naid: yr-no\nurl: https://developer.yr.no/doc/TermsOfService/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://developer.yr.no/doc/License/\n  - https://developer.yr.no/doc/TermsOfService/\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: CC-BY-4.0\n  stance_commercial: unstated\n  text: All open data require attribution as specified in the CC BY 4.0 license\nattribution:\n  required: true\n  text: You must give appropriate credit, provide a link to the license, and indicate if changes were made.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/yr-no/data-license/yr-no-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from Yr's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Forecast
- Meteorology
- Climate
- Norway
- Nordic
- Open Data
- Aviation Weather
- Marine Weather
- Alerts
---
