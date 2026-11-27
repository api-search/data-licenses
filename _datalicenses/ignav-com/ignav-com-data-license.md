---
api_specs:
- filename: ignav-com-airports-api-openapi.yml
  format: yaml
  label: ignav-com Airports API
  slug: ignav-com-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ignav-com/openapi/ignav-com-airports-api-openapi.yml
- filename: ignav-com-fares-api-openapi.yml
  format: yaml
  label: ignav-com Fares API
  slug: ignav-com-fares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ignav-com/openapi/ignav-com-fares-api-openapi.yml
- filename: ignav-com-health-api-openapi.yml
  format: yaml
  label: ignav-com Health API
  slug: ignav-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ignav-com/openapi/ignav-com-health-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: false
    text: Ignav requires no attribution, additional permission, or additional fee for these uses.
  data:
    license: custom
    stance_commercial: allowed
    text: This includes raw flight and itinerary data, historical snapshots, derived statistics, public reports, paid products, and services.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: use, copy, modify, combine, analyze, publish, redistribute, and sell that data for any lawful purpose.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: ignav-com
output_license: custom
provenance_date: '2026-11-09'
provider_name: ignav-com
provider_slug: ignav-com
slug: ignav-com-data-license
source_date: '2026-11-09'
source_filename: ignav-com-data-license.yml
source_heading: Data License
source_page: https://ignav.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: ignav-com\naid: ignav-com\nurl: https://ignav.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: use, copy, modify, combine, analyze, publish, redistribute, and sell that data for any lawful purpose.\ndata:\n  license: custom\n  stance_commercial: allowed\n  text: This includes raw flight and itinerary data, historical snapshots, derived statistics, public reports, paid\n    products, and services.\nattribution:\n  required: false\n  text: Ignav requires no attribution, additional permission, or additional fee for these uses.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/ignav-com/data-license/ignav-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from ignav-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Flights
- Travel
- Pricing
- Data
---
