---
api_specs:
- filename: statsd-wire-protocol-asyncapi.yml
  format: yaml
  label: StatsD Wire Protocol
  slug: statsd-wire-protocol
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/statsd/asyncapi/statsd-wire-protocol-asyncapi.yml
- filename: dogstatsd-wire-protocol-asyncapi.yml
  format: yaml
  label: DogStatsD Wire Protocol
  slug: dogstatsd-wire-protocol
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/statsd/asyncapi/dogstatsd-wire-protocol-asyncapi.yml
- filename: statsd-configuration-api-openapi.yml
  format: yaml
  label: StatsD Configuration API
  slug: statsd-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statsd/openapi/statsd-configuration-api-openapi.yml
- filename: statsd-counters-api-openapi.yml
  format: yaml
  label: StatsD Counters API
  slug: statsd-counters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statsd/openapi/statsd-counters-api-openapi.yml
- filename: statsd-gauges-api-openapi.yml
  format: yaml
  label: StatsD Gauges API
  slug: statsd-gauges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statsd/openapi/statsd-gauges-api-openapi.yml
- filename: statsd-health-api-openapi.yml
  format: yaml
  label: StatsD Health API
  slug: statsd-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statsd/openapi/statsd-health-api-openapi.yml
- filename: statsd-stats-api-openapi.yml
  format: yaml
  label: StatsD Stats API
  slug: statsd-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statsd/openapi/statsd-stats-api-openapi.yml
- filename: statsd-timers-api-openapi.yml
  format: yaml
  label: StatsD Timers API
  slug: statsd-timers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statsd/openapi/statsd-timers-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
  data:
    license: custom
    stance_commercial: conditional
    text: to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software
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
name: StatsD
output_license: null
provenance_date: '2026-11-10'
provider_name: StatsD
provider_slug: statsd
slug: statsd-data-license
source_date: '2026-11-10'
source_filename: statsd-data-license.yml
source_heading: Data License
source_page: https://github.com/statsd/statsd/blob/master/LICENSE
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: StatsD\naid: statsd\nurl: https://github.com/statsd/statsd/blob/master/LICENSE\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: to deal in the Software without restriction, including without limitation the rights to use, copy, modify,\n    merge, publish, distribute, sublicense, and/or sell copies of the Software\nattribution:\n  required: true\n  text: The above copyright notice and this permission notice shall be included in all copies or substantial portions\n    of the Software.\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/statsd/data-license/statsd-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from StatsD's own page on 2026-11-10.
synthetic: false
tags:
- Aggregation
- Daemon
- DogStatsD
- Line Protocol
- Metrics
- Observability
- Open Source
- StatsD
- TCP
- UDP
- Wire Protocol
---
