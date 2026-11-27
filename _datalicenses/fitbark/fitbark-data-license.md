---
api_specs:
- filename: fitbark-activity-api-openapi.yml
  format: yaml
  label: FitBark Activity API
  slug: fitbark-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-activity-api-openapi.yml
- filename: fitbark-dog-api-openapi.yml
  format: yaml
  label: FitBark Dog API
  slug: fitbark-dog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-dog-api-openapi.yml
- filename: fitbark-goals-api-openapi.yml
  format: yaml
  label: FitBark Goals API
  slug: fitbark-goals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-goals-api-openapi.yml
- filename: fitbark-user-api-openapi.yml
  format: yaml
  label: FitBark User API
  slug: fitbark-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-user-api-openapi.yml
- filename: fitbark-oauth-api-openapi.yml
  format: yaml
  label: FitBark O Auth API
  slug: fitbark-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-oauth-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Any rendering or display of FitBark Data in your Developer Application must provide attribution to FitBark
  data:
    license: null
    stance_commercial: conditional
    text: You may make no further use of the FitBark Data, without express User consent
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: FitBark grants you a non-exclusive, revocable, non-sublicenseable, non-transferable royalty free license to use the FitBark API solely to develop, reproduce and distribute Developer Applications.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: FitBark
output_license: custom
provenance_date: '2026-11-09'
provider_name: FitBark
provider_slug: fitbark
slug: fitbark-data-license
source_date: '2026-11-09'
source_filename: fitbark-data-license.yml
source_heading: Data License
source_page: https://help.fitbark.com/en/articles/6490193-api-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: FitBark\naid: fitbark\nurl: https://help.fitbark.com/en/articles/6490193-api-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: FitBark grants you a non-exclusive, revocable, non-sublicenseable, non-transferable royalty free license\n    to use the FitBark API solely to develop, reproduce and distribute Developer Applications.\ndata:\n  license: null\n  stance_commercial: conditional\n  text: You may make no further use of the FitBark Data, without express User consent\nattribution:\n  required: true\n  text: Any rendering or display of FitBark Data in your\
  \ Developer Application must provide attribution to FitBark\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/fitbark/data-license/fitbark-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from FitBark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Dogs
- Pets
- Wearables
- Activity Tracking
- Health
- IoT
- Fitness
---
