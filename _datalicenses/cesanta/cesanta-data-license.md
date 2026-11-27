---
api_specs:
- filename: cesanta-data-api-openapi.yml
  format: yaml
  label: Cesanta Data API
  slug: cesanta-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cesanta/openapi/cesanta-data-api-openapi.yml
- filename: cesanta-devices-api-openapi.yml
  format: yaml
  label: Cesanta Devices API
  slug: cesanta-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cesanta/openapi/cesanta-devices-api-openapi.yml
- filename: cesanta-keys-api-openapi.yml
  format: yaml
  label: Cesanta Keys API
  slug: cesanta-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cesanta/openapi/cesanta-keys-api-openapi.yml
- filename: cesanta-logs-api-openapi.yml
  format: yaml
  label: Cesanta Logs API
  slug: cesanta-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cesanta/openapi/cesanta-logs-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Cesanta will not access or use Customer Data, except as necessary to provide the Services to Customer.
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
name: Cesanta
output_license: null
provenance_date: '2026-11-09'
provider_name: Cesanta
provider_slug: cesanta
slug: cesanta-data-license
source_date: '2026-11-09'
source_filename: cesanta-data-license.yml
source_heading: Data License
source_page: https://cesanta.com/Cloud_Platform_ToS.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Cesanta\naid: cesanta\nurl: https://cesanta.com/Cloud_Platform_ToS.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Cesanta will not access or use Customer Data, except as necessary to provide the Services to Customer.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/cesanta/data-license/cesanta-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Cesanta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IoT
- Embedded
- Device Management
- Firmware
- OTA
- Networking
- MQTT
---
