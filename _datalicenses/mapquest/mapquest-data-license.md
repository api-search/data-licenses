---
api_specs:
- filename: mapquest-directions-api-openapi.yml
  format: yaml
  label: MapQuest Directions API
  slug: mapquest-directions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapquest/openapi/mapquest-directions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: You may not commercially exploit the Materials or the underlying data
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: MapQuest grants you a nonexclusive, non-transferable license to view and print the Materials solely for your own personal non-commercial use.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: MapQuest
output_license: custom
provenance_date: '2026-11-10'
provider_name: MapQuest
provider_slug: mapquest
slug: mapquest-data-license
source_date: '2026-11-10'
source_filename: mapquest-data-license.yml
source_heading: Data License
source_page: https://hello.mapquest.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: MapQuest\naid: mapquest\nurl: https://hello.mapquest.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: MapQuest grants you a nonexclusive, non-transferable license to view and print the Materials solely for\n    your own personal non-commercial use.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You may not commercially exploit the Materials or the underlying data\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/mapquest/data-license/mapquest-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from MapQuest's own page on 2026-11-10.
synthetic: false
tags:
- Geocoding
- Mapping
- Maps
- Navigation
- Routing
- Traffic
---
