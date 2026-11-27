---
api_specs:
- filename: validic-devices-api-openapi.yml
  format: yaml
  label: Validic Devices API
  slug: validic-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-devices-api-openapi.yml
- filename: validic-marketplace-connections-api-openapi.yml
  format: yaml
  label: Validic Marketplace & Connections API
  slug: validic-marketplace-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-marketplace-connections-api-openapi.yml
- filename: validic-observations-data-api-openapi.yml
  format: yaml
  label: Validic Observations & Data API
  slug: validic-observations-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-observations-data-api-openapi.yml
- filename: validic-push-service-api-openapi.yml
  format: yaml
  label: Validic Push Service API
  slug: validic-push-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-push-service-api-openapi.yml
- filename: validic-streaming-api-openapi.yml
  format: yaml
  label: Validic Streaming API
  slug: validic-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-streaming-api-openapi.yml
- filename: validic-users-api-openapi.yml
  format: yaml
  label: Validic Users API
  slug: validic-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-users-api-openapi.yml
- filename: validic-measurements-api-openapi.yml
  format: yaml
  label: Validic Measurements API
  slug: validic-measurements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-measurements-api-openapi.yml
- filename: validic-organizations-api-openapi.yml
  format: yaml
  label: Validic Organizations API
  slug: validic-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-organizations-api-openapi.yml
- filename: validic-streams-api-openapi.yml
  format: yaml
  label: Validic Streams API
  slug: validic-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-streams-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: owners of Apps may require data attribution such that when data generated using their respective App is displayed to a Connected User or Client Customer, such App owner, the name of the App, and/or certain other information relating thereto be displayed.
  data:
    license: null
    stance_commercial: conditional
    text: Client shall (and ensure that its Customers shall) not use or disclose any Connected User's Authorized Data for any purpose other than the Permitted Uses without the express prior written consent of the Connected User.
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
name: Validic
output_license: null
provenance_date: '2026-11-10'
provider_name: Validic
provider_slug: validic
slug: validic-data-license
source_date: '2026-11-10'
source_filename: validic-data-license.yml
source_heading: Data License
source_page: https://validic.com/online-service-agreement-inform/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Validic\naid: validic\nurl: https://validic.com/online-service-agreement-inform/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: null\n  stance_commercial: conditional\n  text: Client shall (and ensure that its Customers shall) not use or disclose any Connected User's Authorized Data\n    for any purpose other than the Permitted Uses without the express prior written consent of the Connected User.\nattribution:\n  required: true\n  text: owners of Apps may require data attribution such that when data generated using their\
  \ respective App is\n    displayed to a Connected User or Client Customer, such App owner, the name of the App, and/or certain other\n    information relating thereto be displayed.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/validic/data-license/validic-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from Validic's own page on 2026-11-10.
synthetic: false
tags:
- Health Data
- Digital Health
- Wearables
- Remote Patient Monitoring
- Health IoT
- Interoperability
- HIPAA
---
