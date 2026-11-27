---
api_specs:
- filename: strava-activities-api-openapi.yml
  format: yaml
  label: Strava Activities API
  slug: strava-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-activities-api-openapi.yml
- filename: strava-athletes-api-openapi.yml
  format: yaml
  label: Strava Athletes API
  slug: strava-athletes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-athletes-api-openapi.yml
- filename: strava-clubs-api-openapi.yml
  format: yaml
  label: Strava Clubs API
  slug: strava-clubs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-clubs-api-openapi.yml
- filename: strava-gear-api-openapi.yml
  format: yaml
  label: Strava Gear API
  slug: strava-gear-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-gear-api-openapi.yml
- filename: strava-routes-api-openapi.yml
  format: yaml
  label: Strava Routes API
  slug: strava-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-routes-api-openapi.yml
- filename: strava-segment-efforts-api-openapi.yml
  format: yaml
  label: Strava Segment Efforts API
  slug: strava-segment-efforts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-segment-efforts-api-openapi.yml
- filename: strava-segments-api-openapi.yml
  format: yaml
  label: Strava Segments API
  slug: strava-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-segments-api-openapi.yml
- filename: strava-streams-api-openapi.yml
  format: yaml
  label: Strava Streams API
  slug: strava-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-streams-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Strava Data provided by a specific user can only be displayed or disclosed in your Developer Application to that user.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Strava
output_license: custom
provenance_date: '2026-11-10'
provider_name: Strava
provider_slug: strava
slug: strava-data-license
source_date: '2026-11-10'
source_filename: strava-data-license.yml
source_heading: Data License
source_page: https://www.strava.com/legal/api
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Strava\naid: strava\nurl: https://www.strava.com/legal/api\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Strava Data provided by a specific user can only be displayed or disclosed in your Developer Application\n    to that user.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/strava/data-license/strava-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from Strava's own page on 2026-11-10.
synthetic: false
tags:
- Cycling
- Fitness
- Fitness Tracking
- Running
- Sports
---
