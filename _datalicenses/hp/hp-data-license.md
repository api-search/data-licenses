---
api_specs:
- filename: hp-analytics-api-openapi.yml
  format: yaml
  label: HP Analytics API
  slug: hp-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hp/openapi/hp-analytics-api-openapi.yml
- filename: hp-devices-api-openapi.yml
  format: yaml
  label: HP Devices API
  slug: hp-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hp/openapi/hp-devices-api-openapi.yml
- filename: hp-incidents-api-openapi.yml
  format: yaml
  label: HP Incidents API
  slug: hp-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hp/openapi/hp-incidents-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Developer shall clearly identify all Services as the property of HP.
  data:
    license: custom
    stance_commercial: prohibited
    text: HP retains all right, title and interest (including all copyright, trademark, trade secret, and any other applicable intellectual or industrial property rights) in and to the Services.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: Developer may use the Services for its own internal purposes, and/or distribute the applications created by use of the Services in connection with Developer’s commercial products, subject to the terms set forth in this Agreement.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: HP
output_license: null
provenance_date: '2026-11-09'
provider_name: HP
provider_slug: hp
slug: hp-data-license
source_date: '2026-11-09'
source_filename: hp-data-license.yml
source_heading: Data License
source_page: https://developers.hp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: HP\naid: hp\nurl: https://developers.hp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: Developer may use the Services for its own internal purposes, and/or distribute the applications created\n    by use of the Services in connection with Developer’s commercial products, subject to the terms set forth in\n    this Agreement.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: HP retains all right, title and interest (including all copyright, trademark, trade secret, and any other\n    applicable intellectual or industrial property rights)\
  \ in and to the Services.\nattribution:\n  required: true\n  text: Developer shall clearly identify all Services as the property of HP.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/hp/data-license/hp-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from HP's own page on 2026-11-09.
synthetic: false
tags:
- Computer Hardware
- Device Management
- Printing
- Technology
- Fortune 100
---
