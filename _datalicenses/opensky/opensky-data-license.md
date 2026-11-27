---
api_specs:
- filename: opensky-flights-api-openapi.yml
  format: yaml
  label: OpenSky Network Flights API
  slug: opensky-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensky/openapi/opensky-flights-api-openapi.yml
- filename: opensky-state-vectors-api-openapi.yml
  format: yaml
  label: OpenSky Network State Vectors API
  slug: opensky-state-vectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensky/openapi/opensky-state-vectors-api-openapi.yml
- filename: opensky-tracks-api-openapi.yml
  format: yaml
  label: OpenSky Network Tracks API
  slug: opensky-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensky/openapi/opensky-tracks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You must cite the data as follows
  data:
    license: custom
    stance_commercial: conditional
    text: solely for the purpose of non-profit research and non-profit education
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Any use by a for-profit or commercial entity requires written permission and a license granted by the OpenSky Network.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: OpenSky Network
output_license: custom
provenance_date: '2026-11-10'
provider_name: OpenSky Network
provider_slug: opensky
slug: opensky-data-license
source_date: '2026-11-10'
source_filename: opensky-data-license.yml
source_heading: Data License
source_page: https://opensky-network.org/about/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: OpenSky Network\naid: opensky\nurl: https://opensky-network.org/about/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Any use by a for-profit or commercial entity requires written permission and a license granted by the OpenSky\n    Network.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: solely for the purpose of non-profit research and non-profit education\nattribution:\n  required: true\n  text: You must cite the data as follows\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/opensky/data-license/opensky-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from OpenSky Network's own page on 2026-11-10.
synthetic: false
tags:
- Aviation
- Flight Tracking
- ADS-B
- Aircraft
- Airport
- Real-Time
- Historical Data
---
