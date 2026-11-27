---
api_specs:
- filename: edmunds-vehicle-api-openapi.yml
  format: yaml
  label: Edmunds Vehicle API
  slug: edmunds-vehicle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edmunds/openapi/edmunds-vehicle-api-openapi.yml
- filename: edmunds-aiplugin-api-openapi.yml
  format: yaml
  label: Edmunds Aiplugin API
  slug: edmunds-aiplugin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edmunds/openapi/edmunds-aiplugin-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You must include an Edmunds Web Logo on your Developer Application.
  data:
    license: custom
    stance_commercial: conditional
    text: limited, non-exclusive, non-assignable, non-transferable, non-sublicensable, royalty-free
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Access to the Edmunds APIs and other Edmunds Materials shall be solely through the Developer Application and displayed only to End Users.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Edmunds
output_license: custom
provenance_date: '2026-11-09'
provider_name: Edmunds
provider_slug: edmunds
slug: edmunds-data-license
source_date: '2026-11-09'
source_filename: edmunds-data-license.yml
source_heading: Data License
source_page: https://developer.edmunds.com/terms_of_service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Edmunds\naid: edmunds\nurl: https://developer.edmunds.com/terms_of_service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Access to the Edmunds APIs and other Edmunds Materials shall be solely through the Developer Application\n    and displayed only to End Users.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: limited, non-exclusive, non-assignable, non-transferable, non-sublicensable, royalty-free\nattribution:\n  required: true\n  text: You must include an Edmunds Web Logo on your Developer Application.\ninterface_license:\n  url:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/edmunds/data-license/edmunds-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Edmunds's own page on 2026-11-09.
synthetic: false
tags:
- Automobiles
- Cars
- Vehicles
- Vehicle Data
- Dealership
- Reviews
- Pricing
- Automotive
---
