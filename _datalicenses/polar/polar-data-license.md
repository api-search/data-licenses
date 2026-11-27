---
api_specs:
- filename: polar-cardio-load-api-openapi.yml
  format: yaml
  label: Polar Cardio load API
  slug: polar-cardio-load-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-cardio-load-api-openapi.yml
- filename: polar-continuous-heart-rate-api-openapi.yml
  format: yaml
  label: Polar Continuous Heart Rate API
  slug: polar-continuous-heart-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-continuous-heart-rate-api-openapi.yml
- filename: polar-daily-activity-api-openapi.yml
  format: yaml
  label: Polar Daily activity API
  slug: polar-daily-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-daily-activity-api-openapi.yml
- filename: polar-daily-activity-deprecated-api-openapi.yml
  format: yaml
  label: Polar Daily activity (deprecated) API
  slug: polar-daily-activity-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-daily-activity-deprecated-api-openapi.yml
- filename: polar-elixir-trade-biosensing-api-openapi.yml
  format: yaml
  label: Polar Elixir&trade; Biosensing API
  slug: polar-elixir-trade-biosensing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-elixir-trade-biosensing-api-openapi.yml
- filename: polar-exercises-api-openapi.yml
  format: yaml
  label: Polar Exercises API
  slug: polar-exercises-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-exercises-api-openapi.yml
- filename: polar-exercises-deprecated-api-openapi.yml
  format: yaml
  label: Polar Exercises (deprecated) API
  slug: polar-exercises-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-exercises-deprecated-api-openapi.yml
- filename: polar-nightly-recharge-api-openapi.yml
  format: yaml
  label: Polar Nightly Recharge API
  slug: polar-nightly-recharge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-nightly-recharge-api-openapi.yml
- filename: polar-physical-info-api-openapi.yml
  format: yaml
  label: Polar Physical info API
  slug: polar-physical-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-physical-info-api-openapi.yml
- filename: polar-physical-info-deprecated-api-openapi.yml
  format: yaml
  label: Polar Physical info (deprecated) API
  slug: polar-physical-info-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-physical-info-deprecated-api-openapi.yml
- filename: polar-player-training-sessions-api-openapi.yml
  format: yaml
  label: Polar Player training sessions API
  slug: polar-player-training-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-player-training-sessions-api-openapi.yml
- filename: polar-pull-notifications-api-openapi.yml
  format: yaml
  label: Polar Pull notifications API
  slug: polar-pull-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-pull-notifications-api-openapi.yml
- filename: polar-sleep-api-openapi.yml
  format: yaml
  label: Polar Sleep API
  slug: polar-sleep-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-sleep-api-openapi.yml
- filename: polar-sleepwise-trade-api-openapi.yml
  format: yaml
  label: Polar SleepWise&trade; API
  slug: polar-sleepwise-trade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-sleepwise-trade-api-openapi.yml
- filename: polar-team-api-openapi.yml
  format: yaml
  label: Polar Team API
  slug: polar-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-team-api-openapi.yml
- filename: polar-team-training-sessions-api-openapi.yml
  format: yaml
  label: Polar Team training sessions API
  slug: polar-team-training-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-team-training-sessions-api-openapi.yml
- filename: polar-users-api-openapi.yml
  format: yaml
  label: Polar Users API
  slug: polar-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-users-api-openapi.yml
- filename: polar-webhooks-api-openapi.yml
  format: yaml
  label: Polar Webhooks API
  slug: polar-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polar/openapi/polar-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: shall credit Polar Ecosystem as the source of Data when displaying any Data, or any data derived from Data in Your application or service
  data:
    license: custom
    stance_commercial: prohibited
    text: You shall not at any time do or cause to be done any such act or thing which in any way impairs, or intends to impair, any right, title, interest or any Intellectual Property Rights of Polar
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: use the Licensed Materials solely for the purposes of proprietary application or services development
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Polar
output_license: custom
provenance_date: '2026-11-10'
provider_name: Polar
provider_slug: polar
slug: polar-data-license
source_date: '2026-11-10'
source_filename: polar-data-license.yml
source_heading: Data License
source_page: https://www.polar.com/en/legal/polar-api-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Polar\naid: polar\nurl: https://www.polar.com/en/legal/polar-api-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: use the Licensed Materials solely for the purposes of proprietary application or services development\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You shall not at any time do or cause to be done any such act or thing which in any way impairs, or intends\n    to impair, any right, title, interest or any Intellectual Property Rights of Polar\nattribution:\n  required: true\n  text: shall credit Polar Ecosystem as the\
  \ source of Data when displaying any Data, or any data derived from Data\n    in Your application or service\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/polar/data-license/polar-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Polar's own page on 2026-11-10.
synthetic: false
tags:
- Fitness
- Health
- Wearables
- Heart Rate
- Sports
- Training
- Sleep
- Activity Tracking
- Sensors
- Bluetooth
- Wellness
---
