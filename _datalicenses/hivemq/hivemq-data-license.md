---
api_specs:
- filename: hivemq-asyncapi.yml
  format: yaml
  label: HiveMQ MQTT over WebSocket
  slug: mqtt-websocket
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/hivemq/asyncapi/hivemq-asyncapi.yml
- filename: hivemq-data-hub-api-openapi.yml
  format: yaml
  label: HiveMQ Data Hub API
  slug: hivemq-data-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemq/openapi/hivemq-data-hub-api-openapi.yml
- filename: hivemq-management-api-openapi.yml
  format: yaml
  label: HiveMQ Management API
  slug: hivemq-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemq/openapi/hivemq-management-api-openapi.yml
- filename: hivemq-mqtt-api-openapi.yml
  format: yaml
  label: HiveMQ Mqtt API
  slug: hivemq-mqtt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemq/openapi/hivemq-mqtt-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: You may use the Sites and their content for personal, non-commercial, or lawful business evaluation purposes consistent with the Acceptable Use Policy.
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
name: HiveMQ
output_license: null
provenance_date: '2026-11-09'
provider_name: HiveMQ
provider_slug: hivemq
slug: hivemq-data-license
source_date: '2026-11-09'
source_filename: hivemq-data-license.yml
source_heading: Data License
source_page: https://www.hivemq.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: HiveMQ\naid: hivemq\nurl: https://www.hivemq.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: You may use the Sites and their content for personal, non-commercial, or lawful business evaluation purposes\n    consistent with the Acceptable Use Policy.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/hivemq/data-license/hivemq-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from HiveMQ's own page on 2026-11-09.
synthetic: false
tags:
- MQTT
- IoT
- Messaging
- Message Broker
- Pub/Sub
- WebSocket
- Real-Time
---
