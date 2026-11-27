---
api_specs:
- filename: flightaware-airports-api-openapi.yml
  format: yaml
  label: FlightAware Airports API
  slug: flightaware-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-airports-api-openapi.yml
- filename: flightaware-alerts-api-openapi.yml
  format: yaml
  label: FlightAware Alerts API
  slug: flightaware-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-alerts-api-openapi.yml
- filename: flightaware-flights-api-openapi.yml
  format: yaml
  label: FlightAware Flights API
  slug: flightaware-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-flights-api-openapi.yml
- filename: flightaware-foresight-api-openapi.yml
  format: yaml
  label: FlightAware Foresight API
  slug: flightaware-foresight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-foresight-api-openapi.yml
- filename: flightaware-history-api-openapi.yml
  format: yaml
  label: FlightAware History API
  slug: flightaware-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-history-api-openapi.yml
- filename: flightaware-miscellaneous-api-openapi.yml
  format: yaml
  label: FlightAware Miscellaneous API
  slug: flightaware-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-miscellaneous-api-openapi.yml
- filename: flightaware-operators-api-openapi.yml
  format: yaml
  label: FlightAware Operators API
  slug: flightaware-operators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-operators-api-openapi.yml
- filename: flightaware-account-api-openapi.yml
  format: yaml
  label: FlightAware Account API
  slug: flightaware-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-account-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: All no-charge, web-based FlightAware products, APIs, and data are licensed solely for personal use, and you may not use them for any other purpose.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Any products, APIs, and data, for which you pay FlightAware may be used solely in accordance with the specific terms of any additional license provided to you at the time of purchase.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: FlightAware
output_license: custom
provenance_date: '2026-11-09'
provider_name: FlightAware
provider_slug: flightaware
slug: flightaware-data-license
source_date: '2026-11-09'
source_filename: flightaware-data-license.yml
source_heading: Data License
source_page: https://www.flightaware.com/about/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: FlightAware\naid: flightaware\nurl: https://www.flightaware.com/about/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Any products, APIs, and data, for which you pay FlightAware may be used solely in accordance with the specific\n    terms of any additional license provided to you at the time of purchase.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: All no-charge, web-based FlightAware products, APIs, and data are licensed solely for personal use, and\n    you may not use them for any other purpose.\nattribution:\n  required:\
  \ null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/flightaware/data-license/flightaware-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from FlightAware's own page on 2026-11-09.
synthetic: false
tags:
- Aviation
- Flights
- Flight Tracking
- Mapping
- Radar
- Satellite
- Traffic Control
---
